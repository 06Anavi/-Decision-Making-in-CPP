🎯 Aim-

To explore key decision-making structures in C++ including if else, if else if ladder, and switch case through foundational examples like checking odd or even, finding the largest of three numbers, identifying vowels or consonants, and using switch statements.

📚 Theory-

    Conditional statements control the flow of execution based on evaluated conditions, allowing for dynamic and flexible logic handling.
    These constructs are crucial for enabling programs to “think” and respond to input or state variations.

🔄 If Else Statement-

The if else structure allows a program to make a binary decision.
If a condition evaluates as true, one block of code is executed; otherwise, the alternate block runs.
It is useful for simple yes or no logic checks where you’re choosing between two distinct paths.

🧭 If Else If Else Ladder-

This expands decision making to multiple conditions.
The program evaluates conditions sequentially from top to bottom.
As soon as one condition is true, its corresponding block runs and the rest are skipped.
The final else acts as a fallback if none of the prior conditions match.
Ideal for layered logic where multiple outcomes are possible.

🎚️ Switch Case Statement-

The switch case structure offers a cleaner alternative to multiple if checks when you're dealing with discrete values such as menu options or fixed states.
It matches the value of a variable against predefined cases and executes the matched case block.
A default case handles anything that doesn’t fit the listed options.

📋 Algorithms-

✅ Odd or Even Number Detection-

    Start
    Declare an integer variable num
    Prompt the user to enter a number
    Input the number into num
    Check if num % 2 == 0
        If true → Display "Even"
        Else → Display "Odd"
    End

✅ Largest of Three Numbers-

    Start
    Declare three integer variables a, b, and c
    Prompt the user to enter all three numbers
    Input the values
    Compare:
        If a > b && a > c → Display a is largest
        Else if b > c → Display b is largest
        Else → Display c is largest
    End

✅ Vowel or Consonant Using ASCII-

    Start
    Declare a character variable ch
    Prompt the user to enter a character
    Input ch
    Check if ch is between 'A' to 'Z' or 'a' to 'z' (ASCII 65–90 or 97–122)
        If true → Check if ch is 'A', 'E', 'I', 'O', 'U' or lowercase equivalents
            If true → Display "Vowel"
            Else → Display "Consonant"
        Else → Display "Not a letter"
    End

✅ Month Selector Using Switch Case-

    Start
    Declare an integer variable choice
    Display menu options for months (1 to 12)
    Prompt the user to enter a choice
    Input choice
    Use switch(choice)
        Match cases from 1 to 12 to corresponding month
        If no match → Display "Invalid Input"
    End

🧠 Conclusion-

Decision making is at the heart of intelligent programming.
Whether you're branching logic with if else, scaling conditions with else if ladders, or simplifying options via switch case, mastering these structures equips you to write smarter and more dynamic code.
Let the compiler follow your logic line by line, decision by decision.
