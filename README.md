# neumf-evaluation

Comparison of *[Matrix Factorization](https://en.wikipedia.org/wiki/Matrix_factorization_(recommender_systems)) (MF)*, *[Neural Matrix Factorization](https://arxiv.org/pdf/1708.05031) (NeuMF)*, and *NeuMF* with *[MMR](https://www.cs.cmu.edu/~jgc/publication/The_Use_MMR_Diversity_Based_LTMIR_1998.pdf)* postprocessing. 

#### Data

The data for this project was exported from *[EasyStudy](https://github.com/radimvalis/EasyStudy-NeuMF)* framework.

#### Commands

To convert the notebook to HTML, run the following command:

```
jupyter nbconvert --to html --template pj --execute evaluation.ipynb
```