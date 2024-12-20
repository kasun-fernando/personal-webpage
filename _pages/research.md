---
layout: postmod      
title: Research              
permalink: /Research/          
---
Broadly, the prime focus of my research is the interplay among probability theory, dynamical systems, and statistics. I investigate 
- <b>statistical properties of dynamical systems and Markov processes</b>,
- <b>inferential statistics in the context of dynamical systems</b>, and 
- <b>higher order asymptotics for limit theorems</b>   

using spectral theory and a combination of techniques from classical probability theory, stochastic analysis, statistics, and dynamical systems. 

Recently, I have started looking at      
- <b>applications of machine learning</b> in various settings. 

## Invariants and Universality
When studying physical systems with many degrees of freedom, it is impossible to keep track of microscopic behaviour based on physical laws. Imagine writing equations of motion for about $6 \times 10^{23}$ gas particles (about 1 mole) with inter-dependencies and solving that system of equations!

<img src="images/particles.png" height="250" align="center" hspace="250" vspace="20" title="A closed many particle system"/>
        
_Statistical Physics_ is the study of how these particle-particle interactions describe systems on a macroscopic scale. One can calculate _observable properties_ of a system either as averages over _phase trajectories_ (Ergodic Theory) or as averages over an _ensemble_ of systems, each of which is a copy of the system (Thermodynamics). In either case, **invariant measures** of systems play a crucial role, and showing their existence (and uniqueness) of them is a problem of importance. In fact, the **ergodic invariant measures** can be used to describe the statistics of a system entirely.  

Many systems have the extra layer of difficulty of the presence of interacting components that vary on disparate timescales. _Fast-slow partially hyperbolic systems_ (on the torus) investigated by [Jacopo De Simoi](https://www.math.toronto.edu/jacopods/) and [Carlngelo Liverani](https://www.mat.uniroma2.it/~liverani/) during the last decade are the simplest but theoretically non-trivial examples of this kind. I have an ongoing project with Jacopo De Simoi about the existence of **invariant measures** and their decay of correlations for fast-slow partially hyperbolic systems with positive centre Lyapunov exponents. 

Some systems are deterministic flows with discontinuities at random times at which they make random jumps. Such _Piece-wise Deterministic Markov Processes_ have numerous applications to science and engineering. I am interested in studying the existence of **invariant measures** in such systems. Drawing parallels with some of my previous work, [Pratima Hebbar](https://sites.google.com/view/pratimahebbar/home) and I expect that statistical properties of switching systems can be studied.

The Central Limit Theorem, a widely studied statistical property of systems, is an example of **universality** where, due to aggregation of microscopic information, at the macroscopic scale the averaged asymptotic behaviour of the system follows a bell curve independent of the underlying mechanism of information generation. **Universality** has deep consequences for applications in very applied fields like Biology and Economics as well as more theoretical fields like Number Theory. With [Tanja Schindler](https://sites.google.com/a/sns.it/tschindler/), we proved the Central Limit Theorem for the real part, imaginary part and the absolute value of the _Riemann-zeta function_ sampled over a class of dynamical systems on $\mathbb{R}$ with _heavy-tailed_ invariant measures. This result has potential number theoretic applications because it extends well-known results on _sampling the Lindel&ouml;f hypothesis_.

<img src="https://www.alanzucconi.com/wp-content/uploads/2015/05/galton-board.jpg" height="250" align="center" hspace="250" vspace="5" title="Galton board illustrating the Central Limit Theorem"/>

## Higher-order Asymptotics
Ergodic Theory asserts that most of the realizations of an ergodic system distribute according to an ergodic invariant measure. This fact has far-reaching consequences for practical applications that range from celestial mechanics to molecular dynamics and drug design. However, for these finite-time applications, exact **asymptotics** of universality (including probabilistic _limit laws_) describing systems are required. 

With [Dmitry Dolgopyat](https://www.math.umd.edu/~dolgop/), we extended the existing theory of _Edgeworth expansions_ (**higher-order asymptotics** of the Central Limit Theorem) for independent and identically distributed random variables to encompass _typical_ discrete random variables and provided precise descriptions of the failure of such expansions. The next natural question is whether it is possible to describe the error in the Central Limit Theorem when we pick a particular discrete random variable instead of describing typical errors. This is an ongoing project.

<img src="https://cdn-thumbs.imagevenue.com/2b/d9/fd/ME15BEQ2_t.png" height="225" align="center" hspace="50" vspace="20" title="A Sinai billiard trajectory"/>

As an extension of one of my previous projects with Carlngelo Liverani, [Fran&ccedil;oise P&egrave;ne](http://lmba.math.univ-brest.fr/perso/francoise.pene/) and I introduced a general theory of Edgeworth expansions and **higher-order asymptotics** in the Mixing Local Limit Theorems for _weakly dependent_ for (possibly unbounded) random variables arising as observations from mostly hyperbolic dynamical systems or Markov processes. The hyperbolic systems that we discuss like Sinai billiards and piece-wise expanding maps are natural models in many applications: billiard models in optics, acoustics, and classical mechanics, and expanding maps in random number generators, biological and medical models to name a few. There is an ongoing project with Fran&ccedil;oise P&egrave;ne on generalizing this theory further to include systems that exhibit _intermittent_ behaviour. 

With Pratima Hebbar, we look at the **higher-order asymptotics** of Large Deviations that describe the extremal behaviour of orbits. In particular, this theory leads to the exact description of the **asymptotics** of fundamental solutions of parabolic PDEs that model Branching Diffusion Processes.   

## Computing Precise Estimates
Having exact asymptotics of the statistical behaviour alone is insufficient for applications. The problem of finding more accurate and more **precise estimates** of parameters in systems appears naturally in many areas, including machine learning, physics, econometrics, and engineering. Moreover, one should be able to apply tools from statistics to limited dynamically generated data and obtain meaningful inferences.   

Even though there has been significant progress in the application of tools from inferential statistics to deterministic dynamics, _the bootstrap_, a versatile tool that achieves higher-order estimation accuracy than the normal approximation, had not been implemented until my work with [Nan Zou](https://sites.google.com/site/nzoupersonal/home). Our bootstrap enables one to evaluate the **randomness of estimates** of important dynamical quantities like the top _Lyapunov exponent_ and _metric entropy_ by constructing their 95% confidence intervals. Currently, we are working on coming up with **better estimates** for _spectral densities_ of dynamical systems. 

<img src="https://i.ibb.co/G3VqRDG/bootstrap.png" align="center" height="225" hspace="150" vspace="5" title="The boostrap for iid data"/>

In recent years, with the proliferation of machine learning research, modeling and prediction of real-world phenomena have progressed to the next level. The problem of **computing estimates** for an unknown probability distribution using sample data is crucial for applications; for example, **computing estimates** of invariant densities of dynamical systems. In machine learning, _Normalizing flow_ (NF) is a supervised learning procedure that determines the probability distribution of sample data by performing a maximum likelihood optimization. With [Sameera Ramasinghe](https://www.linkedin.com/in/sameeraramasinghe/), we introduced a framework to construct NFs that demonstrate higher robustness against initial errors. Even though NFs are susceptible to numerical instabilities, this is the first time robustness of NFs is investigated in the literature. 

<img src="https://cdn-thumbs.imagevenue.com/0f/c8/7d/ME15BEQ6_t.png" align="center" height="225" hspace="300" vspace="20" title="From top to bottom: ground truth, NF prediction and predicted density"/>

<!--
<img src="https://miro.medium.com/max/2648/1*SgeDm_wb2QNSF0CSYVmhuw.jpeg" align="center" height="225" hspace="250" vspace="20" title="The boostrap for iid data"/>
<img src="https://cdn-thumbs.imagevenue.com/5a/85/f4/ME15BEQ1_t.png" align="center" 
     height="225" hspace="100" vspace="20"/>  
<img src="https://cdn-thumbs.imagevenue.com/f5/31/c3/ME15BEQ7_t.png" align="left" height="120" hspace="20" vspace="50"/>
---
**Failure of Edegworth expansions in the discrete iid setting**           
<font size = "3">Collaborator: Dmitry Dolgopyat</font>
---
**Existence of Edgeworth expansions for weakly dependent random variables**          
<font size = "3">Collaborators: Carlangelo Liverani, Fran&ccedil;oise P&egrave;ne</font>
---
**Exact Large deviation asymptotics for weakly dependent random variables**           
<font size = "3">Collaborator: Pratima Hebbar</font>
---
**Adapting the bootstrap for dynamically generated data**        
<font size = "3">Collaborator: Nan Zou</font>
---
**Estimating entropy of continued fraction expansions**             
<font size = "3">Collaborators: Seulbee Lee, Stafano Marmi</font>
---
**Estimating data distirbutions via normalizing flows**            
<font size = "3">Collaborator: Sameera Ramasinghe</font>
---
**Statistics of Riemann-zeta function sampled over chaotic systems**            
<font size = "3">Collaborators: Tanja Schindler</font>
---
**Invariant measures for deterministic fast-slow systems**            
<font size = "3">Collaborator: Jacopo De Simoi</font>
---

 <details open> 
<summary><b>Error terms in the local and the central limit theorem for weakly dependent random variables</b></summary>     
  
(Dynamical Systems and Stochastic Processes)<br><br>In applications, the dynamically generated data available to us are always finite-time observations. Hence, one key problem is to control the error of approximation of asymptotic behaviour. When the observations are independent identically distributed (iid), a uniform asymptotic expansion called the Edgeworth Expansion is used to describe the error of normal approximation in the Central Limit Theorem (CLT). Since sequences of experimental observations are never iid, we introduced a general theory of Edgeworth expansions for weakly dependent (possibly unbounded) random variables.<br><br>
As a direct application of this theory, we obtain error estimates of the CLTs for a large class of hyperbolic dynamical systems and Markov chains. The hyperbolic systems that we discuss like Sinai billiards and piecewise expanding maps are natural models in many applications like billiard models in optics, acoustics and classical mechanics, and expanding maps in random number generators, biological and medical models to name a few.<br><br>
There are many unsolved problems in this direction. There are interesting examples of non-Gaussian stable laws in dynamical systems. Is it possible to describe the error terms in other stable laws? Earlier, we were able to obtain exact limit theorems for random matrix product -->
