### CSE 15L: Lab Report 2
*Week 4, 24 April 2022*

**Github Code Differences**

![Github Screenshots](./Images/Updated%20Code.png)

**Failure Inducing Tests**

The following test files exposed bugs in the code:
- [Extra Line](https://github.com/nickjrjobe/markdown-parser/blob/main/extraLineTest.md)
![Extra Line](./Images/Extra%20Line%20Fail.png)
The extra line was stopping the loop from stopping when necessary. I wrote code to check if there was an extra line and break if it was there.

- [Image](https://github.com/nickjrjobe/markdown-parser/blob/main/imageLink.md)
![Image](./Images/Image%20Fail.png)
It treated images like hyperlinks. I wrote code to check if there was an exclamation before the link.

- [MissingBracket](https://github.com/nickjrjobe/markdown-parser/blob/main/missingBracketTest.md)\
![MissingBracket](./Images/Missing%20Bracket%20Fail.png)
Missing brackets triggered an index out of bounds exception. For wrongly formated links, I made the code ignore them.





