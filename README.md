# 📚 Monthly Language Learning Module

> One programming language per month — 12 languages, 48 structured weeks, zero fluff.

## Languages covered

| Month | Language | Level |
|-------|----------|-------|
| 1 | Python | Beginner |
| 2 | JavaScript | Beginner |
| 3 | TypeScript | Intermediate |
| 4 | Rust | Intermediate |
| 5 | Go | Intermediate |
| 6 | SQL | Beginner |
| 7 | Kotlin | Intermediate |
| 8 | Haskell | Advanced |
| 9 | C | Advanced |
| 10 | Swift | Intermediate |
| 11 | Elixir | Advanced |
| 12 | Assembly (x86) | Advanced |

## How to use

**Option 1 — Open locally (recommended)**
```bash
git clone https://github.com/YOUR_USERNAME/language-learning-module
open language-learning-module.html
```
Progress is saved automatically in your browser's `localStorage`.

**Option 2 — GitHub Pages**
1. Go to your repo **Settings → Pages**
2. Set source to `main` branch, root folder
3. Visit `https://YOUR_USERNAME.github.io/language-learning-module`

## Structure

Each month is broken into 4 weeks:
- **Weeks 1–3** — Core concepts with specific topics to cover
- **Week 4** — Project week to consolidate knowledge

Click any week card to mark it complete. Your progress persists across sessions.

## Customize it

Want different languages or a different order? Edit the `curriculum` array in `language-learning-module.html`:

```js
{ month: 1, lang: "Python", icon: "🐍", level: "beginner",
  tagline: "Your tagline here",
  weeks: [
    { title: "Week 1 topic", tasks: "Specific things to learn" },
    ...
  ],
  resources: ["Resource 1", "Resource 2", ...] }
```

## Contributing

PRs welcome! Ideas for contributions:
- Add more languages (Ruby, PHP, Zig, Clojure...)
- Add links to free resources
- Add a GitHub Actions workflow to auto-publish to GitHub Pages

---

Built with plain HTML/CSS/JS — no dependencies, no build step.
