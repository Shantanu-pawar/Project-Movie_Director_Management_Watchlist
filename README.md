# Project-Movie_Director_Management_Watchlist

## Project Overview:

* Creating a watchlist management application using Spring Boot.  <br>
* Organizing movie and director records for a cinephile's watchlist.  <br>
* Employing an MVC architecture for a structured application design. <br>

## Model Classes:

Defining Movie and Director classes as model entities.
Properties include name, duration, IMDb rating, and more.
Constructors for no-args and all-args scenarios.
Getters and setters to access and manipulate properties.
Controller Class - MovieController.java:

Implementing RESTful endpoints for CRUD operations:
Adding movies and directors individually.
Pairing existing movies with directors.
Retrieving movie and director information.
Getting movie names for a director.
Listing all movie names.
Deleting directors and their associated movies.
Utilizing Spring annotations for URL mapping and HTTP methods.
Using ResponseEntity to encapsulate responses with appropriate status codes.
Service Class - MovieService.java:

Encapsulating business logic for operations defined in the controller.
Handling interactions between the controller and the repository.
Implementing methods for adding, pairing, retrieving, and deleting data.
Ensuring proper data validation and error handling.
Repository Class - MovieRepository.java:

Simulating data storage using in-memory HashMap(s).
Storing movie and director records.
Providing methods to interact with the stored data.
Application Flow:

HTTP requests are received by the controller.
Controller delegates operations to the service layer.
Service layer interacts with the repository for data management.
Responses are constructed using ResponseEntity objects for consistent formatting.
Note:

Pay attention to proper annotation usage in classes for accurate behavior.
Follow the provided requirements meticulously to ensure successful compilation.
Thoroughly test all APIs using tools like Postman to validate functionality.
Learning Outcomes:

Demonstrating proficiency in Spring Boot development.
Implementing MVC architecture for structured application design.
Managing CRUD operations using controller, service, and repository layers.
Handling HTTP requests and responses using ResponseEntity.
Simulating data storage using in-memory HashMap(s).