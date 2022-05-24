### CSE 15L: Lab Report 4
*Week 8, 22 May 2022*

[Here](https://github.com/ryankosta/good-markdown-parser)'s the code we reviewed.

**Predicted Results**

According to VSCode preview:

Snippet 1: \[\'google.com, google.com, ucsd.edu]

Snippet 2: \[a.com, a.com(()), example.com]

Snippet 3: \[https://sites.google.com/eng.ucsd.edu/cse-15l-spring-2022/schedule]

**Testing Code**

![Snippet 1,2 & 3 JUnit Implementation](./Images/Screen%20Shot%202022-05-22%20at%2012.19.04%20PM.png)

![Test Files](./Images/Screen%20Shot%202022-05-22%20at%2012.25.08%20PM.png)

*My implementation*

![My implementation](./Images/Screen%20Shot%202022-05-22%20at%2012.32.48%20PM.png)

*Reviewed Implementation*
![Reviewed implementation](./Images/Screen%20Shot%202022-05-22%20at%2012.48.14%20PM.png)

*Commenting on the Test Results*
- My implementation could be improved to address backticks using small changes. This could be addressed by adding if statements to check for them. 
- Addressing the interesting brackets cases would be more difficult as this would require tracking opening and closing brackets. I think this would take more than 10 lines as you would need a stack to track them and make sure the opening and closing parentheses matched up.
- I believe addressing the third snippet would require small changes. We could check for "/n" characters and then remove them by concating the two separate substrings that it divides. If the resulting string is valid then the link would be added. If not then it could be ignored.




