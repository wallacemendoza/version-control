# `GIT_WORKFLOW_MASTERY`

```ascii
╔═══════════════════════════════════════════════════════════════╗
║                    PRODUCTION BRANCH                           ║
╚═══════════════════════════════════════════════════════════════╝
```

<div align="center">

![Git](https://img.shields.io/badge/GIT-PRODUCTION-F05032?style=for-the-badge&logo=git&logoColor=white)
![HTML](https://img.shields.io/badge/HTML-88.1%25-E34F26?style=for-the-badge&logo=html5&logoColor=white)

### ⚡ Professional Git Workflow Demonstration ⚡

**`GIT`** × **`BRANCHING`** × **`MERGING`** × **`TAGGING`**

</div>

-----

## 🎯 `STATUS: PRODUCTION_READY`

This branch contains the **stable, production-ready code** — fully tested and tagged releases only.

```yaml
current_branch: "main"
status: "production"
purpose: "Stable releases with semantic versioning"
protection: "Merge requests required"
```

-----

## 🚀 `VIEW_DEVELOPMENT_BRANCHES`

### **For active development and Git workflow examples:**

### 👉 **[Switch to `Working` branch](https://github.com/wallacemendoza/version-control/tree/Working)** 👈

```bash
git checkout Working
```

### **For QA/staging environment:**

### 👉 **[Switch to `Test` branch](https://github.com/wallacemendoza/version-control/tree/Test)** 👈

```bash
git checkout Test
```

-----

## 📦 `MAIN_BRANCH_PURPOSE`

```diff
Production Environment
├─ ✓ Tagged releases (v1.0.0, v1.1.0, etc.)
├─ ✓ Fully tested features
├─ ✓ Stable, deployable code
├─ ✓ Protected from direct commits
└─ ✓ Merge requests required
```

### Branch Strategy:

```
main (Production)
  ↑
  └─ Merges from Working after QA approval
     
Working (Development)
  ├─ Active feature development
  ├─ Integration testing
  └─ Merge requests to main

Test (Staging/QA)
  ├─ Pre-production testing
  ├─ Quality assurance
  └─ User acceptance testing
```

-----

## 🏷️ `RELEASES`

View tagged releases and version history:

```bash
# List all releases
git tag -l

# Checkout specific version
git checkout v1.0.0

# View release details
git show v1.0.0
```

-----

## 🎓 `GIT_WORKFLOW_PROJECT`

Demonstration of professional version control practices including:

- Feature branch workflows
- Merge strategies (no fast-forward)
- Conflict resolution
- Release tagging & versioning
- Commit message conventions
- Multi-branch management

**For full Git workflow documentation and examples, check the `Working` branch.**

-----

<div align="center">

### **[⚡ GO TO WORKING BRANCH ⚡](https://github.com/wallacemendoza/version-control/tree/Working)**

`main` = Production • `Working` = Development • `Test` = QA

</div>