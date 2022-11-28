# Numerical Methods

In this repository you can find all the methods related to the Numerical Methods subject
of the Universidad de la Amazonia.

The thematic content consists of:

* [Roots of Functions. Zeros of Functions](https://github.com/smaje99/numerical-methods-udla/blob/main/raices%20de%20funciones.ipynb)
    * Closed Methods
        * Bisection method
        * Regula falsi method
    * Open Methods
        * Fixed point method
        * Newton-Raphson method
        * Secant method
* [Linear Equation System. Lineal Algebra](https://github.com/smaje99/numerical-methods-udla/blob/main/sistema%20de%20ecuaciones%20lineales.ipynb)
    * Gauss elimination method
    * Gauss-Jordan elimination method
    * LU decomposition method
    * Inverse matrix method
    * Gauss-Seidel method [no work]
* [Numerical Derivation and Integration](https://github.com/smaje99/numerical-methods-udla/blob/main/Derivaci%C3%B3n%20e%20Integraci%C3%B3n%20Num%C3%A9rica.ipynb)
    * Numerical Derivative
    * Simpson 3/8 method

---

## Setup
Step 1. Clone the repository.
```
git clone https://github.com/smaje99/numerical-methods-udla.git
```

Step 2. Create the virtual environment and install the libraries.
```
py -m venv venv
```
```
venv\Scripts\activate
```
```
pip install -r requirements.txt
```

Step 3. Create the kernel for Jupyter Notebook.
```
python -m ipykernel install --user --name venv --display-name "Python (Numerical)"
```
```
deactivate
```

Step 4. Run Jupyter Notebook
```
jupyter notebook
```

This commands are set to work on Windows.