# EXP-2 Java program to compare two numbers

## AIM:
To write a java program to compare two numbers.

## PROCEDURE:
### STEP 1:
Import the required packages
### STEP 2:
Get two inputs from the user
### STEP 3:
Compare them using comparative operator.
### STEP 4:
If first number is greater display first number is greater.
### STEP 5:
If second number is greater then display first number is lesser.
### STEP 6:
If Both numbers are equal then display both are equal.

## PROGRAM:
```java
import java.util.Scanner;
public class Compare {
    public static void main(String[] args)
    {
        Scanner sc=new Scanner(System.in);
        int num1,num2;
        System.out.print("Enter Two numbers: ");
        num1=sc.nextInt();
        num2=sc.nextInt();
        if(num1>num2)
        {
            System.out.println(num1+" is greater than "+num2);
        }
        else if(num1<num2)
        {
            System.out.println(num1+" is smaller than "+num2);
        }
        else
        {
            System.out.println(num1+" and "+num2+" are equal");
        }
    }
}
```
## OUTPUT:
![image](https://github.com/Karthikeyan21001828/Java_EX02/assets/93427303/bee1d856-6f14-4232-9d3f-c6943ad06e41)

## RESULT:
A java program to compare two numbers.
