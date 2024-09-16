## Assignment 1

### Example
Here’s an example of how the output will be structured:

Input (testcases/testcase-1/input.txt):

States: {s0, s1, s2, s3}
Alphabet: {a, b}
Start State: s0
Accept States: {s3}
Transitions:
s0 -> a -> s0, s1
s0 -> b -> s0
s1 -> a -> s2
s1 -> b -> s2
s2 -> a -> s3
s2 -> b -> s3

Generated Output:
testcases/testcase-1/dfa_image.png: Graphical representation of the DFA.
testcases/testcase-1/minimized_dfa_image.png: Graphical representation of the minimized DFA.