# Lab 04 - SOP/POS and KMaps

In this lab, you’ve learned how to apply KMaps, Sum Of Products and Products of
sums to simplify digital logic equations. Then, you’ve proven out that they work
using an implemented design on your Basys3 boards.

## Rubric

| Item | Description | Value |
| ---- | ----------- | ----- |
| Summary Answers | Your writings about what you learned in this lab. | 25% |
| Question 1 | Your answers to the question | 25% |
| Question 2 | Your answers to the question | 25% |
| Question 3 | Your answers to the question | 25% |

## Lab Summary

Summarize your learnings from the lab here.
I this lab we were given a truth table. From that we found the SOP and POS. With this we then made KMaps for both of them to find the minterms and maxterm. After that we then simiulated what the waveforms would look like to make sure we got the correct equations. Once that was done we could connect the physical board and checked if the the leds would turn on when the switches are mathched up with the thruth table. Lastly, we looked at the schmatic to check if the LUT Equation mathces the SOP equation we found.

## Lab Questions

### Why are the groups of 1’s (or 0’s) that we select in the KMap able to go across edges?
Groups are able to go across the edges in KMaps because all adjecent cells need to only have a one varable diffrence. So, this includes vertically, horizontally and across edges.
### Why are the names Sum of Products and Products of Sums?
It is called the sum of products because the expersions are being OR which is multiplication and then being sumed togerther which is AND. The product of sums is called that because the expresions are being sumed together first which is ANDs and then being multiplyed together which is represented by ORs in boolean logic.

### Open the test.v file – how are we able to check that the signals match using XOR?
We are able to check the signals are correct because XOR it is checking that both the minterm and maxterm are reprsenting the same logic function. This is because if the signals don't match the test will fail.
