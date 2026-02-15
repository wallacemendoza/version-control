# `GIT_WORKFLOW_MASTERY`

```ascii
╔═══════════════════════════════════════════════════════════════╗
║                    QA / STAGING BRANCH                         ║
╚═══════════════════════════════════════════════════════════════╝
```

<div align="center">

![Git](https://img.shields.io/badge/GIT-QA/STAGING-FFA500?style=for-the-badge&logo=git&logoColor=white)
![Status](https://img.shields.io/badge/STATUS-TESTING-yellow?style=for-the-badge)

### 🧪 Quality Assurance & Pre-Production Testing 🧪

**`TESTING`** × **`QA`** × **`STAGING`** × **`VALIDATION`**

</div>

-----

## 🎯 `STATUS: QA_ENVIRONMENT`

This branch serves as the **staging/QA environment** — features are tested here before production deployment.

```yaml
current_branch: "Test"
status: "staging"
purpose: "Pre-production testing & quality assurance"
workflow: "Receives merges from Working, promotes to main after approval"
```

-----

## 🧪 `TESTING_WORKFLOW`

```
Working Branch (Dev)
      ↓
   [Merge]
      ↓
Test Branch (QA) ← You are here
      ↓
   [QA Pass]
      ↓
   [Merge]
      ↓
main Branch (Production)
```

### Purpose:

- **User Acceptance Testing (UAT)**
- **Integration Testing**
- **Performance Testing**
- **Cross-browser Testing**
- **Final QA Approval**

-----

## 🚀 `VIEW_OTHER_BRANCHES`

### **For complete implementation and documentation:**

### 👉 **[Switch to `Working` branch](https://github.com/wallacemendoza/version-control/tree/Working)** 👈

```bash
git checkout Working
```

### **For production-ready code:**

### 👉 **[Switch to `main` branch](https://github.com/wallacemendoza/version-control)** 👈

```bash
git checkout main
```

-----

## 📋 `TEST_BRANCH_CHECKLIST`

Before merging to production:

```diff
✓ All features function correctly
✓ No critical bugs
✓ Cross-browser compatibility verified
✓ Mobile responsiveness confirmed
✓ Performance metrics acceptable
✓ User acceptance testing completed
✓ Documentation updated
✓ Ready for production deployment
```

-----

## 🔄 `MERGE_WORKFLOW`

```bash
# Merge from Working to Test
git checkout Test
git merge Working
git push origin Test

# After QA approval, merge to main
git checkout main
git merge --no-ff Test
git tag -a v1.1.0 -m "Release version 1.1.0"
git push origin main --tags
```

-----

<div align="center">

### **[⚡ GO TO WORKING BRANCH FOR FULL DOCS ⚡](https://github.com/wallacemendoza/version-control/tree/Working)**

`main` = Production • `Working` = Development • `Test` = QA/Staging

</div>