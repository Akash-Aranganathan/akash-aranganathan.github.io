---
layout: archive
title: "Research Interests"
permalink: /research/
author_profile: true
---

### Overview
Biological systems have evolved such that collectively they perform a vast range of functions. Understanding the governing principles of such “living” systems is quite an interesting puzzle. In my research career, I aim to investigate and demystify such systems by developing methods and theories on them. 

<img src='/images/overview.jpeg'>

### Protein Biomolecule
Protein (globular protein) is a biological molecule that has been thought to function via its three-dimensional structure (the so-called protein fold). However, environmental factors such as temperature, pH, ion concentration, and the presence of other biomolecules will affect the behaviour of protein molecules, thereby affecting their function. Thus, for a given protein's chemical information (primary sequence), the protein folding problem is to investigate the most probable structural fold, folding pathways, and other relatively long-lived structures under certain environmental conditions. For this, statistical mechanics provides a strong ensemble-based framework to the protein folding problem. 

Further, Molecular dynamics (MD) simulations provide atomistic insight by propagating biomolecular motion under a pre-defined Hamiltonian. These simulations enable sampling of diverse conformational ensembles to identify metastable and transition states, offering an atomistic/structural view of biomolecular function. However, accurately capturing equilibrium probabilities (free energy) remains challenging due to the time and length-scale limitations of standard MD. Recent developments in Artificial Intelligence(AI) approaches – such as AlphaFold2/3, and BioEMU – have revolutionized structure and ensemble prediction, yet incorporating environmental conditions into these models remains a major open problem. In attempting to address all these questions, my current Ph.D. research is presented as follows.

### Research Works
1. **Conformational Ensembles of Protein Molecules**: I have developed an efficient protocol, AlphaFold2RAVE, by integrating AlphaFold2, an AI-based structure-prediction method, with an AI-augmented enhanced-sampling procedure. From sequence alone, AlphaFold2RAVE generates thermodynamically ranked conformational ensembles and a low-dimensional representation that can be transferred across protein homologs. Using this method, I have demonstrated the ability to calculate relative free energies, generate ranked structures for primary drug target proteins, including kinases and GPCRs, and validate the potential of this approach in drug discovery through retrospective docking.
2. **Protein-Protein Interactions**: Beyond drug discovery, I employed the AlphaFold2RAVE method to enhance CAR T-cell therapy for solid and liquid tumors, particularly during relapse, when tumor cell presentation to the immune system declines. These predictions were then validated through in vivo and in vitro experiments. This approach opens a new field of synapse engineering informed by the biophysics of the synapse at the atomic level.
3. **Protein Backbone Relaxation**: I have also worked on obtaining timescale information from a non-causal, machine-learned conformational ensemble generator by fitting a Langevin equation to the ensemble. Further, I have demonstrated the need to reweight these ensembles to achieve better backbone relaxation dynamics.
