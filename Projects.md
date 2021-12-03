# Year-end projects 

The final project for this course consist in a reproducibility challenge. You are asked to reproduce one or two plots from a published paper in machine learning.  Your task is to 1) Attempt Reproduce numerically the results presented in the paper in their setting, or a slightly different one. 2) explain why these results are important and put them into context. 3) Review critically your attempt at reproduction, and discuss critically the paper in view of your own results. and 4) propose other directions based on your understanding.  If the authors of the paper provided code, you may use it, but then you are expecte to go beyond just running their code, and instead apply it to new examples. If you cannot reproduce the results because dataset are, e.g. too big, try a simpler smaller dataset. Be creative, and try to find your own opinion on the work.  You may work in teams of 2-5 people.


## List of projects and papers

[1] **Bad Global Minima Exist and SGD Can Reach Them**, *Shengchao Liu, Dimitris Papailiopoulos, Dimitris Achlioptas*. [click here](https://arxiv.org/abs/1906.02613)  Minimas of ehe empricial risk found by gradient descent method in deep learning are usually associated with good generalization properties. In this paper, the authors showed that there exists other minimas with really *terrible* generalization property, and show how to actually find them in pratice. Suggested reproduced images are Fig. 1, but any plot in the paper is interesting.

[2] **Reconciling modern machine learning practice and the bias-variance trade-off** *Mikhail Belkin, Daniel Hsu, Siyuan Ma, Soumik Mandal*. [click here](https://arxiv.org/abs/1812.11118) This work showed that the generalization in function of the number of parameters can sometimes looked very different from the classical presentation, and describe what they call the "double descent" phenomenon, that demonstrated that over-aprametrization does not necessarly hurt generlization in machine learning. Many plots could be repriduces, such as Fig [2], Fig. [4] and many more.

[3] **Understanding deep learning requires rethinking generalization** *Chiyuan Zhang, Samy Bengio, Moritz Hardt, Benjamin Recht, Oriol Vinyals*. [click here](https://arxiv.org/abs/1611.035308) This paper was critical in showing that the standard wisdom reguarding generalization was completly wrong, by just training neural nets with random label.  All Figure are interested and should/could be reproduced, though you may find that it could be better to use simpler dataset (aka, CIFAR, Fashion MNIST, instead of imagenet!)


## Notes:

*  Project will account for 40% of the final grade. You may work in teams of 2-5 people. There will be a limited number of project to choose from, and you will not be able to chose other projects. Each team member's contribution should be highlighted. You should use the project as an opportunity to "learn by doing".

* *Written Report:*  You will write a maximum 4 page PDF report on your findings, using LaTeX. We also welcome a jointed jupyter notebook.   Please make sure to take into account the following consideration.
a) Reproducibility: Your classmates should be able to reproduce your results based on your report only. Describe what preprocessing is required, what hyper-parameter values you selected and why, and clearly describe the overall pipeline you used. b) Code :Try to make your code as readable as possible. c) Clarity: Explain clearly what you are trying to do. Explain why do you it. The reader should understand your work WITHOUT having to read the original paper. d) Critical thinking: If you do not reproduce similar results as in the original paper,  be critical of your approach, of (perhaps) of the onbe in the paper. 

* A latex template that could be use for your report is given [here](https://github.com/epfml/ML_course/tree/master/projects/project1/latex-example-paper) 



* We are definitly aware that not all tasks have the same difficulty. We will take the difficulty of the question into account when grading, so none of the choices will have any disadvantage for you.
