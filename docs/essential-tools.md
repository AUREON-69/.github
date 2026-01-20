# Essential Tools

## Terminal

**Shell:**
- bash (default everywhere)
- zsh (better interactive features)

Pick one. Master it.

**Terminal emulator:**
- Built-in terminal (fine)
- Alacritty (fast)
- kitty (features)

Don't obsess. Default works.

## Editor

**Choose one:**

**vim**
- Everywhere by default
- Modal editing
- `vimtutor` to learn

**emacs**
- Lisp-based extensibility
- Built-in tutorial: `C-h t`

**Not:**
- VS Code (crutch)
- Any IDE (abstracts too much when learning)

Later, use whatever. First, learn with constraints.

## Text Processing

```bash
grep    # Pattern matching
sed     # Stream editing  
awk     # Text processing language
cut     # Column extraction
sort    # Sorting
uniq    # Deduplication
tr      # Character translation
wc      # Counting
```

These compose. Learn them.

## File Operations

```bash
find    # Locate files
xargs   # Build commands from input
rsync   # Copy with sync
tar     # Archive
gzip    # Compress
```

## Version Control

```bash
git     # Only version control that matters
```

Learn it properly:
- Command line only initially
- Understand the object model
- Read `.git/config`

## Development

**Language (pick one to start):**
- C (understand the machine)
- Python (scripting, automation)
- Shell (system glue)

**Build tools:**
- make (universal)
- Compiler for your language

## Monitoring

```bash
ps      # Processes
top     # Resource usage
htop    # Better top
df      # Disk space
du      # Disk usage
netstat # Network connections
ss      # Socket statistics
```

## Network

```bash
curl    # Transfer data
nc      # Netcat - network Swiss army knife
ssh     # Remote access
scp     # Secure copy
dig     # DNS lookup
ping    # Connectivity test
```

## System

```bash
chmod   # Change permissions
chown   # Change ownership
ln      # Links
env     # Environment
export  # Set environment variables
```

## Config Management

**Dotfiles:**

```bash
~/.bashrc
~/.vimrc
~/.gitconfig
```

Keep them in git. Sync across machines.

Example structure:
```
~/dotfiles/
  bashrc
  vimrc
  gitconfig
  install.sh  # Symlink script
```

## What Not to Install

- Fancy frameworks before understanding basics
- GUI tools that hide what's happening
- "Productivity" tools with steep learning curves
- Anything requiring constant updates
- Tools that don't compose with others

## Installation

**Package manager:**
- apt (Debian/Ubuntu)
- pacman (Arch)
- brew (macOS)
- dnf (Fedora)

Use your system's package manager. Avoid random install scripts.

## Learning Path

1. Shell + editor
2. Text tools
3. Git
4. Programming language
5. System tools

Learn what you need when you need it.

## Test Yourself

Can you:
- Edit a file without a mouse?
- Find and replace text in multiple files?
- Process log files to extract specific data?
- Write a script to automate a task?
- Commit changes to git from terminal?

These are the basics. Master them first.
