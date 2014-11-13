# One Time Pad Decrypter

This project is a simple command line application for trying to break a one time pad cipher given two cipher texts encrypted with the same one time pad.

## Install



## How To Use

replace variables C1 and C2 in main.py with your own two cipher texts. Next, run the following command:

```bash
python main.py " and "
```

Where the additional command line argument is your guess as to what the encrypted message might contain. 

The program will converts your guess into bits, XOR it with each subsection of ASCII bytes contained in C1 of the same length and then XOR the result with each subsection of ASCII bytes (same length) in C2, returning all possible messages in uncovers. 

If any of the results look like a possible message (i.e it reads like english, etc...) then this might be part of the message and you can begin to try expanding upon it with further guesses.

Pro tip: The longer a string your initial guess is, the fewer potential matches it will return!

Good luck!
