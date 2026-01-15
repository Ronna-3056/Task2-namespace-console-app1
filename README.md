using System;

class Task2
{
    static void Main()
    {
        // Step 2: Declare and initialize the jagged array
        int[][] numberMatrix = new int[][]
        {
            new int[] { 2, 4, 6, 8, 10 }, // Row 0
            new int[] { 1, 3, 5, 7, 9 }   // Row 1
        };

        Console.WriteLine("The number matrix has been initialized.");

        // Step 4: Extract the Digits
        int digit1 = numberMatrix[1][3]; // Row 1, Index 3 (Value: 7)
        int digit2 = numberMatrix[0][0]; // Row 0, Index 0 (Value: 2)
        int digit3 = numberMatrix[1][4]; // Row 1, Index 4 (Value: 9)

        // Step 5: Combine into a string (the password)
        string password = digit1.ToString() + digit2.ToString() + digit3.ToString();

        // Final Output
        Console.WriteLine("The password is: " + password);
 }
}
