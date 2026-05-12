# Mathematics for Machine Learning &mdash; Companion Series

A twelve-deck companion to the textbook *Mathematics for Machine Learning* by
**Marc Peter Deisenroth, A. Aldo Faisal &amp; Cheng Soon Ong** (Cambridge
University Press, 2020). Each deck is a single-page interactive presentation
served on GitHub Pages &mdash; KaTeX-rendered mathematics, dark-theme canvas
illustrations, at least one in-browser interactive widget per chapter, and a
written line-by-line walk through the most important results of the book.

The companion is independent and unofficial. Authors retain all rights to the
original text; this series links to the freely available PDF at
[mml-book.github.io](https://mml-book.github.io/) and re-presents the material
visually for self-study.

**Live index:** https://brendanjameslynskey.github.io/MML_Hub/

## Presentations in this series

### Part I &mdash; Mathematical Foundations

| # | Title | Status | Description |
|---|-------|--------|-------------|
| 01 | [Introduction and Motivation](https://brendanjameslynskey.github.io/MML_01_Introduction/) | live | The four pillars (regression, dim. reduction, density estimation, classification) and the four mathematical foundations (linear algebra, analytic geometry, vector calculus, probability). Interactive map of the book. |
| 02 | [Linear Algebra](https://brendanjameslynskey.github.io/MML_02_Linear_Algebra/) | live | Systems of linear equations, matrices, Gaussian elimination, vector spaces, basis &amp; rank, linear &amp; affine maps. Interactive row-reduction stepper. |
| 03 | [Analytic Geometry](https://brendanjameslynskey.github.io/MML_03_Analytic_Geometry/) | live | Norms, inner products, lengths &amp; distances, angles, orthonormal bases, orthogonal complements, orthogonal projections, rotations. Interactive projection demo. |
| 04 | [Matrix Decompositions](https://brendanjameslynskey.github.io/MML_04_Matrix_Decompositions/) | live | Determinant &amp; trace, eigendecomposition, Cholesky, the singular value decomposition, low-rank approximation, the matrix-decomposition taxonomy. Interactive SVD image compressor. |
| 05 | [Vector Calculus](https://brendanjameslynskey.github.io/MML_05_Vector_Calculus/) | live | Partial derivatives, the gradient, Jacobian, gradient of matrix expressions, the chain rule, backpropagation, automatic differentiation, multivariate Taylor series. Interactive gradient-descent visualiser. |
| 06 | [Probability and Distributions](https://brendanjameslynskey.github.io/MML_06_Probability_and_Distributions/) | live | Sample spaces, sum &amp; product rules, Bayes' theorem, summary statistics, the Gaussian (with marginalisation and conditioning), conjugacy, the exponential family, change of variables. Interactive Bayes' theorem and Gaussian explorer. |
| 07 | [Continuous Optimisation](https://brendanjameslynskey.github.io/MML_07_Continuous_Optimisation/) | live | Gradient descent (with momentum), constrained optimisation &amp; Lagrange multipliers, convex sets &amp; functions, linear &amp; quadratic programming, duality. Interactive descent paths on a 2D loss surface. |

### Part II &mdash; Central Machine Learning Problems

| # | Title | Status | Description |
|---|-------|--------|-------------|
| 08 | [When Models Meet Data](https://brendanjameslynskey.github.io/MML_08_When_Models_Meet_Data/) | live | Data &amp; features, empirical risk minimisation, the bias-variance trade-off, regularisation, cross-validation, MLE vs MAP, directed graphical models. Interactive bias-variance and learning-curve demo. |
| 09 | [Linear Regression](https://brendanjameslynskey.github.io/MML_09_Linear_Regression/) | live | Least squares as orthogonal projection, ridge / MAP regularisation, Bayesian linear regression with posterior predictive distribution, feature maps. Interactive regression playground with conjugate updates. |
| 10 | [Dimensionality Reduction with PCA](https://brendanjameslynskey.github.io/MML_10_PCA/) | live | Variance-maximisation view, reconstruction-error view, eigenvectors of the covariance, low-rank approximation, PCA in high dimensions, probabilistic PCA, latent-variable perspective. Interactive 2D &rarr; 1D PCA visualiser. |
| 11 | [Density Estimation with GMMs](https://brendanjameslynskey.github.io/MML_11_Gaussian_Mixture_Models/) | live | Mixture model likelihood, the EM algorithm derived from the latent-variable view, responsibilities, the lower bound, soft vs hard clustering, model-order selection. Interactive 2D EM animator. |
| 12 | [Classification with SVMs](https://brendanjameslynskey.github.io/MML_12_Support_Vector_Machines/) | live | Separating hyperplanes &amp; margins, the primal hard- and soft-margin SVM, the Lagrange dual, support vectors, the kernel trick (linear, polynomial, RBF), numerical solution. Interactive 2D kernel SVM demo. |

## Pedagogical arc

The book is famously split down the middle. **Part I** is *mathematics for*
machine learning &mdash; the linear algebra, geometry, calculus, probability
and optimisation that ML uses every day, taught with the rigour of a maths
text but explicitly motivated by ML use-cases. **Part II** then revisits four
canonical ML problems (regression, PCA, GMM, SVM) and shows that each of them
is built directly out of the tools assembled in Part I.

This companion follows the same arc. Decks 01&ndash;07 develop the
mathematical machinery. Decks 08&ndash;12 use it: every result in linear
regression is a projection from deck 03, every step of EM uses the
multivariate Gaussian from deck 06, and the SVM dual uses the Lagrange
multipliers from deck 07. By the end you can read the algorithms in their
linear-algebraic and probabilistic form, not as recipes.

## How to read each deck

- Open the live presentation linked in the table above &mdash; everything
  renders in the browser, no install required.
- Scroll. Each deck is a vertical sequence of slides with a slide number in
  the corner; the table of contents on slide 00 links to each one.
- The interactive widgets are designed to be *touched*. Drag the sliders,
  click the canvases, change the seeds. The numbers update live.
- Keep the [book PDF](https://mml-book.github.io/book/mml-book.pdf) open
  alongside &mdash; chapter and section numbers in each deck correspond to
  the book, so you can dive deeper into any proof.

## Credits and references

The presentations are a companion to, not a replacement for, the original
book. All credit for the underlying exposition belongs to:

> Deisenroth, M. P., Faisal, A. A. &amp; Ong, C. S. (2020).
> *Mathematics for Machine Learning.* Cambridge University Press.
> [mml-book.github.io](https://mml-book.github.io/)

The authors generously make the full PDF freely available for download.
Please cite the book if you use these decks for teaching.

This companion uses:
- [KaTeX](https://katex.org/) for math rendering
- HTML Canvas API for all interactive visualisations
- No build step, no JavaScript framework, no external data

Single-page HTML; clone the chapter repo and open `index.html` to run offline.

## Where this fits

- Part of the [Mathematics](https://github.com/BrendanJamesLynskey/Mathematics)
  hub &mdash; a collection of interactive presentation series in pure and
  applied mathematics.
- Companion to the [Linear Algebra for AI / ML](https://github.com/BrendanJamesLynskey/LLM_Hub_Linear_Algebra)
  series on the [LLMs](https://github.com/BrendanJamesLynskey/LLMs) hub
  &mdash; which lands the same maths *inside* a transformer rather than
  inside the four canonical ML problems.

## License

The presentations themselves are released for educational use.
The book's exposition, figures and worked examples remain copyright of
Deisenroth, Faisal &amp; Ong &mdash; this series links to the freely
distributed PDF rather than reproducing the text.
