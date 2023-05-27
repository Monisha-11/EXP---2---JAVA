# EXP-2 -> COMPARE TWO NUMBERS

## AIM :
TO Write a Java program to compare two numbers

## SOFTWARE REQUIRED :
IntelliJ IDEA COMMUNITY EDITION

## ALGORITHM :

To compare two numbers in Java, you can use the following algorithm:

1) Declare two variables to hold the numbers you want to compare.
2) Use an if statement to compare the two numbers.
3) The above code compares number1 and number2 and prints a message indicating the result of the comparison.

## PROGRAM :
```java
import java.util.Scanner;
public class Main
{
   public static void main(String[] args) {
       Scanner sc=new Scanner(System.in);
       System.out.println("Enter the First NUmber : ");
       int num = sc.nextInt();
       System.out.println("Enter the Second NUmber : ");
       int num1 = sc.nextInt();
       if(num==num1)
       {
           System.out.println("These Values Are Equal");
       }
       else
       {
           System.out.println("These Values Are Not Equal");
       }
   }
}
```
## OUTPUT :

![image](https://github.com/Monisha-11/EXP-2---JAVA/assets/93427240/b9a39464-8e85-4293-a106-70c58cb793a5)

## RESULT :

Thus the code of compare two numbers in java is executed successfully and obtain the result.

