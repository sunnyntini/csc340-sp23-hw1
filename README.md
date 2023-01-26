# csc340-sp23-hw1

This assignment is to make sure you are comfortable using Git. At the end, you will have created your own branch off of a main branch, made your own edits, pushed those edits to the source server, and will have sent a pull request to have your changes merged with the main branch. Be sure to add your GitHub name to the assignment "Give Me Your Github Username" located on this Canvas course. You will receive an invitation to participate in the project via email once I have uploaded your username to the GitHub repo. That's when you know you will have permission to push your changes to the GitHub server.

## Step One: Clone this repo to your local machine:
https://github.com/sunnyntini/csc340-sp23-hw1.git 

git clone [URL]

## Step Two: Create your own branch.
Name it your first initial and your last name. ie. Mark Smith would be msmith 

git checkout -b [BRANCH NAME]

## Step Three: Open the file AboutMe.txt and edit it in a plain text editor.
Add your name, underline it using dashes. Write a short paragraph about yourself.

## Step Four: Add the edited file to the commit.

git add --all

## Step Five: Commit your file.

git commit -m "Write a brief description of why you are making this commit."

## Step Six: Pull from the main branch into your branch.
More edits may have been to the document from other users in the time it took you to clone the file and update it.
To resolve any potential conflicts and make sure your document is up-to-date, pull from Main again.
Note, if there are any updates or merge conflicts that have to be resolved, Go to Step 4.

git pull origin main

## Step Seven: Push your branch to origin.

git push origin [BRANCH NAME]

## Step Eight: Log into GitHub and make a pull request.

Note: This file is public. Do not add any information that you would not want someone to read who might happen upon it.

Also Note: When editing the text file, do not use a word processing program. This will add formatting characters that can break the readability of a plain text file. Use a text editor such as Notepad++ or SublimeText. The file type should remain as .txt, not .rtf, or .pdf, or .doc, or .docx.

Submit a link to the pull request that you created.