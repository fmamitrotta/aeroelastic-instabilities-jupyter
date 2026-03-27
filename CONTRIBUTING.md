# Contributing to Introduction to Aeroelastic Instabilities with Jupyter Notebooks

Thank you for your interest in contributing to this educational project! Contributions of all kinds are welcome.

## Ways to Contribute

- **Report bugs**: If a notebook cell produces an error or unexpected output, [open an issue](https://github.com/fmamitrotta/aeroelastic-instabilities-jupyter/issues/new).
- **Fix typos or improve explanations**: Submit a pull request with your corrections.
- **Suggest new exercises or examples**: Open an issue describing your idea.
- **Improve visualizations**: Better plots or interactive widgets are always appreciated.
- **Add translations**: If you'd like to translate the materials into another language, please open an issue to discuss.

## Getting Started

1. Fork the repository
2. Clone your fork:
   ```bash
   git clone https://github.com/YOUR-USERNAME/aeroelastic-instabilities-jupyter.git
   cd aeroelastic-instabilities-jupyter
   ```
3. Create a conda environment:
   ```bash
   conda env create -f environment.yml
   conda activate aeroelastic-instabilities-jupyter
   ```
4. Create a new branch for your changes:
   ```bash
   git checkout -b my-improvement
   ```
5. Make your changes and verify all notebooks run without errors
6. Submit a pull request

## Guidelines

- **Keep notebooks beginner-friendly**: The target audience includes students with no prior Python experience.
- **Preserve the "coding as translation" pattern**: When adding code, present the mathematical formula first, then translate it to Python step by step.
- **Test your changes**: Run all modified notebooks from top to bottom to ensure they execute without errors.
- **Clear notebook outputs**: Before committing, clear all cell outputs to keep the repository size manageable. You can do this via `Kernel > Restart & Clear Output` in Jupyter.
- **Follow existing style**: Match the variable naming conventions (e.g., `rho` for density, `k_theta` for torsional stiffness) and commenting style used in the existing notebooks.

## Code of Conduct

Please be respectful and constructive in all interactions. We are committed to providing a welcoming and inclusive environment for everyone.

## Questions?

If you have questions about contributing, feel free to [open an issue](https://github.com/fmamitrotta/aeroelastic-instabilities-jupyter/issues) or contact the instructor at francesco.mitrotta@uc3m.es.
