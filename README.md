# walmarthackathon

Sentiment analysis for Employee and User reviews

bhc.l is the lex file that generates tokens

bhc.y is the bison file that parses a given review into different POS(parts of speech).

input2 is the text file containing the review.

polarity.txt is the file containing adjectives with given polarity between 0-1.

0 represents greater negativity and 1 represents greater positivity whereas 0.5 is the neutral point.

use cmd to run the lex and bison files by checking that flex and bison are intsalled and PATH variable is set to the directory where gcc.exe file of any application is stored.

All the above files must be in the flex and bison installed directories.
