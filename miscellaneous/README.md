#### nth palindrome of k digits:
half num = (n-1) + 10^(k) if k is odd <br>
         = (n-1) + 10^(k-1) otherwise <br>
   
no of 1 digit palindromes = 9 <br>
no of 2 digit palindromes = 9 <br>
no of 3 digit palindromes = 90 <br>
no of 4 digit palindromes = 90 <br>
no of 5 digit palindromes = 900 <br>
and so on....

https://www.geeksforgeeks.org/find-nth-even-length-palindromic-number-formed-using-digits-x-and-y/

Palindrome problems: divide the problem into half and try to solve it

#### Base conversion on java
Integer.toString( 
            Integer.parseInt(number, sBase), 
            dBase);