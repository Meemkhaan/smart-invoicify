# One-time GitHub setup (if not pushed yet)

The local repo is ready. Complete these steps once:

## 1. Create the public repository

On GitHub: **New repository** → name `smart-invoicify` → **Public** → do **not** add README, .gitignore, or license (empty repo).

## 2. Push this folder

```bash
cd smart-invoicify
git remote add origin https://github.com/Meemkhaan/smart-invoicify.git
git push -u origin main
```

(If `origin` already exists, use `git push -u origin main` only.)

## 3. Enable GitHub Pages

Repository **Settings → Pages**:

- **Build and deployment → Source:** GitHub Actions  
- After the first push, open **Actions** and confirm **Deploy GitHub Pages** succeeds.

Site URL: **https://meemkhaan.github.io/smart-invoicify/**

## 4. Re-authenticate GitHub CLI (optional)

```bash
gh auth login -h github.com
```

Use account **Meemkhaan** if you manage repos from the CLI.
