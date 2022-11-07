
# Loops & Conditional construction 2

With solving the problems, I show learned techniques and understanding of the language at a basic level.


## Documentation

BPM Counter:

Write a program, which receives BPM (beats per minute) and number of beats from the console and calculates how many bars (1 bar == 4 beats) the beats equal to, then calculates the length of the sequence in minutes and seconds.
The bars must always be rounded to the first digit after the decimal point (i.e. 1.75 bars  1.8 bars).


Input:
2 integers 

Output:
{how many bars} bars - {how many minutes}m {how many seconds}s


DNA-Sequences:

Write a program, which prints all the possible nucleic acid sequences (A, C, G and T), in the range [AAA…TTT]. Each nucleic acid sequence is exactly 3 nucleotides (letters) long. Print a new line every 4 sequences.
Each nucleotide has a corresponding numeric value – A => 1, C => 2, G => 3, T => 4.
For every sequence, take the sum of its elements (e.g. ACAC => 1 + 2 + 1 + 2 = 6) and if it’s equal to or larger than the match sum, print the sequence with an “O” before and after it, otherwise print “X” before and after it.

Input:
1 integer 

SMS-typing:

Write a program, which emulates typing an SMS, following this guide:
Like old phone SMSing
Following the guide, 2 becomes “a”, 22 becomes “b”
222 becomes “c”, 3 becomes “d” and so on.

Input:

  On the first line, you will receive n - the number of characters – integer in the range [1…30],

  On the next n lines, you will receive integers, representing the text message characters.


Output:

Print all the characters together, forming a text message string.


Vapos-store:

After the previous problem, you feel like taking a break, so you go on the Vapor Store to buy some video games. Write a program, which helps you buy the games. The valid games are the following games:
OutFall 4: 39,99$, CS: OG: 15,99$, Zplinter Zell: 19,99$, Honored 2: 59,99$, RoverWatch: 29,99$, RoverWatch Origins Edition: 39,99$.

On the first line, you will receive your current balance – a floating-point number in the range [0.00…5000.00].
Until you receive the command “Game Time”, you have to keep buying games. When a game is bought, the user’s balance decreases by the price of the game.
Additionally, the program should obey the following conditions:

•	If a game the user is trying to buy is not present in the table above, print “Not Found” and read the next line.

•	If at any point, the user has $0 left, print “Out of money!” and end the program.

•	Alternatively, if the user is trying to buy a game which they can’t afford, print “Too Expensive” and read the next line.

When you receive “Game Time”, print the user’s remaining money and total spent on games, rounded to the 2nd decimal place.


