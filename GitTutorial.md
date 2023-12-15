# Git and GitHub Exercise for Beginners

## Objective

The objective of this exercise is to introduce beginners to basic Git and GitHub commands. By completing this exercise, participants will gain hands-on experience with version control and collaboration using Git and GitHub.

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
    ## Contributors

    - Your Name
    ```

   Replace "Your Name" with your actual name.

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
