# Markdown / README.md Cheat Sheet

This file contains common Markdown syntax used in GitHub README files.

## 1. Headings

```markdown
# Heading 1
## Heading 2
### Heading 3
#### Heading 4
```

More `#` symbols create smaller headings.

## 2. Bold and Italic

```markdown
**Bold text**

*Italic text*

***Bold and italic***
```

## 3. Bullet List

```markdown
- Item 1
- Item 2
- Item 3
```

### Nested List

```markdown
- Item 1
  - Sub-item 1
  - Sub-item 2
```

## 4. Numbered List

```markdown
1. First
2. Second
3. Third
```

## 5. Link

```markdown
[Google](https://www.google.com)
```

Syntax:

```text
[Display text](URL)
```

## 6. Image

```markdown
![Image description](image.png)
```

Syntax:

```text
![Alternative text](image URL or path)
```

## 7. Inline Code

Use single backticks:

```markdown
Run `git status` to check the repository.
```

## 8. Code Block

Use three backticks:

````markdown
```bash
git status
git add .
git commit -m "Initial commit"
```
````

### Python Example

````markdown
```python
print("Hello")
```
````

The language after the opening backticks enables syntax highlighting.

## 9. Quote

```markdown
> This is an important note.
```

## 10. Horizontal Line

```markdown
---
```

## 11. Line Break

```markdown
First line<br>
Second line
```

`<br>` is HTML and can be used inside Markdown.

## 12. Checkbox

```markdown
- [ ] Task not completed
- [x] Task completed
```

## 13. Table

```markdown
| Name | Age |
|------|-----|
| John | 25  |
| Alex | 30  |
```

### Table Alignment

```markdown
| Left | Center | Right |
|:-----|:------:|------:|
| A    | B      | C     |
```

## 14. Escape Special Characters

Use `\` when you want a special Markdown character to be displayed instead of interpreted.

```markdown
\# This is not a heading
```

## Quick Reference

| Syntax          | Purpose                  |   |       |
| --------------- | ------------------------ | - | ----- |
| `#`             | Heading 1                |   |       |
| `##`            | Heading 2                |   |       |
| `###`           | Heading 3                |   |       |
| `**text**`      | Bold                     |   |       |
| `*text*`        | Italic                   |   |       |
| `***text***`    | Bold + italic            |   |       |
| `- item`        | Bullet list              |   |       |
| `1. item`       | Numbered list            |   |       |
| `[text](URL)`   | Link                     |   |       |
| `![alt](image)` | Image                    |   |       |
| `` `code` ``    | Inline code              |   |       |
| ` ``` `         | Code block               |   |       |
| `>`             | Quote                    |   |       |
| `---`           | Horizontal line          |   |       |
| `<br>`          | Line break               |   |       |
| `- [ ]`         | Unchecked checkbox       |   |       |
| `- [x]`         | Checked checkbox         |   |       |
| `               |                          | ` | Table |
| `\`             | Escape special character |   |       |

## Commonly Used Code Block Languages

````markdown
```bash
# Bash commands
```

```powershell
# PowerShell commands
```

```python
# Python code
```

```javascript
// JavaScript code
```

```json
{
  "name": "example"
}
```

```yaml
name: example
```

```html
<h1>Hello</h1>
```

```text
Plain text
```
````

## Basic Pattern for a README

A typical README can be structured using:

```markdown
# Project Name

Short description.

## Features

- Feature 1
- Feature 2

## Installation

Installation instructions.

## Usage

Usage instructions.

## Configuration

Configuration details.

## Examples

Examples and code blocks.

## Notes

Important information.

## License

License information.
```
