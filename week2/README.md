Problem Statement

This week's coding challenge is to have strings such that consecutive characters are different. For example, ABABA, but not ABAA. 
Given a string containing characters A and B only, change it into an acceptable string. To do this, you are allowed to 
delete the characters in the string.

Your task is to find the minimum number of required deletions.

Input Format 

String

Output Format 

Print the minimum number of deletions required.

Sample Input

AAAA
BBBBB
ABABABAB
BABABA
AAABBB

Sample Output

3
4
0
0
4

Explanation

AAAA                                = 3 deletions
BBBBB                              = 4 deletions
ABABABABABABABAB,     = 0 deletions
BABABA                            = 0 deletions
AAABBB                            = 4 deletions