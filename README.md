Github Documentation:

1. Creating a GitHub Account
If you don't have a GitHub account, you need to sign up for one at github.com.

2. Installing Git
Git is a version control system that GitHub is built on. Install Git from git-scm.com if you haven't already.

3. Setting Up Git
Configure Git with your username and email address using the following commands:

```
git config --global user.name "Your Name"
git config --global user.email "youremail@example.com"
```
4. Creating a New Repository
Click on the "+" sign in the top-right corner of GitHub and select "New repository".
Choose a name for your repository, add a description if needed, and select other options like visibility (public or private).
Click on "Create repository".

5. Cloning a Repository
To work on an existing repository locally, you need to clone it to your computer:
```
git clone https://github.com/yourusername/repository-name.git

```

6. Making Changes
Navigate to the cloned repository directory.
Make changes to files using any text editor or IDE.
7. Staging Changes
Use the git add command to stage changes for commit:

```
git add filename   # Stage a specific file
git add .          # Stage all changes
```

8. Committing Changes
Commit staged changes with a descriptive message:
```
git commit -m "Your commit message"
```
9. Pushing Changes
Push committed changes to the remote repository:

```
git push origin branch-name
```

Replace branch-name with the name of the branch you're working on, typically main or master.

10. Pulling Changes
If there are new changes in the remote repository, pull them to your local repository:
```
git pull origin branch-name
```

11. Branching and Merging
Create a new branch to work on a new feature or fix:
```
git checkout -b new-feature
```
