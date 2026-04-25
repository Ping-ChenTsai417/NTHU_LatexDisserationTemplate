# NTHU Dissertation LaTeX Template

參照國立清華大學學位論文格式範本： https://www.lib.nthu.edu.tw/use/thesis_template.html

A clean, easy-to-use LaTeX template for writing Doctoral dissertations and Master's thesis at National Tsing Hua University (NTHU). This template complies with NTHU's formatting requirements and supports both Chinese and English content.

## 🚀 Quick Start

You can use this template online via Overleaf or locally on your computer using a LaTeX editor.

### Option 1: Using Overleaf (Recommended)
1. Compress all the files in this template into a single `.zip` file.
2. Go to [Overleaf](https://www.overleaf.com/) and click **New Project** -> **Upload Project**.
3. Upload your `.zip` file.
4. **Important**: Set the compiler. Click on the **Menu** (top-left) -> **Compiler** -> select **pdfLaTeX** (or **XeLaTeX** depending on your CJK font setup).
5. Open `main.tex` and click **Recompile**.

### Option 2: Using Local Editors (TeXmaker, TeXstudio, VS Code)
1. Ensure you have a LaTeX distribution installed (e.g., [TeX Live](https://tug.org/texlive/) or [MiKTeX](https://miktex.org/)).
2. Open `main.tex` in your preferred editor.
3. Make sure your editor is configured to compile using `pdfLaTeX` or `XeLaTeX`.
4. Compile the document (usually `F5` or `F6` depending on the editor). 
*Note: You may need to compile multiple times (e.g., pdfLaTeX -> Biber -> pdfLaTeX -> pdfLaTeX) to properly generate the bibliography and table of contents.*

---

## 📂 Project Structure

```text
├── main.tex                 # The main document (compile this file!)
├── nthu_thesis.cls          # The custom NTHU dissertation class file (do not rename)
├── 2026Titlepage.tex        # Cover page layout and formatting
├── front/                   # Frontmatter directory
│   ├── Eng_Abstract.tex     # English Abstract
│   ├── C_Abstract.tex       # Chinese Abstract
│   ├── acknowledgement.tex  # Acknowledgements
│   └── Nomenclature.tex     # List of Symbols/Abbreviations
├── contents/                # Main chapters directory
│   ├── chapter01.tex        # Introduction
│   ├── chapter02.tex        # Literature Review
│   └── ...                  # Add more chapters as needed
├── back/                    # Backmatter directory
│   └── appendix01.tex       # Appendices
├── references.bib           # Bibliography / References database
└── README.md                # This file
