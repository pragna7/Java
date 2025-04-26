# Java
// Java Program to find 
// the LCM of two numbers
import java.io.*;

// Driver Class
class GFG {
    // main function
    public static void main(String[] args)
    {
        // Numbers
        int a = 15, b = 25;

        // Checking for the largest
        // Number between them
        int ans = (a > b) ? a : b;

        // Checking for a smallest number that
        // can de divided by both numbers
        while (true) {
            if (ans % a == 0 && ans % b == 0)
                break;
            ans++;
        }

        // Printing the Result
        System.out.println("LCM of " + a + " and " + b
                           + " : " + ans);
    }
}








// Java Program to Check if Given Integer is Odd or Even
// Using Brute Forcew Approach

// Importing required classes
import java.io.*;
import java.util.Scanner;

// Main class
class GFG {

	// Main Driver Method
	public static void main(String[] args)
	{
		// Declaring and initializing integer variable
		int num = 10;

		// Checking if number is even or odd number
		// via remainder
		if (num % 2 == 0) {

			// If remainder is zero then this number is even
			System.out.println("Entered Number is Even");
		}

		else {

			// If remainder is not zero then this number is
			// odd
			System.out.println("Entered Number is Odd");
		}
	}
}




import java.util.Scanner;

public class PowerOfNumber {

 public static void main(String[] args) {

 Scanner input = new Scanner(System.in);

 System.out.print(“Enter base: “);

 int base = input.nextInt();

 System.out.print(“Enter exponent: “);

 int exponent = input.nextInt();

 long result = 1;

 while (exponent != 0) {

 result *= base;

 –exponent;

 }

 System.out.println(“Result: ” + result);

 input.close();

 }

}





// Java program to find a leap year
// Importing Classes/Files
import java.io.*;

// Class for leap-year dealing
public class GeeksforGeeks {
	// Method to check leap year
	public static void isLeapYear(int year)
	{
		// flag to take a non-leap year by default
		boolean is_leap_year = false;

		// If year is divisible by 4
		if (year % 4 == 0) {
			is_leap_year = true;

			// To identify whether it is a
			// century year or not
			if (year % 100 == 0) {
				// Checking if year is divisible by 400
				// therefore century leap year
				if (year % 400 == 0)
					is_leap_year = true;
				else
					is_leap_year = false;
			}
		}

		// We land here when corresponding if fails
		// If year is not divisible by 4
		else

			// Flag dealing- Non leap-year
			is_leap_year = false;

		if (!is_leap_year)
			System.out.println(year + " : Non Leap-year");
		else
			System.out.println(year + " : Leap-year");
	}

	// Driver Code
	public static void main(String[] args)
	{
		// Calling our function by
		// passing century year not divisible by 400
		isLeapYear(2000);

		// Calling our function by
		// passing Non-century year
		isLeapYear(2002);
	}
}



// Java program to find factorial
// of given number

// Driver Class
class Test {
    // Method to find factorial
    // of given number
    static int factorial(int n)
    {
        int res = 1, i;
        for (i = 2; i <= n; i++)
            res *= i;
        return res;
    }

    // main method
    public static void main(String[] args)
    {
        int num = 5;
        System.out.println("Factorial of " + num + " is "
                           + factorial(5));
    }
}




// Java program to compute
// simple interest for given principal
// amount, time and rate of interest.
import java.io.*;

class GFG {
    public static void main(String args[])
    {
        // We can change values here for
        // different inputs
        float P = 1, R = 1, T = 1;

        /* Calculate simple interest */
        float SI = (P * T * R) / 100;
        System.out.println("Simple interest = " + SI);
    }
}

// This code is contributed by Anant Agarwal.

