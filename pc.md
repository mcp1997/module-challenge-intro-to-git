## Research Questions 

Now that you are all set up, it's time to learn a little more about the tools of the trade. Edit this file and answer the following questions. You are going to need to start familiarizing yourself with the [GitHub docs](https://docs.github.com/en). Docs (short for documentation) are the instructions on how to use a languge or program. A large part of your job as a developer will be learning how to read and work with documentation. Please reference the GitHub docs when answering the questions below. If you cannot find what you are looking for in the docs, you can always start to practice your Google skills!

1. What is Git?
  Git is a version control system. It can maintain a repository with many collaborators and track any changes made to the repository, as well having the ability to roll back to any previous state of the repository.

2. What is the difference between Git and GitHub?
  Git is the version control system in of itself, while Github is an online server where repositories can be stored, cloned, modified and more by any collaborators.

3. Why do we create a branch?
  Creating a branch before pushing all code to the main branch can allow a team of collaborators to track all the changes made by individual collaborators and approve them before merging them with the main branch, to assure all changes are desired and working before changing the main code.

4. What is the purpose of a Pull Request?
  If code is open source with an infinite number of collaborators, it's often recommended to collaborate using forks, where each developer creates their own copy of the source code on their personal accounts and make whatever changes they see fit. If this code is then to be merged with the main project, a "Pull Request" is submitted with the changes, where the original authors can review and choose to merge them with the main code.

5. What is the command you can use to switch between branches? For example you are working on the FIRSTNAME-LASTNAME branch and you want to switch back to main.
  git checkout 'BRANCH-NAME'

6. Explain the difference between `git fetch`, `git merge` and `git pull`. What does each command do?
  git fetch downloads new data from a remote repository without integrating any changes into your local repository.
  git merge integrates, or merges any changes seen from the latest downloaded remote repository into the local repository.
  git pull is a combination of these commands.

7. What is a merge conflict?
  When two branches contain differing changes to the same file, for example, a merge conflict will happen when trying to combine the two branches into the main branch.

8. How do you resolve a merge conflict?
  A new commit must be made to resolve any competing changes before being able to merge a branch into the main one.
