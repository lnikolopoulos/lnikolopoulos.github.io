---
title: "Research"
layout: textlay
excerpt: "Research"
sitemap: false
permalink: /research/
---

# Research


The Quantum Dynamics Computation Unit (QDCU) undertakes theoretical studies of the dynamics (the motions, and energy and momentum exchanges) of quantum systems in the atomic and molecular level governed mainly by quantum mechanics. Specifically, the QDCU activities include research in the theory and calculation of strong laser field-atomic dynamics. The focus is on the ultrashort dynamics (on the time scale of atto- and-femtosecond)  since this is also the order of the response of the atomic and molecular systems. To this we develop ab-initio structure and quantum dynamic methods based on the configuration interaction (CI) approach combined with the direct propagation of the TDSE.

A major viepoint of the group is to investigate atomic dynamics problems of direct experimental interest. So our work so far  pursuits leading edge research with the least approximations possible. This makes the theory and implementation much harder compared to simplified approaches but of a lot more validity. The starting point is always the time-dependent Schrodinger Equation in the presence of the external radiation pulse, \(E(t) \). The information about the system's atomic structure is contained in its Hamiltonian, \( H_a \). Within QM the dynamics is described by the system's quantum state, \\(H_a(t)\\) . All these elements put together in the position representation we have:

\\[
\imath \frac{\partial}{\partial t}\psi(\textbf{X},t) 
= \left( H_a + V(t) \right) \psi(\textbf{X},t)
\\]

where \\(\textbf{X}=(\textbf{x}_1,\textbf{x}_2,\cdots \textbf{x}_n)\\)represents the dynamic degrees for all electrons in the system. 
This is the central Equation-of-Motion for quantum dynamics to be solved. According QM, determination of $|\psi(\textbf{X},t)\rangle $ provides the answers to 'all' questions that make sense.

Questions of interest include: (i) What is the rate of ionization of the system (ii) What are the energies of the ejected electrons? (iii) what is their radial and angular distribution patterns? (iv) What is the final state of the ionized system? (v) Is there any radiation generated following the interaction of the system with the laser?


![]({{ site.url }}{{ site.baseurl }}/images/respic/layers_real.jpg){: style="width: 200px; float: left; border: 5px"}



![]({{ site.url }}{{ site.baseurl }}/images/respic/layers_fft.jpg){: style="width: 300px; float: right; border: 10px"}

A main goal is to use modern technology to build in-house new codes needed to process data in a parallel mode. A non-trivial task for medium-size institutes with limited resources. Along these line of thinking and practice we invest some time developing a TDSE code capable to run on CPU and GPU platforms using the freely available openCL language. The results of this project resulted to few publications which supported the Thesis by [Cathal O'Broin](http://doras.dcu.ie/20806/) and the 1st prize from the Computational Group of the Institute of Physics/UK for the best PhD Thesis in UK/Ireland for [2016](https://www.iop.org/activity/groups/subject/comp/prize/page_40691.html#gref).