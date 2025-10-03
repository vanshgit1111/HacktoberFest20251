# Shell Commands Collection 🐚

Welcome to the Shell Commands Collection for Hacktoberfest 2025! This directory is designed to help developers learn and share useful bash/shell commands through practical examples.

## 🎯 How to Contribute

We welcome contributions of useful shell commands! Follow these guidelines to contribute:

### 📝 Contribution Guidelines

1. **One Command Per File**: Each bash file (`.sh`) should contain exactly one shell command or command sequence
2. **File Naming**: Name your file descriptively (e.g., `find-files.sh`, `process-monitor.sh`)
3. **Command Structure**: Include the shell command with proper syntax
4. **Documentation**: Add clear comments explaining what the command does
5. **Examples**: Include usage examples and expected output where helpful

### 📋 File Template

Create your bash file following this template:

```bash
#!/bin/bash

# Command: [your-command]
# Description: Brief explanation of what this command does
# Usage: How to use this command
# Example: Practical example of the command in action
# Output: What to expect as output (if applicable)

# The actual shell command
[your-command]
```

### 💡 Example Contribution

Here's an example of a properly formatted contribution (`list-processes.sh`):

```bash
#!/bin/bash

# Command: ps aux
# Description: Display information about all running processes
# Usage: ps aux [| grep pattern] to filter results
# Example: Use this to see all processes or find specific ones
# Output: Shows PID, user, CPU%, memory%, and command for each process

# List all running processes with detailed information
ps aux
```

### 🚀 Getting Started

1. **Fork this repository**
2. **Create a new branch** for your contribution:

   ```bash
   git checkout -b add-shell-command-[command-name]
   ```

3. **Create your bash file** in the `SHELL/` directory
4. **Follow the template** and guidelines above
5. **Test your command** to ensure it works correctly
6. **Make your script executable**:

   ```bash
   chmod +x your-command.sh
   ```

7. **Commit your changes**:

   ```bash
   git add .
   git commit -m "Add [command-name] shell command explanation"
   ```

8. **Push to your branch**:

   ```bash
   git push origin add-shell-command-[command-name]
   ```

9. **Create a Pull Request**

### 📚 Command Categories

Consider contributing commands from these categories:

#### 📁 File Operations

- `ls`, `find`, `locate`, `du`, `df`
- `cp`, `mv`, `rm`, `mkdir`, `rmdir`
- `chmod`, `chown`, `touch`

#### 🔍 Text Processing

- `grep`, `sed`, `awk`, `cut`, `sort`
- `head`, `tail`, `less`, `more`
- `wc`, `tr`, `uniq`

#### 🖥️ System Monitoring

- `ps`, `top`, `htop`, `free`, `df`
- `lsof`, `netstat`, `ss`, `iostat`
- `uptime`, `who`, `w`

#### 🌐 Network Operations

- `curl`, `wget`, `ping`, `traceroute`
- `ssh`, `scp`, `rsync`
- `nslookup`, `dig`

#### 📦 Archive & Compression

- `tar`, `zip`, `unzip`, `gzip`
- `7z`, `compress`, `uncompress`

#### ⚙️ Environment & Variables

- `env`, `export`, `alias`, `which`
- `echo`, `printf`, `read`

#### 🔧 Process Management

- `kill`, `killall`, `jobs`, `bg`, `fg`
- `nohup`, `screen`, `tmux`

#### 📊 Performance & Debugging

- `strace`, `ltrace`, `time`
- `vmstat`, `sar`, `dmesg`

### ✅ Quality Standards

- Commands should be commonly used or particularly useful
- Include clear, concise explanations
- Test commands before submitting (be careful with destructive commands)
- Use proper bash syntax and formatting
- Make sure your script is executable (`chmod +x filename.sh`)
- Include safety warnings for potentially dangerous commands

### 🛡️ Safety Guidelines

- **Destructive Commands**: Add clear warnings for commands that can delete files or modify system settings
- **Root Access**: Clearly indicate if a command requires sudo/root privileges
- **System Impact**: Mention if a command is resource-intensive or might affect system performance
- **Test Environment**: Recommend testing in safe environments for system-level commands

### 🤝 Community Guidelines

- Be respectful and inclusive
- Help others learn shell scripting through clear documentation
- Avoid duplicate commands (check existing files first)
- Ask questions if you're unsure about anything
- Include alternative approaches when applicable

### 📝 Documentation Best Practices

- Use clear, descriptive comments
- Include real-world use cases
- Mention common options and flags
- Explain expected output format
- Add troubleshooting tips for complex commands

## 📁 Current Commands

Check the files in this directory to see what commands have already been contributed and avoid duplicates.

---

**Happy Contributing!** 🎉

Make your mark on Hacktoberfest 2025 by helping others master the command line, one shell command at a time!
