# Contributing Guide (Beginner Friendly)

## Prerequisites
- A GitHub account
- Git installed on your computer
- A code editor (VS Code is fine)

## Before You Start
- Be kind and respectful
- Ask questions if you’re stuck
- Small changes are welcome (typo fixes, docs, examples)

## Step-by-step: Your First Pull Request

### 1) Fork this repository
- Open this repo on GitHub
- Click **Fork** (top-right)
- This creates your own copy under your account

### 2) Clone your fork to your computer
- Open your fork on GitHub
- Click **Code** → copy the URL
- Run:

    git clone <PASTE_YOUR_FORK_URL>
    cd Introduction-To-Open-Source

Example:

  git clone https://github.com/<your-username>/Introduction-To-Open-Source.git

### 3) Create a new branch
- Keep main clean
- Create a branch for your change:

    git checkout -b my-first-change

### 4) Make your changes
- Pick a beginner task in the [practice/](practice/) folder
- Edit files carefully
- Keep changes small

### 5) Check your changes
- Make sure the markdown looks okay
- Quick check:

    git status
    git diff

### 6) Commit your changes
- Stage your changes:

    git add .
- Commit with a clear message:

    git commit -m "Add my name to practice list"

### 7) Push your branch to GitHub
- Push your branch:

    git push -u origin my-first-change

### 8) Create a Pull Request (PR)
- Go to your fork on GitHub
- You should see a button like **Compare & pull request**
- Fill in:
  - What you changed
  - Why you changed it
- Click **Create pull request**

## After You Open a PR
- A maintainer may:
  - Ask for small changes
  - Leave comments
  - Merge your PR
- If you need to update your PR:
  - Make edits

    git add .
    git commit -m "Fix review feedback"
    git push

## Code of Conduct (Basics)
- Be respectful
- Be patient with beginners
- No harassment or rude comments
- Give helpful feedback

## DO’s and DON’Ts

### DO
- Read the README first
- Keep PRs small
- Write clear commit messages
- Link to the issue (if there is one)
- Ask for help if you’re stuck

### DON’T
- Don’t edit unrelated files
- Don’t spam with many tiny PRs at once
- Don’t copy large code from other sources
- Don’t be rude in comments

## Need Help?
- Open an issue with:
  - What you tried
  - What happened
  - Screenshots (optional)
