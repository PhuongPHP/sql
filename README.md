# sql
 ##How to check if a stored procedure exists in sql server
 -- check store có rồi thì xóa 
IF OBJECT_ID(N'[dbo].[spa_Search]', N'P') IS NOT NULL
    DROP PROCEDURE [dbo].[spa_Search]
GO
