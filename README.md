# Learn Git

This is my little Git playground hands-on way to get comfortable with the basics. I built it to walk through the essentials: creating files, staging, committing, tweaking configs, and just getting a feel for how Git works in real life.

## Repository

**GitHub Link:** [Check it out here](https://github.com/Ericokim/learn_git)

---

## Getting Started

If you want to follow along, pop open your terminal and run through these steps:

```bash
# Make a new folder and jump into it
mkdir learn_git
cd learn_git

# Create a file
touch third.txt

# Initialize Git
git init

# Stage and commit the file
git add third.txt
git commit -m "adding third.txt"

# Peek at your commit history
git log

# Add another file
touch fourth.txt
git add fourth.txt
git commit -m "adding fourth.txt"

# Remove a file
rm third.txt
git add .
git commit -m "removing third.txt"

# Check the updated history
git log

# Tweak your global Git settings
git config --global core.pager cat
git config --global --list
```

---

## What This Covers

- **Tracking Files:** Learn how Git keeps tabs on your changes.
- **Commit History:** See your timeline and understand what’s happening under the hood.
- **Config Tweaks:** Customize Git to behave the way you want.
- **Cleanup Practice:** Try removing files and committing those changes.
- **Command Confidence:** Build muscle memory with Git syntax.

---

## Want to Contribute?

If you’ve got ideas to improve this or want to add your own twist:

1. Fork the repo
2. Make a new branch (`git checkout -b your-feature`)
3. Add your changes
4. Commit and push (`git commit -m "your message"`)
5. Send in a pull request

---

## License

MIT License—so feel free to use, remix, and share it. Just give credit where it’s due.

---
