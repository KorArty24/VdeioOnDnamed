"Creative Refactoring" (unfinished) of the project from Jonas Fagerberg's book
Repo pattern substituted for Query object pattern. Experimented with more complex queries (order by course duration).
Database has been moved to the Docker container.
Initial seeding has been completely rewriten to allow for the use of the object graph and guarantee clean db for each test. 
Added integration tests (NUnit framework) to test DAL. 
Migration to be applied to a db (originally in docker container), through the standard EF Core migration procedure.
FrontEnd dashboard was substituted for a simple list, to provide for sorting and filtering, which is backed (so far only sorting, filtering requires 
changes in seeding mechanism ) by AJAX scripting, 
what makes sorting more lightweight https://www.thereformedprogrammer.net/asp-net-core-razor-pages-how-to-implement-ajax-requests/
To be continued...

