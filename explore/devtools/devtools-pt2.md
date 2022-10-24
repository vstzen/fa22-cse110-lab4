## 1
The bug was that result was being calculated using string appending, so the sum value was incorrect

## 2
I would fix it by surrounding num1 and num2 in the results initialization line with parseInt, so it uses regular integer addition.