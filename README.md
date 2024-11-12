 Problem Description:
 
 In a string containing only lowercase letters of the alphabet (“a” through “z”), we say a
 letter is heavy if it appears more than once in the string, and light otherwise.
 We will be given a number of strings. For each string, we would like to determine whether
 the letters of the string alternate between light and heavy.
 Input Specification
 The first line of input will consist of two positive integers T and N, representing the number
 of strings and the length of each string.
 The next T lines each contain a sequence of N lowercase letters of the alphabet.

Output Specification:

Output T lines, where each line will be either T or F. If the i-th input string does alternate
between light and heavy letters, the i-th line of output should be T; and otherwise, the i-th
line of output should be F.

Sample Input 1:

3 4
abcb
bcbb
babc

Output for Sample Input 1:

T
F
T

 Sample Input 2:
 
 2 3
 abc
 bcb
 
 Output for Sample Input 2:
 
 F
 T
