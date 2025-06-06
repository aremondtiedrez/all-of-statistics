# all-of-statistics
Self-study of Wasserman's All of Statistics.
- Extensive notes and solutions to the theoretical exercises are provided as a PDF [file](https://github.com/aremondtiedrez/all-of-statistics/blob/main/all_of_statistics_notes.pdf).
- Solutions to the coding exercises are provided as jupyter notebooks.

## Reference notebooks
The coding exercises include the implementation of several important statistical inference techniques.
For ease of access, we list these here.
 1. Confidence bands for the empirical CDF: chapter 7, [exercise 3](https://github.com/aremondtiedrez/all-of-statistics/blob/main/ch07/Chapter%2007%20-%20Exercise%2003.ipynb)
    and [exercise 7](https://github.com/aremondtiedrez/all-of-statistics/blob/main/ch07/Chapter%2007%20-%20Exercise%2007.ipynb).
 2. Bootstrap confidence intervals: chapter 8, [exercise 3](https://github.com/aremondtiedrez/all-of-statistics/blob/main/ch08/Chapter%2008%20-%20Exercise%203.ipynb).
 3. Permutation test: chapter 10, bonus, [permutation tests](https://github.com/aremondtiedrez/all-of-statistics/blob/main/ch10/Chapter%2010%20-%20Bonus%20-%20Permutation%20Tests.ipynb).
 4. Goodness-of-fit test: chapter 10, bonus, [goodness-of-fit test](https://github.com/aremondtiedrez/all-of-statistics/blob/main/ch10/Chapter%2010%20-%20Bonus%20-%20Goodness-of-fit%20Test.ipynb) (only for a Normal model).
 5. Confidence intervals (both normal and percentile) from both parametric bootstrap and posterior distributions:
    chapter 11, exercise 4, [version 2](https://github.com/aremondtiedrez/all-of-statistics/blob/main/ch11/Chapter%2011%20-%20Exercise%2004%20-%20Version%202.ipynb).
 6. James-Stein estimator (and comparison to the MLE) with a nice tabulated summary of the results: chapter 12, [exercise 6](https://github.com/aremondtiedrez/all-of-statistics/blob/main/ch12/Chapter%2012%20-%20Exercise%2006.ipynb).
 7. Simple linear regression, with plots: chapter 13, [exercise 6](https://github.com/aremondtiedrez/all-of-statistics/blob/main/ch13/Chapter%2013%20-%20Exercise%2006.ipynb).
 8. Multiple linear regression, with varying model selection procedures: chapter 13, [exercise 7](https://github.com/aremondtiedrez/all-of-statistics/blob/main/ch13/Chapter%2013%20-%20Exercise%2007.ipynb).
 9. Logistic regression, with varying model selection procedures: chapter 13, exercise 11, [version 3](https://github.com/aremondtiedrez/all-of-statistics/blob/main/ch13/Chapter%2013%20-%20Exercise%2011%20-%20Version%203.ipynb).
10. Sampling uniformly at random from the $(k−1)$–dimensional simplex: chapter 14, [exercise 3](https://github.com/aremondtiedrez/all-of-statistics/blob/main/ch14/Chapter%2014%20-%20Exercise%2003.ipynb).
11. Cheap way to generate symmetric positive-definite matrices (although the distribution is not guaranteed to be anything specific):
    chapter 14, [exercise 4](https://github.com/aremondtiedrez/all-of-statistics/blob/main/ch14/Chapter%2014%20-%20Exercise%2004.ipynb).
12. Fisher confidence interval for the correlation: chapter 14, [exercise 5](https://github.com/aremondtiedrez/all-of-statistics/blob/main/ch14/Chapter%2014%20-%20Exercise%2005.ipynb).
13. Testing the independence of two binary random variables: chapter 15, [exercise 4](https://github.com/aremondtiedrez/all-of-statistics/blob/main/ch15/Chapter%2015%20-%20Exercise%2004.ipynb).
14. Testing the independence of two discrete random variables: chapter 15, [exercise 5](https://github.com/aremondtiedrez/all-of-statistics/blob/main/ch15/Chapter%2015%20-%20Exercise%2005.ipynb).
15. Testing the independence of a continuous random variable and a binary random variable: chapter 15, [exercise 7](https://github.com/aremondtiedrez/all-of-statistics/blob/main/ch15/Chapter%2015%20-%20Exercise%2007.ipynb).
16. Density estimation via histograms and kernel density estimators, with cross-validation selection of the amount of smoothing and confidence band:
    chapter 20, exercise 2, [version 2](https://github.com/aremondtiedrez/all-of-statistics/blob/main/ch20/Chapter%2020%20-%20Exercise%2002%20-%20Version%202.ipynb),
    [version 3](https://github.com/aremondtiedrez/all-of-statistics/blob/main/ch20/Chapter%2020%20-%20Exercise%2002%20-%20Version%203.ipynb), and
    [version 4](https://github.com/aremondtiedrez/all-of-statistics/blob/main/ch20/Chapter%2020%20-%20Exercise%2002%20-%20Version%204.ipynb)
    (version 2 takes care of histogram estimation, version 3 takes care of kernel density estimation, and version 4 performs kernel density estimation, with given bandwidth, using the Fast Fourier Transform).
17. Nonparametric regression via the Nadaraya-Watson kernel estimator: chapter 20, [exercise 3](https://github.com/aremondtiedrez/all-of-statistics/blob/main/ch20/Chapter%2020%20-%20Exercise%2003.ipynb).
18. Cosine basis approximation: chapter 21, [exercise 6](https://github.com/aremondtiedrez/all-of-statistics/blob/main/ch21/Chapter%2021%20-%20Exercise%2006.ipynb).
19. Haar wavelet basis approximation: chapter 21, [exercise 12](https://github.com/aremondtiedrez/all-of-statistics/blob/main/ch21/Chapter%2021%20-%20Exercise%2012.ipynb).
20. Haar wavelet density estimation: chapter 21, [exercise 10](https://github.com/aremondtiedrez/all-of-statistics/blob/main/ch21/Chapter%2021%20-%20Exercise%2010.ipynb).
21. Cosine basis regression: chapter 21, exercise 7, [version 2](https://github.com/aremondtiedrez/all-of-statistics/blob/main/ch21/Chapter%2021%20-%20Exercise%2007%20-%20Version%202.ipynb).
22. Haar wavelet basis regression: chapter 21, exercise 7, [version 3](https://github.com/aremondtiedrez/all-of-statistics/blob/main/ch21/Chapter%2021%20-%20Exercise%2007%20-%20Version%203.ipynb).
23. Classification via LDA, QDA, logistic regression, and trees, including $k$-fold cross-validation and very rudimentary feature selection (using a Wald test to test for significant intra-class mean differences):
    chapter 22, exercise 3, [version 3](https://github.com/aremondtiedrez/all-of-statistics/blob/main/ch22/Chapter%2022%20-%20Exercise%2003%20-%20Version%203.ipynb).
24. Classification using a linear SVM, i.e. an Optimal Separating Hyperplane classifier (in the terminology of the aforementioned [notes](https://github.com/aremondtiedrez/all-of-statistics/blob/main/all_of_statistics_notes.pdf)):
    chapter 22, [exercise 5](https://github.com/aremondtiedrez/all-of-statistics/blob/main/ch22/Chapter%2022%20-%20Exercise%2005.ipynb).
25. Classification using SVM with polynomial kernels of various degrees (including building an sklearn pipeline to normalize the data):
    chapter 22, exercise 8, [version 2](https://github.com/aremondtiedrez/all-of-statistics/blob/main/ch22/Chapter%2022%20-%20Exercise%2008%20-%20Version%2002.ipynb).
26. Classification using SVM with Gaussian kernel, including hyper-parameter search to minimize the cross-validation estimate of the true error rate:
    chapter 22, [bonus 3](https://github.com/aremondtiedrez/all-of-statistics/blob/main/ch22/Chapter%2022%20-%20Bonus%2003.ipynb).
27. Classification using kernel logistic regression (with both polynomial kernels and the Gaussian kernel), including building a custom KernelTransformer to streamline that process:
    chapter 22, [bonus 2](https://github.com/aremondtiedrez/all-of-statistics/blob/main/ch22/Chapter%2022%20-%20Bonus%2002.ipynb).
28. $k$-nearest neighbors classification, including cross-validation search for the best $k$:
    chapter 22, [exercise 9](https://github.com/aremondtiedrez/all-of-statistics/blob/main/ch22/Chapter%2022%20-%20Exercise%2009.ipynb).
29. Bagging (based on trees): chapter 22, [exercise 11](https://github.com/aremondtiedrez/all-of-statistics/blob/main/ch22/Chapter%2022%20-%20Exercise%2011.ipynb).
30. Boosting (using AdaBoost, and based on trees): chapter 22, [exercise 12](https://github.com/aremondtiedrez/all-of-statistics/blob/main/ch22/Chapter%2022%20-%20Exercise%2012.ipynb).
