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

### SETL

**Select:** Identification of the data that you want to analyse

**Extract:** Connecting to the particular data source and pulling out the data

**Transform:** Modifying the extracted data to standardise it

**Load:** Pushing the data into the data warehouse

### Relational Data Model

#### Vocabulary

1. **Tables**

2. **Columns/Attributes**

3. **Constraints:**
   1. **Entity Constraints:** Example an attribute being unique, NULL or PK
   2. **Referential Constraints:** Example foreign key
   3. **Semantic Constraints:** Example data type, max/min length or enumeration

### ERD

**Entity-Relationship Diagram**, can be thought of as a map of the database schema. We can visualise the structure of the entire schema and answer the following questions just by looking at the ERD:

- What are the tables that it contains?
- What are the columns that each table contains?
- What is/are the data types and constraint/s (if any) for each column?
- What are the relationships between the various tables?

- **Entity Type/Entity:** It is nothing but a table in the schema. For example, 'orders' and 'payments' are both entity types.
- **Attribute:** It is a column in an entity type. For example, 'orderNumber' is an attribute in the 'orders' entity type.
- **Relationship Types:** They are the lines between the tables. They define the relationships among the tables. These can be of various types based on their **cardinalities**, i.e., one-to-one, one-to-many, many-to-many, etc.

**Note:** self-referential relationship -> the table refers to itself.

## SQL Process
