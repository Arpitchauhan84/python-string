 the task is to check if the string is symmetrical and palindrome or not. A string is said to be symmetrical if both 
 the halves of the string are the same and a string is said to be a palindrome string if 
 one half of the string is the reverse of the other half or if a string appears same when read forward or backward.
 
 Approach 1: 
 The approach is very naive. In the case of palindrome, a loop is run to the mid of the string 
 and the first and last characters are matched. If the characters are not similar then the loop breaks and the string is not 
 palindrome otherwise the string is a palindrome. In the case of symmetry, if the string length is even then the string is broken 
 into two halves and the loop is run, checking the characters of the strings of both the half. If the characters are not similar then
 the loops break and the string is not symmetrical otherwise the string is symmetrical. If the string length is odd then 
 the string is broken into two halves in such a way that the middle element is left unchecked, and the above same step is repeated.
