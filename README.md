# \_3_kyu

Your task is to write function findSum.

Up to and including n, this function will return the sum of all multiples of 3 and 5.

For example:

findSum(5) should return 8 (3 + 5)

findSum(10) should return 33 (3 + 5 + 6 + 9 + 10)

P -

Write a function for findSum that accounts for "up to and including n" to return the sum of all multiples of 3 and 5.

E -

findSum(5) should return 8 (3 + 5)

findSum(10) should return 33 (3 + 5 + 6 + 9 + 10)

find sum (15) should return 60 (3 + 5 + 6 + 9 + 10 + 12 + 15)

find sum (18) should return 78 (3 + 5 + 6 + 9 + 10 + 12 + 15 + 18)

find sum (20) should return 98 (3 + 5 + 6 + 9 + 10 + 12 + 15 + 18 + 20)

find sum (2) should return invalid - not a multiples of 3 or 5

D -

array of integers that are multiples of 3 or 5

A -

For n, determine the integers that are multiples of 3 and 5, including n to determine the array to be summed.

If n is not a multiple of 3 or 5, n is invalid and this cannot be complete.
