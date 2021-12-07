# Year-end projects 

The final project for this course will consist in a **Reproducibility Challenge**. That is, you will have to *critically reproduce the results from a published machine learning paper*. To be precise, we expect you to reproduce a couple of plots or tables from an established paper. Overall, the tasks for your final project assignment are:

1. Attempt to reproduce numerically the results presented in the paper using the same settings described in this work, or slightly different ones. 
2. Explain why these results are important and put them into context. 
3. Review critically your attempt at reproduction, and discuss critically the paper in view of your own results. 
4. Propose new research directions based on your understanding.

## Project guidelines

*  This project will account for 40% of the final grade. There will be a limited number of project to choose from, and you will not be able to choose other projects. You should use the project as an opportunity to "learn by doing".

* You may work in **teams of 2-5 people**. Each team member's contribution should be highlighted. 

* **Written Report:**  You will write a **maximum 4 pages** PDF report on your findings using LaTeX, but we will also welcome the inclusion of an additional Jupyter notebook where you illustrate how you reproduced the main results. In general, please make sure to take into account the following consideration: 
1. *Reproducibility*: Your classmates should be able to reproduce your results based on your report only. Describe what pre-processing is required, what hyper-parameter values you selected and why, and clearly describe the overall pipeline you used. 
2. *Code*: Try to make your code as readable as possible. Instructions on how to run your code should also be provided. 
3. *Clarity*: Explain clearly what you are trying to do. Explain why do you it. The reader should understand your work *WITHOUT* having to read the original paper. 
4. *Critical thinking*: If you do not reproduce similar results as in the original paper, be critical of your approach, and (perhaps) of the one in the paper. 

* A LaTeX template that could be use for your report is given [here](https://github.com/epfml/ML_course/tree/master/projects/project1/latex-example-paper) 

* If the authors of the paper provided code, you may use it, but note that you will, then, be expected to go beyond just running their code, and instead apply it to new examples or settings. 

* In some cases, you will find that you cannot reproduce some results due to computational constraints e.g. used datasets are too big. In those cases, feel free to try reproducing the results using a simpler or smaller dataset. 

* We expect you to be creative and critical of your work and the work of others. You should try to form your own opinion of the reproduced work.

* We are definitely aware that not all tasks have the same difficulty. We will take the difficulty of the question into account when grading, so none of the choices will have any disadvantage for you.

## List of projects and papers

[1] **Bad global minima exist and SGD can reach them**, *Shengchao Liu, Dimitris Papailiopoulos, Dimitris Achlioptas*. [click here](https://arxiv.org/abs/1906.02613)  Minima of the empirical risk found by the gradient descent method in deep learning are usually associated with good generalization properties. In this paper, however, the authors showed that this is not always the case, as there exist other minima with really *terrible* generalization properties. They also provide a simple method to find those *bad minima* in practice. We suggest to reproduce Fig. 1, but reproducing any other plot in the paper will be equally interesting.

[2] **Reconciling modern machine learning practice and the bias-variance trade-off** *Mikhail Belkin, Daniel Hsu, Siyuan Ma, Soumik Mandal*. [click here](https://arxiv.org/abs/1812.11118) This work showed that the generalization performance as a function of the number of parameters of a machine learning method can sometimes looked very different from its classical presentation. In particular, the authors describe what they call the "double descent" phenomenon, demonstrating that over-parameterization does not necessarily hurt generalization in machine learning. Many plots can be easily reproduced. We suggest Fig. 2 and Fig. 4, but many more are equally interesting.

[3] **Understanding deep learning requires rethinking generalization** *Chiyuan Zhang, Samy Bengio, Moritz Hardt, Benjamin Recht, Oriol Vinyals*. [click here](https://arxiv.org/abs/1611.035308) This paper was critical in showing that the standard wisdom regarding generalization was completely wrong at the time: By training neural networks with random labels, the authors debunked many classical beliefs about generalization, and sparked a new fruitful generation of works which critically studied generalization in deep learning.  All figures from this paper are interesting and should/could be reproduced. However, you may find that it could be better to use simpler dataset, e.g., CIFAR or Fashion MNIST, rather than Imagenet!

[4] **AugMix: A simple data processing method to improve robustness and uncertainty** *Dan Hendrycks, Norman Mu, Ekin D. Cubuk, Barret Zoph, Justin Gilmer, Balaji Lakshminarayanan*. [click here](https://arxiv.org/abs/1912.02781) This paper proposes a new *lightweight* data augmentation scheme that can boost the robustness of a neural network to common corruptions. This is today one of the most popular data augmentation schemes used in the literature, and it is used as standard baseline in many studies. The results on CIFARx-C are of great interest. Table 1 and Figure 12 can be easily reproduced, although probably using different architectures than the ones provided in this work. A critical ablation study of the different parameters of AugMix could also be very interesting.

[5] **Towards learning convolutions from scratch** *Behnam Neyshabur*. [click here](https://arxiv.org/abs/2007.13657) This paper argues that radically changing the type of optimizer can imbue a simple fully connected neural network with the right inductive biases to classify complex images. Table 2 and Fig. 3 and Fig. 4 are of great interest.

