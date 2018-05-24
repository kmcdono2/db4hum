---
title: Relational
nav: true
---

# Fundamental Considerations

- What question(s) will a database allow you to answer? Once you have a research question, you can reformulate it to suit the sources you find that have relevant information.

For example:

  What is the importance of foreign authorship in the development of French prose fiction? (How many novels printed in Paris during the 18th c. were written by authors who were not French?)  

  How does the application of different book censorship/privilege policies affect access to prose fiction in the 18th c.? (Which titles are unique or recur in different manuscript sources documenting book seizures, privileges, etc.)  

  Were eighteenth-century engineers in Brittany a cohesive social group? (What picture of engineers emerges from tax roles?)  

  How did participating in highway construction impact reactions to political events in the spring of 1789?  (Is there a connection between the spatial distribution of highway construction work and highly polarized rhetoric captured in village complaints at the beginning of the French Revolution?)  


- How will you use the database to answer these questions?
  What kinds of queries/visualizations/maps will it allow you to perform/create?  




# How do you create a relational database?

A relational database, as its name suggests, helps you relate/match information that occurs in separate tables. It does this by connecting keys (a unique identifier for a single piece of information).

A **primary key** is a special column in a table whose values (perhaps numbers, perhaps names) are
unique within that column. A primary key has three qualities: 1) it is unique across all
records in the table; 2) it has a non-NULL value for each record in the table for the entire
lifetime of the record; 3) its value never changes during the lifetime of the record.

A **foreign key** is a value in a table that is a primary key from a different table. Foreign keys need
not be unique. Foreign keys make relational databases possible.

### Data Modeling

1. Develop the structure based on your goals and source material
 - determine what the rows and columns will be

 - determine how you represent information

#### Design Principles




  EXAMPLE CSV vs. multiple tables (repeating authors for each book)

#### "Source-oriented"

If you are creating a database to replicate as much as possible an individual or set of similar sources, you may want to closely relate the design (the schema) to the original source structure.

#### "Method-oriented"

If you are working at a composite level, you can design your database to capture specific kinds of information that will help you answer your research question. In this case it is important to document the provenance of the information in each cell.



# Exercise 1

Navigate to [this Google Sheet of "bad data"](https://docs.google.com/spreadsheets/d/1i9jPZaQHoqJ4Tti7TPJwKkGoL70lULD8cRmhqfwbESU/edit?usp=sharing).

{% include figure.html file="AMRennes_tax_role_ex.png" alt="tax role example" width="75%" %}

  - Thoughts about the layout?  
  - Thoughts about data entry?  
  - How would you describe the relationships between the information in each column?  
  - Would this be a good candidate for a relational table?  

Using a piece of scratch paper, sketch out a new schema for the information in this single table.

  - What tables would you create? What would be the columns in those tables? How are the tables related to each other (e.g. which primary keys act as foreign keys in other tables?)

Compare your schema with [this one](https://app.quickdatabasediagrams.com/#/schema/7rR1maovaUymxmhwaS-AIQ).

 - 












2. Create a standardized data entry procedure


documentation
about modeling decisions
and data entry process


DEALING WITH UNCERTAINTY/GAPS
exampkes of how projects how modeled uncertainty


3. Document where information originates
4. Document any data transformations (e.g. standardization of dates, etc.)


5. Begin collecting data in single sheets (Excel, Google sheets)


## A note on documentation
Document in whatever way makes sense to you.
- Github repository wikis are an excellent place to preserve documentation.





## What do you do with the database?

### Querying
local Query

API

vs UI (use FBTEE)




SQL

### Visualizing/Mapping
Since databases record relationships, seeing these outside of table form or query results can be enlightening or help you demonstrate an argument.
