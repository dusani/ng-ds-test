# Quiz 2

Instructions: create a new repository called ng-ds-test. Within this repo, create a README.md file. Copy and paste all of these questions into this README file and answer them.

1. Name and describe the two main operations of a stack (to add and remove data).
Answer:
A stack works as a Last In First Out (LIFO) operation.
The two main operations are:
  1. To add data use an insert prototype method to the Stack class.
  2. To remove data use a pop prototype method to the Stack class.


2. Name and describe the two main operations of a queue (to add and remove data).
Answer:
A queue uses a First In First Out (FIFO) type operation.
The two main operations are:
  1. To add data use an enqueue prototype method to the Queue class.
  2. To remove data use a dequeue prototype method to the Queue class.

3. Draw the tree resulting from adding the following sequence of numbers to an empty tree: 30, 45, 15, 10, 50, 40, 20, 27
Answer:
------------------30
----------15-------------45
-------10----20-------40----50
----------------27

4. Is this tree balanced? If not, which rotation needs to be done? (Use the following rotation as an example: rightRotation(30), or leftRotation(10))
Answer:
  The tree is balanced

5. Now add 29. Is the tree balanced? If not, which rotation needs to be done? (Use the following rotation as an example: rightRotation(30), or leftRotation(10))
Answer:
------------------30
----------15-------------45
-------10----20-------40----50
----------------27
------------------29

6. Consider the following tree:    
  ------5  
  ---2-----8  
  -1--3  

  Now add 0 to the tree. Which one is the first node to go out of balance?
  Answer:
    ------5  
    ---2-----8  
    -1--3  
  --0

7. How do you fix this node? (Use the following rotation as an example: rightRotation(30), or leftRotation(10))

8. What are the four main steps of mergesort?
Answer:
  1. Recognize
  2. Divide
  3. Conquer
  4. Combine


9. Say you have a program which handles the login queue to a game server. The game server is able to log in one person every one second. Assume that one second must elapse after a person logs in with an empty queue before they are removed from the queue. Draw the state of the queue at 12:00:06, considering the following sequence of events:
    1. At 12:00:00 Hades logs in
    2. At 12:00:00 Ares logs in
    3. At 12:00:00 Zeus logs in
    4. At 12:00:00 Buzz Light Year logs in
    5. At 12:00:02 Kanye West logs in
    6. At 12:00:03 Taylor Swift logs in
    7. At 12:00:03 Darkwing Duck logs in
    8. At 12:00:04 Evil Mickey logs in.

10. Solve https://www.hackerrank.com/challenges/compare-the-triplets - be mindful that you are required to print the output to the console in exactly the format that was asked. You are not required to return a value, just print to the console. Also be mindful to use JavaScript.

11. Solve https://www.hackerrank.com/challenges/mini-max-sum - be mindful that you are required to print the output to the console in exactly the format that was asked. You are not required to return a value, just print to the console. Also be mindful to use JavaScript.
