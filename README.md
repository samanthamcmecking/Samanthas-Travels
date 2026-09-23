# DT4 Website Template
 Template for your final project

Kia ora koutou. This repo is a starter template for the final project website template. Follow the steps below to get your own copy set up in VS Code and pushed to your own GitHub account.
 
## 1. Get your own copy of the template
 
1. Go to this repository on GitHub.
2. Click the green **"Use this template"** button (top right, above the file list).
3. Select **"Create a new repository"**.
4. Choose your own GitHub account as the owner, give your new repo a name (e.g. `your-name-mobile-template`), and set it to **Public**.
5. Click **"Create repository from template"**.
You now have your own independent copy of this project on your GitHub account, with a clean history — it isn't linked back to the original.
 
## 2. Clone your new repo into VS Code
 
1. On your new repo's GitHub page, click the green **"Code"** button and copy the HTTPS URL.
2. Open VS Code.
3. Open the Command Palette (`Ctrl+Shift+P` on Windows/Linux, `Cmd+Shift+P` on Mac) and choose **"Git: Clone"**.
4. Paste the URL you copied, then choose a folder on your computer to save it in.
5. When prompted, click **"Open"** to open the cloned folder in VS Code.
Alternatively, from a terminal:
 
```bash
git clone https://github.com/YOUR-USERNAME/your-repo-name.git
cd your-repo-name
code .
```
 
## 3. Make changes and push them back to your own GitHub
 
Once you've made edits in VS Code:
 
```bash
git add .
git commit -m "Describe what you changed"
git push -u origin main
```
## 4. To work on your code on your home Laptop or Computer

Open VS Code on your laptop (you can download VS Code for free here - https://code.visualstudio.com/Download ).

#### First time only, to set things up on your home computer: 
```bash
git clone https://github.com/YOUR-USERNAME/your-repo-name.git
```
or:
1. click the green **"Code"** button and copy the HTTPS URL.
2. Open VS Code.
3. Open the Command Palette (`Ctrl+Shift+P` on Windows/Linux, `Cmd+Shift+P` on Mac) and choose **"Git: Clone"**.
4. Paste the URL you copied, then choose a folder on your computer to save it in.
5. When prompted, click **"Open"** to open the cloned folder in VS Code.

#### Every session: PULL the latest changes before starting work:
```bash
git pull
```

#### At the end of each work session: push changes back up:
```bash
git add .
git commit -m "Describe what you changed"
git push
```
