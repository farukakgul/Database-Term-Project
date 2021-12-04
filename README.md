# Database-Term-Project
CS-322 (Introduction to database systems) course term project at EPFL. 

The report includes the three milestones of our term project.

- In the first milestone we analyzed the dataset and extract the ER (Entity-Relationship) model, translating
it to relational schema, as well as getting acquainted with a DBMS.

- In the second milestone, we expressed a set of queries on top of the loaded database. The goal of this
part is to familiarize with data loading and the task of data processing and eventual cleaning (meaning
transforming data if needed). We also applied our SQL skills, and get a first intuition about how query
performance is directly dependent on i) the way you formulate a query and ii) the logical and physical design of
your database.

- Finally, in the third part of the project we expressed a set of more sophisticated SQL queries, which we
also analyzed to come up with a detailed description of the execution and propose an improvement. We
analyzed the queries and their respective query plans in order to optimize the execution, either with building
appropriate index structures or rewriting the queries to make the execution more efficient (or both), and discuss
about the decisions that query optimizer took, such as if it even considered the newly created index structure. 

Group Members:
- Öykü Irmak Hatipoğlu
- Ömer Faruk Akgül
- Burak Öçalan
 
Note: The dataset contains a subset of data from the California Highway Patrol collected from the Statewide Integrated
Traffic Records System (SWITRS), covering traffic collisions in the state of California in 2018. These reports have
been collected by the Highway Patrol, recorded electronically for archival and preservation based on the forms
filed by officers.
