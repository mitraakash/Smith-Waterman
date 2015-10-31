# Smith-Waterman
Used to align two nucleotide/protein sequences with user specific scores for matches, mismatches and gaps.

User enters the input as FASTA files which are read by the program. The program then displays said sequence after stripping the header of the file, thereby only showing you the sequence.

Once you have your 2 sequences, the user enters their custom scoring range for gaps, mismatches and matches. Note, there is no gap extension penalty included.

Program displays the matrix that was generated from the Smith Waterman pairwise local alignemnt and provides the optimal alignment sequence for both input files with respect to each other.
