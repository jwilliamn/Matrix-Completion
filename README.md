# Matrix-Completion

Sometimes also called the Netflix Problem, The main task in this problem is to fill or complete the missing entries of an incomplete matrix M.

In this project we explore and analyze several algorithms to solve the matrix completion problem such as Convex Relaxation, SVD and RPCA, and its corresponding implementation.

For a detailed explanation and formulation of such algoriths refer to the [project report](https://github.com/jwilliamn/Matrix-Completion/blob/master/Final_Project_Report.pdf).
We also made a presentation easy to understand, here [slides](https://github.com/jwilliamn/Matrix-Completion/blob/master/Final_Project_Report.pdf).

Here we show some results of the matrix completion applied to an image:

Original Image             |  Incomplete Image
:-------------------------:|:-------------------------:
![](gs.jpg)  |  ![](noise_0.6.jpg)


After performing matrix completion on the incomplete image we get:
Original Image             |  Complete Image
:-------------------------:|:-------------------------:
![](gs.jpg)  |  ![](results/nucnorm_0.6.jpg)


## Reproducibility
To reproduce the results of the experiments, follow the guidelines here:

### Prerequisites
A machine that supports the following packages

- Pillow
- numpy
- cvxpy
- scikit-image 
- opencv-python

### Getting Started

Installation:

- Clone this repository:
```bash
git clone https://github.com/jwilliamn/Matrix-Completion
cd Matrix-Completion
```

- Install requirements:
```bash
pip install -r requirements.txt
```
