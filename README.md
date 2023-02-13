# Java_Labs
Repository containing lab exercises/mini projects written in Java and completed for my class Advanced Programming. The labs are listed in the order that they were completed, which corresponds to their level of complexity.

## Contents

- 3mer_Generator: The purpose of this lab is to test the occurrence of the DNA 3 mer 'AAA' in 1000 randomly generated 3 mers when the odds of any given base ('A','T','C','G') being rolled is uniformly distributed and compare it to the occurrence under non-uniform distribution.
- Weighted_Alphabet_Generator: The purpose of this lab is to generator two random alphabets given arrays of characters and their weights. The returned alphabet's weight should be within a 0.01 roundoff error of 1.
- FASTA_Analyzer: This lab includes a static factory method that parses a FASTA file and returns the contents as FastaSequence objects. The sequences are evaluated for total GC content and counts for each base ('A','T','C','G'). An output file is generated contianing the results of the evaluation, the headers, and the sequences. To test this code, use the file 'testFasta.fa' and compare the output file to 'analysis.txt' located in the FASTA_Analyzer folder.
