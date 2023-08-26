# Core-java-Xwrokz
Software trainee training for java developer role 


Encapsulation- The process of grouping tha data into single unit/block (class).


                   public class BankDTO{
                          
                              private dataMember,default Constructor, public getter & setter
 
                     }
  
                    DTO stands for Data Transfer Object. It is a design pattern used in software development to transfer data between   
                    different layers or modules of an application. The main purpose of a DTO is to encapsulate data and transport it between 
                    different parts of the application in a simple and efficient manner.



---- MVC Architecture----

MVC stands for Model-View-Controller, and it is a software architectural pattern used in software development to separate an application into three interconnected components, 
each with its specific role and responsibility. The MVC architecture promotes the separation of concerns and enhances code organization, maintainability, and scalability.

Model:

The Model represents the application's data and business logic.
It encapsulates the data and provides methods to interact with and manipulate the data.
It does not directly depend on the View or the Controller.
In the context of a database-backed application, the Model often interacts with the database to fetch, store, or update data.
View:

The View is responsible for the presentation layer and represents the user interface.
It displays the data from the Model to the user and handles user input.
The View is passive, meaning it does not contain any business logic or data manipulation.
It communicates with the Model through the Controller to update the data.
Controller:

The Controller acts as an intermediary between the Model and the View.
It receives user input from the View and processes it.
It interacts with the Model to update the data based on user input or application logic.
It then updates the View to reflect the changes in the data.
The flow of communication in the MVC architecture typically follows these steps:

User interacts with the View by providing input (e.g., clicking a button, entering data).
The View forwards the input to the Controller.
The Controller processes the input and may update the Model accordingly.
The Controller notifies the View of any changes in the Model's data.
The View retrieves the updated data from the Model and displays it to the user.
Benefits of using MVC architecture:

Separation of Concerns: Each component has a specific role and responsibility, making the code more organized and maintainable.
Reusability: Different Views can reuse the same Model and Controller components, promoting code reusability.
Testability: The separation of concerns makes it easier to write unit tests for each component independently.
Scalability: MVC allows for easy scalability and extensibility of the application.
MVC is widely used in web development frameworks like Spring (Java), Django (Python), Ruby on Rails, and ASP.NET (C#). It is 
also commonly used in desktop application development and mobile app development.
