# Project About
Using SQL Server as a database, N Tier Architecture architectures consisting of BusinessLayer, DataAccessLayer, DTOLayer, EntityLayer, PresentationLayer, SignalRApiForSQL and SingalRConsume layers are supported and coded with APIs with Codefirst discussion using ASP.Net Core 5.0 and Entity Framework Core technologies. In addition, MSSQL and Postgre SQL databases were also used.

This project represents a web feature operating under the holiday limitation. It is a project with three different owners, where various holiday options are listed on the site, users can access their personal accounts and information about the site, and the administrative user can perform CRUD operations included in the site.
# Development Stages
<li>Layers were created and the overall structure of the project was determined.<li>
Context class was defined for database operations and migration was performed.
    3.Data access was made using DataAccesLayer and BusinessLayer Generic Interfaces.
    Database operations were performed using the Repository Design Pattern approach.
    The accuracy of the entered data was checked using the Fluent Validation library.
    Performance improvement was achieved by using Partial Async and View Component structures.
    CRUD operations were performed using MSSQL database.
    Listing and getting the comments made according to the route they belong to.
    User login was made using Identity and user's profile information was retrieved.
    Login and Register pages were created.
    Custom Identity Validator operations were performed.
    User profile and picture information was updated with Identity.
    Active, pending, past and new reservation pages for the logged in user have been created.
    Removed the Include method and Ef dependency.
    Container dependencies and startup structures were refactored.
    A 404 not found page has been created.
    Both dynamic and static excel and pdf reports pages were created.
    Email sending has been done.
    Ajax operations are done.
    The Data Transfer Object (DTO) layer was created and data transfer processes were optimized using AutoMapper.
    The Api Project was used in the main project.
    The hotel list was taken from Rapid Api Booking.
    Data operations were decomposed using the CQRS Design Pattern.
    Using the MediatR library, the operations were done in a more streamlined way.
    Unit Of Work was implemented and database operations were made more manageable.
    Visitor data set was created via API.
    Pivot table was created for visitors using CrossTab.
    Instant data display was performed on the graph using SignalR.
    Role CRUD operations performed.
    We completed the camp with multi-language support and forgot password pages.
