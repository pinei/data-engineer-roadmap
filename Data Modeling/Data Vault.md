# Data Vault

The Data Vault Modeling techniques are a hub and spoke design - a mix of normalized modeling components with type 2 dimensional properties in the Satellites.

It is in fact a hybrid data model - spanning some of the flexibility of 3NF and combining it with some of the techniques of dimensional modelling.

Data Vault Model would be an Enterprise Data Warehouse layer, NOT a Data Delivery layer

## Framework

The framework that the Data Vault Modeling components rely on include a staging area, an enterprise data warehouse (physical not logical), followed by Star Schemas, cubes, and other data release mechanisms to properly push the data to the end-users or business.

