## JWT Authentication :
stateless ,
scalable ,
ideal for APIs ,
frontend/backend separation friendly ,
mobile friendly

Why better than session auth?
Because server doesn’t need session memory.

Great for distributed systems.
## kestrel - server of ASP.NET :
Kestrel + ASP.NET Core generally enforce HTTPS locally.
## LINQ and ORM

Often **LINQ** works together with **ORM** , but they both are doing different purpose. 
- ORM -> Helps to talk with database. Which translates Objects to rows & columns and vice versa. 
- LINQ -> A query built in C# , to easliy talk with DB . 

**You always write LINQ not ORM**

The query which you write to talk with DB is LINQ , then the **ORM** does the translational part. From Object -> rows/columns
## Entity Framework (EF) 
Entity Framework is Microsoft's ORM (Object Relational Mapper).

**EF Core** -> is the modern, lightweight, cross-platform version of Entity Framework.

Alternatives : 

ADO.NET ->
Maximum control.

Dapper -> 
High-performance APIs.
