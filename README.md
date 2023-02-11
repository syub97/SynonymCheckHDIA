# Corss HDI Container to read data

## Source Data
CS1TAB.csv​

## Source Table
CS1TAB.hdbtable

## Load data into Source Table​
CS1TAB.hdbtabledata​

## Containder Role
CS1XHDIO.hdbrole  
-- object_privileges / SELECT priviledge on table CS1TAB

CS1XHDIA.hdbrole  
-– schema_privileges / SELECT METADATA on schema

## 2 Solutions to read data from another HDI container
1. using HDI Service  
Binding HDI Source Contianer directly to Target Container   
which user will be used?
2. using User provider Service  
Binding UPS to Target Container
3. using SDA with hana cloud connecter for hana on premise  
not yet success with MSSQL Server
4. using SDI to create link with other database  
success with MSSQL