# learnable-


## 	What is Version control? 

- Version control is a system that tracks changes to a project's code, enabling collaboration among developers, maintaining a historical record, and     facilitating efficient management of code alterations.Version control is crucial in software development, allowing teams to collaboratively manage code changes.

##  What is the difference between Git and GitHub? 

- Git is a distributed version control system that tracks changes in source code during software development. It operates locally on a developer's machine, allowing them to create branches, commit changes, and manage versions efficiently while GitHub, on the other hand, is a web-based platform that utilizes Git for version control. It provides a centralized hub where developers can store their Git repositories, collaborate on projects, and leverage additional features like pull requests, issue tracking, and code reviews. In essence, Git is the tool, while GitHub is the platform that hosts Git repositories and enhances collaboration.


##	List other GitHub alternatives
 - GitLab
- Bitbucket
- SourceForge


 ##	Write the difference between Git fetch and Git pull

In simple terms,the difference between Git Fetch and Git pull is that Git Fetch gets the latest changes from a remote repository but doesn't automatically merge them with your local code and Git pull on the other hand, gets the changes from the remote—but it also automatically merges them into your current working branch.

## Explain in simple terms, git rebase and the command for it. 

-Git rebase is a command used to reorganize or modify the commit history of a branch. It allows one to integrate changes from one branch into another by applying each commit on top of the destination branch. This can result in a cleaner and more linear commit history. This process can create a more straightforward, linear history compared to the potentially complex branching structure that can result from using git merge. 

The command for git rebase is 

   ```bash
   git checkout <your_branch>
   git fetch origin
   git rebase origin/main
   git rebase --continue
   git push origin <your_branch> --force
   ```


## Explain in simple terms, git cherry-pick and the command for it. 

-Git cherry-pick is a command in Git that allows you to apply a specific commit from one branch to another. It enables you to select a single commit and copy it to the current working branch without bringing the entire commit history.
To use git cherry-pick, you first identify the commit you want to copy using its commit hash, you switch to the branch where you want to apply this commit.
Using the command:

  ```bash
   git cherry-pick <commit-hash>
  ```
  
You replace <commit-hash> with the actual hash of the commit you want to pick and Git will apply the changes from the specified commit to your current branch.






