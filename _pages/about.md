---
permalink: /
title: ""
excerpt: ""
author_profile: true
redirect_from: 
  - /about/
  - /about.html
---

{% if site.google_scholar_stats_use_cdn %}
{% assign gsDataBaseUrl = "https://cdn.jsdelivr.net/gh/" | append: site.repository | append: "@" %}
{% else %}
{% assign gsDataBaseUrl = "https://raw.githubusercontent.com/" | append: site.repository | append: "/" %}
{% endif %}
{% assign url = gsDataBaseUrl | append: "google-scholar-stats/gs_data_shieldsio.json" %}

## 😄 About Me

I am a Ph.D. candidate in Electronic Science and Technology at <span class="accent">Anhui University</span>, Hefei, China, advised by Prof. <span class="accent">Zhixiang Huang</span> and Assoc. Prof. <span class="accent">Guoda Xie</span>. I conduct my research at the <a href="http://icsp.ahu.edu.cn/" class="accent-link">Key Laboratory of Intelligent Computing and Signal Processing, Ministry of Education</a> and the <a href="http://imis.ahu.edu.cn" class="accent-link">Anhui Province Information Materials and Intelligent Sensing Laboratory</a>.

Since Jun. 2026, I have been a visiting joint Ph.D. student at the <span class="accent">School of Electrical and Electronic Engineering (EEE)</span>, <span class="accent">Nanyang Technological University (NTU), Singapore</span>, working with Assoc. Prof. <span class="accent">Eng Leong Tan</span>, supported by the <span class="accent">China Scholarship Council (CSC)</span>. The visit runs from Jun. 2026 to Jun. 2027.

My research focuses on <span class="accent">computational electromagnetics and multiphysics numerical simulation</span>, in particular the <span class="accent">finite-difference time-domain (FDTD) method</span>: unconditionally stable and divergence-preserving implicit schemes (CDI-, HIE-, ADI-FDTD), symplectic high-order time integration, conformal and non-uniform/subgrid modeling, perfectly matched layers, and the simulation of dispersive, anisotropic, plasma and stochastic media. <a href="https://scholar.google.com/citations?user=uqxq_AQAAAAJ" aria-label="View my Google Scholar profile">
  <img src="https://img.shields.io/endpoint?url={{ url | url_encode }}&logo=Google%20Scholar&labelColor=f6f6f6&color=9cf&style=flat&label=citations" alt="Google Scholar citation count">
</a>


## 🔥 News

- **2026**: 🎉 Our paper on an efficient CFS-PML based on the vector-scalar potential formulation for quantum-electromagnetic multiphysics simulations is accepted by <span class="accent">Computer Physics Communications</span>. [Paper](https://doi.org/10.1016/j.cpc.2026.110427)
- **2026**: 🎉 Two first-author papers, on a modified conformal CD-HIE-FDTD method and a non-uniform grid CDI-FDTD method, are accepted by <span class="accent">IEEE TAP</span>. [Paper 1](https://doi.org/10.1109/TAP.2026.3749017) [Paper 2](https://doi.org/10.1109/TAP.2026.3729839)
- **2026-08**: 🎉 Two papers, on the Z-transform divergence-preserving ADI-FDTD method and the stochastic CDI-FDTD method, are published in <span class="accent">IEEE TAP</span>.
- **2026-06**: Joined the group of <span class="accent">Assoc. Prof. Eng Leong Tan</span> at <span class="accent">NTU, Singapore</span> as a CSC-funded visiting joint Ph.D. student (Jun. 2026 – Jun. 2027).
- **2025-09**: 🎉 Our paper on the leapfrog CD-HIE-FDTD method with CFS-PML is published in <span class="accent">IEEE TAP</span>. [Paper](https://doi.org/10.1109/TAP.2025.3574871)
- **2025-08**: 🎉 Our paper on the unified arbitrary-order symplectic FDTD(p,q) algorithm is published in <span class="accent">IEEE TMTT</span>. [Paper](https://doi.org/10.1109/TMTT.2025.3547000)

## 📝 Publications

(\* corresponding author)

### First-author papers

🔹 **<u>G. Hou</u>**, Y. Tang, X. Wu, X. Ren, M. Fang, G. Xie, and Z. Huang.  
*An Unconditionally Stable Non-uniform Grid CDI-FDTD Method for Microstrip Structures with Voltage Source Ports.* [Paper](https://doi.org/10.1109/TAP.2026.3729839)<br>
<i>IEEE Transactions on Antennas and Propagation</i>, early access, 2026.

---

🔹 **<u>G. Hou</u>**, X. Wu, H. Fang, C. Wang, G. Xie, X. Ren, and Z. Huang.  
*A Modified Conformal CD-HIE-FDTD Method with Enhanced Numerical Stability for Simulating Curved PEC Targets.* [Paper](https://doi.org/10.1109/TAP.2026.3749017)<br>
<i>IEEE Transactions on Antennas and Propagation</i>, early access, 2026.

---

🔹 **<u>G. Hou</u>**, G. Wang, G. Xie, X. Ren, Y. Li, Z. Huang, and A. Z. Elsherbeni.  
*Z-Transform Based Divergence-Preserving ADI-FDTD Method and Its Integration with Subgrid Techniques for GPR Simulations.*<br>
<i>IEEE Transactions on Antennas and Propagation</i>, vol. 74, no. 8, pp. 7228–7243, Aug. 2026.

---

🔹 **<u>G. Hou</u>**, Y. Chen, G. Xie, W. Ding, Y. Li, and Z. Huang.  
*A Numerical Study of Efficient Leapfrog CD-HIE-FDTD Method with CFS-PML Technique.* [Paper](https://doi.org/10.1109/TAP.2025.3574871)<br>
<i>IEEE Transactions on Antennas and Propagation</i>, vol. 73, no. 9, pp. 6670–6685, Sep. 2025.

---

🔹 **<u>G. Hou</u>**, G. Xie, Y. Chen, K. Song, X. Deng, M. Fang, Y. Li, Z. Huang, and A. Z. Elsherbeni.  
*A Unified Arbitrary-Order Symplectic FDTD(p,q) Algorithm Based on Matrix Exponential Method for Anisotropic Time-Varying Plasma and PML.* [Paper](https://doi.org/10.1109/TMTT.2025.3547000)<br>
<i>IEEE Transactions on Microwave Theory and Techniques</i>, vol. 73, no. 8, pp. 4630–4646, Aug. 2025.

---

🔹 **<u>G. Hou</u>**, G. Xie, W. Ding, Y. Li, Y. Hong, and Z. Huang.  
*A Numerical Study of the Symplectic FDTD(p,q) Method Combined with Matrix Exponential Technique for Anisotropic Magnetized Plasma.* [Paper](https://doi.org/10.1016/j.cpc.2025.109735) [Code](https://github.com/houguilin777/A-Numerical-Study-for-Anisotropic-Magnetized-Plasma)<br>
<i>Computer Physics Communications</i>, Art. no. 109735, 2025.

### Corresponding-author papers

🔹 G. Xie, W. Hu, **<u>G. Hou\*</u>**, X. Ren, W. E. I. Sha, and Z. Huang.  
*Construction of an Efficient CFS-PML Technique Based on the Vector-Scalar Potential Formulation and Its Application in Quantum-Electromagnetic Multiphysics Simulations.* [Paper](https://doi.org/10.1016/j.cpc.2026.110427)<br>
<i>Computer Physics Communications</i>, vol. 330, Art. no. 110427, Jan. 2027.

---

🔹 G. Xie, X. Wu, **<u>G. Hou\*</u>**, G. Wang, X. Ren, Y. Li, X. Wu, and Z. Huang.  
*An Unconditionally Stable Stochastic CDI-FDTD Method for Electromagnetic Wave Propagation in Media with Uncertain Material Properties.*<br>
<i>IEEE Transactions on Antennas and Propagation</i>, vol. 74, no. 8, pp. 7396–7407, Aug. 2026.

### Co-authored papers

🔹 G. Xie, **<u>G. Hou</u>**, K. Xu, K. Niu, N. Feng, Y. Li, Z. Huang, and A. Z. Elsherbeni.  
*Extension of FLOD-FDTD Method for Multiterm Modified Lorentz Model.* [Paper](https://doi.org/10.1109/TAP.2023.3315055)<br>
<i>IEEE Transactions on Antennas and Propagation</i>, vol. 71, no. 11, pp. 8830–8840, Nov. 2023.

---

🔹 G. Xie, **<u>G. Hou</u>**, N. Feng, K. Song, M. Fang, Y. Li, X. Wu, and Z. Huang.  
*Auxiliary Differential Equation (ADE) Method Based Complying-Divergence Implicit FDTD Method for Simulating the General Dispersive Anisotropic Material.*<br>
<i>Optics Express</i>, vol. 31, no. 11, pp. 18468–18486, 2023.

---

🔹 Z. Wang, **<u>G. Hou</u>**, G. Xie, X. Ren, G. Wang, Z. Huang, and X. Wu.  
*A Novel S-FLOD-CD-FDTD Method for Simulating Stochastic Media.*<br>
<i>IEEE Transactions on Antennas and Propagation</i>, 2026.

---

🔹 Y. Chen, G. Xie, **<u>G. Hou</u>**, Z. Song, Y. Li, Z. Huang, and A. Z. Elsherbeni.  
*An 3D Unconditionally Stable CDI-FDTD Method Based on the Conformal Technique for Simulating Complex Curved PEC Objects.*<br>
<i>IEEE Transactions on Antennas and Propagation</i>, 2025.

---

🔹 Y. Chen, **<u>G. Hou</u>**, G. Wang, X. Ren, G. Xie, and Z. Huang.  
*Efficient Implementation of Divergence-Preserving-HIE-FDTD Method and Its CFS-PML.*<br>
<i>IEEE Transactions on Microwave Theory and Techniques</i>, 2025.

Full list on <a href="https://scholar.google.com/citations?user=uqxq_AQAAAAJ" class="accent-link">Google Scholar</a>.


## 📖 Education

- *Jun. 2026 – Jun. 2027*, Visiting Joint Ph.D. Student (CSC), School of EEE, Nanyang Technological University, Singapore  
  Supervisor: Assoc. Prof. Eng Leong Tan

- *Sep. 2024 – Present*, Ph.D. Candidate, Electronic Science and Technology, Anhui University, Hefei, China  
  Supervisors: Prof. Zhixiang Huang and Assoc. Prof. Guoda Xie

- *Sep. 2021 – Sep. 2024*, M.E., Electronic Science and Technology, Anhui University, Hefei, China


## 🛠 Projects

- **Electromagnetic Shielding & Multiphysics Simulation for RFICs**  
  Modeling of electromagnetic coupling structures; development of multiphysics simulation programs; implementation of coupled solvers for improved accuracy.


## 💻 Skills

- **Numerical methods**: FDTD method and its unconditionally stable variants; modeling of complex dispersive media and multi-scale structures; multiphysics simulation.
- **Programming & tools**: MATLAB (numerical computing and algorithm development), CST Studio Suite, COMSOL Multiphysics.
