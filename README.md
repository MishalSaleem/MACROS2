# MACROS2
# Palindrome Checker using Macros in Assembly (MASM/TASM)

This is a simple *Palindrome Checker* program written in *8086 Assembly Language* using *macros* instead of procedures. The program checks whether an entered string is a palindrome or not.

It is written using *MASM-compatible syntax*, and works on MASM, TASM, or EMU8086.

---

## Features

- Uses *macros only*, not procedures.
- Accepts input string from user (up to 30 characters).
- Displays the *length* of the input.
- Checks and displays if the string is a *PALINDROME* or *NOT A PALINDROME*.
- Follows clean formatting with **newlines added only in main**.

---

## How It Works

1. Prompts: ENTER A STRING:
2. Takes character-by-character input until Enter key.
3. Displays: LENGTH: X
4. Outputs either:
   - PALINDROME
   - NOT A PALINDROME

---

## Sample Output
![image](https://github.com/user-attachments/assets/078a18bc-116b-4b3c-acaf-8c9c1544a29c)
![image](https://github.com/user-attachments/assets/80336cf8-7b53-4dc3-8224-4978229fa54b)

# ASCII Character Sorter in 8086 Assembly

This 8086 Assembly program takes *three characters* from the user and prints them in *ascending order based on their ASCII values*.

## Description

The program:
- Prompts the user to input 3 characters.
- Stores the characters.
- Sorts them using basic comparisons.
- Displays the characters from smallest to greatest (by ASCII).

## Features

- Uses *macros* for cleaner and reusable code.
- No external libraries – pure Assembly logic.
- Simple and easy to understand.

## Program Workflow

1. *Prompt*:  
   Enter three characters:

2. *Input*:  
   User enters 3 characters (e.g., c a b)

3. *Sorting Logic*:
   - Compare first and second characters
   - Compare first and third characters
   - Compare second and third characters
   - Use XCHG to swap if needed

4. *Output*:  
  ![image](https://github.com/user-attachments/assets/745e8568-ffb6-4291-894b-6d84259904b7)

# Even or Odd Checker in 8086 Assembly

This 8086 Assembly language program determines if a single-digit number (0–9) entered by the user is *even* or *odd*.

## Description

The program:
- Prompts the user to enter a digit (0–9).
- Converts the ASCII input to its numeric value.
- Uses bitwise operations to check if the number is even or odd.
- Displays the result.

## Features

- Uses macros for message printing and formatting.
- Simple input and decision-making using AND and CMP instructions.
- Clean structure and easy to follow logic.

## How It Works

1. *Prompt*:  
   The program displays:  
   Enter a single-digit number(0-9)

2. *Input Handling*:
   - Takes a single character using INT 21h.
   - Converts ASCII to number by subtracting 48 ('0').

3. *Logic*:
   - Uses AND al, 1 to isolate the least significant bit.
   - If result is 0, the number is *even*.
   - If result is 1, the number is *odd*.

4. *Output*:
   - Displays the appropriate message:
     - The number is Even.
     - The number is Odd.

## Sample Input & Output
![image](https://github.com/user-attachments/assets/a59c1c49-cd2b-49d1-b274-f61454b45a98)
![image](https://github.com/user-attachments/assets/afc24fe9-80df-4689-ae88-dcb439b66982)

