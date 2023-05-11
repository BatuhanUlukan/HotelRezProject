# Project About
Using SQL Server as a database, N Tier Architecture architectures consisting of BusinessLayer, DataAccessLayer, DTOLayer, EntityLayer, PresentationLayer, SignalRApiForSQL and SingalRConsume layers are supported and coded with APIs with Codefirst discussion using ASP.Net Core 5.0 and Entity Framework Core technologies. In addition, MSSQL and Postgre SQL databases were also used.

This project represents a web feature operating under the holiday limitation. It is a project with three different owners, where various holiday options are listed on the site, users can access their personal accounts and information about the site, and the administrative user can perform CRUD operations included in the site.
# Development Stages
<li>Layers were created and the overall structure of the project was determined.
<li>Context class was defined for database operations and migration was performed.
<li>Data access was made using DataAccesLayer and BusinessLayer Generic Interfaces.
<li>Database operations were performed using the Repository Design Pattern approach.
<li>The accuracy of the entered data was checked using the Fluent Validation library.
<li>Performance improvement was achieved by using Partial Async and View Component structures.
<li>CRUD operations were performed using MSSQL database.
<li>Listing and getting the comments made according to the route they belong to.
<li>User login was made using Identity and user's profile information was retrieved.
<li>Login and Register pages were created.
<li>Custom Identity Validator operations were performed.
<li>User profile and picture information was updated with Identity.
<li>Active, pending, past and new reservation pages for the logged in user have been created.
<li>Removed the Include method and Ef dependency.
<li>Container dependencies and startup structures were refactored.
<li>A 404 not found page has been created.
<li>Both dynamic and static excel and pdf reports pages were created.
<li>Email sending has been done.
<li>Ajax operations are done.
<li>The Data Transfer Object (DTO) layer was created and data transfer processes were optimized using AutoMapper.
<li>The Api Project was used in the main project.
<li>The hotel list was taken from Rapid Api Booking.
<li>Data operations were decomposed using the CQRS Design Pattern.
<li>Using the MediatR library, the operations were done in a more streamlined way.
<li>Unit Of Work was implemented and database operations were made more manageable.
<li>Visitor data set was created via API.
<li>Pivot table was created for visitors using CrossTab.
<li>Instant data display was performed on the graph using SignalR.
<li>Role CRUD operations performed.
<li>We completed the camp with multi-language support and forgot password pages.
