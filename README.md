# TodoApi-ASP.NetCoreWebAPI
TodoApi using the ASP.NET Core Web API. Controller-based web API that uses a database.

<br>

Design
<img href="design.jpg" alt="design-screenshot">

<br>

Swagger Documentation <br>
<img href="https://learn.microsoft.com/en-us/aspnet/core/tutorials/web-api-help-pages-using-swagger?view=aspnetcore-8.0">link</img>


<ul>
  <li>A model is a set of classes that represent the data that the app manages. The model for this app is the TodoItem class.</li>
  <li>The database context is the main class that coordinates Entity Framework functionality for a data model. In ASP.NET Core, services such as the DB context must be registered with the dependency injection (DI) container. The container provides the service to controllers.</li>
  <li>Add new Scaffolded Item in the Controllers folder to generate code.</li>
  <li>The return type of <code>ActionResult&lt;T></code> type. ASP.NET Core automatically serializes the object to JSON and writes the JSON into the body of the response message.</li>
  <li></li>
</ul>