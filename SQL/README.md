# SQL

## Data Warehouse

1. **Subject-oriented:** A data warehouse should contain information about a few well-defined subjects rather than the enterprise.
2. **Integrated:** A data warehouse is an integrated repository of data. It contains information from various systems within an organisation.
3. **Non-volatile:** The data values in a database cannot be changed without a valid reason.
4. **Time-variant:** A data warehouse contains historical data for analysis.

### Structure of a Data Warehouse

primary methods of designing a data warehouse is **dimensional modelling**.

Two key elements of dimensional modelling:

1. Facts: the numerical data
2. Dimensions: metadata attached to the fact variable

### Star Schema

A schema is an outline of the entire data warehouse. It shows how different data sets are connected and how the different attributes of each data set are used for the data warehouse.

Star Schema is the simplest and most effective schema in a data warehouse. A fact table in the center surrounded by multiple dimension tables resembles a star in the Star Schema model.

![alt text](./images/starSchemaExample.jpeg)

The fact table maintains one-to-many relations with all the dimension tables. Every row in a fact table is associated with its dimension table rows with a foreign key reference.

## SQL Process
