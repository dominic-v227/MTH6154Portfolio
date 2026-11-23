# 1. Interest rates

[Back to contents](../README.md)

## Summary

In your own words, the main ideas of the lesson. Short sentences are fine.

Maths is written between dollar signs. For example `$A = P(1+i)^n$` shows
as $A = P(1+i)^n$, and a displayed formula uses double dollars:

$$
\left(1+\frac{i^{(m)}}{m}\right)^m = 1+i
$$

## My example

A situation you made up (your own numbers, not the ones in the lecture
notes), worked step by step.

## Solved exercises

### Exercise 1(from Exercise Sheet 1)
a) Suppose you put £700 in a bank account with nominal interest rate 3%.
How much money will be in the bank account three years from now if the interest is compounded annually?
Using the formula A= P(1+r/n)^nt with n=1, r=0.03, t=3 and P=700, A=700(1+0.03)^3= £764.91
b) How much money will be in the bank account three years from now if the interest is compounded monthly?
Using the same formula in part a, n=12 so 700(1+0.03/12)^36=£765.41
c) How much money will be in the bank account three years from now if the interest is compounded semi-annually?
From the same formula, this time n=2: A=700(1+0.03/2)^6=£765.84
d) How much money will be in the bank account three years from now if the interest is compounded continuously
Using a different formula in A=Pe^rt, A=700e^0.03*3=£765.92
e)Find the effective interest rates reff
 for each case
 i) reff= (1+0.03)-1 as for one year you use the formula from part a and subtract P from it and divide it all by P
 ii) reff=(1+0.03/12)^12 -1 as for one year you use the formula from part a and subtract P from it and divide it all by P
 iii) reff=(1+0.03/2)^2 -1 as for one year you use the formula from part a and subtract P from it and divide it all by P
 iv) (Pe^r-P)/P= e^r-1=e^0.03-1= as the effective annual rate for continuous compuhnding is e^r-1
f) Suppose the inflation rate is 2%. Calculate the ‘inflation adjusted interest rate’ for each case 
From part a, 
g) Suppose interest is compounded semi-annually.How long will it take for the bank balance to grow to £1000? 
For this part, you need to work out the time t when the formula A= P(1+r/n)^nt=£1000  by taking logs,In(1000/700)=2tIn(1.015) t=11.98 so round up to get 12 years

## Spreadsheet

[01-InterestRates.xlsx](../spreadsheets/01-InterestRates.xlsx): what it
does, which cells to change and what to look at.
