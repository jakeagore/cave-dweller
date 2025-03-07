# 🚀 Getting Started with Git & GitHub (For Beginners)

This guide helps you:
✅ Install Git on **Windows** and **macOS**  
✅ Download the project from GitHub  
✅ Make changes and push updates back to the repository  

---

## 1️⃣ Install Git

### For Windows:
1. Go to: https://git-scm.com/download/win
2. The download will start automatically.
3. Open the installer and follow the setup. Use **default options** unless you're sure.
4. When finished, check if Git works:
   - Open **PowerShell** or **Command Prompt**
   - Type:  
     ```bash
     git --version
     ```
   - If you see the version number, you're good!

### For macOS:
1. Open **Terminal**.
2. Type:
   ```bash
   git --version
   ```
3. If Git is already installed, you'll see the version.  
   If not, you'll be prompted to install **Xcode Command Line Tools**. Click **Install** and follow the steps.
4. Once installed, check again with:
   ```bash
   git --version
   ```

---

## 2️⃣ Download (Clone) the Project
This creates a copy of the project on your computer.

1. Go to the GitHub page for the project. Example:
   ```
   https://github.com/yourusername/cave-dweller
   ```
2. Click the green **"Code"** button and copy the URL.
3. In Terminal (macOS) or PowerShell (Windows):
   ```bash
   git clone https://github.com/yourusername/cave-dweller.git
   ```
4. Go into the project folder:
   ```bash
   cd cave-dweller
   ```

---

## 3️⃣ How to Work on the Project
When you want to start working:
```bash
git pull
```
This updates your local copy with any new changes from the team.

---

## 4️⃣ Making Changes
1. Open the project in your editor (e.g., Unity, Visual Studio).
2. Edit, add files, or fix bugs as needed.
3. Save your work.

---

## 5️⃣ Sending Your Changes Back (Commit & Push)
### Step 1: Check what changed:
```bash
git status
```

### Step 2: Stage your changes:
```bash
git add .
```
(The `.` adds everything you've changed.)

### Step 3: Commit your changes with a short message:
```bash
git commit -m "Describe what you did here"
```

### Step 4: Push your changes to GitHub:
```bash
git push
```

---

## 🧠 Everyday Workflow (Quick Summary)
```bash
# Before you start working each day:
git pull

# After you're done:
git add .
git commit -m "What you changed"
git push
```

---

## ❗️ Important Tips
- **Always `git pull` before starting work** to stay up to date.
- Write clear commit messages so the team knows what you've done.
- If there are conflicts (Git will tell you), ask for help or follow the prompts to fix them.
- If you're unsure, **never be afraid to ask!**
