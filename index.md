This is an introductory course in the theory of statistics, inference, and machine learning, with an emphasis on theoretical understanding & practical exercises. The course will combine, and alternate, between mathematical theoretical foundations and practical computational aspects in python.

**Professor:** Florent Krzakala

**Teaching Assistants:** Davide Ghio, Ortiz Jimenez Guillermo,  Dimitriadis Nikolaos, Luca Pesce

### Content
The topics will be chosen from the following basic outline:

- Statistical inference: Estimators, Bias-Variance, Consistency, Efficiency, Maximum likelihood, Fisher Information.
- Bayesian inference, Priors, A posteriori estimation, Expectation-Minimization.
- Supervised learning : Linear Regression, Ridge, Lasso, Sparse problems, high-dimensional Data, Kernel methods, Boosting, Bagging. K-NN, Support Vector Machines, logistic regression, Optimal Margin Classifier
- Statistical learning theory: VC Bounds and Uniform convergence, Implicit regularisation, Double-descent
- Unsupervised learning : Mixture Models, PCA & Kernel PCA, k-means
- Deep learning: multi-layer nets, convnets, auto-encoder, Gradient-descent algorithms
- Basics of Generative models & Reinforcement learning


For students: [Moodle Link](https://moodle.epfl.ch/course/view.php?id=16783) & videos of the course on [TubeSwitch](https://tube.switch.ch/channels/P21dFjFlzG)

Discussions: You can discuss and ask questions on the course. We use slack, which is a great platform for this, here is the invitation to join the forum [forum on slack](https://join.slack.com/t/lecturee411-2021/shared_invite/zt-wctokqj5-Gsk8mp790JmMjDakedJArA) which is valid until the end of october.


### Lecture List:

Short video on [introduction and course information](https://tube.switch.ch/videos/OtMpZ1csbC)

* **21/9: (i) All of probability** [video part-a](https://tube.switch.ch/videos/O5cTqs2NT7),[video part-b](https://tube.switch.ch/videos/9GNFirFjRw) [video part-c](https://tube.switch.ch/videos/hg4GoRppXj); [lecture notes](https://www.overleaf.com/1222519813bdjmdjmjjpbx)
 
This first class is a recap on probability theory that will serve us well in this class. A good reference, and an absolutly recommended reading, for this lecture is Chap. 1-5 in [All of statistics](http://egrcc.github.io/docs/math/all-of-statistics.pdf) by Wasserman. 

* **28/9: (ii) All of statistics** [video part-a](https://tube.switch.ch/videos/B3r56XLIvj),[video part-b](https://tube.switch.ch/videos/BpUsMuh7p3); [lecture notes](https://www.overleaf.com/2917916729ycfdqnyjhbzp)

This second class is focused on the theory of [maximum likelihood estimation](https://en.wikipedia.org/wiki/Maximum_likelihood_estimation). There are many good references on the topic, including for instance chap. 9 in [All of statistics](http://egrcc.github.io/docs/math/all-of-statistics.pdf), or for the Bayesian point of view, [MacKay](http://www.inference.org.uk/itprnn/book.pdf) chap 2 and 3.

* **5/10: (iii) Supervised learning and KNN** [video part-a](https://tube.switch.ch/videos/y0T46zQ8Uz),[video part-b](https://tube.switch.ch/videos/WPxmNebck8). [video part-c](https://tube.switch.ch/videos/kiCjZ4fytL); [lecture notes](https://www.overleaf.com/7116425623ttfcnbvcncmt)

A good read on supervised statistical learning is chapter 2 in [An Introduction to Statistical Learning](https://www.statlearning.com/) by James, Witten, Hastie and Tibshirani. They also discuss in detail K-neareast neighbors.

* **12/10: (iv) Gradient descents**  [video part-a](https://tube.switch.ch/videos/ymhYGS5FBp),[video part-b](https://tube.switch.ch/videos/Uty6vSGfg2); [lecture notes](https://www.overleaf.com/7338629352qxyrtrjtsvnc) 

Gradient descent is the workhorse of all modern machine learning methods. There are many ressourse on gradient descent, from [pedagogical ones](https://ruder.io/optimizing-gradient-descent/) to [technical ones](https://gowerrobert.github.io/pdf/M2_statistique_optimisation/grad_conv.pdf). Proximal operators are very powerful and are well described in this set of lectures [Tibshirani1](https://www.stat.cmu.edu/~ryantibs/convexopt/lectures/grad-descent.pdf), [Tibshirani2](https://www.stat.cmu.edu/~ryantibs/convexopt/lectures/subgrad.pdf),[Tibshirani3](https://www.stat.cmu.edu/~ryantibs/convexopt/lectures/prox-grad.pdf).

* **19/10 and 26/10 (v) Linear methods** [video part-a](https://tube.switch.ch/videos/Uty6vSGfg2),[video part-b](https://tube.switch.ch/videos/GKTjPNui5i);[video part-c](https://tube.switch.ch/videos/qBtMeqUMOc),[video part-d](https://tube.switch.ch/videos/zO13qoBH8o); [video part-e](https://tube.switch.ch/videos/MzXSD93VPv)  [lecture notes](https://www.overleaf.com/project/616057accbec194c682a91d9) 

Linear methods are the simplest among all parametric methods, but are still extremly useful! A good discussion of OLD, Ridge and LASSO can be found in Chap 6, section 2 in [An Introduction to Statistical Learning](https://www.statlearning.com/). Another good reference is [this one](https://www.whitman.edu/documents/Academics/Mathematics/DeVine.pdf). Linear classification methods are also at the center of machine learning technics, and are discussed in details in chapter 4 of [An Introduction to Statistical Learning](https://www.statlearning.com/).

* **2/11 (vi) Features maps and Kernels**  [video part-a](https://tube.switch.ch/videos/MzXSD93VPv), [video part-b](https://tube.switch.ch/videos/Ds7TOUPDdf) , [video part-c](https://tube.switch.ch/videos/jI8tvckQ6v)  [lecture notes](https://www.overleaf.com/6449339267zqgbjzscxrtx) 

Richers features maps that linear ones, and Kernel methods, are one of the most important aspect of supervised machine learning. Michael Jordan's [notes on kernel](https://people.eecs.berkeley.edu/~jordan/kernels/0521813972c02_p25-46.pdf) are a good reference. The review from [Hofmann,  Scholkopf and Smola](https://arxiv.org/pdf/math/0701907.pdf) is also very complete. Scikit-learn has a [detailed and very efficient implementation](https://scikit-learn.org/stable/modules/kernel_approximation.html).

* **9/11 and 16/11 (vii) Neural networks & deep learning**  [video part-a](https://tube.switch.ch/videos/h3MKqCh2FF)[lecture notes](https://www.overleaf.com/4275199117yvpktswnmhqy) 

Over the last decades, neural networks have made quite an impact, one might even say that they are at the origin of a revolution in machine learning and artificial intelligence.  This simple website allows you to get intuition on how they actually work for simple dataset: [Tensorflow playground](https://playground.tensorflow.org). The [universal approximation theorem](https://en.wikipedia.org/wiki/Universal_approximation_theorem) is discussed in many references (see for instance [here](https://ai.stackexchange.com/questions/13317/where-can-i-find-the-proof-of-the-universal-approximation-theorem/13319)). Despite Backpropagation being a rather trivial application of the chain rule of derivatives from Newton and Liebnitz [notes](https://cs.stanford.edu/~quocle/tutorial1.pdf), it is the cornerstone of learning neural network.


### Lab classes:

* Before the classes: [A short intro to python](TP0/Intro%20to%20Python.ipynb) and to vizualization and making plots with [Matplotlib](TP0/Visualization.ipynb)).

* Week 1 (22/9): Introduction to statistics with python [EXO1](https://github.com/IdePHICS/FundamentalLearningEPFL2021/blob/main/TP1/FoIL_ex1_public.ipynb);[Solution](https://github.com/IdePHICS/FundamentalLearningEPFL2021/blob/main/TP1/solution/FoIL_ex1_solved.ipynb)

* Week 2 (29/9): Estimation with maximum likelihood [EXO2](https://github.com/IdePHICS/FundamentalLearningEPFL2021/blob/main/TP2/FoIL_ex2_public.ipynb);[Solution](https://github.com/IdePHICS/FundamentalLearningEPFL2021/blob/main/TP2/solution/FoIL_ex2_solved.ipynb)

* Week 3 (6/10): Supervised learning with kNN [EXO3](https://github.com/IdePHICS/FundamentalLearningEPFL2021/blob/main/TP3/TP3_FoIL_public.ipynb);[Solution](https://github.com/IdePHICS/FundamentalLearningEPFL2021/blob/main/TP3/Solution/FoIL_TP3_solved.ipynb)

* Week 4(13/10): Gradient descents [EXO4](https://github.com/IdePHICS/FundamentalLearningEPFL2021/blob/main/TP4/FoIL_ex4_public.ipynb);[Solution](https://github.com/IdePHICS/FundamentalLearningEPFL2021/blob/main/TP4/solution/FoIL_ex4_solved.ipynb)

* Week 5(20/10): Linear methods [EXO5](https://github.com/IdePHICS/FundamentalLearningEPFL2021/blob/main/TP5/FoIL_ex5_public.ipynb);[Solution](https://github.com/IdePHICS/FundamentalLearningEPFL2021/blob/main/TP5/solution/FoIL_ex5_solved.ipynb)

* Week 6(27/10): Classification with linear methods [EXO6](https://github.com/IdePHICS/FundamentalLearningEPFL2021/blob/main/TP6/FoIL_TP6.ipynb);[Solution](https://github.com/IdePHICS/FundamentalLearningEPFL2021/blob/main/TP6/Solution/FoIL_TP6_solved.ipynb)

* Week 7(3/11): Kernel methods[EX07](https://github.com/IdePHICS/FundamentalLearningEPFL2021/tree/main/TP7);[Solution](https://github.com/IdePHICS/FundamentalLearningEPFL2021/blob/main/TP7/Solution/FoIL_TP7_solved.ipynb)

* Week 8(10/11): Backpropagation [EX08](https://github.com/IdePHICS/FundamentalLearningEPFL2021/tree/main/TP8);[Solution](https://github.com/IdePHICS/FundamentalLearningEPFL2021/blob/main/TP8/FoIL_TP8_sol.ipynb)

* Week 9(19/11): Pytorch and NN [EX09](https://github.com/IdePHICS/FundamentalLearningEPFL2021/blob/main/TP9/Foil_TP9.ipynb)

### Homeworks: 

* HW1 (Due october 19, on moodle) [Maximum likelihood and Probability](https://github.com/IdePHICS/FundamentalLearningEPFL2021/blob/main/HW/Homework1_EE411.pdf)

* HW2 (Due November 23, on moodle) [Linear models, and Bias-Variance trade-of](https://github.com/IdePHICS/FundamentalLearningEPFL2021/blob/main/HW/Homework2_EE411.pdf)

### Projects: TBD

### A list of references

* A good book for probability and statistics, accessible to students, is Larry A. Wasserman 's <a href="https://www.ic.unicamp.br/~wainer/cursos/1s2013/ml/livro.pdf">All of Statistics</a>. 
* An accessible introduction to statistical learning is given in <a href="https://web.stanford.edu/~hastie/ElemStatLearn/">Elements of Statistical Learning </a> by Jerome H. Friedman, Robert Tibshirani, and Trevor Hastie. 
* Another great reference is <a href="https://www.amazon.com/Machine-Learning-Probabilistic-Perspective-Computation/dp/0262018020">Machine Learning:A Probabilistic Perspective<a/> by Kevin P. Murphy. MacKay's <a href="https://www.amazon.com/Machine-Learning-Probabilistic-Perspective-Computation/dp/0262018020">Machine Learning:A Probabilistic Perspective <a href="https://www.inference.org.uk/itprnn/book.pdf">Information Theory, Inference and Learning Algorithms</a> is also a very useful ressource.
* Modern Deep learning is well covered in this recent book:
<a href="http://d2l.ai/">Dive into Deep Learning<a/> by A. Zhang, Z. Lipton, M. Li, A.J. Smola. 
* Un recent, et excellent, livre de reference en Francais: <a href="https://www.amazon.fr/Introduction-Machine-Learning-Chloé-Agathe-Azencott/dp/2100780808">Introduction au Machine Learning </a> par Chloé-Agathe Azencott. 
  
  
### Course Policies

* Homeworks: There will be three homework assignments, each worth 15% of the final grade. 
* Scribing: Each students is expected to provide scribing for at least one lecture. Scribing will also count for 15% of the final grade.
  Student must write their name on the list of scribes and claim lectures on [the scribing list](https://docs.google.com/document/d/13N8_0I5Waz566e3IlQPDKKMZNXvGN5vQYaYAh0Dl6kk/edit?usp=sharing) together with ready-to-se overleaf links (see latex section below).   
* Projects: Project will account for 40% of the final grade. You may work in teams of 2-4 people. There will be a limited number of project to choose from, and you will not be able to chose other projects. Each team member's contribution should be highlighted. You should use the project as an opportunity to "learn by doing".
* Exam: There will be no written exam.
* Videos: videos of the lecture will be posted on the [SwichTube channel](https://tube.switch.ch/channels/P21dFjFlzG) of the course.
* Academic Integrity: Collaboration among students is allowed, and encouraged, but is intended to help you learn. In other words, you may work on solving assignments together, but you should always write up your solutions separately. You should always implement code alone as well. Whenever collaboration happens, it should be reported by all parties involved in the relevant homework problem.
 
### FAQ
* How can I use python on my computer? 
 
Two good options to run python online are EPFL Noto & Google Colab. [Noto](https://www.epfl.ch/education/educational-initiatives/cede/digitaltools/jupyter-notebooks-for-education/) is EPFL’s JupyterLab centralized platform. It allows teachers and students to use notebooks without having to install python on their computer. [Google colab](https://research.google.com/colaboratory/) provides a similar solution, with the added avantage that it gives access to GPUs. For instnace, you can open the jupyter notebook corresponding to the first exercice by a) opening google colab in your browser) b) selecting github, and  c) writing the path `https://github.com/IdePHICS/FundamentalLearningEPFL2021/blob/main/TP1/FoIL_ex1_public.ipynb`

* I do not know any python! What should I do? 

[TP0](https://github.com/IdePHICS/FundamentalLearningEPFL2021/tree/main/TP0) provides a short introduction. If you need more and really need to study python, here is a a good [Python and NumPy Tutorial](https://github.com/kuleshov/cs228-material/blob/master/tutorials/python/cs228-python-tutorial.ipynb).
 
* What is overleaf? 
 
 If you cannot compile LaTeX on your own computer (and even if you can, this is often a good strategy anyway), EPFL is providing Overleaf Professional accounts for all students: [Overleaf EPFL](https://www.overleaf.com/edu/epfl#overview) . With Overleaf you can write and compile LaTeX directly from your web browser. 
