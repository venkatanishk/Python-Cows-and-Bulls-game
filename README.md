# Python-Cows-and-Bulls-game


Cows and Bulls is a pen and paper code-breaking game usually played between 2 players. In this, a player tries to guess a secret code number chosen by the second player. The rules are as follows:

A player will create a secret code, usually a 4-digit number.  This number should have no repeated digits.
Another player makes a guess (4 digit number) to crack the secret number. Upon making a guess, 2 hints will be provided- Cows and Bulls.
Bulls indicate the number of correct digits in the correct position and cows indicates the number of correct digits in the wrong position. For example, if the secret code is 1234 and the guessed number is 1246 then we have 2 BULLS (for the exact matches of digits 1 and 2) and 1 COW (for the match of digit 4 in the wrong position)

The player keeps on guessing until the secret code is cracked. The player who guesses in the minimum number of tries wins.
Explanation:

Let’s see a sample run for better understanding.

Secret Code: 3768

Guess: 1234
Response: 0 bulls, 1 cow
Guess: 5678
Response: 1 bull, 2 cows
Guess: 1678
Response: 1 bull, 2 cows
Guess: 3678
Response: 2 bulls, 2 cows
Guess: 3148
Response: 2 bulls, 0 cows
Guess: 3768
You guessed right!
