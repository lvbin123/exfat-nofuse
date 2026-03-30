# Contributing to exfat-nofuse

Thank you for your interest in contributing to this project!

## How to Share Local Files / 如何提交本地文件

If you have local files (such as kernel patches, bug reports, or test cases) that you would like to share with the project, the best way is to use Git and GitHub:

### Option 1: Fork and Pull Request (Recommended)

1. [Fork](https://github.com/lvbin123/exfat-nofuse/fork) this repository on GitHub.
2. Clone your fork locally:
   ```bash
   git clone https://github.com/<your-username>/exfat-nofuse.git
   cd exfat-nofuse
   ```
3. Copy your files into the repository directory.
4. Commit and push them:
   ```bash
   git add <your-files>
   git commit -m "Add: <description of your changes>"
   git push origin main
   ```
5. Open a Pull Request from your fork to this repository.

### Option 2: Open an Issue

If you do not want to create a pull request, you can open a [GitHub Issue](https://github.com/lvbin123/exfat-nofuse/issues/new) and attach your files there (GitHub supports file attachments in issues).

### Option 3: Paste Code Inline

For small patches or code snippets, you can paste them directly into an issue or pull request description using a fenced code block:

```c
// Your patch or code snippet here
```

---

## 中文说明

如果您想向本项目提交本地目录下的文件（如内核补丁、问题报告、测试用例等），推荐以下几种方式：

1. **Fork + Pull Request**（推荐）：Fork 本仓库，将您的文件添加到本地克隆中，然后提交 Pull Request。
2. **提交 Issue**：在 [Issues 页面](https://github.com/lvbin123/exfat-nofuse/issues/new) 新建 Issue，并将文件作为附件上传。
3. **直接粘贴代码**：对于小的补丁或代码片段，可以直接在 Issue 或 Pull Request 描述中以代码块的形式粘贴。

---

## Code Style

Please follow the existing Linux kernel coding style used throughout the project (see [Linux kernel coding style](https://www.kernel.org/doc/html/latest/process/coding-style.html)).

## Reporting Bugs

When reporting bugs, please include:
- Linux kernel version
- Distribution and version
- Steps to reproduce the issue
- Any relevant kernel log output (`dmesg`)
