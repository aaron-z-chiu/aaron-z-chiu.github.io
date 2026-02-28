---
title: "A three-dimensional multi-phase-field vesicles model and its practical finite difference solver"
collection: publications
category: manuscripts
permalink: /publication/2025-08-25-3d-vesicles-model
excerpt: '<b>Authors:</b> Yutong Wu, <b>Zecheng Qiu</b>, Junxiang Yang <sup><img src="../images/mail.png" style="height:1em; vertical-align:text-top;"></sup><br><br><i>This paper proposes a three-dimensional multi-phase-field model for vesicles and a practical finite difference solver.</i>'
date: 2026-1-22
venue: 'Computer Physics Communications'
# slidesurl: ''
paperurl: 'https://doi.org/10.1016/j.cpc.2026.110053'
codeurl: 'https://github.com/aaron-z-chiu/multiple-vesicles'
citation: 'Y. Wu, <b>Z. Qiu</b>, J. Yang, A three-dimensional multi-phase-field vesicles model and its practical finite difference solver,Computer Physics Communications 321 (2026) 110053.'
---

<b>Authors:</b> Yutong Wu, <b>Zecheng Qiu</b>, Junxiang Yang <sup><img src="../images/mail.png" style="height:1em; vertical-align:text-top;"></sup>

This paper presents a three-dimensional multi-phase-field vesicles model and discusses its practical finite difference solver. It is currently published in Computer Physics Communications (CPC).

**[Free Access]** Elsevier provides 50 days of free access to the paper. You can download the full paper **for free** via <a href="https://authors.elsevier.com/c/1mWXh2OInzQhY" target="_blank" rel="noopener noreferrer">this link</a> (**valid until March 19, 2026**).

**Highlights:**
* New phase-field model is developed for multiple vesicles.
* The model satisfies the global constraints preserving properties.
* A practical and easy finite difference method is presented.
* The simulation code is shared for the interested readers.

**Role & Responsibilities:**
* **Engineered the Core Solver:** Developed a high-performance C++ numerical solver from scratch, successfully implementing a semi-implicit finite difference scheme for 3D vesicle dynamics.
* **Validated Model Fidelity:** Performed extensive sensitivity analysis and parameter tuning, ensuring the simulation strictly adhered to energy conservation laws and global constraints.
* **Delivered Research Impact:** Co-authored the published manuscript and managed the open-source code release, ensuring high reproducibility through detailed documentation and build automation.

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