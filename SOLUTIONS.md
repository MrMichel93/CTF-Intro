# CTF Challenge Solutions Guide

This file contains the locations of all 5 flags for instructors.

## Flag Locations

### Flag #1: CTF{Flag #1}
**Location:** `challenge/documents/reports/2024/secret_report.txt`
**Finding Method:** Navigate through documents/reports/2024/ and read secret_report.txt
```bash
cd challenge/documents/reports/2024
cat secret_report.txt
```

### Flag #2: CTF{Flag #2}
**Location:** `challenge/.hidden_secrets`
**Finding Method:** Use `ls -a` to see hidden files (files starting with .)
```bash
cd challenge
ls -a
cat .hidden_secrets
```

### Flag #3: CTF{Flag #3}
**Location:** `challenge/...really_hidden_file.txt`
**Finding Method:** Use `ls -a` to see files with unusual names (starting with ...)
```bash
cd challenge
ls -a
cat ...really_hidden_file.txt
```

### Flag #4: CTF{Flag #4}
**Location:** `challenge/data/backup/old/ancient_backup.txt`
**Finding Method:** Navigate deep into nested directories
```bash
cd challenge/data/backup/old
cat ancient_backup.txt
```

### Flag #5: CTF{Flag #5}
**Location:** `challenge/data/logs/verbose.log`
**Finding Method:** Read through a long log file or use grep to search
```bash
cd challenge/data/logs
cat verbose.log
# OR use grep:
grep -r "CTF" challenge/
```

## Quick Solution Commands

To find all flags quickly:
```bash
cd challenge
grep -r "CTF{Flag" .
```

## Teaching Points

1. **File Navigation:** Students learn to use `cd` and `ls` effectively
2. **Hidden Files:** The `-a` flag reveals hidden files
3. **File Reading:** Using `cat` to read file contents
4. **Search Tools:** Introduction to `grep` for text searching
5. **Persistence:** Encourages thorough exploration

## Difficulty Level

- Flag #1: Medium - Requires navigation through nested directories
- Flag #2: Easy-Medium - Requires knowledge of hidden files
- Flag #3: Medium - Hidden file with unusual name
- Flag #4: Medium-Hard - Deep nesting requires patience
- Flag #5: Hard - Long file that benefits from using grep

Total files: 43
Total directories: 25
