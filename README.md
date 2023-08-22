# Project-Movie_Director_Management_Watchlist

## Project Overview:

* Creating a watchlist management application using Spring Boot.  <br>
* Organizing movie and director records for a cinephile's watchlist.  <br>
* Employing an MVC architecture for a structured application design. <br>

## Model Classes:

* Defining **Movie** and **Director** classes as model entities. <br>
* Properties include name, duration, IMDb rating, and more. <br>
* Constructors for no-args and all-args scenarios.<br>
* Getters and setters to access and manipulate properties.<br>
  
## Controllers and Endpoints:

* Implementing RESTful endpoints for CRUD operations: <br>
    Adding movies and directors individually.<br>
    Pairing existing movies with directors.<br>
    Retrieving movie and director information.<br>
    Getting movie names for a director.<br>
    Listing all movie names.<br>
    Deleting directors and their associated movies.<br>
    <br>
* Utilizing Spring annotations for URL mapping and HTTP methods.<br>
* Using ResponseEntity to encapsulate responses with appropriate status codes.<br>


## Implementing MVC architecture for structured application design. <br>
Managing CRUD operations using controller, service, and repository layers.
Handling HTTP requests and responses using ResponseEntity.
Simulating data storage using in-memory HashMap(s).

## Application Flow:

1. HTTP requests are received by the controller. <br>
2. Controller delegates operations to the service layer.<br>
3. Service layer interacts with the repository for data management.<br>
4. Responses are constructed using ResponseEntity objects for consistent formatting. <br>

