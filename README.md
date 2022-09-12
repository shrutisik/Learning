# .Net Core

- SOLID Principles 
- How does .Net Core Project start and work internally?
- Dependency injection
- Static class
- Sealed class
- Abstract class
- Dispose and finalize 
- Abstract Vs Interfaces
- Middlewares
- Static Vs Singleton
- Design patterns(Factory, Adaptor, Singleton, Inversion of control, composite, strategy)
- Where to check Http Headers before Action method? 
  - We can do it in middlewares and extract headers from Request.
- Ado. net (Open Connection/ closed connection)
- Diff between const and readonnly 
- Test driven & behavior driven
- How to create NuGet Package locally?
  - Create a class libary project, Add a new Package source by giving the path of nupkg file in Tools and Features Nuget Package Manager. Then in Properties just          enter details of Package along with version, build the project and just Pack it. And share it on a shared folder so everyone can access it. So everyone witll have      to include the package source on their machine via Tools and Features and while Managing nuget packages just select our package source and everyone will be able        to access it.
- Run Code Analysis
  - It is just to get some warnings in our code and optimize it
- SONAR Qube 
  - It is also to find some warnings in code and keep a check on quality of code. run.bat is used to run SONAR.
- Reflection in C#
- Access Modifiers in C#
- Start to end UI to DB call
- What is Unit testing
- How are services registered in .Net Core?
- Authentication & Authorization
  - Authentication(validating credentials)
  - Authorization(Checking permissions for a user)
  - JWT is an open standard for securely transmitting info as a JSON obj. JWT token consists of Header, Payload, Signature.
- Rest Vs SOAP
- Diff bet Single & SingleOrDefault, First & FirstOrDefault 
  - Single cannot handle null it will throw exception whereas SingleOrDefault will handle null. Both throw error if we get more than one element.
- List all LINQ functions
  - Single & SingleOrDefault, First, FirstOrDefault, Take, TakeWhile, Skip, Select, Where, Union, OrderBy, ThenBy, All, Any, Contains, Count, Sum, Max, Min etc.
- Types of EF
  - Code First 
  - Database First 
- EF Commands 
  - enable migrations
  - add migrations 
  - remove migrations (removes previous migrations)
  - update database 
  - script migration (creates SQL script from Migrations)
  - Drop-Database 
- What methods we have in Migration Class
  - Up and Down methods
- SP in EF 
  - DbSet<TEntity>.FromSql(), DbContext.Database.ExecuteSqlCommand()
- Entity State 
  - Added, Modified, Deleted, Unchanged, Detached
- Transient, Scoped & Singleton
- Deferred & Immediate Execution
- DBSet & DBContext why are they used
- Migrate the schema of database?
- How to access appsettings file
- Exception handling
- Diff bet List & Dictionary
- Left JOin in LINQ
- LINQ queries
- Automapper in C#
- ICollection in C#
- IEnumerable Vs IQueryable
- Multi-Threading in C#
- Async Await in C#
- IOC, DI
- Delegates
- Lambda
- Advantages of REST
  




# SQL 
- SQL Injection
- How to improve SQL performance?
  - We can implement DB reflection i.e, Master Slave DB structure or DB Sharding or Inmemory/Cache DB structure
  - Avoid using OR Conditions & Use No lock 
  - Use Indexing 
- Indexes (Use sysIndexes table from System for Index info)
  - Clustered - There can be only 1 CI on a table over Primary key by default.The values are stored on B-Tree in a sorted manner
  - Non-Clustered - There can be max 999 NCI on a table, they can be on single column or on multiple columns. Memory address of values are stored in B-Tree hence, the     values are not sorted. 
- SP Vs Func 
- Group by, having clause
- ACID properties
- Diff betweem Rank and Dense Rank
- nth highest salary 
  - select top 1 salary from (select distinct top N salary from employees order by salary desc) Result order by salary
  - Using dense rank: select salary, Dense_Rank() over (order by salary Desc) as DenseRank from Employees
- Cursors
- Compound & Primary contraint
- Execution plan in SQL
- 






# Postman 

- Http Verbs 
- Accept-encoding
- Content-type
- Gzip
- Bearer token
- Load testing

  
# Couchbase No-SQL
  
  - What is CouchBase NoSQL?
  - 


# Angular

- Observables
- Callback
- Promises
- Observable Vs Promises
- Dependency Injections
- Services 
- Tree shaking
- Subjects 
- RxJs library 
- How does Angular project start?
- Bundling and Minifying
- CanActivate/Authguard 
- Enable prod 
- Lazy loading Vs Eager loading for modules 
- How does routing work internally in angular?
- LINQ in Angular 
- Injecting the services(who creates object in angular?)
- Pipes/Filters
- Life cycle hooks 
- local storage & session storage
- let, var, const 
- Template driven & Form driven 
- Properties in forms for highlighting (touch, pristine)
- Form control Validations
- Interceptors
- The way we do ng-prod what we do for dev?
- How to use live value throughout the angular project?
- Session, local & Storage types
- Diff between == & ===
- Directives in angular
- Event loop in JS
- Closure
- Decorators in angular
- ElementREf, @Hostbinding, @Hostlistener?
- Child to Parent & Parent to child data transfer
- Event emitters
- @Injectable


# Azure

- How do you publish a website on Azure 
- Types of blobs 
- What resources gets created when VM is created?
- How can we set expiration of blob?
- How to give access to people of blob?
- CICD
