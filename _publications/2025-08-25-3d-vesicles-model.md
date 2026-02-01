---
title: "A three-dimensional multi-phase-field vesicles model and its practical finite difference solver"
collection: publications
category: manuscripts
permalink: /publication/2025-08-25-3d-vesicles-model
excerpt: '<b>Authors:</b> Y. Wu, <b>Z. Qiu</b>, J. Yang<br><br><i>This paper proposes a three-dimensional multi-phase-field model for vesicles and a practical finite difference solver.</i>'
date: 2026-1-22
venue: 'Computer Physics Communications'
# slidesurl: ''
paperurl: 'https://doi.org/10.1016/j.cpc.2026.110053'
codeurl: 'https://github.com/aaron-z-chiu/multiple-vesicles'
citation: 'Y. Wu, <b>Z. Qiu</b>, J. Yang, A three-dimensional multi-phase-field vesicles model and its practical finite difference solver,Computer Physics Communications 321 (2026) 110053.'
---

<b>Authors:</b> Y. Wu, <b>Z. Qiu</b>, J. Yang

This paper presents a three-dimensional multi-phase-field vesicles model and discusses its practical finite difference solver. It is currently published in Computer Physics Communications (CPC).

**[Free Access]** Elsevier provides 50 days of free access to the final version. You can download the full paper **for free** via [this link](https://authors.elsevier.com/c/1mWXh2OInzQhY) (**valid until March 19, 2026**).

**Main Contributions:**
* Implemented a hybrid numerical solver for 3D fluid vesicle dynamics in C++, integrating phase-field models into an existing simulation framework.
* Applied a semi-implicit finite difference scheme to evolve phase-field equations, ensuring rigorous numerical stability and energy conservation.
* Optimized memory management and data storage strategies, significantly reducing computational overhead for multi-vesicle interaction simulations.

<table style="border: none; width: 100%; margin-top: 20px;">
  <tr style="border: none;">
    <td width="50%" style="border: none; text-align: center; vertical-align: top; padding: 10px;">
      <img src="../images/8cell.gif" alt="8-Vesicle Packing" style="width: 100%; border-radius: 8px; box-shadow: 0 4px 6px rgba(0,0,0,0.1);">
      <div style="margin-top: 8px; font-style: italic; color: #666; font-size: 0.9em; line-height: 1.5;">
        Phase-field simulation of 8 spherical vesicles with 2 phase-field variables.
      </div>
    </td>
    <td width="50%" style="border: none; text-align: center; vertical-align: top; padding: 10px;">
      <img src="../images/3cell.gif" alt="3-Vesicle RGB" style="width: 100%; border-radius: 8px; box-shadow: 0 4px 6px rgba(0,0,0,0.1);">
      <div style="margin-top: 8px; font-style: italic; color: #666; font-size: 0.9em; line-height: 1.5;">
        Phase-field simulation of 3 stacked vesicles with distinct phase-field variables.
      </div>
    </td>
  </tr>
</table>