# Julia Sets Visualization Project

This project visualizes **Julia sets** for complex polynomials using Python. It demonstrates fractal generation by iterating over quadratic functions and provides tools for detailed visualizations.

## Features

- Detects **non-attractive fixed points** for the function \( f(z) = z^2 + c \).
- Approximates the **Julia set** by iterating through fixed points.
- Visualizes the Julia set using:
  - Scatter plots
  - Grid-based visualizations
- Extensible to handle **generalized polynomials**.

## How to Run

1. Clone the repository and navigate to the project directory.
2. Install the required libraries:
   ```bash
   pip install numpy matplotlib
   ```
3. Run the `julia-sets.ipynb` file in Jupyter Notebook or JupyterLab.
4. Modify parameters (e.g., \( c \) and \( N \)) to explore different Julia sets.

## Visualizations

The project provides two main visualization methods:

- **Scatter Plot:** Displays the Julia set as a collection of points in the complex plane.
- **Imshow Grid:** Provides a grid-based view for higher resolution and artistic representation.

## Example Usage

The notebook includes examples for generating Julia sets with different parameters. For instance:

```python
c = -0.12 + 0.74j
N = 10
plot_julia_set(c, N)
imshow_julia_set(c, N)
```

## License

This project is licensed under the **MIT License**. See the `LICENSE` file for details.
