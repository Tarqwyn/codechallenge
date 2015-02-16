Problem Statement

Ransome likes strings in which consecutive characters are different. For example, he likes ABABA, while he doesn't like ABAA. Given a string containing characters A and B only, he wants to change it into a string he likes. To do this, he is allowed to delete the characters in the string.

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