# Discrete Simulation using SimPy

These are my notes on the Udemy corse
[Learn SimPy from Scratch](https://www.udemy.com/course/learn-simpy-from-scratch/)
by [Mantic wise](https://www.udemy.com/user/manticwise/).

## Setup

This project uses [uv](https://docs.astral.sh/uv/) for dependency management and
running Python tools.

### Dependencies

The project dependencies are defined in `pyproject.toml`:

- [simpy](https://simpy.readthedocs.io/): Discrete event simulation library
- [jupyter](https://jupyter.org/): Interactive notebook environment
- [nbconvert](https://nbconvert.readthedocs.io/): Convert Jupyter notebooks to
  other formats

### Running Commands

All commands should be run with `uv run`:

```bash
# Render the notebook to HTML
make render

# Convert notebook to LaTeX
make %.tex

# Convert notebook to PDF
make %.pdf

# Clean build artifacts
make clean
```

## Jupyter Notebook

The notes are in the Jupyter Notebook file `discrete-simulation.ipynb`.

There is also a [Google Colab](https://colab.google/) version of the notebook
available here,
[Discrete Simulation using SimPy](https://colab.research.google.com/drive/1fKhOAQW6Uxzld5DO66LFx8PZbQU1g1Y_?usp=sharing).

## Resources

- [Jupyter Documentation](https://jupyter.org/documentation)
- [nbconvert Documentation](https://nbconvert.readthedocs.io/en/latest/)
- [SimPy Documentation](https://simpy.readthedocs.io/en/latest/)
- [Udemy Course: Learn SimPy from Scratch](https://www.udemy.com/course/learn-simpy-from-scratch/)