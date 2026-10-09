# Number Theory: Addition


In this lab you've learned the basics of number theory as it relates to addition.


## Rubric


| Item | Description | Value |
| ---- | ----------- | ----- |
| Summary Answers | Your writings about what you learned in this lab. | 25% |
| Question 1 | Your answers to the question | 25% |
| Question 2 | Your answers to the question | 25% |
| Question 3 | Your answers to the question | 25% |
## Lab Summary
This week we learned how to create a full_adder file with an XOR and AND gate that we could implement in our top file to create a two bit adder. After this lab it feels like it is easier to understand adders and I feel like we could have created a three or four bit adder fairly easily.


## Lab Questions


### 1 - How might you add more than two bits together?
By continuing to use the full_adder file we could have made a full_adder C and a full_adder D and created more wires from the carry out to the carry in. in this way we could have created outputs for each bit in the adder.


### 2 - What is the importance of the XOR gate in an adder?
It creates the output for each bit in the adder where as the AND gate creates the carry out


### 3 - What is the largest number a two bit adder can handle? What happens when you go over?
Three is the largest number it can handle because two bits can only represent Zero to Three. Going over would create a carry out of 1.
