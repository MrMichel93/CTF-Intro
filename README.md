# CTF Challenge - Terminal Navigation

Welcome to your first Capture The Flag (CTF) challenge! 🚩

## Objective

Your mission is to find **5 hidden flags** scattered throughout the `challenge` directory. Each flag is formatted as:
```
CTF{Flag #X}
```
where X is a number from 1 to 5.

## What You'll Learn

This challenge will help you practice essential terminal commands:
- `cd` - Change directory
- `ls` - List files and directories
- `ls -a` - List all files (including hidden ones)
- `cat` - Display file contents
- `grep` - Search for text patterns
- `find` - Search for files
- `pwd` - Print working directory

## Getting Started

1. Navigate to the challenge directory:
   ```bash
   cd challenge
   ```

2. Start exploring! Use `ls` to see what's in the current directory.

3. Use `cd` to move into different folders and `cat` to read file contents.

4. Keep track of the flags you find!

## Hints

- 💡 Not all files are visible with just `ls` - try `ls -a`!
- 💡 Some flags are buried deep in nested directories
- 💡 Files with unusual names might hide secrets
- 💡 Large files might require searching with `grep`
- 💡 Check everywhere - some places seem unlikely but contain treasures!

## Advanced Commands (Optional)

If you want to speed up your search:
- `grep -r "CTF" .` - Recursively search for "CTF" in all files
- `find . -name "*.txt"` - Find all text files
- `find . -type f` - List all files in current directory and subdirectories

## Challenge Level

This challenge is designed for students who have basic command-line experience. Take your time and explore systematically!

## How to Submit

Once you've found all 5 flags, make a list of them in order (Flag #1 through Flag #5) and show them to your instructor.

Good luck, explorer! 🔍