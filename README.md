# Professional Software Engineer Resume Template (LaTeX)

![License](https://img.shields.io/badge/license-MIT-blue.svg) ![LaTeX](https://img.shields.io/badge/language-LaTeX-green.svg)

This repository contains the source code for my professional resume template, built using LaTeX. I designed this template specifically for software engineering roles, focusing on clean typography, efficient space utilization, and—most importantly—**ATS (Applicant Tracking System) compatibility**.

It uses a modular structure that makes it easy to swap out sections, add project details, or update skills without breaking the layout.

## 🚀 Key Features

* **ATS-Friendly:** Includes `glyphtounicode` and standard font mappings to ensure robots can parse text correctly.
* **Vector Icons:** Integrated `fontawesome5` for crisp, professional social icons (GitHub, LinkedIn, Email, etc.).
* **Space Efficient:** Adjusted margins and spacing to maximize content on a single page without looking cluttered.
* **Custom Macros:** Pre-defined LaTeX commands like `\resumeSubheading` and `\resumeProjectHeading` to standardize formatting across sections.

---

## 🛠️ Getting Started

You can edit this resume using an online editor (easiest) or a local LaTeX environment.

### Option 1: Overleaf (Recommended)

1.  Download the `main.tex` file from this repository.
2.  Create a new project on [Overleaf](https://www.overleaf.com/).
3.  Upload `main.tex` to your project.
4.  Set the compiler to **pdfLaTeX** (usually the default).
5.  Click **Recompile**.

### Option 2: Local Development

If you prefer VS Code or a local terminal, ensure you have a TeX distribution installed (TeX Live for Linux/Windows or MacTeX for macOS).

1.  **Clone the repository:**
    ```bash
    git clone [https://github.com/samarthsaxena2004/software-engineer-resume.git](https://github.com/samarthsaxena2004/software-engineer-resume.git)
    cd software-engineer-resume
    ```

2.  **Compile:**
    ```bash
    pdflatex main.tex
    ```
    *Note: You may need to run this twice to resolve certain layouts properly.*

---

## 📝 Customization Guide

I have commented the code heavily to make navigation easy, but here is a breakdown of the custom commands I created for this template.

### 1. Contact Information
At the top of `main.tex`, look for the `\begin{center}` block. You can update the icons and links here:

```latex
\faLinkedin\ \underline{\href{[https://linkedin.com/in/YOUR_ID](https://linkedin.com/in/YOUR_ID)}{[linkedin.com/in/YOUR_ID](https://linkedin.com/in/YOUR_ID)}}
\faGithub\ \underline{\href{[https://github.com/YOUR_ID](https://github.com/YOUR_ID)}{[github.com/YOUR_ID](https://github.com/YOUR_ID)}}
