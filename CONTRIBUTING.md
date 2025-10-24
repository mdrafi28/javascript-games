# 🤝 Contributing Guidelines — JavaScript Games (Hacktoberfest 2025)

Thank you for your interest in contributing to the **JavaScript Games for Beginners** project! 🎮  
This repository is a part of **Hacktoberfest 2025**, and we welcome contributions from everyone — whether you’re a beginner or an experienced developer.

Please take a moment to read these guidelines to make the contribution process smooth and effective. 💪

---

## 🧩 Ways to Contribute

You can contribute to this project in several ways:

- 🕹️ Add a **new game** built using JavaScript, HTML, and CSS
- 🐞 Fix bugs in existing games
- 🎨 Improve the **UI/UX** or add animations
- 📘 Update **documentation**, comments, or project structure
- 💡 Suggest new features or enhancements via issues

> This project is **beginner-friendly** — feel free to explore, experiment, and learn!

---

## ⚙️ Setting Up Your Environment

1. **Fork** this repository by clicking the **Fork** button on the top right of the GitHub page.
2. **Clone** your forked copy:
   ```bash
   git clone https://github.com/<your-username>/javascript-games.git
   ```
3. **Navigate** to the project directory:
   ```bash
   cd javascript-games
   ```
4. **Create a new branch** for your feature or fix:
   ```bash
   git checkout -b feature-new-game
   ```
5. Make your changes, test your game, and ensure there are no errors in the browser console.

---

## 💡 Best Practices for Contributions

✅ Follow these simple rules before creating a Pull Request (PR):

- Create one PR per feature or fix.
- Use clear and descriptive commit messages.  
  Example:
  ```bash
  git commit -m "Add new game: Memory Match with timer"
  ```
- Ensure your code is well-formatted and easy to read.
- Include a brief description of what your PR does.

> **Tip:** Small, well-documented changes are easier to review and get merged faster!

---

## 🧠 How to Add a New Game

If you’re adding a new game, follow this structure:

```
javascript-games/
 ┣ 📂 content/
 ┃ ┗ 📂 contribution/
 ┃   ┗ 📂 your-name-games/
 ┃    ┣ 📜 index.html
 ┃    ┣ 📜 style.css
 ┃    ┗ 📜 script.js
```

Each game folder should contain at least:

- `index.html` — main game structure
- `style.css` — styling and visuals
- `script.js` — game logic

Also, include a short description of your game in the main [README.md](./README.md) table under **Example Games**.

---

## 🧾 Submitting a Pull Request

1. **Stage and commit** your changes:
   ```bash
   git add .
   git commit -m "Add new game: Flappy Bird Clone"
   ```
2. **Push** your branch to your forked repository:
   ```bash
   git push origin feature-new-game
   ```
3. Go to your GitHub repo → Click **Compare & Pull Request**.
4. Fill out the PR template and submit your pull request.
5. Wait for review and feedback.

> If your PR is valid and helpful, it will be merged and labeled **`hacktoberfest-accepted`** 🎉

---

## 🏷️ Labels and Their Meaning

| Label                    | Description                                 |
| ------------------------ | ------------------------------------------- |
| `hacktoberfest-accepted` | PR approved and counts toward Hacktoberfest |
| `good first issue`       | Great starting point for beginners          |
| `help wanted`            | Maintainer needs community support          |
| `enhancement`            | Suggestion for a new feature or improvement |
| `bug`                    | Reports or fixes for broken code            |

---

## 🚫 Avoid These Common Mistakes

- Don’t submit spammy PRs (e.g., random text or empty files).
- Avoid renaming or deleting other contributors’ files.
- Don’t copy other projects or duplicate existing games.
- Avoid unnecessary large image or media files.

> PRs that are spam or irrelevant will be **marked as invalid** and **won’t count** for Hacktoberfest.

---

## 💬 Need Help?

If you get stuck or need clarification:

- Open an **Issue** with your question.
- Join discussions under existing PRs.
- Or mention the maintainer in a comment for guidance.

We’re happy to help! 💬

---

## 🌟 Final Note

Thank you for contributing to **JavaScript Games for Beginners**!  
Your effort helps create a better space for learning, creativity, and collaboration.

> “Play. Code. Learn. Contribute.” — _Hacktoberfest 2025_ 💻🎮
