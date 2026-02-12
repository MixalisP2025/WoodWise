# 🚀 How to Push WoodWise to GitHub

Follow these simple steps to upload your project to GitHub!

## Prerequisites

1. **Install Git** (if you haven't already)
   - Windows: Download from [git-scm.com](https://git-scm.com/)
   - Mac: Open Terminal and run `git --version` (it will prompt to install if needed)
   - Linux: `sudo apt-get install git` or `sudo yum install git`

2. **GitHub Account**
   - You already have one! 😊
   - Repository URL: https://github.com/MixalisP2025/WoodWise.git

---

## Step-by-Step Instructions

### 1. Open Terminal/Command Prompt

**Windows:**
- Press `Win + R`, type `cmd`, press Enter
- Or search for "Command Prompt" in Start menu

**Mac:**
- Press `Cmd + Space`, type "Terminal", press Enter

**Linux:**
- Press `Ctrl + Alt + T`

### 2. Navigate to Your Project Folder

```bash
# If files are in Downloads folder:
cd Downloads

# Or wherever you saved the files
cd /path/to/your/woodwise/files
```

### 3. Configure Git (First Time Only)

```bash
# Set your name
git config --global user.name "Mixalis P"

# Set your email (use your GitHub email)
git config --global user.email "your-email@example.com"
```

### 4. Initialize Git Repository

```bash
# Initialize the repository
git init

# Check status (you'll see all your files)
git status
```

### 5. Add All Files

```bash
# Add everything
git add .

# Or add specific files
git add woodwise.html
git add README.md
git add WOODWISE_APP_CONVERSION_GUIDE.md
git add LICENSE
git add .gitignore
```

### 6. Create Your First Commit

```bash
git commit -m "🌲 Initial commit - WoodWise v1.0 with all features"
```

### 7. Connect to GitHub Repository

```bash
# Add the remote repository
git remote add origin https://github.com/MixalisP2025/WoodWise.git

# Verify it was added
git remote -v
```

### 8. Push to GitHub

```bash
# Push to main branch
git push -u origin main

# If you get an error about "master" vs "main", try:
git branch -M main
git push -u origin main
```

**⚠️ You'll be prompted for:**
- Username: `MixalisP2025`
- Password: Use a **Personal Access Token** (not your GitHub password)

---

## Getting a Personal Access Token

If you don't have a token yet:

1. Go to GitHub.com → Click your profile picture → Settings
2. Scroll down to **Developer settings** (bottom left)
3. Click **Personal access tokens** → **Tokens (classic)**
4. Click **Generate new token** → **Generate new token (classic)**
5. Name it: "WoodWise App"
6. Set expiration: 90 days (or No expiration)
7. Check these permissions:
   - ✅ `repo` (all sub-items)
   - ✅ `workflow`
8. Click **Generate token**
9. **COPY IT IMMEDIATELY** (you won't see it again!)
10. Use this as your password when pushing

---

## Verify Upload

After pushing, visit:
**https://github.com/MixalisP2025/WoodWise**

You should see:
- ✅ woodwise.html
- ✅ README.md
- ✅ WOODWISE_APP_CONVERSION_GUIDE.md
- ✅ LICENSE
- ✅ .gitignore

---

## Making Future Updates

When you make changes:

```bash
# 1. Check what changed
git status

# 2. Add changed files
git add .

# 3. Commit with a message
git commit -m "Add new feature: AR measurement"

# 4. Push to GitHub
git push
```

---

## Common Issues & Solutions

### Issue: "Repository not found"
**Solution:** Make sure the repository exists on GitHub first
```bash
# Go to github.com/MixalisP2025 and create "WoodWise" repo
# Then retry the push
```

### Issue: "Permission denied"
**Solution:** Use Personal Access Token instead of password

### Issue: "Branch 'master' doesn't exist"
**Solution:**
```bash
git branch -M main
git push -u origin main
```

### Issue: "Updates were rejected"
**Solution:** Pull first, then push
```bash
git pull origin main --rebase
git push origin main
```

---

## Quick Command Reference

```bash
# Status of files
git status

# Add all files
git add .

# Commit changes
git commit -m "Your message here"

# Push to GitHub
git push

# Pull latest changes
git pull

# View commit history
git log --oneline

# Create new branch
git checkout -b feature-name

# Switch branches
git checkout main
```

---

## Alternative: GitHub Desktop (GUI)

Don't like command line? Use GitHub Desktop!

1. Download: [desktop.github.com](https://desktop.github.com)
2. Install and sign in
3. Click: **File → Add Local Repository**
4. Select your WoodWise folder
5. Click **Publish repository**
6. Done! ✅

---

## Need Help?

- **GitHub Docs**: [docs.github.com](https://docs.github.com)
- **Git Tutorial**: [git-scm.com/book](https://git-scm.com/book/en/v2)
- **Video Tutorial**: Search "How to push to GitHub" on YouTube

---

## Your Repository Structure

After pushing, your GitHub repo will look like:

```
WoodWise/
├── README.md                           ← Main documentation
├── woodwise.html                       ← The app!
├── WOODWISE_APP_CONVERSION_GUIDE.md   ← How to make it mobile
├── LICENSE                             ← MIT License
├── .gitignore                          ← Files to ignore
└── PUSH_TO_GITHUB.md                   ← This guide
```

---

## Next Steps After Pushing

1. ✅ **Add a description** to your repo on GitHub
2. ✅ **Add topics/tags**: wood, identification, firebase, react-native
3. ✅ **Star your own repo** (why not? 😄)
4. ✅ **Share the link** with friends/social media
5. ✅ **Start converting to mobile app** using the guide!

---

**🎉 Congratulations! Your project is now on GitHub!**

**Repository:** https://github.com/MixalisP2025/WoodWise

---

**Questions?** Open an issue on GitHub or check Stack Overflow!
