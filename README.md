# StringConversionMinimization
This is the solution for a very interesting question for string manipulation that I recently countered in a challenge!



Given two strings, make them identical using minimum moves possible.

These moves could include one or more of the following:

Select any character in any of the strings and repeat it by adding another instance of this character exactly after it. For example, in a single move abc will change to abbc by repeating the character b.

Select any two adjacent and identical characters from any of the strings and remove one of the characters. For example, in a single move, abbc will change to abc by deleting one of the b characters. However, it cannot be converted to bbc.

The 2 moves are independent and it’s not necessary that a move of the first type should be followed by an move of the second type (or vice versa).

# Input Format
The first line of input consists of an integer t which denotes the number of test cases. This is followed by t lines each containing two strings a and b separated by a space.

# Output Format
Print the minimum number of moves that are required to make the strings identical or print -1 if the solution cannot be derived.

Constraints
1 <= t <= 1000
1 <= |a|,|b| <= 10000

# Sample Input
6
bootless bottles
bet beet
foo food
ambiguous ambiguous
access aces
abbbbccc aaaabbbc

# Sample Output
3
1
-1
0
2
6
