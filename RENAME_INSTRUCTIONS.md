# Repository Rename Instructions

## Current Status
- **Current Name:** `helical-sat-hueristic` (misspelled)
- **Desired Name:** `Helical-SAT-Heuristic` (correctly spelled and capitalized)

## Steps to Rename GitHub Repository

### 1. Rename on GitHub

1. Go to your repository: https://github.com/Zynerji/helical-sat-hueristic
2. Click on **Settings** (top right)
3. Scroll down to the "Repository name" section
4. Change the name from `helical-sat-hueristic` to `Helical-SAT-Heuristic`
5. Click **Rename**

GitHub will automatically:
- ✅ Set up redirects from the old URL to the new one
- ✅ Update all internal references
- ✅ Preserve all issues, PRs, and commit history

### 2. Update Local Git Remote

After renaming on GitHub, update your local repository:

```bash
cd /home/user/helical-sat-hueristic

# Update the remote URL to the new repository name
git remote set-url origin https://github.com/Zynerji/Helical-SAT-Heuristic.git

# Verify the change
git remote -v

# Test the connection
git fetch origin
```

### 3. (Optional) Rename Local Directory

To match the new repository name:

```bash
cd /home/user
mv helical-sat-hueristic Helical-SAT-Heuristic
cd Helical-SAT-Heuristic
```

## What's Already Updated

✅ **README.md** - All references updated to:
- Clone URL: `https://github.com/Zynerji/Helical-SAT-Heuristic.git`
- Directory name: `Helical-SAT-Heuristic/`
- Citation URL: `https://github.com/Zynerji/Helical-SAT-Heuristic`

## After Renaming

The new repository will be accessible at:
- **New URL:** https://github.com/Zynerji/Helical-SAT-Heuristic
- **Old URL:** https://github.com/Zynerji/helical-sat-hueristic (redirects automatically)

## Summary

**Before:**
- ❌ helical-sat-hueristic (misspelled, lowercase)

**After:**
- ✅ Helical-SAT-Heuristic (correct spelling, capitalized)

This change:
- Fixes the spelling: hue**u**ristic → heu**r**istic ✓
- Capitalizes properly: helical-sat-heuristic → Helical-SAT-Heuristic ✓
- Maintains all history and links (GitHub provides automatic redirects) ✓
