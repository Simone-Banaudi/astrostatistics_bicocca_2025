# Astrostatistics and Machine Learning

[Davide Gerosa](https://davidegerosa.com/)  - davide.gerosa@unimib.it  
University of Milano-Bicocca, 2025.




[![Binder](https://mybinder.org/badge_logo.svg)](https://mybinder.org/v2/gh/dgerosa/astrostatistics_bicocca_2025/HEAD)
&emsp; [![](https://custom-icon-badges.herokuapp.com/badge/launch-unimib%20virtual%20machine-orange.svg?logo=container&logoColor=white)](https://vdi-libaas.si.unimib.it/)


## Aims

The use of statistics is ubiquitous in astronomy and astrophysics. Modern advances are made possible by the application of increasingly sophisticated tools, often dubbed "data mining", "machine learning", and "artificial intelligence". This class provides an introduction to (some of) these statistical techniques in a very practical fashion, pairing formal derivations with hands-on computational applications. Although examples will be taken almost exclusively from the realm of astronomy, this class is appropriate for all Physics students interested in machine learning.


## Lectures

1. **[Introduction I](lectures/L01_introduction.ipynb)**. Data mining and machine learning. My research interests. Python setup. Version control with git. *
2. **[Probability and Statistics I](lectures/L02_probability.ipynb)**. Probability. Bayes' theorem. Random variables. *
3. **[Probability and Statistics II](lectures/L03_probability.ipynb)**. Monte Carlo integration. Descriptive statistics. Common distributions. *
4. **[Probability and Statistics III](lectures/L04_probability.ipynb)**. Central limit theorem. Multivariate pdfs. Correlation coefficients. Sampling from arbitrary pdfs. *
5. **[Frequentist Statistical Inference: I](lectures/L05_frequentist.ipynb)**. Frequentist vs Bayesian inference. Maximum likelihood estimation. Omoscedastic Gaussian data, Heteroscedastic Gaussian data, non Gaussian data. *
6. **[Frequentist Statistical Inference: II](lectures/L06_frequentist.ipynb)**. Maximum likelihood fit. Role of outliers. Goodness of fit. Model comparison. Gaussian mixtures. Boostrap and jackknife. *
7. **[Frequentist Statistical Inference: III](lectures/L07_frequentist.ipynb)**. Hypothesis testing. Comparing distributions, KS test. Histograms. Kernel density estimators. *
8. **[Bayesian Statistical Inference: I](lectures/L08_bayesian.ipynb)**. The Bayesian approach to statistics. Prior distributions. Credible regions. Parameter estimation examples (coin flip). Marginalization.
9. **[Bayesian Statistical Inference: II](lectures/L09_bayesian.ipynb)**. Parameter estimation examples (Gaussian data, background). Model comparison: odds ratio. Approximate model comparison.
10. **[Bayesian Statistical Inference: III](lectures/L10_bayesian.ipynb)**. Monte Carlo methods. Markov chains. Burn-in. Metropolis-Hastings algorithm.  *
11. **[Bayesian Statistical Inference: IV](lectures/L11_bayesian.ipynb)**. MCMC diagnostics. Traceplots. Autocorrelation length. Samplers in practice: emcee and PyMC3. Gibbs sampling. Conjugate priors.  *
12. **[Bayesian Statistical Inference: V](lectures/L12_bayesian.ipynb)**. Evidence evaluation. Model selection. Savage-Dickey density ratio. Nested sampling. Samplers in practice: dynesty. * 
13. **[Introduction II](lectures/L13_introduction.ipynb)**. Data mining and machine learning. Supervised and unsupervised learning. Overview of scikit-learn. Examples. *
14. **[Clustering](lectures/L14_clustering.ipynb)**. K-fold cross-validation. Unsupervised clustering. K-Means Clustering. Mean-shift Clustering. Correlation functions. *
15. **[Dimensional Reduction I](lectures/L15_dimensionality.ipynb)**. Curse of dimensionality. Principal component analysis. Missing data. Non-negative matrix factorization. Independent component analysis. *
16. **[Dimensional Reduction II - Density estimation](lectures/L16_dimensionality.ipynb)**. Non-linear dimensional reduction. Locally linear embedding. Isometric mapping. t-SNE. Recap of density estimation. KDE. Nearest-Neighbor. Gaussian Mixtures. *Pills of modern research*
17. **[Regression I](lectures/L17_regression.ipynb)**. What is regression? Linear regression. Polynomial regression. Basis function regression. Kernel regression. Over/underfitting. Cross-validation. Learning curves. *
18. **[Regression II](lectures/L18_regression.ipynb)**. Regularization. Ridge. LASSO. Non-linear regression. Gaussian process regression. Total least squares. *
19. **[Classification I](lectures/L19_classification.ipynb)**. Generative vs discriminative classification. Receiver Operating Characteristic (ROC) curve. Naive Bayes. Gaussian naive Bayes. Linear and quadratic discriminant analysis. GMM Bayes classification. K-nearest neighbor classifier. *
20. **[Classification II](lectures/L20_classification.ipynb)**. Logistic regression. Support vector machines. Decision trees. Bagging. Random forests. Boosting. *
21. **[Deep learning I](lectures/L21_deeplearning.ipynb)**. Loss functions. Gradient descent, learning rate. Adaptive boosting. Neural networks. Backpropagation. Layers, neurons, activation functions, regularization schemes. *
22. **[Deep learning II](lectures/L22_deeplearning.ipynb)**. TensorFlow, keras, and pytorch. Convolutional neural networks. Autoencoders. Generative adversarial networks. *

##### Additional lectures not covered in class

23. **[Time series analysis I](lectures/extra/L23_timeseries.ipynb)**. Detect a variability. Fourier analysis. Temporally localized signals. Periodic signals.  Lomb-Scargle periodogram. Multiband strategies. *
24. **[Time series analysis II](lectures/extra/L24_timeseries.ipynb)**. Stochastic processes. Autoregressive models. Moving averages. Power-spectral density. Autocorrelation. White/red/pink noise. Unevenly sampled data.

\* = Time to get your hands dirty!

## :exclamation: Important

Data mining and machine learning are computational subjects. One does not understand how to treat scientific data by reading equations on the blackboard: you will need to get your hands dirty (and this is the fun part!). **Students are required to come to classes with a laptop** or any device where you can code on (larger than a smartphone I would say...). Each class will pair theoretical explanations to hands-on exercises and demonstrations. These are the key content of the course, so please engage with them as much a possible. 

At various points during the lectures you fill find some **"Time to get your hands dirty"** statements. That means you got to start coding! 

## Textbook and Resources

The **main textbook** we will be using is:

["Statistics, Data Mining, and Machine Learning in Astronomy"](https://press.princeton.edu/books/hardcover/9780691198309/statistics-data-mining-and-machine-learning-in-astronomy), Željko, Andrew, Jacob, and Gray. Princeton University Press, 2012.

It's a wonderful book that I keep on referring to in my research. The library has a few copies; you can also download a digital version from the Bicocca library website. What I really like about that book is that they provide the code behind each single figure: [astroml.org/book\_figures](https://www.astroml.org/book_figures/). The best way to approach these topics is to study the introduction on the book, then grab the code and try to play with it.  Make sure you get the updated edition of the book (that's the one with a black cover, not orange) because all the examples have been updated to python 3.   

There are many **other good resources** in astrostatistics, here is a partial list. Some of them are free.  

- ["Statistical Data Analysis"](https://global.oup.com/academic/product/statistical-data-analysis-9780198501558?cc=fr&lang=en&), Cowan. Oxford Science Publications, 1997.
- ["Data Analysis: A Bayesian Tutorial"](https://global.oup.com/academic/product/data-analysis-9780198568322?cc=fr&lang=en&), Sivia and Skilling. Oxford Science Publications, 2006.
- ["Bayesian Data Analysis",](http://www.stat.columbia.edu/~gelman/book/) Gelman, Carlin, Stern, Dunson, Vehtari, and Rubin. Chapman & Hall, 2013. Free!
- ["Python Data Science Handbook",](https://jakevdp.github.io/PythonDataScienceHandbook/) VanderPlas. O'Reilly Media, 2016. Free!
- ["Practical Statistics for Astronomers"](https://www.cambridge.org/core/books/practical-statistics-for-astronomers/CEB9D5F985F062BAD67E7219B96A4CD6), Wall and Jenkins. Cambridge University Press, 2003.
- ["Bayesian Logical Data Analysis for the Physical Sciences",](https://www.cambridge.org/core/books/bayesian-logical-data-analysis-for-the-physical-sciences/09E9A95DAE275F5B005676C71B542598) Gregory. Cambridge University Press, 2005.
- ["Modern Statistical Methods For Astronomy" Feigelson and Babu.](https://www.cambridge.org/core/books/modern-statistical-methods-for-astronomy/941AE392A553D68DD7B02491BB66DDEC) Cambridge University Press, 2012.
- ["Information theory, inference, and learning algorithms"](https://www.inference.org.uk/mackay/itila/book.html) MacKay. Cambridge University Press, 2003. Free!  
- “Data analysis recipes". These free are chapters of a book that is not yet finished by Hogg et al.
    - ["Choosing the binning for a histogram"](https://arxiv.org/abs/0807.4820) [arXiv:0807.4820]
    - ["Fitting a model to data](https://arxiv.org/abs/1008.4686) [arXiv:1008.4686]
    - ["Probability calculus for inference"](https://arxiv.org/abs/1205.4446) [arXiv:1205.4446]
    - ["Using Markov Chain Monte Carlo"](https://arxiv.org/abs/1710.06068) [arXiv:1710.06068]
    - ["Products of multivariate Gaussians in Bayesian inferences"](https://arxiv.org/abs/2005.14199) [arXiv:2005.14199]
 -  ["Practical Guidance for Bayesian Inference in Astronomy"](https://arxiv.org/abs/2302.04703), Eadie et al., 2023.
 - ["Hands-On Machine Learning with Scikit-Learn, Keras, and TensorFlow"](https://www.oreilly.com/library/view/hands-on-machine-learning/9781492032632/), Geron, O'Reilly Media, 2019.
 - ["Machine Learning for Physics and Astronomy"](https://press.princeton.edu/books/paperback/9780691206417/machine-learning-for-physics-and-astronomy), Acquaviva, Princeton University Press, 2023.
 - ["A review of Unsupervised Learning in Astronomy"](https://arxiv.org/abs/2406.17316), S. Fotopoulou et al., 2024.

We will make heavy usage of the python programming language. If you need to refresh your **python skills**, here are some catch-up resources and online tutorials. A strong python programming background is essential in modern astrophysics!   

- ["Scientific Computing with Python"](https://dgerosa.github.io/scientificcomputing_bicocca), D. Gerosa. This is a class I teach for the PhD School here at Milano-Bicocca.
- ["Lectures on scientific computing with Python"](https://github.com/jrjohansson/scientific-python-lectures), R. Johansson et al.  
- [Python Programming for Scientists"](https://astrofrog.github.io/py4sci/), T. Robitaille et al.
- ["Learning Scientific Programming with Python"](https://www.cambridge.org/core/books/learning-scientific-programming-with-python/3D264483BC7B380A3059B3861C661237), Hill, Cambridge University Press, 2020. Supporting code: [scipython.com](https://scipython.com/).
- ["Effective Computation in Physics"](https://www.oreilly.com/library/view/effective-computation-in/9781491901564/), A. Scopatz, K. D. Huff, O'Reilly Media, 2015.
- ["Python for non pythonians"](https://www.amazon.com/Python-non-Pythonians-Over-Programming-Languages/dp/888548686X), Rubera, Grossetti, 2019.

## 2025 Class schedule

The class covers 6 credits = 42 hours = 21 lectures of 2 hours each. Our weekly timeslots are Monday 8.30am-10.30am (sorry) and Thursday 10.30am-12.30pm. Note a few extra lectures on different days/times as well as a few weeks where we're going to skip classes).

Our schedule is as follows. [Here is a public calendar](https://calendar.google.com/calendar/embed?src=7b3eb78f345682c12c065855a0e49c6b21d2f1db72b244bf752dd534a47c6066%40group.calendar.google.com&ctz=Europe%2FRome) with the dates below, which you can import into your calendar software.

1. **Mar 3, 8.30.** Room U2-05.
- Mar 6, holiday
2. **Mar 10, 8.30.** Room U2-05.
3. **Mar 13, 10.30.** Room U2-05.
4. **Mar 17, 8.30.** Room U2-06.
5. **Mar 20, 10.30.** Room U2-05.
- Mar 24, Davide is away for research.
- Mar 27, Davide is away for research.
6. **Mar 31, 8.30.** Room U2-06.
7. **Apr 3, 10.30.** Room U2-01.
8. **Apr 7, 8.30.** Room U1-10.
9. **Apr 8, 10.30.** Room U2-05 (extra lecture).
10. **Apr 10, 10.30.**  Room U2-07.
11. **Apr 14, 8.30.** Room U2-06.
- Apr 17, holiday.
- Apr 21, holiday.
12. **Apr 24, 10.30.** Room U1-04.
13. **Apr 28, 8.30.** Room U1-10.
- May 1, holiday.
14. **May 5, 8.30.** Room U1-10.
- May 8, Davide is away for research.
15. **May 12, 8.30.** Room U1-10.
16. **May 15, 10.30.** Room U2-05.
17. **May 19, 8.30.** Room U1-10.
18. **May 22, 10.30.** Room U2-05.
19. **May 26, 8.30.** Room U1-10.
20. **May 27, 8.30.** Room U2-05 (extra lecture).
- May 29, Davide is away for research.
21. **May 30, 8.30.** Room U2-05 (extra lecture).
- Jun 2, holiday
- Jun 5, 10.30. Davide is away for research
22. Jun 9, 8.30. Room U1-10 (backup slot).
23. Jun 10, 10.30. Room U2-05 (backup slot) 
24. Jun 12, 10.30. Room U2-05 (backup slot)

## Exams

Exam guidelines are available [here](exams.md). Please read that carefully.

## Past editions

- Current: [dgerosa.github.io/astrostatistics_bicocca](https://dgerosa.github.io/astrostatistics_bicocca)
- 2024: [github.com/dgerosa/astrostatistics_bicocca_2024](https://github.com/dgerosa/astrostatistics_bicocca_2024)
- 2023: [github.com/dgerosa/astrostatistics_bicocca_2023](https://github.com/dgerosa/astrostatistics_bicocca_2023)
- 2022: [github.com/dgerosa/astrostatistics_bicocca_2022](https://github.com/dgerosa/astrostatistics_bicocca_2022)

## A huge thanks to:

This class draws heavily from many others that came before me. Credit goes to:

- Stephen Taylor (Vanderbilt University): [github.com/VanderbiltAstronomy/astr_8070_s21](https://github.com/VanderbiltAstronomy/astr_8070_s21).
- Gordon Richards (Drexel University): [github.com/gtrichards/PHYS_440_540](https://github.com/gtrichards/PHYS_440_540).
- Jake Vanderplas (University of Washington): [github.com/jakevdp/ESAC-stats-2014](https://github.com/jakevdp/ESAC-stats-2014).
- Zeljko Ivezic (University of Washington): [github.com/uw-astr-302-w18/astr-302-w18](https://github.com/uw-astr-302-w18/astr-302-w18).
- Andy Connolly (University of Washington): [cadence.lsst.org/introAstroML/](http://cadence.lsst.org/introAstroML).
- Karen Leighly (University of Oklahoma): [seminar.ouml.org/](http://seminar.ouml.org).
- Adam Miller (Northwestern University): [github.com/LSSTC-DSFP/LSSTC-DSFP-Sessions/](https://github.com/LSSTC-DSFP/LSSTC-DSFP-Sessions).
- Jo Bovy (University of Toronto): [astro.utoronto.ca/~bovy/teaching.html](http://astro.utoronto.ca/~bovy/teaching.html).
- Nicolas Audebert (IGN Paris): [github.com/nshaud/ml_for_astro](https://github.com/nshaud/ml_for_astro)
- Thomas Wiecki (PyMC Labs): [twiecki.github.io/blog/2015/11/10/mcmc-sampling](http://twiecki.github.io/blog/2015/11/10/mcmc-sampling).
- Aurelienne Geron (freelancer): [github.com/ageron/handson-ml2](https://github.com/ageron/handson-ml2).


## Careful...

<p align="center">
  <img src="https://imgs.xkcd.com/comics/data_trap.png" />
</p>

Credit: [xkcd 2582](https://xkcd.com/2582/)


