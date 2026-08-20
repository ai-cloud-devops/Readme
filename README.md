# Markdown / README.md Syntax Guide

This README teaches common Markdown syntax by showing the **Markdown code** and the **result it produces**.

---

## 1. Headings

### Markdown

```markdown
# Heading 1
## Heading 2
### Heading 3
#### Heading 4
```

### Output

# Heading 1

## Heading 2

### Heading 3

#### Heading 4

---

## 2. Bold

### Markdown

```markdown
**This is bold text**
```

### Output

**This is bold text**

---

## 3. Italic

### Markdown

```markdown
*This is italic text*
```

### Output

*This is italic text*

---

## 4. Bold + Italic

### Markdown

```markdown
***This is bold and italic***
```

### Output

***This is bold and italic***

---

## 5. Bullet List

### Markdown

```markdown
- Apple
- Banana
- Orange
```

### Output

* Apple
* Banana
* Orange

---

## 6. Nested Bullet List

### Markdown

```markdown
- Fruit
  - Apple
  - Banana
- Vegetables
  - Potato
  - Carrot
```

### Output

* Fruit

  * Apple
  * Banana
* Vegetables

  * Potato
  * Carrot

---

## 7. Numbered List

### Markdown

```markdown
1. Install Git
2. Create repository
3. Add files
4. Commit changes
```

### Output

1. Install Git
2. Create repository
3. Add files
4. Commit changes

---

## 8. Link

### Markdown

```markdown
[Visit GitHub](https://github.com)
```

### Output

[Visit GitHub](https://github.com)

The syntax is:

```text
[Text that user clicks](URL)
```

---

## 9. Image

### Markdown

```markdown
![Git Logo](https://git-scm.com/images/logos/downloads/Git-Icon-1788C.png)
```

### Output

![Git Logo](https://git-scm.com/images/logos/downloads/Git-Icon-1788C.png)

The syntax is:

```text
![Alternative text](image URL)
```

---

## 10. Inline Code

Use a single backtick on each side.

### Markdown

```markdown
Run `git status` to check the repository.
```

### Output

Run `git status` to check the repository.

---

## 11. Code Block

Use three backticks before and after the code.

### Markdown

````markdown
```bash
git status
git add .
git commit -m "Initial commit"
git push
```
````

### Output

```bash
git status
git add .
git commit -m "Initial commit"
git push
```

The word `bash` tells GitHub that the code is Bash and enables syntax highlighting.

---

## 12. Python Code Block

### Markdown

````markdown
```python
name = "John"
print(name)
```
````

### Output

```python
name = "John"
print(name)
```

The language after the three backticks determines syntax highlighting.

Common languages:

```text
bash
powershell
python
javascript
java
json
yaml
html
css
sql
```

---

## 13. Quote

### Markdown

```markdown
> This is an important note.
```

### Output

> This is an important note.

---

## 14. Horizontal Line

### Markdown

```markdown
---
```

### Output

---

## 15. Line Break

Normally, pressing Enter once in Markdown may not create a visible new line.

Use `<br>` when you specifically want a line break.

### Markdown

```markdown
First line<br>
Second line
```

### Output

First line<br>
Second line

---

## 16. Checkbox

### Markdown

```markdown
- [ ] Task not completed
- [x] Task completed
```

### Output

* [ ] Task not completed
* [x] Task completed

GitHub renders these as checkboxes.

---

## 17. Table

### Markdown

```markdown
| Name | Age | Country |
|------|-----|---------|
| John | 25  | USA     |
| Alex | 30  | UK      |
| Ravi | 28  | India   |
```

### Output

| Name | Age | Country |
| ---- | --- | ------- |
| John | 25  | USA     |
| Alex | 30  | UK      |
| Ravi | 28  | India   |

The second line separates the header from the data.

---

## 18. Table Alignment

### Markdown

```markdown
| Left | Center | Right |
|:-----|:------:|------:|
| A    | B      | C     |
| D    | E      | F     |
```

### Output

| Left | Center | Right |
| :--- | :----: | ----: |
| A    |    B   |     C |
| D    |    E   |     F |

The `:` controls alignment:

```text
:-----     Left
:-----:    Center
-----:     Right
```

---

## 19. Strikethrough

### Markdown

```markdown
~~This text is deleted~~
```

### Output

~~This text is deleted~~

---

## 20. Escaping Markdown Characters

Sometimes you want Markdown to display a special character instead of interpreting it.

### Markdown

```markdown
\# This is not a heading
```

### Output

# This is not a heading

The `\` tells Markdown to treat `#` as a normal character.

---

## 21. Combining Markdown

You can combine different Markdown elements.

### Markdown

```markdown
## Git Commands

Use **Git** to manage your code.

Run `git status` to check your files.

> Always check your changes before committing.

- Add files
- Commit changes
- Push to GitHub
```

### Output

## Git Commands

Use **Git** to manage your code.

Run `git status` to check your files.

> Always check your changes before committing.

* Add files
* Commit changes
* Push to GitHub

---

# Quick Reference

| Markdown      | What it does     | Example                      |
| ------------- | ---------------- | ---------------------------- |
| `#`           | Heading 1        | `# Title`                    |
| `##`          | Heading 2        | `## Section`                 |
| `###`         | Heading 3        | `### Subsection`             |
| `**text**`    | Bold             | **text**                     |
| `*text*`      | Italic           | *text*                       |
| `***text***`  | Bold + italic    | ***text***                   |
| `- text`      | Bullet           | - Apple                      |
| `1. text`     | Numbered list    | 1. Apple                     |
| `` `code` ``  | Inline code      | `git status`                 |
| ` ``` `       | Code block       | Code                         |
| `[text](URL)` | Link             | [GitHub](https://github.com) |
| `![alt](URL)` | Image            | Image                        |
| `> text`      | Quote            | > Note                       |
| `---`         | Horizontal line  | Line                         |
| `<br>`        | Line break       | First<br>Second              |
| `- [ ]`       | Unchecked box    | - [ ] Task                   |
| `- [x]`       | Checked box      | - [x] Done                   |
| `\#`          | Escape character | #                            |

---

# Most Important Things to Remember

````text
#              → Heading
##             → Smaller heading
**text**       → Bold
*text*         → Italic
- item         → Bullet
1. item        → Numbered list
`code`         → Inline code
```            → Code block
[text](URL)    → Link
![alt](URL)    → Image
> text         → Quote
---            → Horizontal line
<br>           → Line break
- [ ]          → Checkbox
|              → Table
````

Markdown is primarily **text with special symbols**. GitHub reads those symbols and converts them into formatted content when it displays your `README.md`.
