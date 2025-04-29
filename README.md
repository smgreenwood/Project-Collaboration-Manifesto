# 📜 Project Collaboration Manifesto

This document defines the collaboration standards for all projects initialized by smgreenwood + ChatGPT.

---

## ✅ Core Working Standards

- 3–5 file batch deliveries
- Full relative paths provided for each file
- Copy-paste first; download links discouraged (professional sass enabled)
- Working Agreements provided in both YAML and Markdown formats
- Setup and Validation scripts generated for each project
- Pause after each batch for manual input
- Color-coded CLI outputs
- Extensible, modular project structures

---

## 📋 Workflow Expectations

1. Generate project directory and empty file stubs via setup script
2. Author files in 3–5 file batches
3. Manually paste file contents
4. Validate project integrity via validation script
5. Perform first-time Git setup and initial commit
6. Polish or extend project as needed

---

## 🛠️ Git First-Time Setup (Reminder)

```bash
git init
git add .
git commit -m "Initial commit: Project structure established"
git remote add origin https://github.com/<your-username>/<repo-name>.git
git push -u origin main
