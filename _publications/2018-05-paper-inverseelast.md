---
title: "A modular inverse elastostatics approach to resolve the pressure-induced stress state for in vivo imaging based cardiovascular modeling"
collection: publications
permalink: /publication/2018-05-paper-inverseelast
date: 2018-05-28
venue: 'Journal of the Mechanical Behavior of Biomedical Materials'
paperurl: 'https://doi.org/10.1016/j.jmbbm.2018.05.032'
excerpt: 'We developed a novel, modular inverse elastostatics approach and implemented this methodology in a commercial FEA solver with minor user subroutine interventions.
The accuracy of this methodology was demonstrated in an arterial tube and porcine biventricular myocardium model and subsequently applied to patient-specific aorta and heart models.'
---

[Download paper here](https://doi.org/10.1016/j.jmbbm.2018.05.032)

Patient-specific biomechanical modeling of the cardiovascular system is complicated by the presence of a physiological pressure load given that the imaged tissue is in a pre-stressed and -strained state. 
Neglect of this prestressed state into solid tissue mechanics models leads to erroneous metrics (e.g. wall deformation, peak stress, wall shear stress) which in their turn are used for device design choices, risk assessment (e.g. procedure, rupture) and surgery planning. 
It is thus of utmost importance to incorporate this deformed and loaded tissue state into the computational models, which implies solving an inverse problem (calculating an undeformed geometry given the load and the deformed geometry). 
Methodologies to solve this inverse problem can be categorized into iterative and direct methodologies, both having their inherent advantages and disadvantages. 
Direct methodologies are typically based on the inverse elastostatics (IE) approach and offer a computationally efficient single shot methodology to compute the in vivo stress state. 
However, cumbersome and problem-specific derivations of the formulations and non-trivial access to the finite element analysis (FEA) code, especially for commercial products, refrain a broad implementation of these methodologies. 
For that reason, we developed a novel, modular IE approach and implemented this methodology in a commercial FEA solver with minor user subroutine interventions. 
The accuracy of this methodology was demonstrated in an arterial tube and porcine biventricular myocardium model. 
The computational power and efficiency of the methodology was shown by computing the in vivo stress and strain state, and the corresponding unloaded geometry, for two models containing multiple interacting incompressible, anisotropic (fiber-embedded) and hyperelastic material behaviors: a patient-specific abdominal aortic aneurysm and a full 4-chamber heart model.


