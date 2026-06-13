<h1 align="center">git-learning-examples</h1>

<p align="center">
  <strong>用可运行案例学习 Git：从提交、分支、合并到冲突处理。</strong>
</p>

<p>
  <img alt="Git" src="https://img.shields.io/badge/Git-F05032?logo=git&logoColor=white">
  <img alt="GitHub" src="https://img.shields.io/badge/GitHub-181717?logo=github&logoColor=white">
  <img alt="Learning" src="https://img.shields.io/badge/Type-Learning%20Examples-blue">
  <img alt="Status" src="https://img.shields.io/badge/Status-Building-brightgreen">
  <img alt="License" src="https://img.shields.io/badge/License-MIT-blue">
</p>

<p>
  <img alt="Repo size" src="https://img.shields.io/github/repo-size/kryoncode/git-learning-examples">
  <img alt="Last commit" src="https://img.shields.io/github/last-commit/kryoncode/git-learning-examples">
  <img alt="Commit activity" src="https://img.shields.io/github/commit-activity/m/kryoncode/git-learning-examples">
  <img alt="Stars" src="https://img.shields.io/github/stars/kryoncode/git-learning-examples?style=flat">
  <img alt="Forks" src="https://img.shields.io/github/forks/kryoncode/git-learning-examples?style=flat">
</p>

---

<p align="center">
  <a href="#简体中文">简体中文</a> |
  <a href="#english">English</a>
</p>

## 简体中文

### 项目目标

把 Git 学习拆成一组小案例。每个案例只解决一个问题，方便反复练习。

```text
init -> add -> commit -> branch -> merge -> conflict -> remote -> history
```

### 学习地图

| 阶段 | 主题 | 关键命令 | 状态 |
|---|---|---|---|
| 01 | 初始化仓库 | `git init` `git remote` | Planned |
| 02 | 创建提交 | `git add` `git commit` | Planned |
| 03 | 查看历史 | `git log` `git show` | Planned |
| 04 | 分支操作 | `git branch` `git switch` | Planned |
| 05 | 合并代码 | `git merge` | Planned |
| 06 | 处理冲突 | `git status` `git diff` | Planned |
| 07 | 远程同步 | `git push` `git pull` | Planned |
| 08 | 撤销恢复 | `git restore` `git revert` | Planned |

### Git 命令速览

| 场景 | 命令 |
|---|---|
| 查看状态 | `git status` |
| 暂存文件 | `git add README.md` |
| 提交变更 | `git commit -m "docs: update readme"` |
| 查看提交 | `git log --oneline --graph` |
| 新建分支 | `git switch -c feature/demo` |
| 合并分支 | `git merge feature/demo` |
| 查看远程 | `git remote -v` |
| 推送分支 | `git push -u origin main` |

### 仓库数据

| 指标 | Badge |
|---|---|
| 仓库大小 | ![Repo size](https://img.shields.io/github/repo-size/kryoncode/git-learning-examples) |
| 最近提交 | ![Last commit](https://img.shields.io/github/last-commit/kryoncode/git-learning-examples) |
| 月提交活跃 | ![Commit activity](https://img.shields.io/github/commit-activity/m/kryoncode/git-learning-examples) |
| Issue | ![Issues](https://img.shields.io/github/issues/kryoncode/git-learning-examples) |
| PR | ![Pull requests](https://img.shields.io/github/issues-pr/kryoncode/git-learning-examples) |
| License | ![License](https://img.shields.io/github/license/kryoncode/git-learning-examples) |

### 目录规划

```text
examples/
  01-init/
  02-commit/
  03-log/
  04-branch/
  05-merge/
  06-conflict/
  07-remote/
  08-restore/

notes/
  git-cheatsheet.md
  git-workflow.md
```

### 快速开始

```bash
git clone git@github.com:kryoncode/git-learning-examples.git
cd git-learning-examples
git status
```

### readme-generator 展示点

| 能力 | 当前体现 |
|---|---|
| GitHub 首屏 | 标题、定位、徽章组 |
| 数据装饰 | repo size、last commit、stars、forks、issues |
| 内容结构 | 目标、地图、命令、数据、目录 |
| 学习路径 | 从基础命令到协作场景 |
| 项目可信度 | LICENSE、远程仓库、可复制命令 |

### 推荐 GitHub Topics

```text
git
github
git-learning
version-control
developer-tools
tutorial
examples
```

## English

### Project Goal

Learn Git through small, runnable examples. Each example focuses on one Git scenario.

```text
init -> add -> commit -> branch -> merge -> conflict -> remote -> history
```

### Learning Map

| Stage | Topic | Commands | Status |
|---|---|---|---|
| 01 | Initialize repo | `git init` `git remote` | Planned |
| 02 | Create commits | `git add` `git commit` | Planned |
| 03 | Inspect history | `git log` `git show` | Planned |
| 04 | Work with branches | `git branch` `git switch` | Planned |
| 05 | Merge changes | `git merge` | Planned |
| 06 | Resolve conflicts | `git status` `git diff` | Planned |
| 07 | Sync remotes | `git push` `git pull` | Planned |
| 08 | Restore changes | `git restore` `git revert` | Planned |

### Git Command Cheatsheet

| Scenario | Command |
|---|---|
| Check status | `git status` |
| Stage files | `git add README.md` |
| Commit changes | `git commit -m "docs: update readme"` |
| View commits | `git log --oneline --graph` |
| Create branch | `git switch -c feature/demo` |
| Merge branch | `git merge feature/demo` |
| Show remotes | `git remote -v` |
| Push branch | `git push -u origin main` |

### Repository Stats

| Metric | Badge |
|---|---|
| Repo size | ![Repo size](https://img.shields.io/github/repo-size/kryoncode/git-learning-examples) |
| Last commit | ![Last commit](https://img.shields.io/github/last-commit/kryoncode/git-learning-examples) |
| Monthly activity | ![Commit activity](https://img.shields.io/github/commit-activity/m/kryoncode/git-learning-examples) |
| Issues | ![Issues](https://img.shields.io/github/issues/kryoncode/git-learning-examples) |
| Pull requests | ![Pull requests](https://img.shields.io/github/issues-pr/kryoncode/git-learning-examples) |
| License | ![License](https://img.shields.io/github/license/kryoncode/git-learning-examples) |

### Planned Structure

```text
examples/
  01-init/
  02-commit/
  03-log/
  04-branch/
  05-merge/
  06-conflict/
  07-remote/
  08-restore/

notes/
  git-cheatsheet.md
  git-workflow.md
```

### Quick Start

```bash
git clone git@github.com:kryoncode/git-learning-examples.git
cd git-learning-examples
git status
```

### readme-generator Highlights

| Capability | Current README |
|---|---|
| GitHub first screen | Title, tagline, badges |
| Data badges | repo size, last commit, stars, forks, issues |
| Content structure | goal, map, commands, stats, structure |
| Learning path | basic commands to collaboration scenarios |
| Project trust | LICENSE, remote repo, copyable commands |

### Recommended GitHub Topics

```text
git
github
git-learning
version-control
developer-tools
tutorial
examples
```

## License

[MIT](./LICENSE)
