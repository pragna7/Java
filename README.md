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

