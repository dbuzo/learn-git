# Git & Hugo Study Notes

## Learning Objectives
Following the "From Theory to Practice: A Git Workshop for Beginners" tutorial to master Git with Hugo integration.

## Progress Tracker

### ✅ Completed
- [x] Repository cloned from GitHub
- [x] Basic README created
- [x] SSH key setup for GitHub
- [x] Hugo installation (v0.152.2)
- [x] Hugo site created (/home/uwadavid/my-hugo-site)
- [x] Repository approved for pushing
- [x] .gitignore file created
- [x] Branch creation practice (feature-readme-instructions)

### 🔄 In Progress
- [x] Create and manage branches
- [ ] Practice merging branches
- [ ] Work with remote repositories
- [ ] Resolve merge conflicts
- [ ] Push changes to GitHub

## Commands Learned

### Basic Git Commands
```bash
git init                    # Initialize repository
git add .                   # Stage all changes
git commit -m "message"     # Commit with message
git status                  # Check repository status
git log                     # View commit history
```

### Hugo Commands
```bash
hugo new site <name>        # Create new Hugo site
hugo new posts/<file>.md    # Create new post
hugo server -D              # Start development server
```

### Branch Management
```bash
git branch <name>           # Create new branch
git checkout <name>         # Switch to branch
git merge <branch>          # Merge branch
git branch -d <name>        # Delete branch
```

### Remote Repository
```bash
git remote add origin <url> # Add remote repository
git push origin main        # Push to remote
git pull origin main        # Pull from remote
git clone <url>             # Clone repository
```

## Git Concepts Explained

### Key Terms
- **Branch**: Separate line of development (like a copy of your project)
- **Master/Main**: Default main branch (your primary code)
- **Origin**: Name for your remote repository (GitHub)
- **Merge**: Combining changes from one branch into another
- **Merge Conflict**: When Git can't automatically combine changes
- **Push**: Send your local changes to remote repository
- **Pull**: Download changes from remote repository to local

### Command Order & Flow
```bash
# 1. DAILY WORKFLOW (most common)
git pull origin main        # Get latest changes first
git add .                   # Stage your changes
git commit -m "message"     # Save changes locally
git push origin main        # Send to GitHub

# 2. BRANCH WORKFLOW
git branch feature-name     # Create new branch
git checkout feature-name   # Switch to branch
# ... make changes ...
git add .
git commit -m "message"
git checkout main           # Switch back to main
git merge feature-name      # Combine branch into main
git push origin main        # Send merged changes
```

### What Each Does
- **git pull**: "Download latest version from GitHub"
- **git add**: "Prepare files for saving"
- **git commit**: "Save changes with a message"
- **git push**: "Upload my changes to GitHub"
- **git branch**: "Create a new workspace"
- **git merge**: "Combine two workspaces"

### Simple Rule
**Always pull before you push!**
```bash
git pull origin main    # Get updates first
# ... do your work ...
git push origin main    # Send your work
```

## Notes & Observations
- Git tracks changes in files, not just file creation
- Hugo generates static sites from Markdown files
- Branches allow parallel development without affecting main code
- .gitignore prevents unnecessary files from being tracked
- Merge conflicts require manual resolution

## Next Steps
1. Install Hugo on Windows
2. Create Hugo site in this repository
3. Practice the complete Git + Hugo workflow
4. Document each step and command used