# github-demo-cap
This repo is created for learning GitHub.

# Detail

- Name -> Pravin
- Batch -> CAP08


## Detailed Content

### 1. Introduction to GitHub

**What is GitHub?**

- A web-based platform for version control and collaboration.
- Built on Git, a distributed version control system.

**Why Use GitHub?**

- Collaborate on projects with others.
- Track changes to your codebase.
- Contribute to open-source projects.
- Showcase your work and build a portfolio.

**Basic Concepts and Terminology**

- **Repository (Repo)**: A project containing all the files and their history.
- **Commit**: A snapshot of your changes.
- **Branch**: A parallel version of your repository.
- **Fork**: A personal copy of another user's repository.
- **Pull Request**: A proposal to merge changes from one branch to another.
- **Issue**: A way to track tasks, enhancements, and bugs.

### 2. Setting Up GitHub

**Creating a GitHub Account**

- Visit [GitHub](https://github.com/) and sign up for a free account.

**Installing Git**

- Download and install Git from [Git-scm](https://git-scm.com/).
- Configure Git with your GitHub credentials:
    
    ```bash
    git config --global user.name "Your Name"
    git config --global user.email "your-email@example.com"
    
    ```
    

### 3. Basic Git Commands

**Git Workflow**

- Initialize a repository
- Stage changes
- Commit changes
- Push to a remote repository

**Common Git Commands**

- `git init`: Initialize a new Git repository
- `git clone <repository-url>`: Clone a repository
- `git add <file>`: Stage changes
- `git commit -m "commit message"`: Commit changes
- `git push`: Push changes to a remote repository
- `git pull`: Fetch and merge changes from a remote repository

### 4. Working with GitHub

**Creating a New Repository**

- Click on the "New" button on GitHub.
- Fill in the repository details and create.

**Cloning a Repository**

- Use the `git clone` command with the repository URL:
    
    ```bash
    git clone <https://github.com/username/repository.git>
    
    ```
    

**Committing Changes and Pushing to GitHub**

- Make changes to your files.
- Stage and commit changes:
    
    ```bash
    git add .
    git commit -m "Initial commit"
    git push origin main
    
    ```
    

**Pull Requests and Code Review**

- Create a new branch for your changes.
- Push the branch to GitHub.
- Open a pull request on GitHub for code review.

### 5. Collaboration on GitHub

**Forking Repositories**

- Click the "Fork" button on the repository page to create a personal copy.

**Using Branches**

- Create a new branch:
    
    ```bash
    git checkout -b new-branch
    
    ```
    
- Switch between branches:
    
    ```bash
    git checkout main
    
    ```
    

**Merging Branches**

- Merge changes from one branch to another:
    
    ```bash
    git checkout main
    git merge new-branch
    
    ```
    

### 6. Managing Issues and Projects

**Creating and Managing Issues**

- Navigate to the "Issues" tab in your repository.
- Click "New issue" to create an issue.

**Using GitHub Projects for Task Management**

- Create a new project from the "Projects" tab.
- Add issues and pull requests to the project board.

### 7. GitHub Pages

**Introduction to GitHub Pages**

- A service to host static websites directly from a GitHub repository.

**Hosting a Website on GitHub Pages**

- Create a new repository or use an existing one.
- Create an `index.html` file in the repository.
- Enable GitHub Pages from the repository settings.

### 8. Best Practices and Tips

**Writing Good Commit Messages**

- Keep messages clear and concise.
- Use imperative mood (e.g., "Add feature" instead of "Added feature").

**Using `.gitignore`**

- Create a `.gitignore` file to exclude files and directories from being tracked.
- Common entries include `node_modules/`, `.env`, and `.log`.

**Keeping Your Repository Clean and Organized**

- Regularly merge branches.
- Delete obsolete branches.
- Use descriptive names for branches and commits.
