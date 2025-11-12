# 🧾 Shubham Shejul — AutoCV

This repository automatically builds and publishes my latest resumes using **LaTeX** and **GitHub Actions**.

## 🔗 Live Resume Links

- [Main Resume (MERN Stack)](https://shejulshubham.github.io/resume/cv.pdf)
- [Alternate Resume](https://shejulshubham.github.io/resume/cv_2.pdf)
- [Home Page](https://shejulshubham.github.io/resume/)

---

### ⚙️ AutoCV Setup Summary

- Uses GitHub Actions to compile `cv.tex` and `cv_2.tex` with XeLaTeX.
- Uploads resulting PDFs to GitHub Pages (`gh-pages` branch).
- The site automatically updates on every push to `main`.

---

### 📁 Folder Overview

```
    resume/
    ├── cv.tex
    ├── cv_2.tex
    ├── index.html
    ├── README.md
    └── .github/workflows/build-and-deploy.yml
```
