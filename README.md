# DEB2024 - Seal Team 6 - Project 3

![New Team of 6 cute seals](Images/SealTeam6.PNG)

| Authors     | Danny Bui, Deepti Bist, GWong |
| ---         | ---                           |
|Submission   | 8th Apr 2024                  |
|Data Source  | Northwind Sample DB           |

# Project Context and Goals

Provide the CEO of Northwind insights on 
- Customers,
- Products,
- Revenue, 
- Product movement geographically

# Solution Architecture

![Solution Architecture](Images/SolutionArchitecture.PNG)

# Presentation

[Presentation/README.md](Presentation/README.md)

# Airbyte Cloud

- Setup source

![](Images/AirByteNewSource.PNG)

- Setup destination

![](Images/AirByteSetupDestination.PNG)

- Incremental update

![](Images/AirByteIncrementalExtract.PNG)

# Snowflake x dbt Lab

## Tests
![](Images/DBTGenericTests.PNG)
![](Images/DBTSingularTests.PNG)

## DBT Setup
![](Images/DBTDependenciesSource.PNG)
![](Images/DBTDependenciesRef.PNG)

# Data Modelling

![](Images/SnowFlakeDataModelling.PNG)

![](Images/SnowflakeSchemaRaw.PNG)

The snowflake schema:

![](Images/SnowflakeSchema.PNG)

# Power BI

See contents of the PowerBI folder to inspect the .pbix file.

![](Images/PBIDashboard.PNG)



