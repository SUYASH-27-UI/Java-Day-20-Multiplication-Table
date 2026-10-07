# Java-Day-20-Multiplication-Table
# Java Day 20 - Multiplication Table

## Description

This program takes a number from the user and prints its multiplication table from 1 to 10 using a `while` loop.

## Example Output

```text id="ex20"
Enter a number: 5
5 x 1 = 5
5 x 2 = 10
5 x 3 = 15
5 x 4 = 20
5 x 5 = 25
5 x 6 = 30
5 x 7 = 35
5 x 8 = 40
5 x 9 = 45
5 x 10 = 50
```

## Code

```java id="code20"
import java.util.Scanner;

public class Main
{
    public static void main(String[] args)
    {
        Scanner sc = new Scanner(System.in);

        System.out.print("Enter a number: ");
        int number = sc.nextInt();

        int i = 1;

        while (i <= 10)
        {
            System.out.println(number + " x " + i + " = " + (number * i));
            i++;
        }

        sc.close();
    }
}
```

## Concepts Used

* Scanner
* User Input
* `while` loop
* Multiplication
* Variables
* Increment operator `++`

## How It Works

1. The program asks the user to enter a number.
2. The variable `i` starts from `1`.
3. The `while` loop runs while `i` is less than or equal to `10`.
4. The program multiplies the entered number by `i`.
5. The result is displayed.
6. `i++` increases `i` by 1.
7. The loop stops after the 10th multiplication.

## File Name

`Main.java`

## Goal

The goal of this program is to practice the `while` loop and use it to perform repeated multiplication.
