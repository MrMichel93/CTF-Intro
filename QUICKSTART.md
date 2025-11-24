# Quick Start Guide

## Welcome, CTF Explorer! 🚩

Ready to find some flags? Follow these simple steps:

### Step 1: Get into the Challenge
```bash
cd challenge
```

### Step 2: Look Around
```bash
ls
```
You'll see several directories. Pick one to explore!

### Step 3: Navigate and Read
```bash
cd documents
ls
cat welcome.txt
```

### Step 4: Go Deeper
```bash
cd reports
ls
cd 2024
ls
```

### Step 5: Don't Forget Hidden Files!
```bash
ls -a
```
Files starting with `.` are hidden!

### Important Commands Cheat Sheet

| Command | What it does | Example |
|---------|-------------|---------|
| `pwd` | Show current location | `pwd` |
| `ls` | List files | `ls` |
| `ls -a` | List ALL files (including hidden) | `ls -a` |
| `cd dirname` | Go into a directory | `cd documents` |
| `cd ..` | Go back one level | `cd ..` |
| `cat filename` | Read a file | `cat readme.txt` |
| `grep word filename` | Search for a word in file | `grep CTF file.txt` |
| `grep -r word .` | Search all files for a word | `grep -r CTF .` |

### Tips for Success

1. **Stay organized** - Keep track of where you've been
2. **Read everything** - Even boring files might have hints
3. **Use ls -a** - Some files are hidden!
4. **Don't give up** - The flags are definitely there
5. **Think creatively** - Check unusual places

### When You're Stuck

- Have you checked all directories?
- Did you use `ls -a` to see hidden files?
- Did you read all the files in each directory?
- Try using `grep` to search: `grep -r "CTF" .`

Good luck! 🔍
