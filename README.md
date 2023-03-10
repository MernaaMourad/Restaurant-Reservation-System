The program is briefly a model of a real restaurant,the data of restaurant concerning the user details,tables available,dishes are saved in a XML file loaded in the login form when the program is run.When starting the program you get a prompt to sign in to the application with a username and a password. The user should enter correct credentials to be able to login to his dashboard otherwise he is asked to re-enter them.
Afterthat if the username and password were correct the User is turned to a person using the person factory which creates an object based on the user's role,the person is the parent abstract class and its childs are manager,customer,cook,and waiter each performing specific tasks.

We tried to handle as much as possible of the errors that might occur while running the program based on the user's errors for example if the user clicked save without adding any dishes,if the user entered wrong username or password,..........etc.
The class Diagram was done using staruml software

