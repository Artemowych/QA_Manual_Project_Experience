# [My repositorie](https://github.com/Artemowych/HW_10.git)
#### Task 1. Working with `.gitignore`
1. Clone the repository (created in step 7) to your local machine.
2. Navigate to the cloned repository on your local machine using the `cd` command.
3. Create a file named `text_ignore.txt` via the terminal using `touch`.
4. Edit the `.gitignore` file and add the file name `text_ignore.txt` to it (simply add the line `text_ignore.txt` to `.gitignore`).
5. Make sure that the `text_ignore.txt` file is not tracked by Git by running the `git status` command.
6. Stage all changes using the command:
   ```bash
   git add .
   ```
7. Create a commit to save your changes.
---
#### Task 2. Creating Commits
1. Create an empty file named `main_test.txt`.
2. Stage all changes using the command:
   ```bash
   git add .
   ```
3. Create a commit to save your changes.
---
#### Task 3. Working in Another Branch
1. Create a branch named `develop` and switch to it using the `checkout` command.
2. Create an empty file named `develop_test.txt`.
3. Stage all changes using the command:
   ```bash
   git add .
   ```
4. Create a commit to save your changes.
5. Make any changes to the `develop_test.txt` file, for example, add the line:
   ```
   just a small change
   ```
6. Check the changes using the `git status` command.
7. Stage all changes using the command:
   ```bash
   git add .
   ```
8. Create a commit to save your changes.
---
#### Task 4. Merging Branches
1. Switch to the `main` branch using the `checkout` command.
2. Merge the `develop` branch into `main` (or `master` if `main` does not exist).
3. Review the commits using the `git log` command.
---
#### Task 5. Pushing All Changes to the Repository
1. Export the command history using Git Bash:
   * **Windows:**
     ```bash
     history > command_list.csv
     ```
   * **macOS:**

     ```bash
     history 0 > command_list.csv
     ```
   (This file will appear in the directory where you completed the homework.)
2. Stage all changes using the command:
   ```bash
   git add .
   ```
3. Create a commit to save your changes.
4. Run the `git push` command to upload all changes to the remote repository.

