USE master;
GO

-- Drop and recreate the 'DataBank' database

IF EXISTS (SELECT 1 FROM sys.databases WHERE name = 'DataBank')
BEGIN
	ALTER DATABASE DataBank SET SINGLE_USER WITH ROLLBACK IMMEDIATE;
	DROP DATABASE DataBank;
END;
GO 

-- Create the 'DataBank' database --

CREATE DATABASE DataBank;
GO

USE DataBank;
GO

CREATE SCHEMA bronze;
GO

CREATE SCHEMA silver;
GO

CREATE SCHEMA gold;
GO
