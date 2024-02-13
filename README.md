# Cyberpunk 2077 Breach Protocol Brute Force Solver</h1>

Cyberpunk 2077 Breach Protocol Brute Force Solver is a program that solve Breach Protocol minigames in Cyberpunk 2077 by giving the most optimal solution available. This program uses a brute-force approach, meaning it finds all the possible solutions firsthand then searches for the solution which outputs the highest points.


Components of this game include:
1. Token - consisting of two alphanumeric characters such as E9, BD, and 55.
2. Matrix - consisting of tokens that will be selected to form a code sequence.
3. Sequence - a series of tokens (two or more) that must be matched.
4. Buffer - the maximum number of tokens that can be arranged sequentially.


The rules of the Breach Protocol game include:
1. Players move in a pattern of horizontal, vertical, horizontal, vertical (alternating) until all sequences are successfully matched or the buffer is full.
2. Players start by selecting one token at the top row position of the matrix.
3. Sequences are matched to the tokens in the buffer.
4. A token in the buffer can be used in more than one sequence.
5. Each sequence has a varying reward or prize weight.
6. Sequences have a minimum length of two tokens.


Language: https://www.python.org/downloads/

Library:
1. Tkinter
2. Itertools

### How To Run
Go to src directory,
`python main.py`