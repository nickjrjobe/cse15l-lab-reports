### CSE 15L: Lab Report 5
*Week 10, 5 June 2022*

*Finding the tests with different files*

I wrote the results from the running the test-files with the provided implementation in a file results.txt. Then, I 
wrote the results from the running the test-files with the my implementation in a file myresults.txt. I used
vimdiff to compare the two files and it highlighted the difference. See screenshot below:

![Vimdiff Results](./Images/Screen%20Shot%202022-06-02%20at%202.55.44%20PM.png)

*TEST ONE*

[Here](https://github.com/nidhidhamnani/markdown-parser/blob/main/test-files/194.md)'s the link to the first failing test.

Expected:

![Expected Test 1](./Images/Screen%20Shot%202022-06-05%20at%2011.41.30%20AM.png)

Provided Implementation:

![Provided Actual 1](./Images/Screen%20Shot%202022-06-05%20at%2011.19.11%20AM.png)

My Implementation:

![My Actual 1](./Images/Screen%20Shot%202022-06-05%20at%2011.20.37%20AM.png)

Neither implementation is correct. The correct implementation should result in the link [my_(url)]. My implmentation is searching for whatever is
is in the brackets. My implementation does not consider that the links could contain brackets, and searches for only one way to format links. My 
implementation should check whether there are square brackets [] in order to know whether it is doing the right format check.



*TEST TWO*

[Here](https://github.com/nidhidhamnani/markdown-parser/blob/main/test-files/201.md)'s the link to the second failing test.

Expected:

![Expected Test 2](./Images/Screen%20Shot%202022-06-05%20at%2011.43.30%20AM.png)

Provided Implementation:

![Provided Actual 2](./Images/Screen%20Shot%202022-06-05%20at%2011.21.12%20AM.png)

My Implementation:

![My Actual 2](./Images/Screen%20Shot%202022-06-05%20at%2011.21.54%20AM.png)

My implementation is correct. The provided implementation should to check to make that there are [] before the (). 




