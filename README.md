# Software Engineering (2603-SEG2202)

Welcome to the supplementary repository for the **Software Engineering (2603-SEG2202)** course.

## Introduction

This repository serves as an **optional extra step** designed to help you get familiar with **Git** and **GitHub**, which are essential tools in modern software development.

**Important Notes:**
*   This activity is **completely optional** and carries **no extra marks**.
*   This **DOES NOT** replace the official assignment submission process. You **MUST** submit your assignments to the **eLearn portal** for grading. That is the submission that counts.

## How to Use This Repository

Follow these instructions to set up your own personal version of this repository.

### 1. Set Up Your Private Repository

You need to create your own copy of this repository so that you can work on it independently. You must create a separate entity so that your pushes go to your own account and not to the instructor's repository.

1.  **Clone this repository** to your local machine.
    ```bash
    git clone https://github.com/SinaAbdipoor/2603-seg2202
    cd 2603-seg2202
    ```

2.  **Create a new repository** on your own GitHub account.
    *   **Crucial Step:** Make sure to set the visibility to **PRIVATE** so other students cannot see your code.
    *   Do not initialize it with a README, .gitignore, or license (start empty).

3.  **Point your local code to your new private repository**:
    In your terminal (inside the folder you just cloned), run the following commands to remove the link to the course repository and add your own:
    ```bash
    # Remove the link to the instructor's repository
    git remote remove origin

    # Add the link to YOUR new private repository
    git remote add origin https://github.com/YOUR-USERNAME/YOUR-NEW-REPO-NAME.git

    # Push the code to your new repository
    # (Note: If your default branch is 'master', replace 'main' with 'master')
    git push -u origin main
    ```

### 2. Customize Your Repository

Now that you have your own private repo:
*   **Modify this README.md**: Delete these instructions and write your own introduction, notes, or documentation for your assignments.

### 3. Managing Assignments

There are 4 assignments in this course. For each one:
1.  Complete your assignment work.
2.  **Submit it to the eLearn portal first.** (This is the mandatory step for grading).
3.  Create a folder in your repository (for example, create a folder named `Assignment_1`).
4.  Add your work to that folder and push the changes to your private GitHub repository:
    ```bash
    git add .
    git commit -m "Upload Assignment 1"
    git push
    ```

## Need Help?

If you want to learn more about Git and GitHub, if you are confused by these instructions, or if you want to check with me whether you are doing it correctly, please **ask me during our classes**.