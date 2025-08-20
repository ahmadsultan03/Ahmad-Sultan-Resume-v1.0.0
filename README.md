# Muhammad Ahmad Sultan - Resume

A professionally crafted LaTeX resume template showcasing my experience as an AI/ML Engineer and Software Developer.

## 📋 Overview

This repository contains my professional resume built using LaTeX, designed to be ATS-friendly and easily customizable. The resume highlights my 4+ years of professional experience in AI/ML engineering, full-stack development, and leadership roles.

## 📁 Repository Structure

```
├── .gitignore                              # Git ignore file
├── main.tex                                # LaTeX source file for the resume
├── Ahmad_Sultan_Resume_v1.0.0.pdf          # Compiled PDF version
├── CV v1.0.0.txt                          # Plain text version
├── LICENSE                                 # MIT License
├── profile_pic.png                        # Profile picture (dark background)
├── profilePic.png                          # Profile picture (light background)
└── README.md                               # This file
```

## 🚀 Features

- **ATS-Friendly**: Machine-readable format optimized for Applicant Tracking Systems
- **Professional Layout**: Clean, modern design with proper spacing and typography
- **Comprehensive Sections**: 
  - Professional Summary
  - Education
  - Work Experience
  - Technical Skills
  - Certifications & Training
  - Projects
  - Leadership & Activities
  - Languages
  - Additional Skills
- **Responsive Design**: Optimized for both digital viewing and printing
- **Easy Customization**: Well-structured LaTeX code for easy modifications

## 🛠️ Prerequisites

To compile this resume, you'll need:

- **LaTeX Distribution**: 
  - [TeX Live](https://www.tug.org/texlive/) (Linux/Windows)
  - [MacTeX](https://www.tug.org/mactex/) (macOS)
  - [MiKTeX](https://miktex.org/) (Windows)
- **LaTeX Editor** (Optional but recommended):
  - [Overleaf](https://www.overleaf.com/) (Online)
  - [TeXstudio](https://www.texstudio.org/)
  - [VS Code](https://code.visualstudio.com/) with LaTeX Workshop extension

## 📝 How to Compile

### Method 1: Using Command Line
```bash
# Navigate to the repository directory
cd path/to/resume

# Compile the LaTeX file
pdflatex main.tex

# For bibliography (if needed)
bibtex main
pdflatex main.tex
pdflatex main.tex
```

### Method 2: Using Overleaf
1. Create a new project on [Overleaf](https://www.overleaf.com/)
2. Upload the `main.tex` file
3. Click "Recompile" to generate the PDF

### Method 3: Using TeXstudio
1. Open `main.tex` in TeXstudio
2. Press F5 or click the "Build & View" button

## 🎨 Customization

### Personal Information
Edit the heading section in `main.tex`:
```latex
\begin{tabular*}{\textwidth}{l@{\extracolsep{\fill}}r}
  \textbf{\href{your-website}{\Large Your Name}} & Email: \href{mailto:your-email}{your-email}\\
  \href{}{Your Title} & Mobile: \href{tel:your-phone}{your-phone} \\
  Your Location & LinkedIn: \href{your-linkedin}{your-linkedin} \\
  & GitHub: \href{your-github}{your-github} \\
\end{tabular*}
```

### Adding New Sections
Use the predefined commands:
```latex
\section{New Section}
\resumeSubHeadingListStart
  \resumeSubheading{Title}{Location}{Position}{Date}
  \resumeItemListStart
    \resumeItem{Description of your achievement}
  \resumeItemListEnd
\resumeSubHeadingListEnd
```

### Modifying Colors
Change the title rule color:
```latex
\titleformat{\section}{
  \vspace{-4pt}\scshape\raggedright\large
}{}{0em}{}[\color{your-color}\titlerule \vspace{-5pt}]
```

## 📊 Key Highlights

- **4+ Years** of professional experience in AI/ML and software development
- **10+ Projects** delivered across various domains
- **5+ Technical certifications** from recognized institutions
- **Leadership roles** in academic and professional settings
- **Multilingual** capabilities (6 languages)

## 🏆 Technical Skills Covered

- **AI/ML**: Python, TensorFlow, PyTorch, LangChain, LLMs, RAG, GraphRAG
- **Web Development**: React, Node.js, FastAPI, MERN Stack
- **Databases**: MySQL, PostgreSQL, MongoDB, Neo4j, Vector Databases
- **Tools**: Docker, Git, Jupyter, VS Code, Postman

## 📄 License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## 🤝 Contributing

While this is a personal resume, suggestions for improving the LaTeX template are welcome! Please feel free to:

1. Fork the repository
2. Create a feature branch (`git checkout -b feature/improvement`)
3. Commit your changes (`git commit -am 'Add some improvement'`)
4. Push to the branch (`git push origin feature/improvement`)
5. Create a Pull Request

## 📞 Contact

**Muhammad Ahmad Sultan**
- 📧 Email: [m.ahmadsultan123mas@gmail.com](mailto:m.ahmadsultan123mas@gmail.com)
- 💼 LinkedIn: [ahmadsultan03](https://www.linkedin.com/in/ahmadsultan03/)
- 🐱 GitHub: [ahmadsultan03](https://github.com/ahmadsultan03)
- 🌐 Portfolio: [theahmadsultan.netlify.app](https://theahmadsultan.netlify.app/)

---

⭐ **Star this repository if you found it helpful!**

*Last Updated: August 2025*