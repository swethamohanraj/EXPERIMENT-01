# EXPERIMENT-01 JAVA PROGRAM TO PRINT THE ARITHMETIC OPERATIONS

## AIM:
To perform arithmetic operations using Java programming.

## PROCEDURE:
1.Import required packages.
2.Declare main method with the signature "public static void main(String[] args)".
3.Get two numbers as input.
4.Perform operations like addition,subtraction,multiplication,division and modulus using the two inputs.
5.Print the output on display.

## PROGRAM:
```
import java.util.Scanner;
public class Main {
    public static void main(String[] args) {
        Scanner scan=new Scanner(System.in);
        System.out.print("Enter the first number: ");
        int a=scan.nextInt();
        System.out.print("Enter the second number: ");
        int b=scan.nextInt();
        System.out.println("Sum= "+(a+b));
        System.out.println("Subtraction= "+(a-b));
        System.out.println("Multiplication= "+(a*b));
        System.out.println("Division= "+(a/b));
        System.out.println("Modulus= "+(a%b));

    }
}
```
## OUTPUT:
![image](https://github.com/swethamohanraj/EXPERIMENT-01/assets/94228215/d9c12216-1668-4b9f-a331-a7b01d68068c)

## RESULT:
Hence, Arithmetic operations were performed using java programming language.
