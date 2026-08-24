# MATH 3260 Linear Algebra — Student Course Materials

This repository-ready package contains **student-facing course materials only**.

Included:

- 10 student Jupyter notebooks, one for each chapter;
- 10 chapter-notes PDFs;
- 10 combined worksheet PDFs;
- a course index notebook;
- a small Python requirements file.


## Getting started

### Option 1: Download from GitHub

1. On the GitHub repository page, choose **Code → Download ZIP**.
2. Unzip the downloaded folder.
3. Open `notebooks/00_Course_Index.ipynb`.
4. Open the chapter notebook assigned for class.
5. Save a personal copy before editing so you always retain a clean original.

### Option 2: Run locally with Jupyter

From the repository folder, install the required packages:

```bash
python -m pip install -r requirements.txt
```

Then start JupyterLab:

```bash
jupyter lab
```

### Option 3: Use Google Colab

Upload an individual `.ipynb` file from the `notebooks` folder to Google Colab. The notebooks are designed so that the main static examples still work even when optional interactive widgets are unavailable.

## Course materials

| Chapter | Topic | Student notebook | Notes | Worksheets |
|---:|---|---|---|---|
| 1 | Linear Systems | [Notebook](notebooks/Chapter_01_Student_Linear_Systems.ipynb) | [Notes](notes/Chapter_01_Linear_Systems_Notes.pdf) | [Worksheets](worksheets/Chapter_01_Linear_Systems_Worksheets.pdf) |
| 2 | Matrices | [Notebook](notebooks/Chapter_02_Student_Matrices.ipynb) | [Notes](notes/Chapter_02_Matrices_Notes.pdf) | [Worksheets](worksheets/Chapter_02_Matrices_Worksheets.pdf) |
| 3 | Determinants | [Notebook](notebooks/Chapter_03_Student_Determinants.ipynb) | [Notes](notes/Chapter_03_Determinants_Notes.pdf) | [Worksheets](worksheets/Chapter_03_Determinants_Worksheets.pdf) |
| 4 | Vector Spaces | [Notebook](notebooks/Chapter_04_Student_Vector_Spaces.ipynb) | [Notes](notes/Chapter_04_Vector_Spaces_Notes.pdf) | [Worksheets](worksheets/Chapter_04_Vector_Spaces_Worksheets.pdf) |
| 5 | Inner Product Spaces | [Notebook](notebooks/Chapter_05_Student_Inner_Product_Spaces.ipynb) | [Notes](notes/Chapter_05_Inner_Product_Spaces_Notes.pdf) | [Worksheets](worksheets/Chapter_05_Inner_Product_Spaces_Worksheets.pdf) |
| 6 | Linear Transformations | [Notebook](notebooks/Chapter_06_Student_Linear_Transformations.ipynb) | [Notes](notes/Chapter_06_Linear_Transformations_Notes.pdf) | [Worksheets](worksheets/Chapter_06_Linear_Transformations_Worksheets.pdf) |
| 7 | Eigenvalues and Eigenvectors | [Notebook](notebooks/Chapter_07_Student_Eigenvalues_and_Eigenvectors.ipynb) | [Notes](notes/Chapter_07_Eigenvalues_and_Eigenvectors_Notes.pdf) | [Worksheets](worksheets/Chapter_07_Eigenvalues_and_Eigenvectors_Worksheets.pdf) |
| 8 | Complex Vector Spaces | [Notebook](notebooks/Chapter_08_Student_Complex_Vector_Spaces.ipynb) | [Notes](notes/Chapter_08_Complex_Vector_Spaces_Notes.pdf) | [Worksheets](worksheets/Chapter_08_Complex_Vector_Spaces_Worksheets.pdf) |
| 9 | Linear Programming | [Notebook](notebooks/Chapter_09_Student_Linear_Programming.ipynb) | [Notes](notes/Chapter_09_Linear_Programming_Notes.pdf) | [Worksheets](worksheets/Chapter_09_Linear_Programming_Worksheets.pdf) |
| 10 | Numerical Methods | [Notebook](notebooks/Chapter_10_Student_Numerical_Methods.ipynb) | [Notes](notes/Chapter_10_Numerical_Methods_Notes.pdf) | [Worksheets](worksheets/Chapter_10_Numerical_Methods_Worksheets.pdf) |

## Student workflow

- Read the definitions and worked examples before attempting the worksheet problems.
- Run notebook code cells from top to bottom unless the notebook directs otherwise.
- Predict an answer before running computational verification when possible.
- Show mathematical reasoning in addition to Python output.
- Use exact arithmetic with SymPy when the problem requires exact values.
- Use NumPy/Matplotlib for numerical computation and visualization when appropriate.

## Technical notes

The notebooks use standard Markdown for mathematical callouts rather than raw HTML boxes. This improves portability between Jupyter, GitHub notebook previews, and other notebook environments. Saved cell outputs have been cleared so students begin with a clean working copy.
