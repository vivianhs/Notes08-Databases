# Notes08-Databases
CIT 114 Notes 8:Databases


## What is a Database?
A database is a shared collection of related data used to support the activities of a particular organization. A database can be viewed as a repository of data that is defined once and then accessed by various users.

A database has the following properties:
It is a representation of some aspect of the real world or a collection of data elements (facts) representing real-world information.
A database is logical, coherent and internally consistent.
A database is designed, built and populated with data for a specific purpose.
Each data item is stored in a field.
A combination of fields makes up a table. For example, each field in an employee table contains data about an individual employee.

### Database Management System
A database management system (DBMS) is a collection of programs that enables users to create and maintain databases and control all access to them. The primary goal of a DBMS is to provide an environment that is both convenient and efficient for users to retrieve and store information.

Key Terms
data elements: facts that represent real-world information
database: a shared collection of related data used to support the activities of a particular organization
database management system (DBMS): a collection of programs that enables users to create and maintain databases and control all access to them
table: a combination of fields

## Characteristics and Benefits of a Database
Managing information means taking care of it so that it works for us and is useful for the tasks we perform. By using a DBMS, the information we collect and add to its database is no longer subject to accidental disorganization. It becomes more accessible and integrated with the rest of our work.

To access and re-sort data we:
Creating mailing lists
Writing management reports
Generating lists of selected news stories
Identifying various client needs
The processing power of a database allows it to manipulate the data it houses, so it can:
Sort
Match
Link
Aggregate
Skip fields
Calculate
Arrange


###### A database can be linked to:
A website that is capturing registered users
A client-tracking application for social service organizations
A medical record system for a health care facility
Your personal address book in your email client
A collection of word-processed documents
A system that issues airline reservations
### Characteristics and benefits
Self-describing nature of a database system
Insulation between program and data
Support for multiple views of data
Sharing of data and multiuser system
Control of data redundancy
Data Sharing
Enforcement of integrity constraints
REstriction of unauthorized access
Data independence
Transaction Processing
Provision for multiple videos of data
Backup and recovery facilities


##### Key Terms
concurrency control strategies: features of a database that allow several users access to the same data item at the same time
data type: determines the sort of data permitted in a field, for example numbers only
data uniqueness: ensures that no duplicates are entered
database constraint: a restriction that determines what is allowed to be entered or edited in a table
metadata: defines and describes the data and relationships between tables in the database
read and write privileges: the ability to both read and modify a file
read-only access: the ability to read a file but not make changes
self-describing: a database system is referred to as self-describing because it not only contains the database itself, but also metadata which defines and describes the data and relationships between tables in the database
view: a subset of the database


## Relational Databases
Data model introduced by C. F. Codd in 1970. Currently, it is the most widely used data model.
The relational model has provided the basis for:
Research on the theory of data/relationship/constraint
Numerous database design methodologies
The standard database access language called structured query language (SQL)
Almost all modern commercial database management systems

##### Table
A database is composed of multiple tables and each table holds the data.


##### Column
The principal storage units are called columns or fields or attributes. These house the basic components of data into which your content can be broken down.

##### Domain
A domain is the original set of atomic values used to model data. By atomic value, we mean that each value in the domain is indivisible as far as the relational model is concerned.

##### Records
Records allows to reconstruct the whole document
Records and fields form the basis of all databases. A simple table gives us the clearest picture of how records and fields work together in a database storage project.
Degree 
A degree is the number of attributes in a table


#### Key Terms
atomic value: each value in the domain is indivisible as far as the relational model is concerned
attribute: principle storage unit in a database
column: see attribute
degree: number of attributes in a table
domain: the original sets of atomic values used to model data; a set of acceptable values that a column is allowed to contain
field: see attribute
file: see relation
record: contains fields that are related; see tuple
relation: a subset of the Cartesian product of a list of domains characterized by a name; the technical term for table or file
row: see tuple
structured query language (SQL): the standard database access language
table: see relation
tuple: a technical term for row or record

## Non-relational Databases

## Query for Data

## Manage vs Unmanaged

## Choosing the Right Database Solution

## AWS Database

