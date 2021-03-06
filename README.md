# SudoProgrammer
A Pseudo English to Java Translator

![alt text](https://i.imgur.com/Egf7C0y.png "Sudo Programmer Client")

# Reference Documents
| Symbols        | Symbol Meaning           | Functions  |
| ------------- |:-------------:| -----:|
|“”	|Double quotes	|Used to mention the name of an entity.|
|‘’	|Single quotes	|Used to mention the value of an entity.|
|()	|Open and closed brackets	|Used to mention the pass by reference variable name and the type.|
|{} 	|Open and closed curly brackets	|Used to mention the block start and the block end.|
|# 	|Hash/Pound symbol	|Used to mention a variable that is already declared.|
|. |	Period	|Used to mention an end of line.|


* This program supports basic text editor features such as: Select All, Select, Copy, Paste, Cut via short cut keys. 
* This program is attempts to only make server connection only when ever necessary. 
* To create a new session or to quickly empty the text containers on the client simply press CTRL + R to reset the program.
* This program is capable of translating pseudo English code into Java code

# Tutorial Documents
| Functionality / User Intention        | User Input           | Program Output  |
| ------------- |:-------------:| -----:|		
|Creating a class called DemoClass and make it accessible from every other part of the project. |	Create a new class called "DemoClass" with a visibility of public	|public class DemoClass {}|
|Creating the main method|	main method	|public static void main(String[] args) {}|
|Creating various type of variables|	 variable int "counter" '0'  variable string "myName" 'S K' variable double "salary" '25000.00' variable boolean "selfEmployed" 'true' new int string double variable "currentYear" '2020'	|int counter = 0; String myName = "S K"; double salary = 25000.00; boolean selfEmployed = true; int currentYear = 2020;|
|Creating a new public method called setName that is static type and returns nothing and setting the method argument to a string variable called tempName|	create a new void static method called "setName" with an argument of (String tempName) and set the visibility to public|	public static void setName(String tempName){}|
|Invoking an already created method called setName and passing a value called John Doe to the method	|invoke "setName()" and pass 'John Doe' as the value	|setName("John Doe");|
|Print the returned value by invoking the getName method	|invoke "getName()" and print its value	|System.out.println(getName());|
|Creating a new variable and assigning its value to by referencing another already existing value in the program.	|make a string variable, call it "myName" and set its value to '#name'	|String myName = name;|


# Application Functionality
 
| Functionality | Status  |
| ------------- |:-------------:|		
|Create Class	|✔|
|Create Methods	|✔|
|Invoke Methods	|✔|
|Create Variables|	✔ |
|Call Variables	|✔|
|Set Variables	|✔|
|Print Variables|	✔|
|Create Loops	|❌ - Work in Progress.|
|Create Objects|	❌ - Planned for Future.|

