# STAT 19000
The official STAT 19000 GitHub repository

- Class website: http://www.stat.purdue.edu/datamine/19000
- Class time: Thursdays at 5:00 -- 5:50 PM @ Hillenbrand dining court atrium

## Table of Contents

- [Create a GitHub account](#create-a-github-account)
- [Homework guidelines](#homework-guidelines)
- [How to submit assignments](#how-to-submit-assignments)
- [Grading guidelines](#grading-guidelines)
- [Office hours](#office-hours)

## Create a GitHub Account
If you already have a GitHub account, do not worry about making a new one-- just skip this part!

- Go to github.com
- Fill in the sign-up form on the main page and press 'Sign up for GitHub'

Example sign up form:
![](images/readme/signup_1.png)

- On the next page, press the green 'continue' button:
![](images/readme/signup_2.png)

- The next portion is a survey. Fill it out, or press 'skip this step':
![](images/readme/signup_3.png)


You are now the proud owner of a GitHub account! The next step is to add your name to your profile, so we can better identify you.

- Press your profile icon and click 'Your profile' from the dropdown:
![](images/readme/add_name_1.png)

- On your profile page, click 'Edit profile':  
![](images/readme/add_name_2.png)

- Add your name, first and last:  
![](images/readme/add_name_3.png)

- Press 'Update profile' to save your changes.

**Once you are done creating your account, email your name, purdue ID, and GitHub username to Dr. Ward (mdw@purdue.edu) so we can create your assignment repository!**


## Homework guidelines

We **insist** that everyone document sources of help during the projects. It is **not** OK to copy-and-paste code from classmates or from the web. If a classmate or a website is helpful to you, that is OK as long as you document the source of help, and as long as you still create your own solution and make your own individual comments about the code. It is OK to help each other, but comprehending the material in this class fully is critical.

For projects 1 and 2, the assignments will submitted as text documents (.txt) (Do NOT submit a Microsoft Word file.) Text documents can be created on the Scholar cluster by using one of several text editors. The easiest of these to use is gedit, but nano, emacs, and vi (my favorite) are also options. To open gedit, either find it in the Applications menu or simply type gedit in the terminal.
A sample of how we want the homework to be formatted in the document is shown below.
```
2a.  Use the ls command to learn which of the resulting .csv files is biggest in
	terms of bytes.  How many bytes does this largest file have?

	# lists the contents of the working directory including file size, file permissions, etc
	ls -l
	702878193

	The largest file was 2007.csv with 702878193 bytes.

	2b.  Use the wc command to learn which of the resulting .csv files has the most lines.  How many lines does this largest file have?

	# counts number of lines in all .csv files
	wc -1 *.csv | sort -n
	7453216 2007.csv

	The most lines are in 2007.csv with 7453216 lines.
```

Please copy the question exactly from the problem set, and add **solutions with comments** (explain what the code is doing in the comments). Paste the output of the command into the document below the solution (if more than 10 lines, please just give me either the first or last 10 lines to make the solutions more readable). Write a short sentence explaining the output in the context of the problem.

> The projects later in the semester (after the first few weeks) will be written in RMarkdown. A similar format will be expected on those as well. We will send out an email after the class goes over RMarkdown with a sample of what a project in RMarkdown should look like. 

Continue to the [next section](#how-to-submit-assignments) to learn how to submit your work for grading

## How to submit assignments

### For first-time submissions
- Check your email inbox for a repository invite
    - If you can't find an invite, navigate to https://github.com/thedatamine/FIRSTNAME-LASTNAME
- Accept the invite
- Continue to the [next step](#for-return-customers)

### For return customers
- Go to https://github.com/thedatamine
- Click on the repository named after you (ex. Peggy-Sue):
![](images/readme/submit_1.png)
- You should now be on your assignment repository page:
![](images/readme/submit_2.png)
- Click on the button labeled 'Upload files':  
![](images/readme/upload_button.png)

- Drag and drop your project file
- Press 'Commit changes' to submit your work

If all went well, you should now see your submitted work in your assignment repository!

## Grading guidelines

- Each project will be out of 10 points
- All grades will be posted on [Blackboard](https://mycourses.purdue.edu/)

Project deadlines are subject to change if the majority of individuals have not finished the project. Once a project deadline has passed however, we will reduce by 10 percent per day from the individuals who have not submitted their project solutions. 

## Office hours
Detailed office hours and contact information can be found [here](http://www.stat.purdue.edu/datamine/19000/)
