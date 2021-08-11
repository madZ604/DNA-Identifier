# DNA-Identifier
Identifies to whom a sequence of DNA belongs to, given the DNA sequence and a CSV file consisting of a list of data

The program requires as its first command-line argument the name of a CSV file containing the STR counts for a list of individuals and as its second command-line argument the name of a text file containing the DNA sequence to identify.

For each of the STRs (from the first line of the CSV file), the program computes the longest run of consecutive repeats of the STR in the DNA sequence to identify.

If the STR counts match exactly with any of the individuals in the CSV file, the program prints out the name of the matching individual.

values stored in CSV file as : name, [STR1],[STR2],[STR3]......[STRn]

**Assumption: the STR counts will not match more than one individual.**

Inspired by CS50x 2021 
