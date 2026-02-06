# ECE 281 Lab 1 Prelab

## Prelab questions

### Truth Table
MUX uses turth table C as A input and truth table A as C input
| Month | A | B | C | D | Y |
|-------|---|---|---|---|---|
|       | 0 | 0 | 0 | 0 | x |
| Jan   | 0 | 0 | 0 | 1 | 1 | //D0 Y=D
| Feb   | 0 | 0 | 1 | 0 | 0 |
| Mar   | 0 | 0 | 1 | 1 | 1 | //D4 Y=D
| Apr   | 0 | 1 | 0 | 0 | 0 |
| May   | 0 | 1 | 0 | 1 | 1 | //D2 Y=D
| Jun   | 0 | 1 | 1 | 0 | 0 |
| Jul   | 0 | 1 | 1 | 1 | 1 | //D6 Y=D
| Aug   | 1 | 0 | 0 | 0 | 1 | //D1 Y=D'
| Sept  | 1 | 0 | 0 | 1 | 0 |
| Oct   | 1 | 0 | 1 | 0 | 1 | //D5 Y=D'
| Nov   | 1 | 0 | 1 | 1 | 0 | 
| Dec   | 1 | 1 | 0 | 0 | 1 | //D3 Y=D'
|       | 1 | 1 | 0 | 1 | x |
|       | 1 | 1 | 1 | 0 | x | //D7
|       | 1 | 1 | 1 | 1 | x | //D7

### Boolean Equation

$$
Y = A'D+AC'D'+AB'CD'
$$

### Digital Simulations

In this folder are also Digital templates for you to complete and simulate.  Do not change the file names or the input and output labels in Digital otherwise the autograder will not work.  The autograder will look in the prelab folder for the files.

Complete all three circuits using the various approaches (generic multiplexer symbol, 74151 multiplexer chip, and a sum of products using and/or logic gates).

You may also wish to run test cases.  The first two rows of the truth table have been added to the Digital simulation files as a test.  You may wish to edit the test to add more rows and fully cover all possible cases but this is not required.

## Submission

1. Make sure all prelab files are in this folder
2. Commit all files
3. Push to GitHub
4. Submit to Gradescope
5. Verify submission
