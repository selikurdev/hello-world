# hello-world
Follow this Hello World exercise to get started with GitHub.

# Introduction
GitHub is a code hosting platform for version control and collaboration. It lets you and others work together on projects from anywhere.

This tutorial teaches you GitHub essentials like repositories, branches, commits, and pull requests. You'll create your own Hello World repository and learn GitHub's pull request workflow, a popular way to create and review code.

In this quickstart guide, you will:
  
  Create and use a repository
  
  Start and manage a new branch
  
  Make changes to a file and push them to GitHub as commits
  
  Open and merge a pull request
  
To complete this tutorial, you need a GitHub account and Internet access. You don't need to know how to code, use the command line, or install Git (the version control software that GitHub is built on). If you have a question about any of the expressions used in this guide, head on over to the glossary to find out more about our terminology.

# Creating a branch
Branching lets you have different versions of a repository at one time.

By default, your repository has one branch named main that is considered to be the definitive branch. You can create additional branches off of main in your repository. You can use branches to have different versions of a project at one time. This is helpful when you want to add new features to a project without changing the main source of code. The work done on different branches will not show up on the main branch until you merge it, which we will cover later in this guide. You can use branches to experiment and make edits before committing them to main.

When you create a branch off the main branch, you're making a copy, or snapshot, of main as it was at that point in time. If someone else made changes to the main branch while you were working on your branch, you could pull in those updates.

This diagram shows:

The main branch
A new branch called feature
The journey that feature takes before it's merged into main
Diagram of the two branches. The "feature" branch diverges from the "main" branch, goes through stages for "Commit changes," "Submit pull request," and "Discuss proposed changes," and is then merged back into main.

Have you ever saved different versions of a file? Something like:

story.txt
story-edit.txt
story-edit-reviewed.txt
Branches accomplish similar goals in GitHub repositories.

Here at GitHub, our developers, writers, and designers use branches for keeping bug fixes and feature work separate from our main (production) branch. When a change is ready, they merge their branch into main.

Create a branch
Click the Code tab of your hello-world repository.

Above the file list, click the dropdown menu that says main.
Screenshot of the repository page. A dropdown menu, labeled with a branch icon and "main", is highlighted with an orange outline.

Type a branch name, readme-edits, into the text box.

Click Create branch: readme-edits from main.

Screenshot of the branch dropdown for a repository. "Create branch: readme-edits from 'main'" is outlined in dark orange.
Now you have two branches, main and readme-edits. Right now, they look exactly the same. Next you'll add changes to the new branch.

Making and committing changes
When you created a new branch in the previous step, GitHub brought you to the code page for your new readme-edits branch, which is a copy of main.

You can make and save changes to the files in your repository. On GitHub, saved changes are called commits. Each commit has an associated commit message, which is a description explaining why a particular change was made. Commit messages capture the history of your changes so that other contributors can understand what you’ve done and why.

Under the readme-edits branch you created, click the README.md file.

To edit the file, click .

In the editor, write a bit about yourself. Try using different Markdown elements.

Click Commit changes....

In the "Propose changes" box, write a commit message that describes your changes.

Click Propose changes.

These changes will be made only to the README file on your readme-edits branch, so now this branch contains content that's different from main.
