# DBMS Day 1

## Basic Definitions 

### Data

Data reafers to facts which can be reacorded and have implicite meaning. 

### Information

Processed, meaningful, and usable data is Information. 

### Database

A Database is a collection of related data. 

### DBMS

DBMS is a collection of programs, that enables users to create, maintain and delete a database. It facilitates the process of defining, constructing, manipulating, and sharing database among various users and applications. 

##  Advantage of Database
1) decrease in redundancy of data.
2) security.
3) consistency of data.
4) support multiple uses of data.

## Data Models
A Data Model is a collection of concepts that can be used to describe the structure of a database.

1) High level. ( Conceptual level ) [ E.g : - ER Diagram ]
2) Representational level. ( Logic level ) [ E.g : - Relational Model, Algebra, Constraints ]
3) Physical level. ( low level ) [ E.g : - Indexing & File organisation]

### 1) High level

It provides concepts that are close to the way users perceive data.

### 2) Physical level

These provide concepts of how data is actually getting stored.

### 3) Representational level

It provides concepts which are intermediate b/w High level & Physical level.

## Instance & Schema

The description of the database is called the database schema. It gives the overall design structure and constraints of the database.

The data in the database at a particular moment of time is called database state / Snapshot / Instance.

> Note : - Tuple = rows & Attribute = column

## Anomalies

These are up of three types.

### 1) Insertion Anomaly

If you want to add new information about a department. It can't be added until any student is enrolled in it.

### 2) Deletion Anomaly

If the Tuple regarding the last student of any department is deleted from the table then the information about that department is also deleted.

### 3) Updation Anomaly

If the name of any department is changed then the same should be reflected in every Tuple of that department in the student table.


## Normalization

It basically removes anomalies from the database.

### Goals of Normalization

1) Imparting clear Semantics to the attributes.
2) Reducing redundant information in the Tuples.
3) Reducing Null values in Tuples.
4) Reducing the possibility of the generation of Spurious (Extra) Tuples.