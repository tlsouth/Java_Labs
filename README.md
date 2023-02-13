# Java_Labs
Repository containing lab exercises/mini projects written in Java and completed for my class Advanced Programming. The labs are listed in the order that they were completed, which corresponds to their level of complexity.

## Contents

- 3mer_Generator: The purpose of this lab is to test the occurrence of the DNA 3 mer 'AAA' in 1000 randomly generated 3 mers when the odds of any given base ('A','T','C','G') being rolled is uniformly distributed and compare it to the occurrence under non-uniform distribution.
- Weighted_Alphabet_Generator: The purpose of this lab is to generator two random alphabets given arrays of characters and their weights. The returned alphabet's weight should be within a 0.01 roundoff error of 1.
- FASTA_Analyzer: This lab includes a static factory method that parses a FASTA file and returns the contents as FastaSequence objects. The sequences are evaluated for total GC content and counts for each base ('A','T','C','G'). An output file is generated contianing the results of the evaluation, the headers, and the sequences. To test this code, use the file 'testFasta.fa' and compare the output file to 'FastaAnalysis.txt' located in the FASTA_Analyzer folder.
- Amino_Acid_Quiz: GUI quiz that generates a random index and displays the amino acid located at that index in an array. The user should respond with the one letter code that corresponds to the prompted amino acid. This GUI was built using Java Swing components and includes a countdown timer, prompt for displaying the amino acid, panels that display the number of correct and incorrect guesses, an input area for the user, and buttons to start and cancel the quiz. 
