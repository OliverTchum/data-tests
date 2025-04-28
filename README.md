## Practice Paper: Algorithms & Data - COMS20017

**Time Allowed: 2 Hours**

**This paper contains 20 questions.**

**Each question has exactly one correct answer.**

**All answers will be used for assessment.**

**The maximum for this paper is 100 marks.**

**You may use a calculator.**

**Calculators must be non-programmable.**

**The exam is closed-book (so no additional materials are allowed).**

**You may write workings out on the exam paper, and blank pages are provided at the end for this purpose. These workings out will not be collected or marked. You must enter your answers on the provided answer sheet only.**

**Questions:**

**Q1. Consider a single observation $x = A + w$, where $A$ is an unknown DC level and $w \sim N(0, \sigma^2)$. What is the Cramer-Rao Lower Bound for any unbiased estimator of $A$? [5 marks]**

A. $\sigma^2$

B. $2\sigma^2$

C. $\frac{\sigma^2}{2}$

D. $\frac{\sigma^2}{N}$ (where $N$ is the number of observations)

E. This cannot be determined with a single observation.


**Q2. Suppose we have $N$ independent and identically distributed i.i.d. samples $x[n] \sim N(A, \sigma^2)$ for $n = 0, 1, ..., N-1$, where $A$ is an unknown DC level and $\sigma^2$ is known. The Maximum Likelihood Estimate of $A$ is $$\hat{A}_{MLE} = \frac{1}{N} \sum_{n=0}^{N-1} x[n]$$. What is the variance of this MLE? [5 marks]**

A. $\sigma^2$

B. $N\sigma^2$

C. $\frac{\sigma^2}{N}$

D. $\frac{\sigma^2}{N^2}$

E. The variance depends on the true value of $A$.


**Q3. Consider a parameter estimation problem where the cost function is $C(\theta, \hat{\theta}) = |\theta - \hat{\theta}|$. The Bayesian estimator that minimizes the expected cost under this cost function is the: [5 marks]**

A. Mean of the posterior distribution.

B. Mode of the posterior distribution.

C. Median of the posterior distribution.

D. Minimum Mean Square Error (MMSE) estimator.

E. Maximum Likelihood Estimator (MLE).


**Q4. Given a classification problem with two classes, $\omega_1$ and $\omega_2$, and feature vector $\mathbf{x}$. According to the Bayesian classification rule for minimum error probability, $\mathbf{x}$ is assigned to $\omega_1$ if: [5 marks]**

A. $P(\omega_1|\mathbf{x}) < P(\omega_2|\mathbf{x})$

B. $p(\mathbf{x}|\omega_1) < p(\mathbf{x}|\omega_2)$

C. $P(\omega_1) < P(\omega_2)$

D. $P(\omega_1|\mathbf{x}) > P(\omega_2|\mathbf{x})$

E. $p(\mathbf{x}|\omega_1)P(\mathbf{x}) > p(\mathbf{x}|\omega_2)P(\mathbf{x})$


**Q5. In the context of Bayesian estimation, the denominator $p(x) = \int p(x|\theta)p(\theta) d\theta$ in Bayes' theorem is often referred to as the: [3 marks]**

A. Posterior distribution.

B. Likelihood function.

C. Prior distribution.

D. Evidence.

E. Bayes risk.


**Q6. Consider the multiresolution decomposition of an image using a 2-D wavelet transform at the first level. This process decomposes the image into four regions. These regions are typically referred to as: [4 marks]**

A. Approximation, Horizontal detail, Vertical detail, Diagonal detail.

B. Low-Low, Low-High, High-Low, High-High frequency subbands.

C. Approximation and three detail subbands.

D. Both A and B are correct.

E. A, B, and C are all correct.


**Q7. Which of the following statements about the Minimum Variance Unbiased Estimator (MVUE) is 
FALSE? [4 marks]**

A. The MVUE has zero bias.

B. The MVUE minimizes the variance among all unbiased estimators.

C. There is a standard procedure to find the MVUE for any estimation problem.

D. An unbiased estimator that attains the Cramer-Rao Lower Bound (CRLB) is an MVUE.

E. The MSE of an MVUE is equal to its variance.


**Q8. In a two-class classification problem with prior probabilities $P(\omega_1) = 0.6$ and $P
(\omega_2) = 0.4$, and likelihood functions $p(x|\omega_1)$ and $p(x|\omega_2)$. The decision boundary for a Bayesian classifier that minimizes the error probability is determined by the condition: [5 marks]**

A. $p(x|\omega_1) = p(x|\omega_2)$

B. $P(\omega_1)p(x|\omega_1) = P(\omega_2)p(x|\omega_2)$

C. $P(\omega_1) = P(\omega_2)$

D. $p(x) = p(x|\omega_1) + p(x|\omega_2)$

E. $\frac{p(x|\omega_1)}{p(x|\omega_2)} = 1$


**Q9. Which of the following matrix forms is characterized by having constant values along the anti-diagonals? [3 marks]**

A. Toeplitz matrix

B. Hankel matrix

C. Identity matrix

D. Diagonal matrix

E. Symmetric matrix


**Q10. Consider a scenario where you are estimating the parameters of a sinusoid embedded in noise. This is an example of a problem typically addressed in the field of: [3 marks]**

A. Classification.

B. Regression.

C. Estimation theory.

D. Data clustering.

E. Dimensionality reduction.


**Q11. Given a set of $N$ data points $\{x_i\}_{i=1}^N$, and a model $y = w_1 x + w_0$. The parameters $w_1$ and $w_0$ are estimated using the method of least squares by minimizing: [4 marks]**

A. $\sum_{i=1}^N |y_i - (w_1 x_i + w_0)|$

B. $\sum_{i=1}^N (y_i - (w_1 x_i + w_0))^2$

C. $\sum_{i=1}^N |y_i - (w_1 x_i + w_0)|^2$

D. $\sum_{i=1}^N (y_i - (w_1 x_i + w_0))$

E. $\max_i |y_i - (w_1 x_i + w_0)|$


**Q12. In Principal Component Analysis (PCA), the principal components are the eigenvectors of the: [5 marks]**

A. Data matrix.

B. Covariance matrix of the data.

C. Correlation matrix of the data.

D. Transpose of the data matrix.

E. Inverse of the covariance matrix.


**Q13. What is the role of the eigenvalues obtained from the covariance matrix in PCA? [4 marks]**

A. They define the direction of the principal components.

B. They indicate the amount of variance explained by each principal component.

C. They are used to normalize the eigenvectors.

D. They are the principal components themselves.

E. They are used to reconstruct the original data perfectly.


**Q14. Which of the following is a common technique for noise reduction in the wavelet domain? [3 marks]**

A. Convolution.

B. Filtering in the Fourier domain.

C. Thresholding of wavelet coefficients.

D. Principal Component Analysis.

E. Linear regression.


**Q15. Consider the characteristic function $\Phi(\omega) = exp( - \gamma |\omega|^\alpha)$. The parameters $\alpha$ and $\gamma$ can be estimated by: [5 marks]**

A. Directly computing them from the raw data.

B. Regressing $\log(|\Phi(\omega)|^2)$ against $|\omega|^\alpha$.

C. Regressing $\log(|\Phi(\omega)|)$ against $|\omega|^\alpha$.

D. Regressing $\log(|\Phi(\omega)|^2 + \sigma^2\omega^2)$ against $\omega$.

E. Regressing $\log(|\Phi(\omega)|^2) + \sigma^2\omega^2$ against $\omega$.


**Q16. In the context of Bayesian estimation, a uniform cost function $C(\theta, \hat{\theta})$ leads to the: [5 marks]**

A. Minimum Mean Square Error (MMSE) estimator.

B. Minimum Absolute Error (MAE) estimator.

C. Maximum A Posteriori (MAP) estimator.

D. Bayes risk estimator with quadratic loss.

E. Linear Minimum Mean Square Error (LMMSE) estimator.


**Q17. For a dataset with eigenvalues, what percentage of the total variance is explained by the first two principal components? [4 marks]**

A. 50%

B. 60%

C. 75%

D. 87.5%

E. 90%


**Q18. Given a noisy signal $x[n] = s[n; \theta] + w[n]$, where $w[n]$ is white Gaussian noise with known variance $\sigma^2$. The Cramer-Rao Lower Bound for the variance of any unbiased estimator of $\theta$ depends on: [4 marks]**

A. The variance of the noise $\sigma^2$ only.

B. The number of samples $N$ only.

C. The signal $s[n; \theta]$ and its dependence on $\theta$.

D. The mean of the noise.

E. None of the above.


**Q19. Which of the following statements about the Maximum Likelihood Estimator (MLE) is generally TRUE? [4 marks]**

A. The MLE is always unbiased.

B. The MLE always achieves the Cramer-Rao Lower Bound (CRLB) for any sample size.

C. The MLE is asymptotically consistent under certain regularity conditions.

D. The MLE is always the Minimum Variance Unbiased Estimator (MVUE).

E. The MLE always has a closed-form solution.


**Q20. Consider a linear set of equations represented in matrix form as $\mathbf{Ax} = \mathbf{b}$. Many problems in optimum signal processing, such as Wiener filtering and spectral estimation, require the analysis or solution of such systems where the matrix $\mathbf{A}$ can have special forms like: [3 marks]**

A. Only diagonal.

B. Only identity.

C. Toeplitz and Hankel.

D. Only symmetric.

E. Only orthogonal.

---

## Answers:


Q1. **A**

Q2. **C**

Q3. **C**

Q4. **D**

Q5. **D**

Q6. **E**

Q7. **C**

Q8. **B**

Q9. **B**

Q10. **C**

Q11. **B**

Q12. **B**

Q13. **B**

Q14. **C**

Q15. **C**

Q16. **C**

Q17. **D**

Q18. **C**

Q19. **C**

Q20. **C**
