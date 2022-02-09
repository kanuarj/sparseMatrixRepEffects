# Effects of Parametric and Non-Parametric Methods on High Dimensional Sparse Matrix Representations

This repository is the implementation of [Effects of Parametric and Non-Parametric Methods on High Dimensional Sparse Matrix Representations](https://arxiv.org/abs/2202.02894). If you use this repo or paper, please consider citing it.

The dataset used can be found [here](https://www.kaggle.com/andrewmvd/cyberbullying-classification).

## Citation :
```
@misc{tambe2022effects,
      title={Effects of Parametric and Non-Parametric Methods on High Dimensional Sparse Matrix Representations}, 
      author={Sayali Tambe and Raunak Joshi and Abhishek Gupta and Nandan Kanvinde and Vidya Chitre},
      year={2022},
      eprint={2202.02894},
      archivePrefix={arXiv},
      primaryClass={cs.LG}
}
```
## Results :
The results are calculated on the basis of classification metrics. Precision,  Recall and F1-Score.

### Precision :
The precision for 50 dimensions of the representations over used algorithms is checked.

Algorithm|Macro Average|Weighted Average
:---:|:---:|:---:
Linear Discriminant Analysis|89%|90%
Naive Bayes|79%|80%
Decision Tree|89%|90%
Support Vector Machine|90%|91%

Similarly Macro Averaging Precision is calculated for 100, 500, 1000, 5000 dimensions of sparse matrix representations.
Dimensions| LDA Naive| Bayes| Decision| Tree SVM
:---:|:---:|:---:|:---:|:---:
100| 90%| 83%| 89%| 92%
500 |91% |85%| 91%| 93%
1000 |92% |86%| 91%| 93%
5000 |92% |86%| 92%| 93%

Similarly Weighted Averaging Precision is calculated for 100, 500, 1000, 5000 dimensions of sparse matrix representations.
Dimensions |LDA |Naive Bayes |Decision Tree |SVM
:---:|:---:|:---:|:---:|:---:
100 |91% |83% |90% |92%
500 |92% |85% |91% |93%
1000 |92% |86% |91% |93%
5000 |92% |86% |92% |94%

### Recall :
The Macro Averaging Recall for 50, 100, 500, 1000, 5000 dimensions of sparse matrix representations.
Dimensions |LDA |Naive Bayes |Decision Tree |SVM
:---:|:---:|:---:|:---:|:---:
50 |88% |79% |88% |90%
100 |89% |82% |89% |91%
500 |91% |84% |91% |93%
1000 |91% |85% |91% |93%
5000 |91% |85% |92% |93%

The Weighted Averaging Recall for 50, 100, 500, 1000, 5000 dimensions of sparse matrix representations.
Dimensions |LDA |Naive Bayes |Decision Tree |SVM
:---:|:---:|:---:|:---:|:---:
50 |88% |80% |89% |90%
100 |89% |84% |89% |91%
500 |91% |85% |91% |93%
1000 |91% |86% |91% |93%
5000 |92% |87% |92% |93%

### F1-Score :
F1-Score for 50, 100, 500, 1000, 5000 dimensions of sparse matrix representations.
Dimensions |LDA |Naive Bayes |Decision Tree |SVM
:---:|:---:|:---:|:---:|:---:
50 |88% |80% |89% |90%
100 |89% |84% |89% |91%
500 |91% |85% |91% |93%
1000 |91% |86% |91% |93%
5000 |92% |87% |92% |93%
