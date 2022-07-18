"Creative Refactoring" (unfinished) of the project from Jonas Fagerberg's book. 
Repo pattern was substituted for "Query object" pattern (https://tinyurl.com/repo4queryobject). Experimented with more complex queries (order by course duration), database has been moved to the Docker container.
Initial seeding has been completely rewriten to allow for the use of the object graph and guarantee clean db for each test. Added integration tests (NUnit framework) to test DAL. 
Migration to be applied to a db, through the standard EF Core migration procedure.
FrontEnd dashboard was substituted for a simple list to provide for sorting, backed by by AJAX (https://tinyurl.com/ajaxscr)
To be continued...

