# Python For Beginners series by Microsoft
Goals </br>
  To successfully program a math program using the SAGE tutorial presneted by SDSU </br>
Boundaries / Scope </br>
  Attempting to complete the entire course by the time the project is due </br>
Success criteria </br>
 A simple math program, but eventually a physics program </br>
  Weekly work log with screenshots and summaries to demonstrate activity. </br>
Constraints </br>
  New to sage </br>
Assumptions </br>
  The courses will be available for the duration of the semester.
  I have all required software.
 Stakeholders </br>
 Myself </br>
 Prof. Vaneslow </br>
Timelines </br>
Week 1 Complete Problem statement </br>
Week 2 Watch and practice subjects of vidoes 1 - 5 </br>
Week 3 Watch and practice subjects of videos 6-10 </br>
Week 4 Watch and practice subjects of videos 11-15 </br>
Week 5 Watch and practice subjects of videos 16-20 </br>
Week 6 Watch and practice subjects of videos 21-25 </br>
Week 7 Watch and practice subjects of videos 26-30 </br>
Week 8 Watch and practice subjects of videos 31-35 </br>
Week 9 Watch and practice subjects of videos 36-40 </br>
Week 10 Watch and practice subjects of videos 41-44 </br>
Throughout the course, apply the knowledge gained from the videos to my Integration project. </br>
</br>
# What is Python? </br>
    Python is an interpreted, high-level, general-purpose programming language.Created by
    Guido van Rossum and first released in 1991, Python's design philosophy emphasizes code
    readability with its notable use of significant whitespace. Its language constructs and
    object-oriented approach aims to help programmers write clear, logical code for small
    and large-scale projects.
# Print Statement </br>
    Print statements display output to your console.
A quick example of a print statement. </br>
    Example: ![image](https://user-images.githubusercontent.com/54412579/66274485-4c324700-e84d-11e9-832f-7fe5191853f0.png)
 </br>
    This print statement will output: Hello World! </br>
    Always remember that single quotes '', or double quotes "" can be used to enclose your strings. </br>
</br>
    Sometimes, your program will require your user to input something, like their name, and the </br>
    program will output what the user enters. </br>
    Example: ![image](https://user-images.githubusercontent.com/54412579/66274529-b5b25580-e84d-11e9-8759-956e2742c56d.png) </br>
    These two lines of code will prompt the user with 'Please Enter your name: ', and the print statement will output what the user enters. </br>
Printing a blank line. </br>
  To print a blank line between print statements for your output, there is a simple print statement you </br>
  can use. </br>
  Example: ![image](https://user-images.githubusercontent.com/54412579/66274538-d37fba80-e84d-11e9-8f7a-05843c8b4c62.png) </br>
  This print statement, when placed between lines of output, will essentially create a blank line of text in your output statement, creating space.
  Also, you may put a \n in the midle of a single string, to essentially line break that string. </br>
  Example: ![image](https://user-images.githubusercontent.com/54412579/66274596-2e191680-e84e-11e9-8d97-78ce98231dbd.png)
  You should get something along the lines of ![image](https://user-images.githubusercontent.com/54412579/66274604-425d1380-e84e-11e9-8b97-3812f478f167.png) </br>
# Comments </br>
  Comments are a great way to mark down what your code was trying to do at a certain point, in case you forget. By starting a line of code with a "#," it will initiate a comment, and will not execute that line. </br>
  Example: ![image](https://user-images.githubusercontent.com/54412579/66275532-8ef91c80-e857-11e9-9d82-b17f56855c1b.png) </br>
  Comments will not show in the output for your program, and therefore are a handy way to leave yourself notes about your code.
# Working with Strings </br>
  Strings can be stored in variables, which are essentially placeholders within your code, that will output whatever the value is you have assigned to that variable. </br>
  Example: ![image](https://user-images.githubusercontent.com/54412579/66275678-05e2e500-e859-11e9-8319-69de7f02e6f6.png) </br>
  In the image, I have set up the variable, firstName, and stored a string within the variable, the string being "Brandon," in order to allow me to use firstName later in the code for various purpose. 
  One such purpose, combining strings. Strings can be combined using the "+" symbol, allowing you to put multiple variables together in a single statement. </br>
  Example: ![image](https://user-images.githubusercontent.com/54412579/66275730-902b4900-e859-11e9-8731-c6531f8bd497.png) </br>
  You can see the strategic use of " " added within the final line in order to create space between each variable, otherwise, you would just end up with the two varibables and no space between them.
  Now, there are some interesting things you can do with functions in order to alter a string literal that may be stored within a variable. </br>
  Example: ![image](https://user-images.githubusercontent.com/54412579/66275833-8ce48d00-e85a-11e9-91ba-228a5d4b49a4.png) output: ![image](https://user-images.githubusercontent.com/54412579/66275839-9ec63000-e85a-11e9-802e-a2feedce04af.png) </br>
  Each function alters how the variable is output depending on what you tell it to do. You can see the outputs corralate with the ".xxx" portion of the code. </br>
  Putting all of that together, while using functions for formating, will allow you to do some prety neat stuff. </br>
  Example: ![image](https://user-images.githubusercontent.com/54412579/66275989-36784e00-e85c-11e9-8e87-9bf2b79479ca.png) </br>
  output: ![image](https://user-images.githubusercontent.com/54412579/66275996-45f79700-e85c-11e9-9fa6-c2138691ca46.png) </br>
  You can see how adding the function of .capitalize will force format the user input for firstName, regardless of how they enter it, to the formatted version with the first letter capitalized. </br>
Formatting the strings </br>
Ex: ![string formatting](https://user-images.githubusercontent.com/54412579/68091062-319dbe80-fe49-11e9-99d0-cde3213e4d7e.PNG) </br>
Disregard errors, I did not specify firstName and lastName for the example. But these examples are each different ways to create the same output with the use of placeholders, instead of having to contiuously use the + symbol to add together strings. </br>
Output Ex: ![string format output](https://user-images.githubusercontent.com/54412579/68091135-fbad0a00-fe49-11e9-8588-e07623d207d3.PNG) </br> 
As you can see from the example, each format would produce this same output, regardless of how you decide to format the string.
# Numbers in your code? </br>
When attempting to use numbers in your code, you can store the number, or integer, in a string like so. </br>
Ex: ![pi](https://user-images.githubusercontent.com/54412579/68098082-b78d2a00-fe88-11e9-8eaf-4a540eb3c95f.PNG) </br>
When you run the code and get an output, your output will be 3.14159, because you told the code to print pi, and told the code what pi was. </br>
Now what if you want to tell someone to input a number? All you need to do is assign a name to your string, call the "input" function, and probably write a short print statement telling the user what to do, in case they don't know. Now, you can't just say </br>
print(firstNum + secondNum), you will get exactly that, firstNumsecondNum. In your print statement, you want to tell the code to output the integer version of the string in that place, like this. </br>
Ex: ![input int](https://user-images.githubusercontent.com/54412579/68098190-52860400-fe89-11e9-94a0-6b0126ec0efa.PNG) </br>
If you did everything correct, you should get this: </br>
Ex: ![input int print](https://user-images.githubusercontent.com/54412579/68098208-6893c480-fe89-11e9-9c14-a1d139dbe34a.PNG) </br>
The int call tells the code to output the integer, and all float does is allow it to output a decimal, if there is one. </br>
Python also allows you to do math. Here is a short list of different math symbols and what they do in python: </br>
+ will do addition </br>
- will do subtraction </br>
* will do multiplication </br>
/ will do division </br>
** will multiply to an exponent </br>
Here is an example of what this might look like in code. </br>
Ex: ![math symbols](https://user-images.githubusercontent.com/54412579/68098306-f5d71900-fe89-11e9-95e1-b89af21c824d.PNG) </br>
The output Ex: ![math symbols print](https://user-images.githubusercontent.com/54412579/68098316-025b7180-fe8a-11e9-9e8d-b97b21113209.PNG) </br>
Now what if you want more than just numbers in your print statement. It works fairly similar to concatenating two strings together, but you have to remember to call the int function into the output, or you will get an error. </br>
Ex: ![days](https://user-images.githubusercontent.com/54412579/68098362-43ec1c80-fe8a-11e9-8ca1-ddf028f5027e.PNG) </br>
Output Ex: ![days print](https://user-images.githubusercontent.com/54412579/68098369-4d758480-fe8a-11e9-9615-228fa7186a91.PNG) </br>
# The Dates </br>
Dates can be difficult, but one great thing about python, is it allows you to call from a library, which we will get to later, in order for you to use premade functions to code what you need. Like calling from the "datetime" library, and using the "now" function to get the current date and time. </br>
Ex: ![date](https://user-images.githubusercontent.com/54412579/68098510-19e72a00-fe8b-11e9-8729-bd33b2015577.PNG) </br>
Output Ex: ![date output](https://user-images.githubusercontent.com/54412579/68098524-28354600-fe8b-11e9-9903-1416dfd8cd1a.PNG) </br>
Now maybe you want to manipulate the output of the date, to give you, say, one day ago. Another function within the "datetime" library, called "timedelta," allows you to define a period of time, say one day, and then do string math to get your desired date. </br>
Ex: ![datetime](https://user-images.githubusercontent.com/54412579/68098711-55362880-fe8c-11e9-8b72-c500e6c22369.PNG) </br>
When using timedelta to define days as 1, it allows you to do something like subtract one day from today, and output yesterday. </br>
Output Ex: ![datetime output](https://user-images.githubusercontent.com/54412579/68098750-8f072f00-fe8c-11e9-8515-ddff25d5bb01.PNG) </br>
You can also tell python just to display the day, month, year, hour, minute, or even second. That looks like this: </br>
Ex: ![date format](https://user-images.githubusercontent.com/54412579/68098855-24a2be80-fe8d-11e9-9c89-9547485eeabb.PNG) </br>
Output Ex: ![date format output](https://user-images.githubusercontent.com/54412579/68098861-2ff5ea00-fe8d-11e9-918d-409d9a2a00d7.PNG) </br>
Just place .hour, .minute, or .second in the place of month day or year to get the desired output. </br>
Say you are receinving the date as a string through user input and need to convert it into a "datetime" object in order to properly display it. </br>
Ex: ![birthday](https://user-images.githubusercontent.com/54412579/68099057-608a5380-fe8e-11e9-9104-abe2b80b5525.PNG) </br>
Output Ex: ![birthday output](https://user-images.githubusercontent.com/54412579/68099071-739d2380-fe8e-11e9-9b8f-087f2fbccc34.PNG)
</br>
You can do the samethings here as you previously did with the current day by importing the "timedelta" function. </br>
# Error Handling </br>
Error handling is when an uncontrable factor, like a server goes down, effects the output of your code. Debugging on the other hand, is when you know something is wrong with your code, like incorrect outputs, or crashes. </br>
Errors come in three different types: </br>
Syntax errors: Essentially, the code won't run at all. </br>
Ex: ![syntax](https://user-images.githubusercontent.com/54412579/68099315-d642ef00-fe8f-11e9-9495-b79563e01a11.PNG) </br>
Because you are missing the colon at the end of that line, you get this syntax error: </br>
![syntax output](https://user-images.githubusercontent.com/54412579/68099327-ec50af80-fe8f-11e9-97a2-09356c1f32f8.PNG) </br>
Runtime errors: The code will run, but something is going to go wrong, and the code will blow up. </br>
Ex: ![runtime](https://user-images.githubusercontent.com/54412579/68099422-76991380-fe90-11e9-86e1-3eaf672c9efb.PNG) </br>
Here, python will just tell you that the coder is trying to divide by zero, which we all know is zero, but you will get an error. These errors are almost guarunteed to be in your code, and not the framework. </br>
Output Ex: ![runtime output](https://user-images.githubusercontent.com/54412579/68099443-97616900-fe90-11e9-8f86-f893a4f971b9.PNG) </br>
Logic errors: Everything runs just fine, but you don't get the right response, or a response at all. </br>
Ex: ![logic](https://user-images.githubusercontent.com/54412579/68099705-d0e6a400-fe91-11e9-8cc8-9d5c5578be65.PNG) </br>
You were expecting to get the output you were looking for, but back in your code, you flipped the boolean expression. YOur code still runs, but you get no output because the parameters for an output weren't met, and no errors were committed. </br>
# Handling Conditions </br>
Conditions occur when your code needs to meet a condition. One great way to handle this, is with an "if" statement. Let's take taxes for example. </br>
Ex: ![conditions](https://user-images.githubusercontent.com/54412579/68099844-c973ca80-fe92-11e9-8623-342ac2c746e0.PNG) </br>
You use the "if" statement combined with boolean expressions for when you want your code to do something IF a certain condition is met. If those conditions are met, everything indented under the "if" statement will be run. Some of these conditional boolean expressions are </br>
The symbol >, for Greater than </br>
The symbol <, for Less than </br>
The symbol >=, for Greater than or equal to </br>
The symbol <=, for Less than or equal to </br>
The symbol ==, for Is equal to </br>
The symbol !=, for Is not equal to </br>
You can set a default action to run IF your "if" statement's conditions are not met, and you do that with an "else" statement. </br>
Ex: ![conditions else](https://user-images.githubusercontent.com/54412579/68099984-89611780-fe93-11e9-9a1a-ef0025da32bb.PNG) </br>
As stated, if input does not meet the conditions of the "if" statement, the "else" statement will run. </br>
A cleaner way to write this code, so as to not be redundant, would look something like this: </br>
Ex: ![conditions clean](https://user-images.githubusercontent.com/54412579/68100069-f07ecc00-fe93-11e9-9f5e-6e43f64cffc7.PNG) </br>
The code still checks for the conditions of the "if" statement, and if those aren't met, moves on to the "else" statement, then prints the output of whichever part of the code was ran. </br>
