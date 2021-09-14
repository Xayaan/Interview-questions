# Take-home solidity coding test

This test consists of three sections.
1. Section 1 has 1 question and tests your understanding of Solidity logic.
2. Section 2 has 3 questions and tests you understanding of Solidity security.
3. Section 3 has 1 question and tests your coding skills.
In each section there is a box for your answer, and a box for any other information you may like to add to explain your answer.
For the coding question, please use your own code editor to create and debug the code and then cut and paste your answer into the box.
To start please enter your name and email. We will send a code challenge to the email address which you will need to enter before you can access the questions.

You have 45 minutes to complete the test.
If you have any queries please contact Zayaan at zayaan@royalprotocol.io


Question 1: Understanding Delegate calls

![Q1](https://i.imgur.com/v39LJEL.jpg)
Question: What’s the output of callB? What’s the output of delegateCallB?


Answer below :

——

**Question 2a: Safe or Unsafe**

![Q2a](https://i.imgur.com/CzcZPfn.jpg)

&nbsp;&nbsp;Question: Safe or Unsafe?
Answer : 

**Question 2b: Safe or Unsafe**

![Q2b](https://i.imgur.com/IqWVIqX.jpg)

Question: Safe or Unsafe?
Answer : 

**Question 2c: Safe or Unsafe**

![Q2c](https://i.imgur.com/TtZWBfz.jpg)

Question: Safe or Unsafe?
Answer : 


**Question 3: Coding test**
Please write solidity code to address the issue below. Use your own code editor and then cut and paste the answer into the box below.

There are 2 contracts: Contract A and contract B.
Contract A contains a number x = 1.
Contract B contains a number y = 1.

Contract A contains a publicly available function print(address addressB) which emits an event with the sum of the two numbers. On each call, before emitting the event, x doubles and y triples. Only contracts should be allowed to read from Contract B. The function should be called read().
