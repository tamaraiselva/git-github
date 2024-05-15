# GIT & GIT HUB

## Introduction to Git

### Learn Git: 

#### Beginner's Guide:

- Git is a distributed version control system used for tracking changes in source code during software development.

`git --version`

#### Understanding the Basics: 

- Git allows multiple developers to collaborate on a project simultaneously while keeping track of changes made to the codebase.

`git init`

#### Getting Started with Git:

- To start using Git, you need to install it on your system and configure your identity.

`git config --global user.name "Your Name"`

`git config --global user.email "your.email@example.com"`

## Collaborating Workflows

#### Exploring Collaborative Workflows: 
- Git facilitates collaboration through various workflows such as centralized, feature branch, Gitflow, etc.

## Syncing Operations
Overview of git fetch, git push, and git pull:

- **git fetch:** Fetches changes from a remote repository.

- **git push:** Uploads local repository changes to a remote repository.

- __git pull:__ Fetches changes from a remote repository and merges them into the current branch.

`git fetch origin`

`git push origin master`

`git pull origin master`

## Making a Pull Request

#### Step-by-Step Guide to Making a Pull Request: 

- After making changes in a feature branch, you create a pull request to merge those changes into the main branch.

##### Assuming you've already committed changes
`git checkout main`

`git pull origin main`

`git checkout -b feature-branch`

##### Make changes
`git add.`

`git commit -m "Your message"`

`git push origin feature-branch`

## Using Branches

### Introduction to Git Branches:

- Branches in Git are used to isolate work, experiment with new features, and make changes without affecting the main codebase.

`git branch feature-branch`

##### Working with git branch and git checkout commands:

- git branch: Lists all existing branches.
- git checkout: Switches to a different branch.

`git checkout feature-branch`

## Git Merge

### Explaining git merge operation:

-  Merging integrates changes from one branch into another.

`git merge feature-branch`

## Comparing Workflows

### Overview of Different Workflow Strategies:

#### Feature Branch Workflow: 

- Each feature is developed in a dedicated branch and merged into the main branch upon completion.

#### Gitflow Workflow: 

- A branching model focused on release management.

#### Forking Workflow: 

- Contributors work on their own forked copies of the repository.

## Migrating to Git

#### Why Migrate to Git?

- Git offers advantages such as distributed development, better collaboration, and a rich ecosystem of tools and services.

## SVN to Git Migration

### Preparing for SVN to Git Migration:

- Ensure that your SVN repository is clean and up-to-date before migrating to Git.

## Perforce to Git Migration

### Reasons to Migrate from Perforce to Git: 

- Perforce to Git migration enables teams to leverage Git's distributed nature and better collaboration features.

## Working with Git and Perforce

### Integrating Git and Perforce Workflow:

- Teams can work with both Git and Perforce repositories simultaneously using integration tools and workflows.

## How to Move a Git Repository with History

### Importance of Preserving Repository History: 

- Maintaining the history ensures traceability and helps in understanding the evolution of the codebase.

## Best Practices and Tips

### Tips for Effective Git Usage: 

- Regularly commit changes, write meaningful commit messages, and review code before merging.

## Conclusion

### Recap of Key Concepts Covered:

- Git provides powerful tools for version control and collaboration, essential for modern software development.

`git --help`

### Encouragement to Start Using Git:

- Start using Git today to streamline your development workflow and collaborate more efficiently.

### Additional Resources for Further Learning: 

- Explore online tutorials, documentation, and communities to deepen your understanding of Git.