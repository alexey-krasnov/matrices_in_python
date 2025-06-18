# Matrices in Python

This project contains a list of Jupyter Notebooks that explains and demonstrates the basics of Matrices in Python. The notebooks includes theoretical explanations as well as practical examples.

## References to the articles
- [All you need to know about the basics of Matrices in Python: Part 1](https://medium.com/@alexeykrasnov1989/all-you-need-to-know-about-the-basics-of-matrices-in-python-part-1-ea9dc958d56e)


- [All you need to know about the basics of Matrices in Python: Part 2](https://medium.com/@alexeykrasnov1989/all-you-need-to-know-about-the-basics-of-matrices-in-python-part-2-5b2d66796ac9)

## Project Structure

- Part I: `Matrices_Part_1.ipynb`: the notebook provides Python code snippets that exercise matrix properties: matrix addition, scalar multiplication, matrix multiplication, and the identity matrix.

- Part II `Matrices_Part_2.ipynb`: th not provides Python code snippets that exercise next concepts: the determinant of a matrix, properties of the determinant of a matrix, minor and cofactors of a matrix.

## Prerequisites

To run the notebook, you need to have Python and Jupyter Lab installed. It's recommended to use a virtual environment to manage dependencies.

## Installation

### 1. **Clone the repository:**
 ```sh
 https://github.com/alexey-krasnov/matrices_in_python.git
 cd matrices_in_python
 ```

### 2. **Create a virtual environment:**

#### 2.1 Use venv
```sh
python -m venv my_env
source my_env/bin/activate  # On Windows, use `my_env\Scripts\activate`
```

#### 2.2 Or use conda
A) Download Miniforge3
    
```sh
wget https://github.com/conda-forge/miniforge/releases/latest/download/Miniforge3-MacOSX-arm64.sh
bash Miniforge3-MacOSX-arm64.sh
```
and follow instructions. See the documentation for  [Miniforge](https://github.com/conda-forge/miniforge) for more information.
    
B) Create new Conda Environment with python 3.12
```sh
conda create --name my_env "python<3.12"
source ~/.zshrc 
conda activate my_env
```

### 4. **Install the required packages:**
```sh
pip install -r requirements.txt
```

## **Start Jupyter Lab:**
```sh
jupyter lab
```

## Open the one of the notebook files and run cell by cell.

## Author
[Dr. Aleksei Krasnov](https://github.com/alexey-krasnov)
email: alexeykrasnov1989@gmail.com

Feel free to contribute, report issues, or provide feedback!

## License
This project is licensed under the MIT - see the LICENSE.md file for details.