## Assignment Description

Welcome to your very first assignment!! The goal of this assignment is to introduce you to GitHub Classroom and let you get comfortable using the platform to submit your work. We're using this platform to provide you with an excuse to practice using version control every day. 

To show that you are able to `add`, `commit`, `push`, and `pull` from GitHub, you will clone this repository to your desktop and perform the following actions.

1. Open the RProject in your RStudio console. Browse the different files, particularly the `github-basics.md` file and the `starter-markdown.rmd` file. Use the `starter-markdown.md` file as a place to grab code from if you can't remember how to write things in markdown. 
2. In the base of your folder (in your most basal folder, where the `/data` folder and all other files are), create an RMarkdown file, use the title "Assignment 1" and put your name as the author. Select the default output format as `pdf`. Click `OK`. Now, you will have an RMarkdown tab open, called `Untitled1`. Save this file as `assign-1.rmd`. Delete all the example code from line 8 down. 
3. In this file, please write the following:

    a. Your name  
    b. Your home university in bold  
    c. Your favourite colour in italics  

    Create a code block. In this code block:

      Create two vectors:
        
        ```{r}
        x = c(1,2,3)
        y = c(3,4,5)
        ```
    - Form those two vectors into a dataframe called data with column names x and y
    - Using the `here()` package and function, write that dataframe to a `.csv` file in the `/data` folder of this repository, and call it `student-data.csv`

4. Commit your changes to the file. We will grade the last commit to your repo before the due date. 

**This assignment is worth 2% of your final grade.**

That's it!


