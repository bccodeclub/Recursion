# Recursion
### Starter:
Create an algorithm which creates a fibonacci number.
The sequence is 

n | 0 | 1 | 2 | 3 | 4 | 5 | 6
--- | --- | --- | --- | --- | --- | --- | --- 
f | 1 | 1 | 2 | 3 | 5 | 8 | 13

Make an algorithm which:
Inputs a n value and output the corresponding f value.

Use this photo to help you
![](https://lucasfcosta.com/assets/recursion-bubble-up.png)

### What is recursion?
Recursion is a function which calls upon itself. It splits the problem up into a simpler problem and when the problem gets simple enough, we solve the problem.

**An example of this is in fibonacci numbers:** We know that each fibonacci number is the sum of it and the number before it. Therefore, if we create a function which finds the nth fibonacci in the sequence. f(n) = f(n-1) + f(n-2). The function calls upon itself as you see. when n = 1 or n = 0, we return 1, as we know that the 1st and 0th fibonacci number is 1. If not, then we call the function again.

### Task:
Solve Tower of Hanoi
https://www.mathsisfun.com/games/towerofhanoi.html

Input: The height of the tower, n
Output: The instructions of how to move the disc to achieve the desired position.
The instructions should be in the form,
`a -> b`
where a, b, c are the names of the pegs from left to right

![](http://www.codenuclear.com/wp-content/uploads/2017/08/Tower_of_Hanoi.jpg)

### Extension:
8 Queen Problem
![](https://letstalkdata.com/wp-content/uploads/2015/08/8q_solved.png)

Input: The dimension of the board (Squares in a length of board), n
Output: A way to arrange the queens without them 'killing each other'. Print out the coordinates of each queen in the successful arrangement, with the top-left square being (0,0)

### Finisher:
Talk on Text Based Games which was talked about before half term.
