# Git Commands Collection 🔧

Welcome to the Git Commands Collection for Hacktoberfest 2025! This directory is designed to help developers learn and share useful Git commands through practical examples.

## 🎯 How to Contribute

We welcome contributions of useful Git commands! Follow these guidelines to contribute:

### 📝 Contribution Guidelines

1. **One Command Per File**: Each bash file (`.sh`) should contain exactly one Git command
2. **File Naming**: Name your file descriptively (e.g., `git-status.sh`, `git-branch-create.sh`)
3. **Command Structure**: Include the Git command with proper syntax
4. **Documentation**: Add clear comments explaining what the command does
5. **Examples**: Include usage examples where helpful

### 📋 File Template

Create your bash file following this template:

```bash
#!/bin/bash

# Command: git [your-command]
# Description: Brief explanation of what this command does
# Usage: How to use this command
# Example: Practical example of the command in action

# The actual Git command
git [your-command]
```

### 💡 Example Contribution

Here's an example of a properly formatted contribution (`git-status.sh`):

```bash
#!/bin/bash

# Command: git status
# Description: Shows the working tree status, including staged, unstaged, and untracked files
# Usage: git status [options]
# Example: Use this to check what changes are ready to commit before running git commit

# Show the status of the working directory and staging area
git status
```

### 🚀 Getting Started

1. **Fork this repository**
2. **Create a new branch** for your contribution:

   ```bash
   git checkout -b add-git-command-[command-name]
   ```

3. **Create your bash file** in the `GIT/` directory
4. **Follow the template** and guidelines above
5. **Test your command** to ensure it works correctly
6. **Commit your changes**:

   ```bash
   git add .
   git commit -m "Add git [command-name] explanation"
   ```

7. **Push to your branch**:

   ```bash
   git push origin add-git-command-[command-name]
   ```

8. **Create a Pull Request**

### 📚 Command Categories

Consider contributing commands from these categories:

- **Basic Operations**: `add`, `commit`, `push`, `pull`, `status`
- **Branching**: `branch`, `checkout`, `merge`, `rebase`
- **History**: `log`, `show`, `diff`, `blame`
- **Remote Operations**: `remote`, `fetch`, `clone`
- **Undoing Changes**: `reset`, `revert`, `checkout`
- **Stashing**: `stash`, `stash pop`, `stash apply`
- **Configuration**: `config`, `init`
- **Advanced**: `cherry-pick`, `bisect`, `submodule`

### ✅ Quality Standards

- Commands should be commonly used or particularly useful
- Include clear, concise explanations
- Test commands before submitting
- Use proper bash syntax and formatting
- Make sure your script is executable (`chmod +x filename.sh`)

### 🤝 Community Guidelines

- Be respectful and inclusive
- Help others learn Git through clear documentation
- Avoid duplicate commands (check existing files first)
- Ask questions if you're unsure about anything

## 📁 Current Commands

Check the files in this directory to see what commands have already been contributed and avoid duplicates.

---

**Happy Contributing!** 🎉

Make your mark on Hacktoberfest 2025 by helping others learn Git, one command at a time!
