# 📚 Holberton Shell - Cheat Sheet

## Navigation

Current directory:

```bash
pwd
```

List files:

```bash
ls
```

Detailed list:

```bash
ls -l
```

Show hidden files:

```bash
ls -la
```

Change directory:

```bash
cd directory_name
```

Go to home directory:

```bash
cd
```

Go back one directory:

```bash
cd ..
```

---

# File Management

Create an empty file:

```bash
touch filename
```

Create a directory:

```bash
mkdir directory_name
```

Remove a file:

```bash
rm filename
```

Remove a directory:

```bash
rmdir directory_name
```

Remove a directory recursively:

```bash
rm -r directory_name
```

Copy a file:

```bash
cp source destination
```

Move or rename a file:

```bash
mv old_name new_name
```

---

# View File Contents

Display file:

```bash
cat filename
```

Beginning of a file:

```bash
head filename
```

End of a file:

```bash
tail filename
```

Count lines, words and bytes:

```bash
wc filename
```

---

# Permissions

Display permissions:

```bash
ls -l
```

Change permissions:

```bash
chmod 755 filename
```

Change owner:

```bash
chown user filename
```

---

# Search

Find a file:

```bash
find . -name "filename"
```

Search text:

```bash
grep "text" filename
```

Recursive search:

```bash
grep -r "text" .
```

---

# Redirections

Redirect output:

```bash
echo "Hello" > file.txt
```

Append output:

```bash
echo "Hello" >> file.txt
```

Read from a file:

```bash
cat < file.txt
```

Pipe output:

```bash
cat file.txt | grep "word"
```

---

# Variables

Create a variable:

```bash
NAME="Bertrand"
```

Display a variable:

```bash
echo "$NAME"
```

Environment variables:

```bash
env
```

---

# Shell Scripts

Create a script:

```bash
touch script.sh
```

First line:

```bash
#!/bin/bash
```

Make executable:

```bash
chmod +x script.sh
```

Run:

```bash
./script.sh
```

---

# Git Workflow

```bash
git status
git add .
git commit -m "Meaningful commit"
git push
```

---

# Useful Commands

Current user:

```bash
whoami
```

Current date:

```bash
date
```

Current calendar:

```bash
cal
```

Display command history:

```bash
history
```

Clear terminal:

```bash
clear
```

Manual:

```bash
man command
```

---

# Common Shortcuts

```text
Ctrl + C    Stop current process
Ctrl + D    Exit terminal
Ctrl + L    Clear terminal
Tab         Auto-completion
↑ ↓         Command history
```

---

# Good Practices

* Read the project requirements carefully.
* Use `man` to understand commands.
* Check the current directory with `pwd`.
* Verify files with `ls`.
* Test scripts before pushing.
* Use meaningful commit messages.
* Check `git status` before every commit.

---

# What I Learned

* Navigate through the Linux file system.
* Create, copy, move and delete files.
* Manage permissions.
* Use pipes and redirections.
* Search with `find` and `grep`.
* Create executable shell scripts.
* Use environment variables.
* Read command manuals.
* Work efficiently in the terminal.
* Use Git with Shell projects.

