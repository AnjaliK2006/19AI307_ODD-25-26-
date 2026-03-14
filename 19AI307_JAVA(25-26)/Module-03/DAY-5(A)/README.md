# Ex.No:3(E) INNER CLASS

## QUESTION:
Write a Java program to create an inner class and access it from the outer class.

## AIM:
To write a Java program to create an inner class and access it from the outer class.

## ALGORITHM :
1.	Start the program.
2.	Import the necessary package 'java.util'
3.	Create an outer class outer.
4. Inside the outer class, create an inner class inner with a method print(String name) to display a greeting message.
5. In the main method, read a name from the user using Scanner.
6. Create an object of the outer class, then create an object of the inner class using the outer class object.
7. Call the print() method using the inner class object to display the message and end the program.





## PROGRAM:
 ```
/*
Program to implement a InnerClass using Java
Developed by: K.ANJALI
RegisterNumber:  212224040024
*/
```

## SOURCE CODE:
```
import java.util.*;
public class outer{
    class inner{
        public void print(String name)
        {
            System.out.println("Hello, "+name+"! This message is from the Inner Class.");
        }
    }

 
    public static void main(String[] args){
        Scanner sc=new Scanner(System.in);
        String name=sc.next();
        outer o=new outer();
        outer.inner obj=o.new inner();
        obj.print(name);
    }
}
```






## OUTPUT:



## RESULT:
The Java program was executed successfully.
The inner class was created and accessed through the outer class object, and the greeting message was displayed correctly.
