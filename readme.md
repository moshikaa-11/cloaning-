1. Aim

To learn how to clone a repository from GitHub, add or modify files, and upload the changes back to GitHub.

2. Introduction

GitHub is an online platform used to store, manage, and share source code. Git is a version control system that helps track changes made to files. By using Git and GitHub, developers can collaborate on projects and maintain different versions of their code.

3. Requirements

- A GitHub account
- Git installed on the computer
- A repository on GitHub
- A code editor such as Visual Studio Code
- An internet connection

4. Procedure

Step 1: Create or Select a Repository

1. Open [GitHub](https://github.com/) and sign in.
2. Create a new repository or open an existing repository.
3. Click the **Code** button.
4. Copy the repository's HTTPS URL.

Step 2: Clone the Repository

1. Open Command Prompt, Terminal, or the terminal in Visual Studio Code.
2. Navigate to the folder where you want to store the project.
3. Run the following command:

```bash
git clone https://github.com/USERNAME/REPOSITORY.git
```

Replace `USERNAME` and `REPOSITORY` with the appropriate GitHub username and repository name.

4. Move into the cloned repository folder:

```bash
cd REPOSITORY
```

Cloning downloads a local copy of the repository to your computer.

### Step 3: Add Content to the Repository

1. Open the cloned folder in a code editor.
2. Create a new file, such as `index.html` or `README.md`.
3. Add the required content and save the file.

For example, create a file named `README.md` and add:

```markdown
# My First GitHub Project

This project demonstrates how to clone a repository,
add content, and upload changes to GitHub.
```

### Step 4: Check the Changes

Run the following command:

```bash
git status
```

This command displays new, modified, and untracked files in the repository.

### Step 5: Stage the Changes

Use the following command to prepare the files for committing:

```bash
git add .
```

The command stages all eligible changes in the current repository folder. Make sure you do not stage passwords, API keys, or other private information.

### Step 6: Commit the Changes

Run:

```bash
git commit -m "Add project content"
```

A commit saves a snapshot of the staged changes in the local Git history.

### Step 7: Upload the Changes to GitHub

Run:

```bash
git push
```

This uploads the committed changes to the remote GitHub repository. If authentication or an upstream branch is not configured, Git may ask you to sign in or provide additional setup.

### Step 8: Verify the Upload

1. Open the repository on GitHub in your browser.
2. Refresh the page.
3. Check whether the new file or updated content appears in the repository.

## 5. Commands Used

| Command | Purpose |
|---|---|
| `git clone` | Downloads a repository to the local computer |
| `cd` | Opens the repository directory |
| `git status` | Shows the current state of the files |
| `git add .` | Stages changes |
| `git commit -m` | Saves staged changes in local Git history |
| `git push` | Uploads committed changes to GitHub |

## 6. Result

The GitHub repository was successfully cloned to the local computer. New content was added, staged, committed, and uploaded to GitHub using Git commands.

## 7. Conclusion

Cloning a repository and uploading changes are essential Git and GitHub skills. These steps help developers maintain projects, track modifications, share code, and collaborate with others efficiently.
