# Galti-Se-Mistake
A repository used for our "Good First Bug" Sessions where we walk the participants through the process of contributions on a Git Version control environment.

## Objective

The objective of this exercise is to introduce beginners to basic Git and GitHub commands. By completing this exercise, participants will gain hands-on experience with version control and collaboration using Git and GitHub.
## Structure Overview

### Initialization
If we decide to initialize a new repository, we need to use the git init command. It turns the current directory into a Git repository and starts tracking its content:

```bash
$ mkdir simple-repo; cd simple-repo; git init
Initialized empty Git repository in /simple-repo/.git/
```
Git also creates a hidden directory called .git in it. This directory stores all the objects and refs that Git creates and uses as part of our project’s history. 

After that, in most cases, we want to connect our already created repository with a remote one. We use the git remote command to manage remote links for the current repository:

```bash
$ git remote add origin https://github.com/mukticommunity/tutorials.git
```

We’ve just added a new remote called origin and connected it to the official MUKTI GitHub repository.

### Workflow

Our local repository consists of three different trees maintained by Git.

The first one is the **Working Directory**, which holds the actual version of files.

After making our changes to the files, we can move the files into **Index**, which acts as a staging area. We do this using the git add command. Files in Index begin to be tracked by Git.

Finally, we can apply and save our changes into the **Local Repository **using the git commit command. Committing the changes updates the repository’s HEAD, which always points to the last commit we’ve made.

Those three steps are used to maintain the local changes. But as we know, the repository may also contain an external source. The last step is to synchronize both repositories and publish our changes.

![image](https://github.com/MuktiCommunity/Galti-Se-Mistake/assets/152704361/43ebc787-0d57-489c-a3a0-4b361dbe8d77)


## Instructions

### Step 1: Set Up Your GitHub Account

1. If you don't have a GitHub account, [create one](https://github.com/join).
2. Log in to your GitHub account.

### Step 2: Fork the Repository

1. Go to the exercise repository: [Galti-Se-Mistake](https://github.com/MuktiCommunity/Galti-Se-Mistake).
2. Click on the "Fork" button in the top right corner to create a copy of the repository in your GitHub account.

### Step 3: Clone the Repository Locally

1. On your forked repository, click on the "Code" button and copy the repository URL.
2. Open your terminal (or Git Bash on Windows).
3. Navigate to the directory where you want to clone the repository.
4. Run the following command:

    ```bash
    git clone <repository-url>
    ```

   Replace `<repository-url>` with the URL you copied.

### Step 4: Add Your Name to Contributors

1. Navigate into the cloned repository:

    ```bash
    cd Galti-Se-Mistake
    ```

2. Open the `contributors.md` file using a text editor or run:

    ```bash
    touch CONTRIBUTORS.md
    ```

3. Add your name to the file, following the example:

```markdown
- [Name](Link to your GitHub Profile)
```

### Step 5: Commit Your Changes

1. Add your changes to the staging area:

    ```bash
    git add .
    ```

2. Commit your changes:

    ```bash
    git commit -m "Add your name to CONTRIBUTORS.md"
    ```

### Step 6: Push Changes to GitHub

1. Push your changes to your GitHub repository:

    ```bash
    git push origin main
    ```

   Note: If you are on a branch other than `main`, replace it with the name of your branch.

### Step 7: Create a Pull Request

1. On your GitHub repository, click on the "Pull Requests" tab.
2. Click the "New Pull Request" button.
3. Compare changes and click "Create Pull Request."

### Step 8: Merge Pull Request

1. After creating the pull request, click on the "Merge Pull Request" button.
2. Confirm the merge.

Congratulations! You've successfully completed the Git and GitHub exercise by adding your name to the `CONTRIBUTORS.md` file. This exercise covers basic concepts like forking, cloning, making changes, committing, pushing, and creating a pull request.
