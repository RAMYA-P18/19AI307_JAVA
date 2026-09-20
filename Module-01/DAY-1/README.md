Ex.No:1(A) CLASS & OBJECTS
AIM:
To create a class named 'Student' with String variable 'name' and String variable 'address'.

ALGORITHM :
Start the program.
Define a class named 'Student'
Declare a String variable 'name' and initialize it with the value "John"
Declare a String variable 'address' and initialize it with the value "Chennai"
Define a class named 'Test'
Define the 'main' method within the 'Test' class
Create an object 'obj' of the 'Student' class
Print the value of 'name' and 'address' variables of the 'obj' object
End
PROGRAM:
/*
Program to implement a class & objects using Java
*/
Sourcecode.java:
class Student
{
    String name;
    String address;
}
public class Main
{
    public static void main(String[] args)
   {
        Student obj= new Student();        
        obj.name="John";
        obj.address="Chennai";
        System.out.println(obj.name+" "+obj.address);
    }
}
OUTPUT:
<img width="495" height="206" alt="image" src="https://github.com/user-attachments/assets/f27428dc-0705-434f-b5eb-ed007cdc7d6c" />


RESULT:
Thus, the class named 'Student' with String variable 'name' and String variable 'address' was created successfully.
