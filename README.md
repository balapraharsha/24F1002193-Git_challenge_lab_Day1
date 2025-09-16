# Git Challenge Lab – Day 1  
**Roll Number:** 24F1002193  

This repository contains my work for the **Git Challenge Lab – Day 1**.  
The tasks demonstrate Git basics: commits, branching, merge conflicts, and history visualization.  

---

## 📌 Tasks Completed  

### 1. Repository Setup
- Created directory named `24F1002193-Git_challenge_lab_Day1`.
- Initialized Git inside the directory.

### 2. File Creation & Commits
- Created 5 files (`file1.txt` … `file5.txt`).
- Added content and made **5 separate commits**.

📷 *Screenshot 1:* Git commit history after initial 5 commits.  

---

### 3. Branching
- Created two new branches:
  - `branch1`
  - `branch2`

📷 *Screenshot 2:* Branch list showing `main`, `branch1`, and `branch2`.  

---

### 4. Merge Conflict
- Modified the same file (`templates/index.html`) in **branch1** and **branch2**.
- Merged both into `main`, which resulted in a merge conflict.  

📷 *Screenshot 3:* Terminal showing merge conflict error.  
📷 *Screenshot 4:* `index.html` file showing conflict markers (`<<<<<<<`, `=======`, `>>>>>>>`).  

---

### 5. Conflict Resolution
- Manually resolved the merge conflict by combining changes.  
- Added and committed the resolved file.  

📷 *Screenshot 5:* Terminal after conflict resolution commit.  

---

### 6. Commit History Graph
- Visualized the commit history with branches and merges.  
- Used `git log --oneline --graph --decorate --all` or **Git Graph / GitLens** in VS Code.  

📷 *Screenshot 6:* Commit graph showing commits, branches, and merges.  
- File saved as: `24F1002193_4.png`.  

---

## 🚀 Commands Used
```bash
git init
git add <file>
git commit -m "message"
git branch branch1
git branch branch2
git checkout branch1
git checkout branch2
```

---

## ✅ Outcome
- Learned Git basics: commits, branches, and merging.
- Practiced handling merge conflicts.
- Visualized project history with Git commit graph.

---

git merge <branch>
git log --oneline --graph --decorate --all
