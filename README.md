# Tutorials and experimentation with 'skimage'

This repository contains my notes from following tutorials or personal experimentations with the ['skimage'](https://scikit-image.org/) python library.

## Setup

```bash
python -m venv .env
source .env/bin/activate
pip install --upgrade pip
pip install -r requirements.txt
pre-commit install
```

## Notes

### User Guide

|Notebook                                                                                        |
|:-----------------------------------------------------------------------------------------------|
| [4. A crash course on NumPy for images](./user-guide/04_numpy-for-images.ipynb)                |
| [9. Image adjustment: transforming image content](./user-guide/09_image-adjustment.ipynb)      |
| [10. Geometrical transformations of images](./user-guide/10_geometrical-transformations.ipynb) |

### Examples

| Notebook                                                    | Original article |
|:------------------------------------------------------------|:-----------------|
| [Canny edge detector](./examples/canny-edge-detector.ipynb) | [link](https://scikit-image.org/docs/stable/auto_examples/edges/plot_canny.html)
| [Straight line Hough transform](./examples/straight-line-hough-transform.ipynb) | [link](https://scikit-image.org/docs/stable/auto_examples/edges/plot_line_hough_transform.html) |
