# CISC230 - Evan Gabriel

## factorial2.cpp

- The input being n is the number that marks the largest part of the factorial. 
- For example when I input 7 the program started at 7! and began to multiple n by n-1 until it reached 1. If you put in 5 it will out 120 which is 5!. With the input 6 you get 720 being the final out put after 5 calls the first being 6 * 5.
- The number of calls for this specific program should be n-1. When 6 was input there should have been a total of 5 calls, the first being 6 * 5, then 30 * 4, then 120 * 3, next is 360 * 2, and lastly 720 * 

## ireverse2.cpp

- In this program n is outputted in the reverse order.
- For example when I put 43 it output 34 and it has a total of 2 calls. 10 would output 01 and would also have 2 calls. 285 reverses into 582, however, ths has 3 calls.
- The number of recursive calls is always equal to the digit count of n. 2 digits would be 2 calls, 3 digits is 3 calls and so on.

## sreverse2.cpp

- The input n, in this case a string, is reversed from it's original order similar to the ireverse2 program.
- When frog was input, the out was gorf and we can can assume that the calls is equal to 4. The input dog becomes god which would be three inputs. School becomes loohcs with 6 calls.
- Also similar to the ireverse program, the number of calls would be the length of n. One call would be for each individual character in the string, outputting the word in reverse order.

## permute.cpp

- The n variable in this program is the string that is permutated until every combination using every character is generated.
- The first example i used was hat which had a total of 6 outputs. The amount of calls for hat would be around 16 calls. The word run also have 6 outputs with 16 calls. If it is a two letter word such as "it" then there is two outputs with a total of 4 calls.
- The number of recursive calls depends mostly on the amount of digits for the string. First there is the inital call, then n amount of calls  for the first charactered in a fixed position, then it would be n(n-1) for the first two charcters fixed. The formula continues by multiply (n-2) to n(n-1) and this is the patteren that would continue, which can be represented as "n!".

## tower.cpp

- The input ,n, refers to the number of disks in the hanoi tower
- With an input of 3 the total calls is 7 which is how many moves it takes to move the tower from one side to the other. With 4 disks the calls become 15. 6 disks has a total of 63 recursive calls.
- In terms of n, the amount of calls can be written as 2^n - 1. In another formula it can be seen as T(n) = 1 + 2 * T(n-1) which is essentially the previous calls doubled and then plus 1. So going off of 6, 7 disks would be 63 + 63 = 126 + 1 for 127 recursive calls.

## fibonacci2.cpp (presented in video lesson)

- In this program, n equals the amount of numbers output from the Fibonacci sequence
- When the input for n is 20 the number of calls is 20. If it were to be 30 then the calls would also be 30. If the input was 100 then the calls would also be 100.
- In this program, the number of calls is equal to n. So no matter how many numbers of the sequence you wish to generate it will always equal n. If the numbers weren't stored then the growth would be a little closer to exponential. For example, for this program if n = 4 then there are 4 calls where as the other way would have about 9 calls.
