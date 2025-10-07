# Upload to GitHub - Quick Guide

## Initial Setup (first time only)

```bash
# Navigate to portfolio folder
cd "/mnt/c/Users/User/OneDrive - UNIR/Documentos/Agente de Vida 2025/Career/portfolio"

# Initialize git repository
git init

# Add your GitHub repository as remote
git remote add origin https://github.com/iv0nis/portfolio.git

# Configure your git identity
git config user.name "Ivonis Florindo Lopez"
git config user.email "ivonis.data@gmail.com"
```

## Upload Files

```bash
# Add all files
git add .

# Create commit
git commit -m "Initial portfolio upload - Data Science projects"

# Push to GitHub
git push -u origin main
```

## If 'main' branch doesn't exist, use:

```bash
git branch -M main
git push -u origin main
```

## Update Portfolio (for future changes)

```bash
# Add changed files
git add .

# Commit changes
git commit -m "Update: [describe your changes]"

# Push to GitHub
git push
```

## Organize Projects (recommended structure)

Before uploading, consider organizing your files:

1. Create folders for different project types
2. Add a README.md to each project folder
3. Remove any sensitive data or API keys
4. Clean up notebook outputs if they're too large

```bash
# Create organized structure
mkdir spark-projects machine-learning deep-learning data-analysis
```

Then move your notebooks to appropriate folders.