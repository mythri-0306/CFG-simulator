#CFG Simulator

The CFG Simulator is an interactive web-based tool designed to demonstrate how a Context-Free Grammar (CFG) generates strings through step-by-step derivations. It focuses on the grammar rule:

S→aSb∣ε

This grammar represents a classic pattern where the number of a’s is equal to the number of b’s, with all a’s appearing before b’s (e.g., ab, aabb, aaabbb, etc.).

#Objective

-The main goal of this project is to help students understand:
-How CFG rules are applied
-How strings are derived from a start symbol
-The concept of recursive production rules
-The role of ε (epsilon) in terminating derivations

#How It Works

-The user enters a string as input.
-The simulator checks whether the string follows the CFG rule.
-If valid, it generates a step-by-step derivation starting from S.
-Each step shows how the production rule is applied until the final string is obtained.
-If invalid, the simulator indicates that the string cannot be generated using the given grammar.

#Features

User Input Handling
 -Accepts custom strings for testing.
Step-by-Step Derivation
 -Clearly displays each transformation from S to the final string.
Validation Mechanism
 -Verifies whether the input string belongs to the language defined by the CFG.
Educational Visualization
 -Helps learners understand recursion and grammar expansion visually.
Simple and Clean UI
 -Easy-to-use interface for quick experimentation.

#Example

Input: aabb

Derivation:

S → aSb
  → aaSbb
  → aaεbb
  → aabb

#Concepts Used
 -Context-Free Grammar (CFG)
 -Recursive Definitions
 -String Derivation
 -Formal Languages and Automata Theory

#Author

P. Mythri
