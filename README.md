## Optimal-Transport Research Library

A curated list of optimal transport for Bayesian Inference publications, re-organized from Arxiv (mostly). 

<strong>Last Update: Augst, 19th, 2021</strong>.	 

 If you have any suggestions,  please email to zhuxy3@shanghaitech.edu.cn
 # Gradient Flows
## Papers
| Title                                                                    | Team/Authors              | Venue      | Years     | Notes              |
|---|---|---|---|---|
| [Stein Variational Gradient Descent as Gradient Flow](https://arxiv.org/pdf/1704.07520.pdf)      | <font color=red>Qiang Liu</font> (University of Texas at Austin)           |   NIPS  |   2017 |   |
| [Understanding and Accelerating Particle-Based Variational Inference](https://arxiv.org/pdf/1807.01750.pdf),[[slides]](https://icml.cc/media/icml-2019/Slides/5103.pdf)     | Chang Liu (Tsinghua), Ruiyi Zhang (Duke)|   ICML  |   2019 |   |
| [A Unified Particle-Optimization Framework for Scalable Bayesian Sampling](https://arxiv.org/pdf/1805.11659.pdf)      | Changyou Cben (Buffalo), Ruiyi Zhang (Duck)           |   Uncertainty in AI |   2018 |   |
| [Riemannian Stein Variational Gradient Descent for Bayesian Inference](https://arxiv.org/pdf/1711.11216.pdf)      | Chang Liu (Tsinghua)           |   AAAI  |   2018 |  --- |
| [Fisher information regularization schemes for Wasserstein gradient flows](https://arxiv.org/pdf/1907.02152.pdf)      | Wuchen Li (University of South Carolina) |   JCP  |   2019 |  --- |
|[Interacting Langevin Diffusions: Gradient Structure And Ensemble Kalman Sampler](https://arxiv.org/pdf/1903.08866.pdf)| Alfredo, Wuchen Li| SIAM journal on applied dynamical system| 2019 | ---|
| [SVGD as a kernelized Wasserstein gradient flow of the chi-squared divergence](https://arxiv.org/pdf/2006.02509.pdf)      | Sinho Chewi (MIT)  |   NIPS  |   2021 |  --- |
| [ENTROPY DISSIPATION SEMI-DISCRETIZATION SCHEMES FOR FOKKER-PLANCK EQUATIONS](https://arxiv.org/pdf/1608.02628.pdf)      | SHUI-NEE CHOW, LUCA DIECI, WUCHEN LI  |   Journal of Dynamics and Differential Equations  |   2019 |  --- |
|[Wasserstein variational gradient descent: From semi-discrete optimal transport to ensemble variational inference](https://arxiv.org/pdf/1811.02827.pdf)|  Luca Ambrogioni  |   NIPS  |   2018 |  --- |
|[A note on parametric Bayesian inference via gradient flows](https://services.math.duke.edu/~jliu/research/pdf/Gao_Liu_AMSA2020.pdf)| Yuan Gao (Duke) | Annals of Mathematical Sciences and Applications| 2020 | review: summarizing several recent developments for efficient sampling methods for parameters based on Bayesian inference ---|
## Textbooks
[Gradient Flows in Metric Spaces and in the Space of Probability Measures](http://www2.stat.duke.edu/~sayan/ambrosio.pdf)

[{Euclidean, Metric, and Wasserstein} Gradient Flows:an overview](https://arxiv.org/pdf/1609.03890.pdf)  A brief review
 
# Optimal Transport 
## Papers
| Title                                                                    | Team/Authors              | Venue      | Years     | Notes               |
|---|---|---|---|---|
| [Sinkhorn Distances: Lightspeed Computation of Optimal Transport](https://papers.nips.cc/paper/2013/file/af21d0c97db2e27e13572cbf59eb343d-Paper.pdf)      | Marco Cuturi          |   NIPS  |   2013 |  Efficient algorithm solving Wasserstein distence |
| [Near-linear time approximation algorithms for optimal transport via Sinkhorn iteration](https://arxiv.org/pdf/1705.09634.pdf)      | Philippe Rigollet (MIT)         |   NIPS  |   2017 |  |
|[Wasserstein GAN](https://arxiv.org/pdf/1701.07875.pdf)| M Arjovsky | arXiv  reprint | 2017|  |
| [Wasserstein Variational Inference](https://arxiv.org/pdf/1805.11284.pdf)      | Luca Ambrogioni|   NIPS  |   2018 |  |
|[Learning Generative Models with Sinkhorn Divergences](https://arxiv.org/pdf/1706.00292.pdf)| Aude Genevay |International Conference on Artificial Intelligence and Statistics|2018 | |
| [Neural Architecture Search with Bayesian Optimisation and Optimal Transport](https://arxiv.org/pdf/1802.07191.pdf)      |  Eric P Xing (Carnegie Mellon University)           |   arXiv preprint  |   2018 |   |
| [Functional optimal transport: map estimation and domain adaptation for functional data](https://arxiv.org/pdf/2102.03895.pdf)  |  Ding Zhao(Carnegie Mellon University)         |   arXiv preprint  |   2021 |  --- |
| [Hilbert Sinkhorn Divergence for Optimal Transport](https://openaccess.thecvf.com/content/CVPR2021/papers/Li_Hilbert_Sinkhorn_Divergence_for_Optimal_Transport_CVPR_2021_paper.pdf)      | Guangdong Xu (University of Technology Sydney) |   CVPR  |   2021 |  --- |
| [Unnormalized optimal transport](https://pdf.sciencedirectassets.com/272570/1-s2.0-S0021999119X00212/1-s2.0-S002199911930645X/main.pdf?X-Amz-Security-Token=IQoJb3JpZ2luX2VjEGcaCXVzLWVhc3QtMSJIMEYCIQCD3R3RJCD9j0GOpsZeP1hsl9jlNtDCiZOWx%2F1x2znW9wIhAIfODAeF0b2t%2FbLZBFnJfLbX03qnAAdks7uBzPM79km3KoMECJD%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FwEQBBoMMDU5MDAzNTQ2ODY1IgxOpffR6Xhz8QiGCgcq1wOyDyUtQClrqzn5aVm9r%2Fmsx2k00Bo6nRwhb4403ZkF9ZV9kCsSXRTSmxwlM3xDpKMXlP02sOxmB6ydlF8nRGHsaACXlCspAigOiPfhCHXMP5Mhu%2FLPBQx%2B6Dx0mEAlt3WiieIROJopyioN8MglDbXEbOBmHPf6mAGZz0JZW2YT7PJRSFfhrpFDM1QyQI6v0KlEVyTWLDqnw7JUw9ct%2FlOKLfkMpvlPaRy%2F21a856IwGABqUQSeIKL4Coz71dR9u7FQqr7uSikHsvU8ZVY8avok1PtEj4kpOzofcRbD2vwo7cN7x%2Bhhkfa54qqhTHbZ383xAPDOgVf7kIAx6veAA4xWYvPMO8hvjvflxMh9KSI7%2FR%2FqQoFy0WGlQVW%2B0vLjYbNNIK%2F2OXkBJxGvR6sIDhDHCdzz2n%2FLxcWtvNNU%2F6%2BFW898OFAbTlD1KMalAFkJmnMef7iJ%2F0mgjbVg4M6O1GFo6zJBpJngz2baZth2HQKM8jj8wPlTuTdThXRLdXfLeDhcpCRjolbhVQ8Wb3JU7B21jZEwNKHyNFUd7K5pr8HVlv9wKU36WXeuiDzgNVuJeiKcSMvE%2FD6Qy2Vl8IZG1DrHzbrjFPxK44EBLTpvwEMaFSyIXa37jp8wrsL0iAY6pAFOscSMS21yYTN5s5kA5hDECxU7GAP4TfyL76XNUSiZ%2FCxRSk6Pm8o3w%2FBM64mwTLbjSOn65OEZvNO5iK%2FeSc%2FUI9i9dokk72ZxC2NhCrZ%2F9jqBn15IDxGipUF8GwUdM5z8ZIgyHlAOQS2V%2B72K%2F4t59eYNt6m9ZOhE3xbzX6X8TZ3pYDZBC8BybE456RR1Qg%2FJBx%2FX6RqSrMn5CrCWjG%2Bf7uCCFQ%3D%3D&X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Date=20210818T155545Z&X-Amz-SignedHeaders=host&X-Amz-Expires=300&X-Amz-Credential=ASIAQ3PHCVTYYFSZZN42%2F20210818%2Fus-east-1%2Fs3%2Faws4_request&X-Amz-Signature=3732c5b596a867155b0c5be783d602fec847dd43316dca07804d2ff728114891&hash=e5ecff8d98a72ab1a5e17fc35ef91e714e3fe91897305cddbd46b0080f6615a8&host=68042c943591013ac2b2430a89b270f6af2c76d8dfd086a07176afe7c76c2c61&pii=S002199911930645X&tid=spdf-2cf1002d-4390-41cf-b962-9b62b6561ac5&sid=e32e255e7f38a84ec58aee59415a09cd94f2gxrqa&type=client)      | Sinho Chewi (MIT)  |   NIPS  |   2021 |  --- |
|[Wasserstein variational gradient descent: From semi-discrete optimal transport to ensemble variational inference](https://arxiv.org/pdf/1811.02827.pdf)|  WilfridGangbo, WuchenLi  |   JCP  |   2019 |  --- |
|[ComputatIions of Optimal Transport Distance with Fisher Information Regularization](https://arxiv.org/pdf/1704.04605.pdf)|  WUCHEN LI, PENGHANG YIN  |   JSC  |   2018 |  --- |
## Textbooks
[Optimal transport, old and new](https://cedricvillani.org/sites/dev/files/old_images/2012/08/preprint-1.pdf), Cedric Villani,2008 (classic)
[Computational Optimal Transport ](https://arxiv.org/pdf/1803.00567.pdf),Marco Cuturi,2018
[Optimal Transport for Applied Mathematicians](https://link.springer.com/content/pdf/10.1007/978-3-319-20828-2.pdf),

# Triangular transports
## Papers
| Title                                                                    | Team/Authors              | Venue      | Years     | Notes              |
|---|---|---|---|---|
|[From Knothe’s Rearrangement to Brenier’s Optimal Transport Map](https://arxiv.org/pdf/1205.1099.pdf)|  Nicolas Bonnotte |  SIAM J. Math. Anal  |   2012 |   |
| [Bayesian Inference with Optimal Maps](https://arxiv.org/pdf/1109.1516.pdf)      | Youssef Marzouk           |   JCP  |   2012 |   |
| [Variational inference via decomposable transports: algorithms for Bayesian filtering and smoothing](http://www.approximateinference.org/accepted/SpantiniEtAl2016.pdf)   |Youssef Marzouk|   NIPS  |   2016 |   |
| [A multiscale strategy for Bayesian inference using transport maps](https://arxiv.org/pdf/1507.07024.pdf)      | Youssef Marzouk           |   USIAM on UQ |   2016 |   |
| [Adaptive construction of measure transports for Bayesian inference](http://www.limitcycle.it/dabi/data/pub/2016/NIPS/2016%20%20Adaptive%20construction%20of%20measure%20transports%20for%20Bayesian%20inference.pdf)      | Youssef Marzouk           |   NIPS on Approximation Inference  |   2016 |  |
| [An introduction to sampling via measure transport](https://arxiv.org/pdf/1602.05023.pdf)      | Youssef Marzouk) |   Handbook on UQ  |   2016 |   |
|[Transport map accelerated Markov chain Monte Carlo](https://arxiv.org/pdf/1412.5492.pdf)| Youssef Marzouk|        JMLR     |2018 | |
| [Inference via Low-Dimensional Couplings](jmlr.org/papers/volume19/17-747/17-747.pdf)      | Youssef Marzouk  |   NIPS  |   2019 |   |
| [A transport-based multifidelity preconditioner for Markov chain Monte Carlo](https://arxiv.org/pdf/1808.09379.pdf)      | Youssef Marzouk  |  Advances in Computational Mathematics   |   2019 |   |
|[Greedy inference with structure-exploiting lazy maps](https://arxiv.org/pdf/1906.00031.pdf)|  Youssef Marzouk  |   NIPS  |   2020 |   |
|[Sparse approximation of triangular transports. Part I: the finite dimensional case](https://arxiv.org/pdf/2006.06994.pdf)| Youssef Marzouk | arXiv preprint | 2020 |  |
|[An adaptive transport framework for joint and conditional density estimation](https://arxiv.org/pdf/2009.10303.pdf)|Youssef Marzouk|arXiv preprint|2020 | |
|[Bayesian inference under model misspecification using transport-Lagrangian distances: an application to seismic inversion ](https://arxiv.org/pdf/2105.07027.pdf)|Youssef Marzouk|arXiv preprint|2021 | |
|[Sparse approximation of triangular transports. Part II: the infinite dimensional case](https://arxiv.org/pdf/2107.13422.pdf)|Youssef Marzouk|arXiv preprint|2021 | |
|[Adaptive deep density approximation for Fokker-Planck equations](https://arxiv.org/pdf/2103.11181.pdf)|  Kejun Tang  |  arXiv preprint  |   2021 |   |










