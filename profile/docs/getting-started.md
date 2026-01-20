# Getting Started

## Environment

**Get a Unix environment.**

Linux (Ubuntu, Arch, Debian), macOS with Homebrew, or WSL2 on Windows.

**Learn your shell.**

```bash
# Bash basics
cd, ls, pwd, cp, mv, rm, mkdir
man <command>  # Read the manual
```

**Pick an editor.**

vim or emacs. Commit to one. Learn it properly.

```bash
vimtutor  # If vim
# Or Emacs tutorial: C-h t
```

## Core Tools

**Learn these:**

```bash
grep    # Search text
sed     # Transform text
awk     # Process text
find    # Locate files
xargs   # Build commands
```

**Pipeline thinking:**

```bash
cat file.txt | grep "error" | wc -l
# Better:
grep "error" file.txt | wc -l
# Even better:
grep -c "error" file.txt
```

One tool, one job. Compose them.

## Version Control

**Git from terminal only.**

```bash
git init
git add
git commit
git log
git diff
git branch
git merge
```

No GUI. Learn what's actually happening.

Read `.git/` directory. Understand commits are just objects.

## Build Something

**Write a tool you'll use.**

Ideas:
- Todo manager that's just a text file with smart parsing
- Log analyzer for your system
- Backup script that actually runs
- Personal wiki with grep-able markdown files

Ship it. Use it. Iterate.

## Going Deeper

**Systems programming:**

Learn C. Understand:
- Memory (stack, heap, pointers)
- Process model (fork, exec)
- File descriptors
- Syscalls

**Networking:**

- TCP/IP basics
- Write a simple HTTP server
- Use telnet to talk to servers directly
- Read RFC documents

**Read code:**

Clone repos you use daily. Read the source. Find one small thing to improve.

## Daily Practice

```bash
# Check your system
ps aux | head
df -h
top

# Explore
man hier  # Unix directory structure
ls /usr/bin | wc -l  # How many programs?

# Script something tedious
# Automate when it makes sense
```

## Measure Progress

Can you:
- Configure your environment from scratch?
- Write a shell script without googling syntax?
- Read others' code and understand it?
- Fix a bug in a tool you use?
- Explain how a program works to someone else?

These are signs you're learning.

## Resources

- `man` pages - Read them first
- Source code - Read it second
- Internet - Read it last

## One Rule

Build things. Everything else follows from building things.
