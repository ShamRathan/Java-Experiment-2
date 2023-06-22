# Java-Experiment-1

# Compare Numbers

## Aim:
  To write a Java program to perform comparisons on the given numbers.
  
## Algorithm

Step 1 : Open Intelli J application or any other code editor.

Step 2 : Create a class and name it CompareNumbers.

Step 3 : Using Scanner, we can input numbers from the user.

Step 4 : Write the logic for the program using comparing operators.

Step 5 : Display the operations done the input numbers in the terminal.

## Program
```
Developed by: S.Sham Rathan
Register.no : 212221230093

import java.util.Scanner;
public class Main
{
    public static void main(String[] args) {
        Scanner sc = new Scanner(System.in);
        System.out.println("Enter first number");
        int x = sc.nextInt();
        System.out.println("Enter second number");
        int y = sc.nextInt();
        System.out.println("By comparing two numbers largest number :");
        if (x > y) {
            System.out.println(x);
        } else {
            System.out.println(y);
        }
        System.out.println("By comparing two numbers smallest number :");
        if (x > y) {
            System.out.println(y);
        } else {
            System.out.println(x);
        }
        System.out.println("By comparing two numbers are equal or not :");
        if (x == y) {
            System.out.println("Equal");
        } else {
            System.out.println("Not equal");
        }
    }
}
```




## Output:
![image](https://github.com/ShamRathan/Java-Experiment-2/assets/93587823/b4309277-863f-4a54-83a4-1da36373ac81)



## Result :
  We have successfully created a Java program to display the comparisons on input numbers.
