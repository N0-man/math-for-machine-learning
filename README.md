# Math for machine learning

This repo consist of my learnings while going through the `DAT256x: Essential Mathematics Artificial Intelligence` course on edx as a pre-requisite for MITx Machine Learning Certificaiton.

This Repo would document basic of **Equations, Graphs, Functions, Derivatives, Optimization, Vectors, Matrices, Statistics and Probability** using Python.

### Build Jupiter Book

Install ghp-import

```
pip install ghp-import
```

Build Jupiter Book

```
jb build .
```

From the main branch of your book’s root directory (which should contain the \_build/html folder) call ghp-import and point it to your HTML files

```
ghp-import -n -p -f _build/html
```

> :warning: …ghp-import will DESTROY your gh-pages branch… and assumes that the gh-pages branch is 100% derivative. You should never edit files in your gh-pages branch by hand if you’re using this script…

Your book is available on
https://N0-man.github.io/math-for-machine-learning/
