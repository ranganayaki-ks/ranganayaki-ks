# 👑 GitHub Profile Setup & Deployment Guide

Welcome, **Ranganayaki**! Your custom, production-ready **Royal Blue Luxury GitHub Profile** is ready in [README.md](file:///c:/Users/asus/OneDrive/Documents/Desktop/githun-profile/README.md).

---

## ⚡ 5-Minute Quick Launch to GitHub

### 1. Create Your Profile Repository
1. Log into your GitHub account: **`ranganayaki-ks`**
2. Visit [github.com/new](https://github.com/new).
3. Repository name: **`ranganayaki-ks`** *(must match your GitHub username exactly)*.
4. Set visibility to **Public** 🟢.
5. Do **NOT** check "Add a README file" (since you are pushing your existing local files).
6. Click **Create repository**.

---

### 2. Assets Included in Your Repository
Ensure the following files are in your project folder (`c:\Users\asus\OneDrive\Documents\Desktop\githun-profile`):
- `README.md`: Your complete GitHub profile markdown
- `header.svg`: Custom Royal Blue waving banner with majestic typography
- `footer.svg`: Matching Royal Blue waving footer banner
- `My_image_1.jpeg`: High-resolution portrait photograph
- `badges/linkedin.svg`: Pixel-perfect native LinkedIn vector badge

---

### 3. Push to GitHub via Terminal
Open PowerShell or Git Bash inside this folder (`c:\Users\asus\OneDrive\Documents\Desktop\githun-profile`):

```bash
git init
git add README.md My_image_1.jpeg header.svg footer.svg badges/
git commit -m "feat: launch royal blue luxury github profile"
git branch -M main
git remote add origin https://github.com/ranganayaki-ks/ranganayaki-ks.git
git push -u origin main
```

*(If you have already initialized git and committed before, simply run:)*
```bash
git add README.md header.svg footer.svg badges/
git commit -m "feat: update royal blue theme, header banner & linkedin icon"
git push
```

---

## 🌐 Local Live Preview
You can double-click **`index.html`** or run:
```powershell
Start-Process "index.html"
```
to view your complete profile live in any browser with interactive 1-click clipboard copy!
