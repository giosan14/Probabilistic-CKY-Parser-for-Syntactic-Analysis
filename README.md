**Overview:**

This repository contains Python code for implementing a Probabilistic CKY (Cocke-Kasami-Younger) parser for syntactic analysis of sentences based on probabilistic context-free grammars (PCFGs). The parser is applied to analyze the syntactic structure of sentences using dynamic programming techniques and Viterbi algorithm to determine the most likely parse tree.

**Key Steps:**

1. **Grammar Representation:**
   - The provided PCFG rules are represented in Python using dictionaries to define the set of terminals, non-terminals, and production rules along with their associated probabilities.

2. **Parsing Algorithm:**
   - The Probabilistic CKY parsing algorithm is implemented in Python, allowing for syntactic analysis of sentences based on the given PCFG rules.
   - The algorithm operates by filling in a dynamic programming matrix using bottom-up and left-to-right parsing strategies, computing the probabilities of possible constituents for each cell in the matrix.

3. **Viterbi Algorithm:**
   - The Viterbi algorithm is applied to determine the most probable parse tree for a given sentence based on the probabilities computed during parsing.
   - The algorithm selects the parse tree with the highest probability, representing the most likely syntactic structure of the sentence.
