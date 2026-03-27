# Introduction to Aeroelastic Instabilities with Jupyter Notebooks

[![Binder](https://mybinder.org/badge_logo.svg)](https://mybinder.org/v2/gh/fmamitrotta/aeroelastic-instabilities-jupyter/main)
[![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/fmamitrotta/aeroelastic-instabilities-jupyter)
[![Tests](https://github.com/fmamitrotta/aeroelastic-instabilities-jupyter/actions/workflows/test-notebooks.yml/badge.svg)](https://github.com/fmamitrotta/aeroelastic-instabilities-jupyter/actions/workflows/test-notebooks.yml)
[![License](https://img.shields.io/badge/License-BSD%203--Clause-blue.svg)](https://opensource.org/licenses/BSD-3-Clause)
[![License: CC BY 4.0](https://img.shields.io/badge/License-CC%20BY%204.0-lightgrey.svg)](https://creativecommons.org/licenses/by/4.0/)

Interactive Jupyter notebooks for learning aeroelastic instabilities (divergence, flutter, and galloping) through hands-on computation. Developed as a 10-hour doctoral course (1 ECTS) requiring no prior Python or aerospace engineering background.

> **Run instantly in the cloud** — no installation needed. Click Binder or Colab above.

## 🎯 Course Overview

This 10-hour short doctoral course (1 ECTS credit) provides a hands-on introduction to aeroelastic phenomena through computational exercises. The goal is to allow participants with diverse engineering background (no specific background in aerospace engineering is required) and no prior programming experience in Python to explore the phenomena of divergence and flutter using Python and Jupyter notebooks.

## 📚 Learning Objectives

By the end of this course, you will be able to:
- Understand the fundamental physics of aeroelastic instabilities
- Model and analyze static divergence for the typical section
- Understand quasi-steady aerodynamics and the heave approximation
- Analyze flutter for the 2-DOF typical section using quasi-steady aerodynamics

## 📋 Prerequisites

- Basic knowledge of dynamics and vibrations
- Familiarity with differential equations
- Basic programming experience (Python helpful but not required)
- Your own laptop for hands-on exercises

## 🚀 Getting Started

### Option 1: Run in the Cloud (Recommended for beginners)

Click one of these badges to launch the notebooks in your browser - no installation needed!

- **Binder:** [![Binder](https://mybinder.org/badge_logo.svg)](https://mybinder.org/v2/gh/fmamitrotta/aeroelastic-instabilities-jupyter/main)
- **Google Colab:** [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/fmamitrotta/aeroelastic-instabilities-jupyter)

### Option 2: Local Installation

If you are an experienced user and prefer to run the notebooks locally, make sure you have [git](https://git-scm.com/) and [Anaconda](https://anaconda.org/) installed, and then follow these steps:

```bash
# Clone the repository
git clone https://github.com/fmamitrotta/aeroelastic-instabilities-jupyter.git
cd aeroelastic-instabilities-jupyter

# Create conda environment
conda env create -f environment.yml
conda activate aeroelastic-instabilities-jupyter

# Launch Jupyter
jupyter notebook
```

## 📁 Repository Structure
```
├── notebooks/
│   ├── 00_Python_and_Jupyter_Intro.ipynb
│   ├── 01_Aeroelastic_Polar_and_Torsional_Divergence.ipynb
│   ├── 02_Quasi_Steady_Aerodynamics_and_the_Heave_Model.ipynb
│   ├── 03_Flutter_of_the_Heave-Pitch_Typical_Section_with_Quasi-Steady_Aerodynamics.ipynb
│   └── Take-Home_Assignment_Linear_Aeroelastic_Galloping.ipynb
├── figures/             # Notebook figures
├── slides/              # Lecture slides
├── test_notebook.ipynb  # Environment verification notebook
├── environment.yml      # Conda environment
├── requirements.txt     # Pip requirements
├── LICENSE
└── README.md
```

## 💻 Required Software

All notebooks require:
- Python 3.9+
- NumPy
- SciPy
- Matplotlib
- Jupyter
- Ipympl

## 📝 How to Use These Materials

1. Start with **Notebook 0** if you're new to Python
2. Work through notebooks **1-3** sequentially during class sessions
3. Complete the **take-home assignment**
4. Each notebook contains:
   - Theory introduction with equations
   - Worked examples with step-by-step code
   - Hands-on exercises with TODO markers

## 📧 Contact & Support

**Instructor:** Francesco M. A. Mitrotta  
**Email:** francesco.mitrotta@uc3m.es  

For issues with the notebooks, please [open an issue](https://github.com/fmamitrotta/aeroelastic-instabilities-jupyter/issues).

## 📄 License

(c) 2026 Francesco M. A. Mitrotta. All content is under Creative Commons Attribution [CC-BY 4.0](https://creativecommons.org/licenses/by/4.0/legalcode.txt), and all [code is under BSD-3 clause](https://github.com/fmamitrotta/aeroelastic-instabilities-jupyter/blob/main/LICENSE). 


## 🙏 Acknowledgments

This short course was developed as part of my research visit at the Department of Mechanics, Mathematics and Management (DMMM) of Politecnico di Bari funded by the _"Call for the recruitment of visiting professors/researchers at DMMM for the year 2025"_.

## References

The following references were used in the development of this course:
- Krüger, W. (2025). Introduction into Aeroelasticity (lecture notes). [MechaTwing Summer School](https://www.dlr.de/en/ae/latest/events/mechatwing-summer-school), Gottingen, June 2 – 6, 2025.
- Hodges, D. H., & Pierce, G. A. (2011). Introduction to Structural Dynamics and Aeroelasticity (2nd ed.). Cambridge University Press. https://doi.org/10.1017/CBO9780511997112
- Demasi, L. (2024). Introduction to unsteady aerodynamics and dynamic aeroelasticity. Springer.
- Dimitriadis, G. (2017). Introduction to nonlinear aeroelasticity. Wiley.

In addition, the handbook [_Teaching and Learning with Jupyter_](https://jupyter4edu.github.io/jupyter-edu-book/), and the modules [CFD Python](https://github.com/barbagroup/CFDPython) and [AeroPython](https://github.com/barbagroup/AeroPython) by prof. Lorena A. Barba were invaluable resources for the development of the course materials.

---

⭐ If you find these materials useful, please star this repository!
