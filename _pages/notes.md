---
layout: default
---


A discussion with Dr.Pados on ## Bisimulation:
I was somewhat familiar with the term bisimulation through my phil/logic background (as in Aczell's 'non-well founded set theory' as in here and with some modal logic as in slides). I recently came across its definition in MDPs (based on the work of Desharnais et al. 2002, followed by original Ferns paper 2004, Google brain paper 2020), and therefore its extension to RL (learning bisimulation as state abstraction, bisimulation metric as optimal value function). 
As you might remember, I was working on the term degeneracy - defined as functional redundancy in RL systems where different states map to same/similar actions and different actions mapping to same/similar outcomes/rewards. I can see a strong parallelism between these two terms but some of the recent usage of bisimulation as a metric confused me as it is referred to as "equivarance" (especially in this paper). I understand that equivariance is when the changes in the input "translates" into output (in that paper it relates to analogous tasks), thus variance reflects in the outcome and the function preserves the symmetry. Whereas degeneracy would relate more to "invariance" since the change in the input doesn't change the output - preserves the functioning. I had some readings on the works on equivariance (CNNs, Graph NNs) in the field. 
My question is, briefly, does bisimulation relation necessarily imply same/similar output (or terminal states)? If so, I don't think equivariance would be directly related to bisimulation since it implies similarity in transitions = "behavior" to a potentially different output with same variance? (such as in the case of analogous tasks). But also it makes sense to relate equivariance to bisimulation, since in the strong definition of bisimulation, state transitions should be the same (very nice talk about probabilistic bisimulation) which I think it relates to NFA-DFA (as in Finite Automata) "equivalence" but in that case, terminal states should remain the same (as outputs)?




## Theoretical CS:
# Alternatives to Turing Machines
# Kolmogorov Machines
# New Theory of Computation for AI

## Recent issues in Causality:







[back](../index.md)
