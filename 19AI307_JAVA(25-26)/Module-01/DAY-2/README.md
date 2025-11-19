# Ex.No:1(B) CONDITIONAL STATEMENT

## QUESTION:
In a magical building, an elevator behaves oddly:

If the floor number is divisible by 3 and 5, it skips that floor.

If the floor number is divisible by 3 only, it says "Beware!".

If the floor number is divisible by 5 only, it says "Blessings!".

Otherwise, it announces the floor number.

Write a Java program to simulate this elevator logic for a given floor number.

## AIM:
To write a Java program to simulate this elevator logic for a given floor number.

## ALGORITHM :
1.	Start the program.

2. Import the package java.util.*.

3. Create a Scanner object and read an integer n.

4. If n is divisible by both 3 and 5, print "Skipped".

5. Else if divisible by 3, print "Beware!"; if divisible by 5, print "Blessings!".

6. Otherwise, print "Floor " followed by n and end the program.





## PROGRAM:
 ```
/*
Program to implement a conditional statement using Java
Developed by: Sri Yaline R
RegisterNumber: 212224040325


*/
```

## SOURCE CODE:


```
import java.util.Scanner;

public class ExamRoomAllotment {
    public static void main(String[] args) {
     
        Scanner sc = new Scanner(System.in);
        int n=sc.nextInt();
        if(n%3==0 &&n%5==0)
        {
            System.out.print("Skipped");
        }
        else if(n%3==0)
        {
            System.out.print("Beware!");
        }
        else if(n%5==0)
        {
            System.out.print("Blessings!");
        }
        else
        {
            System.out.print("Floor "+n);
        }
    }
}
 
```




## OUTPUT:
<img width="479" height="388" alt="image" src="https://github.com/user-attachments/assets/e2a1b0e9-5456-46b8-a7c6-dfe62151a4a5" />



## RESULT:
The program successfully writes a Java program to simulate this elevator logic for a given floor number.

