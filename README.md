# bessel_gumbel

This small project (for now the Mathematica notebook `tracy_widom_bessel_gumbel.nb`) numerically checks that the Fredholm determinant of a modified Bessel(0) kernel in exponential coordinates (arising as a gap probability in certain last passage percolation models) coincides with the *standard* Gumbel distribution (see here https://en.wikipedia.org/wiki/Gumbel_distribution for a definition).  

The Fredholm determinant (gap probability) in question is computed using the method of Bornemann (*On the Numerical Evaluation of Fredholm Determinants*, **arXiv:0804.2543 [math.NA]**, available at https://arxiv.org/abs/0804.2543). The modified Bessel kernel is a version of the random matrix theory hard-edge Bessel kernel of Tracy--Widom (*Level-Spacing Distributions and the Bessel Kernel*, **arXiv:hep-th/9304063**, available at https://arxiv.org/abs/hep-th/9304063).

This observation appeared first in a paper of Johansson (*On some special directed last-passage percolation models*, **arXiv:math/0703492**, available at https://arxiv.org/abs/math/0703492). It appears as a remark without proof, see the second equation below (1.8). **Note:** I believe that said equation should read (in LaTeX notation) $U_{-1/2} = ...$ as it is the right-hand side of equation (1.8) for which the Bessel parameter is equal to 0 (see the code). This was further elaborated in these two papers (one being an extended [FPSAC](http://fpsac.org) 2021 abstract of the other, longer version) by [Alessandra Occelli](https://sites.google.com/view/alessandraoccelli/home) and myself: 
  * *Muttalib--Borodin plane partitions and the hard edge of random matrix ensembles* (**arXiv:2011.07890 [math.CO]**, available at https://arxiv.org/abs/2011.07890) and  
  * *Discrete and continuous Muttalib--Borodin processes I: the hard edge* (**arXiv:2010.15529 [math.PR]**, available at https://arxiv.org/abs/2010.15529)  

as can be seen in e.g. Remark 4 of the first reference from the list.
