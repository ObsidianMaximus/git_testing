## Objective

Manage a DevOps project using Git best practices.

## Tools

- **Git**
- **GitHub**

## Deliverables

- Project repository with:
  - Proper commit history
  - Branching strategy (main, dev, feature branches)
  - Pull request usage for merges
  - Well-structured documentation

## Steps

1. **Initialize Repository**
   - Open your terminal in the project folder.
   - Run:
     ```sh
     git init
     ```
   - Add your files:
     ```sh
     git add .
     git commit -m "Initial commit"
     ```
   - Create a new repo on GitHub, then link and push:
     ```sh
     git remote add origin https://github.com/<your-username>/<your-repo>.git
     git push -u origin main
     ```

2. **Branching**
   - To create and switch to a dev branch:
     ```sh
     git checkout -b dev
     git push -u origin dev
     ```
   - To create a feature branch:
     ```sh
     git checkout -b feature
     git push -u origin feature
     ```
   - Always keep `main` as your stable branch.

3. **Pull Requests**
   - Push your feature branch to GitHub.
   - On GitHub, open a Pull Request to merge your feature branch into `dev` (or `dev` into `main`).
   - Request reviews, resolve any conflicts, and merge when approved.

4. **Documentation**
   - Add a `README.md` with project info and instructions.
   - Use markdown for documenting other tasks or features.

5. **.gitignore and Tags**
   - Create a `.gitignore` file to exclude files/folders (e.g., `.env`, `node_modules/`).
   - Tag important commits:
     ```sh
     git tag v1.0.0
     git push origin v1.0.0
     ```

## Outcome

You’ll learn essential version control workflows and Git best practices.
