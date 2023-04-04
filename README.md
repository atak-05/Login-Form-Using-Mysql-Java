## Getting Started

This code talks about how we can create login page using Mysql. 
And I worked on Java..
It has many basic design component.
Its very basic but its very useful

## Folder Structure
> Images
![](jdbc\img\loginInput.png)

The workspace contains two folders by default, where:
`src`:

- **LoginForm.java**:

The main folder ;This is a Java Swing application and allows a user to login. The form has a username and password field. The username and password are verified in the database and if the user is authenticated, the application will be redirected to the main window. Otherwise, the error message is displayed. Database connection is performed using the Java Database Connectivity (JDBC) API. The code covers many Java core concepts, including Swing components, editors, event listeners, and JDBC operations.


-  **MainFrame.java**:
This code creates a Swing interface to display a user's information. The interface contains a JPanel named 'infoPanel' and displays information like user's name, email, phone number and address side by side using GridLayout. Also, using the 'setFont' method, the font, size and thickness of the labels are set.
This class, when called from the Main class, takes a User object and displays the user's information. The interface derives from the JFrame class and sets the title, size, position and visibility. The setDefaultCloseOperation method ensures that the JFrame is closed when the window is closed.In short, this code creates a simple Swing interface to display the user's information.




- **User.java**:
Creates a User class that holds its password. This class can be used to store a user's information and can act as a database to hold user data. However, given security concerns, additional measures are recommended to properly store and process sensitive information such as passwords.






# Referenced Libraries :
It has mysql-connector.jar 


Refenceses :
[I learned this Youtube Channel](https://www.youtube.com/watch?v=kQxsaQgL4B8) </br>
[Mysql connector java jar for dowload](https://dev.mysql.com/downloads/connector/j/)



