Download Link: https://assignmentchef.com/product/solved-cs212-lab-20-adding-exceptions-to-money
<br>
Adding Exceptions to Money.

Rather than create a new project in Eclipse for Lab 20, we will add to the Lab18 project.

Import the class BadWalletMain from Z:Lab20, and look at the code. The array of strings now contains bas instances of bills, such as “B18” and “BAD”.

Create a new exception class called IllegalBillException that extends

IllegalArgumentException (see the lecture on Exceptions if you do not remember how to do this.) Modify class Bill so that is throws a new IllegalBillException is the amount of the bill is not 1, 5, 10, 20, 50 or 100 (there are more bills, but that’s enough.)

Enclose the for loop in class BadWalletMain with a try/catch block that will catch the IllegalBillException and print the errant string to the console, and continue the for loop.. Include a catch clause for the case of the string “BAD” as well.

Run BadWalletMain and see that it terminates normally.