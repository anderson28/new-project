# Project "new-project"

This project is created to demonstrate basic Git workflow.

## Developer Instructions

1. Clone the repository:
    ```bash
    git clone <repository URL>
    ```
   
2. Switch to the development branch:
    ```bash
    git checkout development
    ```

3. Make necessary changes in the README.md file using your preferred text editor.

4. Add changes to the staging area:
    ```bash
    git add README.md
    ```

5. Commit the changes with a descriptive message:
    ```bash
    git commit -m "Commit description"
    ```

6. Push the changes to the remote repository:
    ```bash
    git push origin development
    ```

7. Check the status and ensure everything is up to date:
    ```bash
    git status
    ```

8. Switch back to the main branch and merge the changes:
    ```bash
    git checkout main
    git merge development
    ```

9. Again, check the status and commit the changes:
    ```bash
    git status
    git commit -m "Merge changes from development branch"
    ```

10. Push the changes to the remote repository:
    ```bash
    git push origin main
    ```

11. Your changes are successfully uploaded and merged with the main branch.
