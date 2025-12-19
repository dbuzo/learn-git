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

### 🔄 In Progress
- [ ] Install Hugo theme
- [ ] Initialize Git repository in Hugo project
- [ ] Make first commit with Hugo content

### 📋 To Do
- [ ] Create content files (.md posts)
- [ ] Practice staging and committing changes
- [ ] Set up .gitignore file
- [ ] Create and manage branches
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