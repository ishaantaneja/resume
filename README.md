# Ishaan Taneja — Full-Stack Developer Resume

This repository contains my **Full-Stack Developer resume** in Markdown format, with automated builds to PDF and DOCX using **Pandoc** and **GitHub Actions**. It is lightweight, version-controlled, and GitHub-ready.  

---

## 🚀 Features
- **Source format:** `src/resume.md` (Markdown) — editable and lightweight  
- **Outputs:** `output/resume.pdf` and `output/resume.docx`  
- **Automation:** GitHub Actions workflow auto-builds PDF/DOCX on every push  
- **Version control:** Track every update to resume content  
- **Secure & minimal:** No unnecessary dependencies; no sensitive data committed  

---



---

## ⚡ How to build locally
> Requires **Pandoc** and a minimal LaTeX engine (XeLaTeX) for PDF builds.

**Build DOCX and PDF:**  
```bash
mkdir -p output
pandoc src/resume.md -o output/resume.docx


pandoc src/resume.md -o output/resume.pdf --pdf-engine=xelatex -V geometry:margin=1in


