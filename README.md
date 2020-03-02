# Inches
Given the length in inches, the program will convert the inches to feet and output that measurement.

PROJECT SUMMARY:This program takes the given input from the user and converts it from inches to feet. First, the program prompts the user to input a number for inches. On the output screen, the program asks the user to input a number for inches and it leaves space to type. Next, the program reads and analyzes the input for inches. Then, the program incorporates the input from the user into the formula for feet, which is 12 divided (user’s input) = feet. Lastly, the code calculates and displays the equivalent number of feet based on the given input.


RUNNING THE PROGRAM: To run this program, you need to use Dev-C++ version 5.11. If you want to run my program, download Dev-C++ version 5.11. Then, comipile and run the code. Compiling converts the code I wrote in my program to machine language so that the computer can read and understand it. Machine language is something only a computer can understand.

COMMENTS: In my code there are a lot of comments. Comments are written after forward slashes // because the commpiler will not read anything that you type after //. Comments are essentially there for me and anyone else that reads my code. Comments help add meaning to each line of code like context clues. Comments help guide the reader through my code. You can follow my code easily by reading the comments I left inside of it.

HEADER FILES: Header files are libraries that preprocess the functions and symbols in a program. Header files have to be included at the beginnging of your progam so that in can compile and run. Essentially, header files hold the definition of everything that is included in the code so that the computer program knows exactly what the programmer is using within their code. The header file I used in my program is #include <iostream>. Iostream means input and output stream. This is how I am able to have the user input data and then the program output data. I also used the statement, using namespace std;, alongside my header file. This also allows me to use cin and cout as input/output statements. Cin is input and cout is output. Input statements are where the user types things in. Output statement are what the user will see on the output screen once the code has ran. Cout indicates output along with this << symbol. Cin indicates input along with this >> symbol.

DATA TYPES, IDENTIFIERS, and VARIABLES: A data type is an attribute of data that the computer program can read. Based on which data type you use, the computer will automatically know what you are using that data type for. An identifier names the variables used in the program. The variables in my program store the numbers I need to calculate the equivalent feet from the given input of inches. Variables are used to store information like integers and numbers. Data types are words that the computer program automatically knows. Data types describe what the identifier is. For example: int is a data type that means integer. int feet would mean that feet is an integer number.

The variables in my program include double inches and double feet. Double mean that the value for inches and feet are decimals, but in my program the user can type in an integer value for inches. Depending on the the value that the user types in for inches, the equivalent number of feet will end up being a decimal number. I placed a function that will take the input from the user and use it to calculate the total amount of feet. There are 12 inches in a foot, so the function is feet = (inches) / 12. The (inches) in this equation is the number that the user inputs. Then, the quotient will be stored the the variable feet and output to the screen.

Here is a list of the statements and varibale that I used in my code along with their descriptions. I placed these in the same order that I have my code in: 

Data Type Identifier
double   inches;    -  I am declaring the variable for inches. This is what the user's input will be stored.

double feet;       - I am declaring the varible for feet. This is where the output for the number of feet will be stored.


Statements: All of these statements have to end with a semicolon, otherwise it will cause to program to have an error	

 cout << "The program will convert the given inches to feet." << endl; 
 Description:
 This output statement that explains the purpose of the program. This will appear on the screen after the code is ran.
 
 
cout << "Enter amount of inches. Then press enter key on keyboard to continue." << endl; 
Description:
This is output statement that prompts the user to input the number of inches. Then it prompts the user to press the enter key.


cin >> inches;
Description: This is an input statement that is in my code. On the next line, right under the previous cout statement, is where the user will type in their number of inches. This cin statement is what that next line is on the output screen. The user just types in their number and presses the enter key.


feet = (inches) / 12;  
Description: 
12 inches = 1 foot, so I used this formula to divide the amount of inches by 12 to get the equivalent amount of feet. This will incorporate the number it received from the user into the formula.


cout << "Feet = " << feet << endl; 
Description: 
This output statement displays the results from the feet formula.

















