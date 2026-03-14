# Ex.No:2(E) ACCESS MODIFIERS

## QUESTION:

Create a class Calculator with: One non-static method add(int a, int b) that returns the sum, One static method info() that says "Calculator is ready".

## AIM:

To write a Java program to create a class Calculator with a non-static method add(int a, int b) to return the sum of two numbers and a static method info() to display a message.


## ALGORITHM :
1.	Start the program.
2.	Import the necessary package 'java.util'
3.	Create a class Calculator.
4. Define a non-static method add(int a, int b) that returns the sum of two integers.
5. Define a static method info() that prints the message "Calculator is ready".
6. In the main method, read two integers from the user using Scanner, call the static method using the class name, and create an object of the Calculator class.
7. Call the add() method using the object, display the result, and stop the program.





## PROGRAM:
 ```
/*
Program to implement a Access Modifiers using Java
Developed by: K.ANJALI
RegisterNumber:  212224040024
*/
```

## SOURCE CODE:

```
import java.util.Scanner;

class Calculator {
   public int add(int a,int b){
       return a+b;
   }
   public static void info(){
       System.out.println("Calculator is ready");
   }
}

class prog {
    public static void main(String[] args) {
         Scanner sc=new Scanner(System.in);
         int n=sc.nextInt();
         int m=sc.nextInt();
         Calculator.info();
         Calculator obj=new Calculator();
         System.out.println("Sum: "+obj.add(n,m));
    }
}
```





## OUTPUT:

![alt text](image.png)

## RESULT:

The Java program was executed successfully.
The static method info() displayed the message "Calculator is ready", and the non-static method add() calculated and displayed the sum of the two input numbers.
