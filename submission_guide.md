# Complete Git & GitHub Assignment Guide (Single Repository)

I have merged all tasks into **one single folder** for you. You only need to create **ONE repository** on GitHub.

## 🚀 How to Push Everything to ONE GitHub Repository

1. Go to **GitHub.com** and create a **New repository** named `ost_pac_assignment`.
2. Open your terminal and run:
   ```powershell
   cd "c:\JobSpot\ost pac assignment"
   git remote add origin https://github.com/YOUR_USERNAME/ost_pac_assignment.git
   git push -u origin main
   ```
   *(Replace `YOUR_USERNAME` with your actual GitHub username)*

---

## 📸 What to Screenshot for Each Task

### Task 1: Git Project Workflow
- **Activity:** I have already created a feature branch and merged it in this folder.
- **Screenshot:** In your terminal, run: `git log --oneline --graph --all`. Take a screenshot of the colored graph showing the merge.

### Task 2: GitHub Advanced Usage
1. **README & License:** These are already in the `task2_github_advanced` folder inside your repo.
2. **Closing an Issue:**
   - On GitHub, go to your new `ost_pac_assignment` repository.
   - Create a **New Issue** (e.g., "Fix README typo"). Note the number (e.g., #1).
   - I have already prepared a commit that says "Closes #1".
   - Just run `git push origin main` again after you create the issue, and it will close automatically!
- **Screenshot:** The closed issue page on GitHub.

### Task 3: Open Source Contribution
- This still requires you to **Fork** the `octocat/Spoon-Knife` repository as explained before.
- **Screenshot:** Your forked repository page.

### Task 4: Dependency Management
- **Screenshot:** Open the `task4_dependencies/package.json` file and take a screenshot of the `dependencies` section.
- **Explanation:** Use the `task4_dependencies/versioning_explanation.md` file for your explanation of `^1.2.3`.

---

## ✅ Summary of your local files:
- `/task1_git_workflow`: Shows branching and merging.
- `/task2_github_advanced`: Contains README, LICENSE, and issue closing logic.
- `/task4_dependencies`: Contains `package.json` with express/lodash.

You are all set! Just run the **three commands** at the top to push everything at once.
