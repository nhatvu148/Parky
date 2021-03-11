# An ASP.NET Core Web API

# Create Database in MySQL:

- CREATE DATABASE MyPark;
- USE MyPark;
- CREATE TABLE IF NOT EXISTS `NationalParks`
  (
  `Id` int NOT NULL,
  `Name` nvarchar(128) NOT NULL,
  `State` nvarchar(128) NOT NULL,
  `Created` datetime NOT NULL,
  `Established` datetime NOT NULL,
  CONSTRAINT `PK_NationalParks` PRIMARY KEY (`Id`)
  );
