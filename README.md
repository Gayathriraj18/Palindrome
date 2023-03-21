# Palindrome


## Aim:
To write a C# program to find whether the given string is a Palindrome or not.
## Algorithm:

Step 1: To start the C# program in visual Studio 2022.

Step 2: Create a class and declare two variable with string datatype.

Step 3: Loop over the entire string and reverse it.

Step 4: Use if condition to check whether the string and the reversed string is equal or not.

Step 5: print palindrome if it's equal else print not a palindrome.

Step 6: Save the program and run the program in visual studio 2022.

## Program:

Developed by : Gayathri A

Register Number : 212221230028

```
using System;
namespace Palindrome
{
    class Palindrome
    {
        static void Main()
        {
            string s, rem, rev = "";
            Console.Write("Enter a string: ");
            s = Console.ReadLine();
            rem = s;
            for(int i=s.Length-1;i>=0;i--)
            {
                rev += s[i];
            }
            Console.WriteLine(rev);
            if (rev == rem)
                Console.WriteLine(rem + " is a Palindrome.");
            else
                Console.WriteLine(rem + " is not a Palindrome.");
                
        }
    }
}
```

## Output:

![output](c%23%20ep2.png)

## Result:
Thus the C# program to display whether the given string is Palindrome or not is executed successfully.
