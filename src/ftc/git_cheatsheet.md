# Git Cheatsheet

## Creating a Branch

Once you have a coding task at hand, you should create a branch to separate the code you are writing from code which is already working and is tested.

### Commands

#### Creating and Entering a new branch

``` git checkout -b new-branch-name ```

#### Entering an existing branch

``` git checkout existing-branch-name ```

## Saving changes to Github (Commit & Push)

It is important to commit your changes often, whether you are done with coding for the day or you have finished making a feature. You should push commits regularly so that they are saved on Github just in case.

### Steps

1. Adds all the files which you have changed and new files

``` git add . ```

2. Create a commit with a short message describing what changes you have made

- Ex: "Added intake subsystem", "Saving changes on 06-04-2022"

``` git commit -m "put your commit message here" ```

3. Save your code to github by **pushing** your commits

- If the branch already exists

``` git push ```

- If you are pushing a new branch which isn't already on github

``` git push -u origin HEAD ```

## Creating a Pull Request

Once you make the changes you need to make to the robot code, you can send the code off for review to your captain by creating a pull request.

### Steps

1. Open your github repository on github (the fork which you created, not the repository on AHS-Robotics-Club)

2. Follow the instructions here https://docs.github.com/en/pull-requests/collaborating-with-pull-requests/proposing-changes-to-your-work-with-pull-requests/creating-a-pull-request#creating-the-pull-request

#### Notes

- Make sure you choose the correct base branch (step 4)
- Create a draft pull request if you're not quite done with your code yet (step 6)
