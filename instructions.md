# High-level Project Plan
I have a sql server database and all the information can be found in .sqlserver_creds.

## Main Steps:
    - Setup a project in SnowConvert AI (we have access to the cli tool `scai`)
    - Connect to a SQL Server database and pull catalog information
    - Generate the input code from SQL Server
    - Understand the errors that SnowConvert surfaces
    - Resolve those errors
    - Move the structure and the data to Snowflake

## Notes:
    - Use the COMPUTE_WH when needed.
    - Use SYSADMIN as default.
    - Do all of this in the `AdventureWorks` db in Snowflake which you will create.
    - Use the `snowconvert-assessment` tool to understand the snowconvert assessment and plan this migration in the best manner

> Consult with me every step of the way...as we go through the major steps

