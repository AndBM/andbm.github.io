---
permalink: /
title: "About me"
#excerpt: "About me"
author_profile: true
redirect_from:
  - /about/
  - /about.html
---

I am a theoretical quantum physicist currently working with the [Novo Nordisk Foundation Quantum Computing Programme (NQCP)][nqcp]{:target="_blank"}, an ambitious quantum technology development project at the Niels Bohr Institue, to develop its role at the heart of the thriving Danish quantum technology eco-system.

I have a PhD in physics from the universities of St Andrews and Luxembourg, where I developed an analytical theory of the hybridization between a superconductor and a quantum Hall edge state which emphasized the critical role of the Meissner effect in the successful experimental observation of the phenomenon. Such systems are predicted to host anyonic quasiparticles, with a potential application in topological quantum computing. This work was done under supervision of [Thomas Schmidt][thomas]{:target="_blank"} and [Bernd Braunecker][bernd]{:target="_blank"}.

I received my B.Sc. with distinction and M.Sc., both in physics, from Aarhus University in Denmark.

I have been affiliated with the St Andrews [Centre for Energy Ethics][energy]{:target="_blank"}, which among other things has resulted in [blog posts][blogposts]{:target="_blank"} about the physical aspects of energy production. My other interests include programming and playing music, particularly the piano.

## Scientific publications


### Functional matrix product state simulation of continuous variable quantum circuits
Continuous variable quantum circuits are exciting in part because for such circuits there exists certain encodings with inherent robustness against errors. Continuous variable states are, however, harder to numerically simulate than their discrete variable counterparts due to the fact that classical computers are inherently discrete, and thus some discretisation of the continuum is required. In this work we combine a problem-agnostic discretisation of position space with a functional matrix product state formalism to simulate continuous variable circuits in a way that draws on the benefits of tensor networks. We demonstrate that for broad, shallow circuits of non-Gaussian states, our method is capable of sub-exponential scaling of simulation times, something other state-of-the-art methods like Strawberry Fields fails to achieve.

My colleague Frederik K. Marqversen has further managed to use this method to simulate GKP qubit circuits with finite squeezing at a previously unfeasible scale, establishing fundamental bounds on the amount of squeezing required to achieve quantum advantage for such circuits.

- Andreas B. Michelsen, Frederik K. Marqversen, Michael Kastoryano, _Functional matrix product state simulation of continuous variable quantum circuits_, [arXiv](https://arxiv.org/abs/2504.05860){:target="_blank"}
- Frederik K. Marqversen, Andreas B. Michelsen, Janus H. Wesenberg, Nikolaj T. Zinner, _Impact of finite squeezing on near-term quantum computations using GKP qubits_, [arXiv](https://arxiv.org/abs/2507.15955){:target="_blank"}



### Supercurrent-enabled Andreev reflection in a chiral quantum Hall edge state
Superconductivity and the quantum Hall effect are both examples of a macroscopic number of electrons exhibiting highly correlated behavior with very distinct transport signatures. When interfaced with a superconductor, the quantum Hall edge experiences induced superconducting pairing due to Andreev reflection, a process where electrons reflect off the superconductor as holes. It is expected that this type of system will be a good platform for hosting exotic quasiparticles with
significant impact on quantum computing.

Recent experimental observations of an s-wave superconductor inducing pairing into chiral edge states with parallel spins have led to the question: How can s-wave pairing between electrons with opposite spin and momenta be induced into a seemingly incompatible edge state where electrons have parallel spin and similar momenta? We develop a theoretical model showing that one must take spin-orbit coupling and screening current at the superconductor surface into account to find
pairing induced by electron tunneling between the two systems, providing critical understanding of the system as a platform for quasiparticles.

The full Hamiltonian of the system gives rise to an effective p-wave pairing Hamiltonian of the edge state, which elucidates the dependence of the pairing on the aforementioned surface phenomena. This Hamiltonian also allows analytical predictions for the transport phenomena used as signatures in experimental work, particularly the departures from the well-known zero longitudinal resistance of the quantum Hall effect. The model and its predictions will be useful in future experimental design, and are expected to be generalizable to the fractional quantum Hall effect.

- Andreas B. Michelsen, Patrik Recher, Bernd Braunecker, Thomas L. Schmidt, _Supercurrent-enabled Andreev reflection in a chiral quantum Hall edge state_, [Phys. Rev. Research 5, 013066](https://link.aps.org/doi/10.1103/PhysRevResearch.5.013066){:target="_blank"} / [arXiv](https://arxiv.org/abs/2203.13384){:target="_blank"}


### Current correlations of Cooper-pair tunneling into a quantum Hall system
The concept of a topologically protected quantum state, which can retain its quantum features under conditions where other systems would collapse, is immensely interesting for both theory and technology. A promising proposed host for such states is the hybrid system of a superconductor and a quantum Hall material. Previous research has shown that if these two are interface through a point contact, the Pauli principle suppresses the electron current between the two through the so-called Pauli blockade. In this paper we derive the current noise over the contact for 1D quantum Hall liquids with several filling fractions, as well as with and without electron-electron interactions.

- Andreas B. Michelsen, Thomas L. Schmidt, Edvin G. Idrisov, _Current correlations of Cooper-pair tunneling into a quantum Hall system_, [PRB 102, 125402](https://journals.aps.org/prb/abstract/10.1103/PhysRevB.102.125402){:target="_blank"} / [arXiv](https://arxiv.org/abs/2004.10279){:target="_blank"}


### Ion-induced interactions in a Tomonaga-Luttinger liquid
Current technology allows us to isolate a small number of atoms in an effectively one-dimensional trap, which is an excellent playground to explore quantum mechanics. But since the atoms are electrically neutral, they can be hard to control. Ions, on the other hand, are much easier to control. In our paper we demonstrate that in a mix of atoms and ions, tuning the ion states allows for a degree of control over the atom-atom interactions.

- Andreas B. Michelsen, Manuel Valiente, Nikolaj Zinner and Antonio Negretti, _Ion-induced interactions in a Tomonaga-Luttinger liquid_, [PRB 100, 205427](https://journals.aps.org/prb/abstract/10.1103/PhysRevB.100.205427){:target="_blank"} / [arXiv](https://arxiv.org/abs/1907.07090){:target="_blank"}


## Contact
You can reach me at [andreas@abmichelsen.com][mail].

[thomas]:https://tmqs.uni.lu
[bernd]:https://www.st-andrews.ac.uk/~bhb/
[mail]:mailto:andreas@abmichelsen.com
[energy]:https://energyethics.st-andrews.ac.uk/
[blogposts]:https://abmichelsen.com/outreach/energy-ethics/
[kvantify]:https://www.kvantify.dk/
[nqcp]:https://nqcp.ku.dk/
