My First Project
Added a description
This is branch-A change
This is branch-B change

# Git and Version Control Guide

## Part 1: Introduction to Version Control and Git

### Task 1: Install and Configure Git
- Configure Git with your username and email:
  ```bash
  git config --global user.name "Your Name"
  git config --global user.email "your-email@example.com"

### 2.View your Git configuration
- Use git config --list to verify your configuration.
   ```bash
   git config --list


### Task 2: Initialize a Repository
- git init sets up a Git repository in the current folder. The .git folder contains all necessary
 information for version control.
   ```bash
   git init

### Task 3: Create a File and Make Multiple Commits

 - This demonstrates the core Git workflow: making changes, staging, and committing.
 - echo for file create
 - 
   ```bash
   echo "My First Project" > README.md
   git add README.md
   git commit -m "Initial commit: Added README.md"
   echo "Added a description" >> README.md
   git add README.md
   git commit -m "Updated README with a description"


### Task 4: Check Status and Log
 - git status shows the current state of the working directory.

   ```bash
     git status
 - git log provides a history of commits. The --oneline flag condenses it for readability.

   ```bash
    git log --oneline --graph --decorate

### Task 5: Create and Clone a Repository
  - for clone

    ```bash
      git clone http://YASAR300/-repo