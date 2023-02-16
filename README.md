# junior-codebreaker
Marked Programming Assignment 4 of the "C# Class Development" course of the "C# Programming for Unity Game Development" Specialization by the University of Colorado via Coursera

## Description

Assignment Description

In this assignment, you'll be developing an application that takes a string of characters and counts how many times each of the alphabetic characters appears. Case doesn't matter for the counts, so the string aAa should yield a count of 3 for the letter A. Finally, the program should print, for each character that appears at least once in the phrase, the character and the count for that character.  

Motivation

The letters of the alphabet appear in English prose with specific frequency; for example, the letter A appears far more often than the letter Q. One technique we can use to crack simple substitution encryption techniques is to count the frequency of letter occurrences in the encrypted message, then use information about their frequency in general use to try reasonable character substitutions based on those frequencies to try to crack the encrypted message. This approach works better on longer messages, and it's definitely a brute force cracking technique, but it's better than random guessing!

Your solution must do the following:

    Count how many times each alphabetic character appears in the phrase, ignoring case (so A and a both add to the count of As)

    For each character that appears at least once in the string, print the character and the count for that character. You should have one space between each character count output, with all the character counts on a single line

For example, for the string aAaBbZ, your output should be the following on a single line (be sure to include a newline at the end):

A3 B2 Z1 

Note: The last character count in your output (Z1 for the example above) must be followed by a single space. Trust me, it’s easier that way, so the automated grader assumes you do that!

Helpful Hint 1

The Char class provides useful functions for checking whether or not a character is a letter and converting a character to upper or lower case

Helpful Hint 2

You should use an array of 26 elements to store the counts for each of the characters, with element 0 holding the count of As, element 1 holding the count of Bs, and so on. Be sure to initialize all the elements to 0 before starting to count characters in the user phrase.

The Program.cs file I provided to you contains helper methods that you can use as you develop your solution. The ConvertCharToIndex method converts an upper case character (like A) to the index you should use in your counts array (for A, the corresponding index is 0). Make sure you pass in an upper case character to that method. The ConvertIndexToChar method converts an index to the corresponding character..

Helpful Hint 3

Just ignore non-alphabetic characters as you count the alpha characters in the phrase. They're not errors, they just don't contribute to the character counts.

Running Your Code

## Getting Started

n/a

### Dependencies

* Windows 10
* Microsoft Visual Studio
* .NET

### Installing

* Download link: [Github Repository](https://github.com/lyndonpanton/junior-codebreaker)

### Executing program

1. Go to the root directory
2. Go to the _ProgrammingAssignment4_ directory
3. Open _ProgrammingAssignment4.sln_ in Microsoft Visual Studio
4. Run _Program.cs_

## Help

n/a

## Authors

Lyndon Mykal Panton
[lyndonpanton](https://github.com/lyndonpanton/)

## Version History

* 0.1
    * Initial Release

## License

n/a

## Acknowledgments

Problem provided by the _University of Colorado_ and _Coursera_
