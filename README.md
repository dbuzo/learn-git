# learn-git

A repository for learning Git fundamentals and best practices.

## Purpose
This repository serves as a hands-on learning environment for Git commands, workflows, and version control concepts.

## What I'm Learning
- Basic Git commands (add, commit, push, pull)
- Branching and merging
- Repository management
- Collaboration workflows
- Hugo static site generation
- Merge conflict resolution

## New Features Added
- ✨ Branch management practice
- 📁 Comprehensive Git study notes
- 🚫 .gitignore for security
- 📚 Hugo integration tutorial
- 🔄 Workflow documentation

## Installation Instructions
1. Clone the repository:
   ```bash
   git clone https://github.com/dbuzo/learn-git.git
   cd learn-git
   ```

2. Install Hugo (if following Hugo tutorial):
   ```bash
   # Windows (using Scoop)
   scoop install hugo-extended
   
   # Or using Chocolatey
   choco install hugo-extended
   ```

3. Start learning Git:
   - Read `git-study.md` for comprehensive notes
   - Practice branching and merging
   - Follow the Hugo integration tutorial

## Getting Started
```bash
git clone https://github.com/dbuzo/learn-git.git
cd learn-git
```

## Branch Workflow Practice
```bash
# Create feature branch
git checkout -b feature-name

# Make changes and commit
git add .
git commit -m "Add new feature"

# Switch back to main
git checkout main

# Merge feature
git merge feature-name

# Clean up
git branch -d feature-name
```

## Progress
- [x] Repository setup
- [x] Basic commands practice
- [x] Branching exercises
- [x] SSH key configuration
- [x] Repository approval process
- [ ] Merge conflict resolution
- [ ] Hugo site deployment

## Study Resources
- `git-study.md` - Comprehensive Git learning notes
- `README.md` - This file with setup instructions
- `.gitignore` - Security and cleanup configurations