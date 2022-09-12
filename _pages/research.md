---
layout: postmod      
title: Research              
permalink: /Research/          
---
Broadly speaking, the prime focus of my research is <b>the interplay among probability theory, dynamical systems and statistics</b>. I investigate 
- <b>statistical properties of dynamical systems and Markov processes</b>,
- <b>inferential statistics in the context of dynamical systems</b>, and 
- <b>higher order asymptotics for limit theorems</b>   
 
using spectral theory and a combination of techniques from classical probability theory, stochastic analysis, statistics and dynamical systems. Recently, I have started looking at      
- <b>applications of machine learning</b> to problems related to research topics mentioned before. 

Apart from dynamicists and probabilists, I have formed research connections with machine learning researchers and statisticians, and I am actively searching for interdisciplinary research opportunities.

Below, I briefly discuss some of my research interests thematically. The resulting publications can be found [here](https://kasun-fernando.github.io/personal-webpage/Publications/).

## Invariants 
When studying physical systems with many degrees of freedom, it is impossible to keep track of the microscopic behaviour based on physical laws. Try writing equations of motion for about $10^{23}$ (about 1 mole of) gas particles and solving that system of equations!

<img src="https://cosmolearning.org/images_dir/courses/618/profile-thumbnail-w300.jpg" height="225" align="center" hspace="250" vspace="20"/>
        
The study of _Statistical Physics_ is the study of how these particle-particle interactions describe systems on a macroscopic scale. One can calculate _observable properties_ of a system either as averages over _phase trajectories_ (Ergodic Theory), or as averages over an _ensemble_ of systems, each of which is a copy of the system (Thermodynamics). In either case, **invariant measures** of systems play a crucial role and showing the existence (and uniqueness) of them is a problem of importance. In fact, the **ergodic invariant measures** can be used to describe the statistics of a system completely. 

Many systems have the extra layer of difficulty of the presence of interacting components that vary on disparate timescales. _Fast-slow partially hyperbolic systems_ (on the torus) investigated by [Jacopo De Simoi](https://www.math.toronto.edu/jacopods/) and [Caralngelo Liverani](https://www.mat.uniroma2.it/~liverani/) during the last decade are the simplest but theoretically non-tirival examples of this kind. I have an on-going project (with Jacopo De Simoi) about the existence of **invariant measures** and their decay of correlations for fast-slow partially hyperbolic systems with positive centre Lyapunov exponents. 

Some systems are deterministic flows with discontinuities at random times at which they make random jumps. Such _Piece-wise Deterministic Markov Processes_ have a wide range of applications to science and engineering. I am interested in studying the existence of **invariant measures** in such systems. Drawing parallels with some of my previous work, [Pratima Hebbar](https://sites.google.com/view/pratimahebbar/home) and I expect that statistical properties of switching systems can be studied.

## Asymptotics
Ergodic theory asserts that most of the realisations of an ergodic system distributes according to an ergodic invariant measure. This has far reaching consequences for practical applications that range from celestial mechanics to molecular dynamics and drug design. However, for these finite-time applications, **precise asymptotics** of probabilitistic limit laws describing the system are required. 

With [Dmitry Dolgopyat](https://www.math.umd.edu/~dolgop/), I extended the existing theory of _Edgeworth expansions_ (**higher order asymptotics** of the Central Limit Theorem) for iid random variables to include _typical_ discrete random variables and provided a precise description of the failure of such expansions. The next natural question is whether it is possible to describe the error in the CLT when we pick a particular discrete random variable instead of describing typical errors. This is an on-going project.

<img src="https://cdn-thumbs.imagevenue.com/2b/d9/fd/ME15BEQ2_t.png" height="225" align="center" hspace="50" vspace="20"/>

As an extension of one of my previous projects with Caralngelo Liverani, [Fran&ccedil;oise P&egrave;ne](http://lmba.math.univ-brest.fr/perso/francoise.pene/) and I introduced a general theory of Edgeworth expansions and **asymptotics** in the Mixing Local Limit Theorems for _weakly dependent_ (arising as observations from chaotic dynamical systems or Markov processes) possibly unbounded random variables. The hyperbolic systems that we discuss like Sinai billiards and piecewise expanding maps are natural models in many applications: billiard models in optics, acoustics and classical mechanics, and expanding maps in random number generators, biological and medical models to name a few. There is an on-going project with Fran&ccedil;oise P&egrave;ne on generalizing this theory further to include systems that exhibit _intermittent_ behaviour. 

With Pratima Hebbar, we look at the **asymptotics** of Large Deviations which describe the extremal behaviour of orbits. In particular, this theory leads to the precise description of the long-term behaviour of fundamental solutions parabolic PDEs that model Branching Diffusion Processes. 

## Estimates
Having a precise description of asymptotics of the statistical behaviour alone is not sufficient for applications. Finding **precise estimates** of parameters in systems arise naturally in many areas, including machine learning, physics, econometrics, and engineering. Moreover, one should be able to apply tools from statistics to limited dynamically generated data and obtain meaningful inferences. 

Even though there has been significant progress in applying tools from inferential statistics to deterministic dynamics, _the bootstrap_, a versatile tool that achieves higher-order estimation accuracy than the normal approximation, had not been implemented until my work with [Nan Zou](https://sites.google.com/site/nzoupersonal/home). Our bootstrap enables one to evaluate the randomness of **estimates** by constructing 95% confidence intervals for important dynamical quantities like the top _Lyapunov exponent_ and _metric entropy_. Currently, we are working on coming up with better **estimates** for _spectral densities_ in dynamical systems. 

<img src="https://miro.medium.com/max/2648/1*SgeDm_wb2QNSF0CSYVmhuw.jpeg" align="center" height="225" hspace="250" vspace="20"/>

In the recent years, with the proliferation of machine learning research, modeling and prediction of real world phenomena have progressed to the next level. The problem of computing **estimates** for an unknown probability distribution using sample data is crucial for applications; for example, in estimating invariant densities of dynamical systems. _Normalizing flows_ (NFs) in machine learning is a supervised learning procedure that determines the probability distribution of sample data by performing a maximum likelihood optimization. With Sameera Ramasinghe, I was able to introduce a framework to construct NFs that demonstrate higher robustness against initial errors. This is the first time the robustness of NFs is discussed in the literature even though NFs are susceptible of numerical instabilities in applications. 

<img src="https://cdn-thumbs.imagevenue.com/0f/c8/7d/ME15BEQ6_t.png" align="center" height="225" hspace="300" vspace="50"/>

<!--
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
