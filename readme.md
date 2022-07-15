"Creative Refactoring" (unfinished) of the project from Jonas Fagerberg's book
Repo pattern substituted for Query object pattern. Experimented with more complex queries (order by course duration).
Database has been moved to the Docker container.
Initial seeding has been completely rewriten to allow for the use of the object graph and guarantee clean db for each test. 
Added integration tests (NUnit framework) to test DAL. 
Migration to be applied to a db (originally in docker container), through the standard EF Core migration procedure.

To be continued...

