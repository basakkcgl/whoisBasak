---
layout: default
---


(September 2022) A question on **Bisimulation**:

I was somewhat familiar with the term bisimulation through my phil/logic background (as in Aczell's 'non-well founded set theory' as in [here](https://plato.stanford.edu/entries/nonwellfounded-set-theory/#3.1) and with some modal logic [as in here, slides](https://staff.fnwi.uva.nl/d.j.n.vaneijck2/courses/lai0506/LAI11.pdf)). I recently came across its definition in MDPs (based on the work of [Desharnais et al. 2002](https://ieeexplore.ieee.org/document/1029849), followed by original [Ferns paper 2004](https://www.aaai.org/Papers/AAAI/2004/AAAI04-124.pdf), [Google brain paper 2020](https://ojs.aaai.org/index.php/AAAI/article/view/6564)), and therefore its extension to RL ([learning bisimulation as state abstraction](https://openreview.net/pdf?id=-2FCwDKRREu), [bisimulation metric as optimal value function](https://citeseerx.ist.psu.edu/viewdoc/download?doi=10.1.1.645.306&rep=rep1&type=pdf)). 

As you might remember, I was working on the term degeneracy - defined as functional redundancy in RL systems where different states map to same/similar actions and different actions mapping to same/similar outcomes/rewards. I can see a strong parallelism between these two terms but some of the recent usage of bisimulation as a metric confused me as it is referred to as "equivarance" (especially in this [paper](https://research.facebook.com/publications/bisimulation-makes-analogies-in-goal-conditioned-reinforcement-learning/)). I understand that equivariance is when the changes in the input "translates" into output (in that paper it relates to analogous tasks), thus variance reflects in the outcome and the function preserves the symmetry. Whereas degeneracy would relate more to "invariance" since the change in the input doesn't change the output - preserves the functioning. I had some readings on the works on equivariance ([CNNs](https://openreview.net/pdf?id=Syx72jC9tm), [Graph NNs](https://icml.cc/virtual/2021/poster/9279)) in the field. 
My question is, briefly, does bisimulation relation necessarily imply same/similar output (or terminal states)? If so, I don't think equivariance would be directly related to bisimulation since it implies similarity in transitions = "behavior" to a potentially different output with same variance? (such as in the case of analogous tasks). But also it makes sense to relate equivariance to bisimulation, since in the strong definition of bisimulation, state transitions should be the same (very nice talk about [probabilistic bisimulation](https://simons.berkeley.edu/talks/simulation-bisimulations-probabilistic-systems-their-logical-contents)) which I think it relates to NFA-DFA (as in Finite Automata) "equivalence" but in that case, terminal states should remain the same (as outputs)?


(Spring 2022) Lecture Notes for [Formal Languages and Automata Theory](https://drive.google.com/file/d/1NKybcvr-j9wWdZ6dn146ImT4Y3Bb_HvP/view?usp=drive_link)

(Fall 2021) Lecture Notes for [Information Theory](https://drive.google.com/file/d/1EwVt8kZeXqZhGXscWkRcmW1rKKCShv0T/view?usp=drive_link)


(Summer 2021) New direction in Theoretical CS

Soon to be posted thoughts and notes on:
**Alternatives to Turing Machines: Kolmogorov Machines**
*Encoding and processing information on/via "the structure".*

**New Theory of Computation for AI**

(August 2020) **Recent issues in Causality**:
A summary of what happened in the field since I defended my master's thesis.

(Spring 2019) Cheatsheet & Scanned notes for [Biosystems Modeling and Control Theory, ENG](https://drive.google.com/file/d/1skUDVPE2e6rJ-fHSg_rv75ojIa9oulLe/view?usp=sharing)






[back](../index.md)
