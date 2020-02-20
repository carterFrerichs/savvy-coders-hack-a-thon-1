# Savvy Coders Hack-A-Thon 1: Student Showcase [template]

## Contributors
1.
2.
3.
4.
5.
6.
7.
8.
9.
10.
11.
12.
13.
14.
15.
16.
17.

## Setup
* Instructor forks template repo for product/integration repo
* Students fork the instructor's integration repo and clone it to their machine
* Students set up remote to instructor's repo
```
git remote add <repo name> <repo url>
```

## Student Directions
### Integrator Workflow
1. Edit the README.md file to add your name and a link to your GitHub page to the Contributors section
2. Add, commit, and push your changes to your public GitHub repo
3. On your public repo, create a new pull request and add a comment to describe your changes
4. After the instructor accepts and closes your request, update your repositories with the integration repo
```
git fetch --all
git reset --hard <repo name>/master
```
> **Integrator Workflow Loop (Developer)**
> * Push local commits to public repo
> * Submit pull request on GitHub
> * Fetch data from all remotes
> * Reset local codebase

### Student Showcase
Find the HTML block that corresponds to your number in the README and **only** edit that block to prevent merge conflicts.

Add the following features to your block:
* Your picture
* Your project name and a link to your project's GitHub
* Three of of the following:
  1. Contact/social media list
  2. A quote
  3. A list of hobbies or favorites
  4. A fun fact
  5. A bio paragraph
* Personalized CSS styling that only targets your block or the specific elements within your block

If students finish their blocks early, communicate among each other to work on styling the whole page including the background color, header, footer, and a summary paragraph.
