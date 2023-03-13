<h1 style="text-align: center;">Github Pages 💻🖥️</h1>

# Introduction

<p> Hello students 👋 In this repository we will check if your assignment passed the requirement. </p>

## Requirements:

A Word file with the link to the GitHub repository with your CV and screenshots from the first tasks.

## Steps:

### 1. Let's create a Word document where we will paste our output.

### 2. Create a new repository in your GitHub account. Name the repository "git-features" and make it public. Copy the link to your repository, and paste it into the Word document.

![step1](https://i.imgur.com/6I7LMTY.png)

### 3. Create a folder by going to VSCode terminal, and insert the `mkdir` command and go inside that folder by changing directory via the `cd` command. Make sure that you will open the folder on VSCode.

![step2](https://i.imgur.com/MyA5WSj.png)

### 4. Create a file, and name it "README.md" This file is necessary as an introduction to the repository files: it explains what the repository is for. For this assignment, write what you learned on GitHub features in this file.

![step3](https://i.imgur.com/W09eTxD.png)

### 5. Make sure you are in the newly created directory. Perform the following commands to initialize the repository:

```bash
git init
git remote add origin <https link of the created repository>
git add .
git commit -m "Learnings from GitHub Features"
git push origin master
```

![step4](https://i.imgur.com/H09xzUR.png)

### 6. Let's change the defualt branch name to "Refocus".

- Let's go to our remote repository on Github first and go to settings. When we are on the settings menu, navigate to "Branches" and click on the "Edit" button to rename the default branch name.

![step5](https://i.imgur.com/gOPPuoG.png)

### 7. Now let's upload our CV from the previous project to our Github. First we need to create a new repostory on our Github with the name "last-name-CV". Make sure to change the "last-name" to your own. We will then copy the link of our repository to our Word document.

![step6](https://i.imgur.com/P8FEKvT.png)

### 8. Go to the directory where you saved your whole project on HTML/CSS with your CV. Go to the VS Code terminal, and insert the cd "path-to-CV-folder" command.

### 9. Make sure you are in the correct directory. Perform the following commands in the directory with your CV:

```bash
git init
git remote add origin <https link of the created repository>
git add .
git commit -m "My Personal CV"
git push origin <default branch name>
```

---

# The End

<p> Don't worry if some of your approach is not the same on this repository, it doesn't mean that it is wrong. This is just a guide for you on how to make it. </p>
Happy Coding! 🧑‍💻👩‍💻
