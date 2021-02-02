# Hello Git Instructions

---

## Make your edits to index.html

Open up index.html in the text editor of your choice. Following the comments in the HTML document, make any necessary edits (ex. meta tag, your name, your favourite food, etc.).

After saving your changes, make sure that you are tracking them. 

From the command line, you can add untracked files with the following command: 

`git add <filename>`

Alternatively, to track every file in your directory, use: 

`git add -A`

To make sure that everything was added correctly, you can follow up with:

`git status`

---

## Commit your changes

Next, commit your changes with the following command:

`git commit -m "<Your Message Here>"`

When writing your message, remember to use best practices. You should always write in the present tense (ex. 'this fixes a bug', not 'this fixed a bug') and your message should be descriptive, but your message should not be overly long.

When you've made your commit, you will be ready to submit your project. 

---

## Submitting your work

1. First, make sure the working tree is clean with `git status`.

2. Next, use the following commands:

`git branch -m main`

`git push -u origin main`

3. If this is your first time submitting anything from your machine, you will need to sign into your GitHub account. 

	**Note**: When typing your password you will not see any visual feedback (i.e. no bullet operators or asterisks). This is normal.

4. Congratulations! You're all set. 

