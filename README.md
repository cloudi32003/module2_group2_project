# module2_group2_project

Hello team! this will be the weather application that SCTP Group 2 is going to developed for our first project! It should consist of the following four pages (the name i just set first, please kindly change if you feel that we should rename it)

Do remember once you clone/brance, do a npm install all the dependencies.

# Introduction.js - Bindu
Main purpose is to set a stage to ask user on some information:
1. What is your name?
2. Where do you live?
3. Where do you work?
4. Any planned activity(s) for the next 24 hours?

# MainPage.js - Andrew
Main purpose is to drag out weather api data and allow it to show in ViewMainPage.js

# EmptyForm.js - Johnny
Main purpose is to have a form to add,update and delete user dummy data (UsersData.js)

# UsersData.js - Bindu
Main purpose is to store dummy data to keep some of the users input (representing an api)

# ViewMainPage.js (Newly Added) - Manyu/Andrew
Main purpose is for the visual for main page.
- Reason why i put me or andrew is cause i thought andrew might need this page to show the data to confirm if his logic works.
- but i also understand his page will be the toughest, hence, let me try to share the load.

# module.css - Manyu
- styles for individual pages.

About git, you can use the timestamp in the video to learn about branching
and pull request which we will need for our group project.

https://youtu.be/S7XpTAnSDL4?si=0-utAJyfhkoTPp87

Clone the repository
git clone https://github.com/username/repo.git

Change to the repository directory
cd repo

Create a new branch
git checkout -b feature-branch

*** check you are on the Branch
git branch
- *Form
- main

Make your changes
Stage your changes
git add .

Commit your changes
git commit -m "Add new feature"

Push your branch to GitHub
git push origin feature-branch >>> git push origin form

Create a pull request on GitHub
Go to your repository on GitHub
Click on "Compare & pull request"
Select "main" as the base branch and "feature-branch" as the compare branch
Click on "Create pull request"
Team reviews, comments, and approves
Once approved, you merge the pull request

<<<<<<<<<<Make sure is on my Branch: form, git checkout branch>>>>>>>>>>
- git add . (to add all files)
- git commit -m "your message"
- git push origin your-branch-name

1) Set Manyu’s origin repo as upstream.

👉🏼 git remote add upstream https://github.com/Mmanyuu/module2_group2_project

2) Then fetch and merge the repo to your machine and update your local repo

👉🏼 git pull upstream main 

Now your local repo is updated.

If you want to update YOUR OWN GitHub repo just use the normal 

👉🏼 git push origin main 

Now both your local and remote repos are updated.
