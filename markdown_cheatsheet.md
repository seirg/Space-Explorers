# 🧾 GitHub Markdown Cheat Sheet

## 🧠 Core Concept
Markdown is a lightweight markup language — you format text using plain symbols instead of rich-text buttons.
Used in:
- `README.md` files
- Issues and Pull Requests
- Wikis, Discussions, Comments

> 💡 Tip: GitHub auto-renders `.md` files and allows preview.

---

## 📌 Headings
```markdown
# Project Title
## Section
### Subsection
```

```javascript
function hello() {
  console.log("Hello, World!");
}
```

---

## ✍️ Emphasis
```markdown
*italic*   _also italic_
**bold**   __also bold__
***bold italic***
~~strikethrough~~
```

---

## 📋 Lists
**Unordered:**
```markdown
- Item 1
- Item 2
  - Subitem
```

**Ordered:**
```markdown
1. Step one
2. Step two
    1. step2a
    2. step2b
```

**Checkboxes:**
```markdown
- [x] Done
- [ ] To do
```

---

## 🔗 Links
```markdown
[GitHub](https://github.com)
```
[GitHub](https://github.com)

Or reference style:
```markdown
[GitHub][1]

[1]: https://github.com
```

---

## 🖼️ Images
Remote image: _(raw format needed)_
```markdown
![Alt text](https://raw.githubusercontent.com/SQLtattoo/azd-az104-all-in-one/refs/heads/master/demoguide/images/az104allinone-diagram.png)
```
![Alt text](https://raw.githubusercontent.com/SQLtattoo/azd-az104-all-in-one/refs/heads/master/demoguide/images/az104allinone-diagram.png)


Local example:
```markdown
![Team Orion Logo](./images/team_orion_logo.png)
```
![Team Orion Logo](./images/team_orion_logo.png)

> 💡 Use local `/images/` folder when possible and include descriptive alt text.

---

## 🧱 Code Blocks
Inline: `code`

Multiline:
<pre>
```python
print("Hello, Mars!")
```
</pre>
---

Use `code` like that for inline code.
---

## 📊 Tables
```markdown
| Planet | Distance (AU) | Discovered |
|--------|----------------|-------------|
| Mercury | 0.39 | Ancient |
| Venus | 0.72 | Ancient |
| Earth | 1.00 | — |
```

| Planet | Distance (AU) | Discovered |
|:--------:|----------:|:-------------:|
| Mercury | 0.39 | Ancient |
| Venus | 0.72 | Ancient |
| Earth | 1.00 | — |
---

## 📎 Blockquotes
```markdown
> “Team Orion explores space, one commit at a time.”
```

---

## ⚙️ Horizontal Rule
```markdown
---
```

---

## 💬 Mentions & Emojis
```markdown
@username  – mentions someone
:rocket:   – 🚀
😄 :smile:
❤️ :heart:
👍 :thumbsup:
🚀 :rocket:
🐛 :bug:
✨ :sparkles:
🔥 :fire:
```
---

```mermaid
graph TD;
    A-->B;
    A-->C;
    B-->D;
    C-->D;
```

---


## 🧩 GitHub Flavored Markdown (GFM)
Includes extras like:
- Task lists ✅
- Tables
- Strikethrough
- Syntax highlighting
- Mentions (`@user`)
- PR linking (`#123`)

---

## ✅ Best Practices
- Use headings & lists for structure.
- Keep README.md concise & helpful.
- Preview before committing.
- Always update Markdown through branches + PRs.