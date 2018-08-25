# STAT 19000
The official STAT 19000 GitHub repository


## Table of Contents

- [Create a GitHub account](#create-a-github-account)
- [Homework submission guidelines](#homework-submission-guidelines)
- [How to submit assignments](#how-to-submit-assignments)
- [View your grades](#view-your-grades)
- [Office hours](#office-hours)

## Create a GitHub Account
> If you already have a GitHub account, do not worry about making a new one-- just skip this step!

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

**Once you are done creating your account, email your name and GitHub username to a STAT 190 TA so we can create your assignment repository!**


## Homework submission guidelines


For assignments where work is done in the command line, follow this general procedure:

1. Create a folder called ```project_##```. The ```##``` will be replaced by two-digit number for whichever project you are currently working on. For example, ```project_01``` will contain all files related to project 1.

2. Create a text file called ```solutions.txt```, and write all your solutions in it
    - Format your solution file to look like this:
        ```
        # 1a
        # <optional short explanation>
        <code>
        ---
        <output>


        # 1b
        # get ages, and print the top 5 highest values
        cat file.csv | cut -d, -f10 | sort | head -n5
        ---
        33
        34
        52
        55
        92


        # 2
        cat file.csv | egrep -i '[a-z]' > file.txt


        # 3
        cat file.csv | sort | tail -n4
        ---
        joe     47
        amy     52
        carl    77
        james   81
        ```
    You won't be penalized for small mistakes in your formatting, but please do your best to adhere to this format! It makes the TAs' lives easier.

    - For problems that produce very long answers, limit your output to *at most* 10 lines
        - The ```head``` command is your friend
    - Clearly number and separate individual problems

    > Feel free to add comments to your code to add clarity, especially if you create files. Help your graders understand your solutions!

3. Place ```solutions.txt``` and any other relevant files you may have created into ```project_01```

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

- Drag and drop your project folder
- Press 'Commit changes' to submit your work

If all went well, you should now see your submitted work in your assignment repository!

## View your grades
All grades will be posted on [Blackboard](https://mycourses.purdue.edu/).

## Office hours

- All office hours will be temporarily held in Dr. Ward's office
- Office hours may change during the first couple of weeks of this course

|                      | Monday        | Tuesday      | Wednesday     | Thursday      |
|----------------------|---------------|--------------|---------------|---------------|
| Dr. Ward             |               |              | 7:00-8:00 AM  |               |
| Elizabeth Bell (UTA) |               | 3:00-4:00 PM |               | 3:00-4:00 PM  |
| Luke Francisco (UTA) | 1:30-3:30 PM  |              |               |               |
| Tyler Netherly (UTA) |               | 5:00-7:00 PM |               |               |
| Tim Park       (UTA) | 5:00-6:00 PM  | 4:00-5:00 PM |               |               |
| Sehwan Kim     (GTA) | 9:45-10:45 AM |              | 9:45-10:45 AM |               |
| Yuki Ohnishi   (GTA) |               | 2:00-3:00 PM |               | 2:00-3:00 PM  |
| Juan Shu       (GTA) |               |              |               | 8:30-10:30 AM |
| Yumin Zhang    (GTA) |               |              | 3:00-5:00 PM  |               |
