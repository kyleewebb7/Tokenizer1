This Assignment 1 is for learning how to work with tokens and to become more familiar with C. To compile the program, write in the terminal command line 'gcc prog1_1.c, gcc prog1_2.c' and so on. Each one is individual to itself and has a particular niche that is unique to that program so each one must be compiled, ran, and inputted in one at a time. Then when you have compiled one, use './a.out' in order to run the program. Then input something into the program and based on what program you chose, something mysterious will happen.


Program 1: My first program took in at most 65 characters from the user and it treated the input as a space delimited input and ended it by a newline character. Then my program printed each set of characters to STDOUT without the delimiter, and it was surrounded by equal's signs to show that the spaces were taken out. After 65 chacters were inputted, all other input was ignored as well as multiple delimiters in a row.

Program 2: My second program prompted the user for input with the right carrot character ("> "), then when the user typed in input, it was treated as a space delimited input and stopped by the newline character. Then my program took only 65 chacters of input and ignored anything beyond that. Then my program printed either STR for 'string' or INT for 'integer' for each input token by the user. The output was on a single line and was terminated by a newline character.

Program 3: My third program prompted the user for a space delimited input string with the carrot character ("> ") and it only took in at most, 65 characters. If the user inputted more than two tokens, an error message appeared and the user was re-prompted to an input until the user provided one or two tokens. When the input was correct from the user, my program printed the correct token type either INT for 'integer' or STR for 'string.'

Program 4: My fourth program prompted the user to enter either one or two tokens as input that were space delimited. The input could only be 20 characters or else an error message would pop up. Also if the number of tokens were incorrect, then another error message for the wrong amount of tokens popped up. If an error message popped up, the user was prompted again for input until the user provided a single STR token "quit" which was case insensitive meaning the user could type it with all caps, no caps, some caps the word 'quit' and it would still work. Once quit is inputted, the program will immediately quit the whole program and exit.

Program 5: My fifth program prompted the user to enter space delimited one or two tokens that were at most 65 characters in length. If theuser put too many characters or an incorrect number of tokens error messages would be printed for each specific case. My program continued to prompt the user until the single STR token 'quit' was entered, then it exited out of the program. My program only accepted two token inputs of STR INT and a single toke input of STR. All other inputs were rejected with an error message.


Program 6: My sixth program took in a single command line argument (not the name of my program). If there was more or less than the command line argument, an error message was printed. The command line argument was an integer N. If it was not, an error message popped up. Then my program prompted for N inputs from the user max, correct or not. If the userdidn't quit prior to reaching N, the program termianted after the correct output for that input occurred. 