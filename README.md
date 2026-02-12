# Lexical Twist Puzzle Use Cases

## Project Overview
This project implements the Lexical Twist Puzzle using progressive Use Case–Driven development to demonstrate modular Java programming and OOPS design principles.

## UC1: Display Puzzle Title
Ability to display a static application title "Lexical Twist Puzzle".

## UC2: Accept Word Inputs
Ability to accept two words from the user through console input.

## UC3: Validate Single Word Constraint
Ability to validate that each input contains only one word and terminate gracefully if invalid.

## UC4: Check Reverse Relationship
Ability to check whether the second word is the reverse of the first word (case-insensitive).

## UC5: Transform Word if Reverse Match
Ability to reverse the first word, convert to lowercase, replace vowels with '@', and print the transformed output.

## UC6: Combine Words if Not Reverse
Ability to combine both words, convert to uppercase, and count vowels and consonants.

## UC7: Output Based on Vowel–Consonant Count
Ability to print characters based on rules:
- First 2 unique vowels if vowels > consonants
- First 2 unique consonants if consonants > vowels
- Equality message if counts match

## UC8: Fully Modular OOPS Puzzle System
Ability to implement a modular architecture using:
- LexicalTwistPuzzle (UI)
- LexicalAnalyzer (Logic)
- WordValidator (Validation)

## How to Run
- Compile using `javac LexicalTwistPuzzle.java`
- Run using `java LexicalTwistPuzzle`
