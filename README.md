# Smallest and largest numbers in a list

Write a program that reads a list of integers into a list as long as the integers are greater than zero, then outputs the smallest and largest integers in the list.

## Getting Started

Ex: If the input is: 10,5,3,21,2,-6 The input should be 2, 21.
You can assume that the list of integers will have at least 2 values.


### Prerequisites

PyCharm ,Version: 2020.1.1to run, with Community Edition packages. 


## Running
Once installed you can run the program with the following command

```
n = int(input())
minVal = n
maxVal = n
while(n>0):
    if(minVal>n):
        minVal = n
    if(maxVal<n):
        maxVal = n
    n = int(input())
print(minVal,maxVal)

```

## Thanks

Thank you for contributing to my Calculating app on Py programing.
