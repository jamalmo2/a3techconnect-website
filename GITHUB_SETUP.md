# GitHub Setup Instructions

## Step 1: Create Repository on GitHub

1. Go to https://github.com/new
2. Repository name: `a3techconnect-website` (or your preferred name)
3. Description: "Enterprise Technology Transformation Website - A3 Tech Connect"
4. Choose Public or Private
5. **DO NOT** check "Initialize with README"
6. Click "Create repository"

## Step 2: Connect and Push

After creating the repository, GitHub will show you commands. Use these:

```bash
# Add your GitHub repository as remote (replace YOUR_USERNAME and REPO_NAME)
git remote add origin https://github.com/YOUR_USERNAME/REPO_NAME.git

# Push to GitHub
git push -u origin main
```

## Alternative: Using SSH (if you have SSH keys set up)

```bash
git remote add origin git@github.com:YOUR_USERNAME/REPO_NAME.git
git push -u origin main
```

## After Pushing

Your website will be available at:
- Repository: `https://github.com/YOUR_USERNAME/REPO_NAME`
- You can enable GitHub Pages to host it live at: `https://YOUR_USERNAME.github.io/REPO_NAME`

### Enable GitHub Pages:
1. Go to repository Settings
2. Click "Pages" in the left sidebar
3. Under "Source", select "main" branch
4. Click "Save"
5. Your site will be live in a few minutes!
