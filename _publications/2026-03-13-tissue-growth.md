---
title: "Phase-field modeling and simulation of two- and three-dimensional curvature-dependent tissue growth on surfaces"
collection: publications
category: manuscripts
permalink: /publication/2026-03-13-tissue-growth
excerpt: '<b>Authors:</b> <b>Zecheng Qiu</b>, Yutong Wu, Junxiang Yang <sup><img src="../images/mail.png" style="height:1em; vertical-align:text-top;"></sup><br><br><i>This paper proposes a second-order stabilized semi-implicit ADI operator-splitting solver for simulating curvature-dependent tissue growth on complex 2D & 3D surfaces.</i>'
date: 2026-04-13
venue: 'Submitted to Physica D: Nonlinear Phenomena (Under Review)'
# slidesurl: ''
# paperurl: ''
codeurl: 'https://github.com/aaron-z-chiu/phase-field-tissue-growth'
citation: '<b>Z. Qiu</b>, Y. Wu, J. Yang, Phase-field modeling and simulation of two- and three-dimensional curvature-dependent tissue growth on surfaces, Submitted to Physica D: Nonlinear Phenomena (Under Review).'
---

<b>Authors:</b> <b>Zecheng Qiu</b>, Yutong Wu, Junxiang Yang <sup><img src="../images/mail.png" style="height:1em; vertical-align:text-top;"></sup>

This paper presents a novel numerical framework for modeling curvature-dependent tissue growth on complex scaffolds. It is currently Under Review at *CPhysica D: Nonlinear Phenomena*.

**Main Contributions:**
* Developed and open-sourced a C++ simulation framework implementing a stabilized semi-implicit ADI operator-splitting solver, addressing the stability constraints of traditional explicit time-stepping.
* Achieved second-order temporal accuracy, enabling reliable long-time simulations with improved accuracy–cost balance.
* Extended the baseline 2D formulation to 3D volumetric geometries and implemented the corresponding solver pipeline, supporting simulations in realistic porous/scaffold-like structures.