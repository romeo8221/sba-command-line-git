# sba-command-line-git

# This assessment contains 2 parts. Each part is explained below. You will have 60 minutes to complete the entire assessment (Parts 1 and 2).

## Part One: Git Basics

### Please follow the directions the below. You will be assessed on the completion of each step.

1. Fork a copy of this repository to _your_ GitHub account. 
2. Clone the _forked_ copy to your computer.
3. Add an `index.html` file to the root directory of the repository.
4. Open the index.html file in the nano text editor.
5. Add the following code to your `index.html` file.

````
<!DOCTYPE html>
<html lang="en">
  <head>
    <meta charset="UTF-8">
    <title>HTML 5 Boilerplate</title>
    <link rel="stylesheet" href="style.css">
  </head>
  <body>
    <h1>Command Line and Git SBA</h1>
	<script src="index.js"></script>
  </body>
</html>

````
6. Add the changes to the staging area.
7. Save the the changes to your local repository. Include as your message the full command you used to create the index.html file in step 3.
8. Send the changes to your remote repository.
9. Create a pull request

## Part Two: Command Line

### Please follow the directions the below. You will be assessed on the completion of each step.

### Setup: 
1.  You will need to create a replit.com account to complete this portion. This video provides directions: https://www.youtube.com/watch?v=ZAC0TQEU5gI
2. Start a new "Bash" repl
3. Click on the "Console" tab to run commands in a way similar to Git Bash or Terminal
4. Format your commands with single spaces between commands, options, and arguments. Ex.  `cp file1.txt file2.txt my_directory` `ls -a`

### Use the appropriate commands complete the steps listed below. 

1. Create a folder named `folder1`
2. Navigate to `folder1`
3. Add a file named `file1.txt` to `folder1`
4. Use text commands to add the following text to `file1.txt`: `"grapes\napples\noranges\nlimes\nlemons\napples\ngrapes\npears\nberries\nlimes"` There should be one item per line in the file. Hint: You will need to use -e along with your command to ensure each item is on separate line (ex. `command -e "text here"`)
5. From your current location in the file system, create a folder named `folder2` that is a **_sibling_** of `folder1` using a single command
6. From your current location in the file system, Navigate to `folder2`using a single command
7. Add a file named `file2.txt` in `folder2`
8. Use text commands to add the following text to `file2.txt`: `"grapes\ngrapes\napples\noranges\nlimes\nlimes\nlemons\nlemons\ngrapes\npears\npears\nberries"` Hint: you will need to use -e along with your command to ensure each item is on separate line (ex. `command -e "text here"`)
9. Run the command: `exit` in the Shell
10. Click the `Shell` tab. Located next to the `Console` tab in your repl
11. Run the command `cat ~/.bash_history > my-history.txt`
12. Use the "Invite" button in the top right of the replit.com window to generate a sharable link (as showin in [video](https://www.youtube.com/watch?v=ZAC0TQEU5gI) linked here and above)
13. Take a screenshot of the Console showing the commands you used to complete the assignment
14. Submit your link to the Canvas submission page for this session
15. Submit your screenshot to the Canvas submission page for this session

