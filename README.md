# Introduction to Aeroelastic Instabilities with Jupyter Notebooks

[![Binder](https://mybinder.org/badge_logo.svg)](https://mybinder.org/v2/gh/fmamitrotta/aeroelastic-instabilities-jupyter/main)
[![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/fmamitrotta/aeroelastic-instabilities-jupyter)

Interactive course materials for understanding static and dynamic aeroelastic instabilities using the typical section model.

## 🎯 Course Overview

This 10-hour doctoral course (1 ECTS credit) provides a hands-on introduction to aeroelastic phenomena through computational exercises. Students will explore divergence, flutter, and the effects of unsteady aerodynamics using Python and Jupyter notebooks.

## 📚 Learning Objectives

By the end of this course, you will be able to:
- Understand the fundamental physics of aeroelastic instabilities
- Model and analyze static divergence for the typical section
- Apply quasi-steady aerodynamics to study the simplified dynamic behavior of the typical section
- Understand Theodorsen's unsteady aerodynamic theory
- Use Python for aeroelastic simulations and visualization

## 📋 Prerequisites

- Basic knowledge of structural dynamics and vibrations
- Familiarity with differential equations
- Basic programming experience (Python helpful but not required)
- Your own laptop for hands-on exercises

## 🚀 Getting Started

### Option 1: Run in the Cloud (Recommended for beginners)
Click one of these badges to launch the notebooks in your browser - no installation needed!

- **Binder:** [![Binder](https://mybinder.org/badge_logo.svg)](https://mybinder.org/v2/gh/fmamitrotta/aeroelastic-instabilities-jupyter/main)
- **Google Colab:** [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/fmamitrotta/aeroelastic-instabilities-jupyter)

### Option 2: Local Installation
```bash
# Clone the repository
git clone https://github.com/fmamitrotta/aeroelastic-instabilities-jupyter.git
cd aeroelastic-instabilities-jupyter

# Create conda environment
conda env create -f environment.yml
conda activate aeroelasticity

# Launch Jupyter
jupyter notebook
```

## 📁 Repository Structure
```
.
├── notebooks/
│   ├── 00_Python_and_Jupyter_Intro.ipynb
│   ├── 01_Aeroelastic_Polar_and_Torsional_Divergence.ipynb
│   ├── 02_Quasi_Steady_Aerodynamics_and_the_Heave-Only_Model.ipynb
│   ├── 03_Quasi_Steady_Flutter_of_the_Heave-Pitch_Typical_Section.ipynb
│   ├── 04_Unsteady_Aerodynamics_and_Theodorsen_Function.ipynb
│   └── Assignment_Galloping.ipynb
├── data/              # Data files
├── figures/           # Output figures
├── utils/             # Helper functions
├── environment.yml    # Conda environment
├── requirements.txt   # Pip requirements
└── README.md
```

## 💻 Required Software

All notebooks require:
- Python 3.9+
- NumPy
- SciPy
- Matplotlib
- Jupyter
- Ipywidgets
- Ipympl

See `environment.yml` or `requirements.txt` for complete dependencies.

## 📝 How to Use These Materials

1. Start with **Notebook 0** if you're new to Python
2. Work through notebooks **1-4** sequentially during class sessions
3. Complete the **take-home assignment** after Session 2
4. Each notebook contains:
   - Theory introduction
   - Worked examples
   - Hands-on exercises
   - Reflection questions

## 📧 Contact & Support

**Instructor:** Francesco M. A. Mitrotta  
**Email:** francesco.mitrotta@uc3m.es  

For issues with the notebooks, please [open an issue](https://github.com/fmamitrotta/aeroelastic-instabilities-jupyter/issues).

## 📄 License

(c) 2026 Francesco M. A. Mitrotta. All content is under Creative Commons Attribution [CC-BY 4.0](https://creativecommons.org/licenses/by/4.0/legalcode.txt), and all [code is under BSD-3 clause](https://github.com/engineersCode/EngComp/blob/master/LICENSE). 

[![License](https://img.shields.io/badge/License-BSD%203--Clause-blue.svg)](https://opensource.org/licenses/BSD-3-Clause) [![License: CC BY 4.0](https://img.shields.io/badge/License-CC%20BY%204.0-lightgrey.svg)](https://creativecommons.org/licenses/by/4.0/)

## 🙏 Acknowledgments

Course developed as part of my research visit at the Department of Mechanics, Mathematics and Management (DMMM) of Politecnico di Bari.

---

⭐ If you find these materials useful, please star this repository!
