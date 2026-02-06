---
title: "Semi-implicit ADI operator-splitting method with Richardson extrapolation for the phase-field model of curvature-dependent tissue growth on surfaces"
collection: publications
category: manuscripts
permalink: /publication/2026-02-01-tissue-growth
excerpt: '<b>Authors:</b> <b>Zecheng Qiu</b>, Yutong Wu, Junxiang Yang <sup><img src="../images/mail.png" style="height:1em; vertical-align:text-top;"></sup><br><br><i>This paper proposes a second-order stabilized semi-implicit ADI operator-splitting solver for simulating curvature-dependent tissue growth on complex 2D & 3D surfaces.</i>'
date: 2026-02-01
venue: 'Submitted to Computer Methods in Applied Mechanics and Engineering (Under Review)'
# slidesurl: ''
# paperurl: ''
codeurl: 'https://github.com/aaron-z-chiu/phase-field-tissue-growth'
citation: '<b>Z. Qiu</b>, Y. Wu, J. Yang, Semi-implicit ADI operator-splitting method with Richardson extrapolation for the phase-field model of curvature-dependent tissue growth on surfaces, Submitted to Computer Methods in Applied Mechanics and Engineering (Under Review).'
---

<b>Authors:</b> <b>Zecheng Qiu</b>, Yutong Wu, Junxiang Yang <sup><img src="../images/mail.png" style="height:1em; vertical-align:text-top;"></sup>

This paper presents a novel numerical framework for modeling curvature-dependent tissue growth on complex scaffolds. It is currently Under Review at *Computer Methods in Applied Mechanics and Engineering (CMAME)*.

**Main Contributions:**
* Developed and open-sourced a C++ simulation framework implementing a stabilized semi-implicit ADI operator-splitting solver, addressing the stability constraints of traditional explicit time-stepping.
* Achieved second-order temporal accuracy, enabling reliable long-time simulations with improved accuracy–cost balance.
* Extended the baseline 2D formulation to 3D volumetric geometries and implemented the corresponding solver pipeline, supporting simulations in realistic porous/scaffold-like structures.