# Intellectual Property & Stage-Gate Governance Protocol

**Project:** Project 1: Zero-Degradation Kinetic Thermal Dissipation  
**Framework:** Open Moonshot Dual-Track Evaluation Protocol  
**Version:** 1.0 (Effective September 2026)

---

## 1. Governance Principles & Philosophy

This Moonshot challenge operates on an open-innovation model designed to accelerate fundamental breakthroughs in high-flux microelectronics thermal management. The governance structure ensures transparent evaluation, rigorous technical validation, and protected rights for participating solvers and research institutions.

---

## 2. Intellectual Property (IP) Tracks

Solvers may submit their Phase I theoretical dossiers and finite-element modeling under one of two distinct intellectual property frameworks:

### Track A: Open Public Domain (Default / Recommended)
* **License:** Licensed under the repository's root [Apache License 2.0](../../LICENSE).
* **Visibility:** Accepted Phase I simulation archives and theoretical models are published in the project repository to accelerate global open-hardware standards.
* **Commercial Rights:** The submitting team retains unrestricted parallel commercialization rights while granting non-exclusive, perpetual, royalty-free rights to utilize and build upon the submitted simulation parameters.

### Track B: Proprietary / Commercial Evaluation Track
* **License:** Limited Evaluation License for Review Board Assessment.
* **Visibility:** Dossiers and proprietary simulation meshes are restricted to the designated Review Board under strict reciprocal confidentiality.
* **Commercial Rights:** Submitting teams retain 100% background and foreground IP. Finalists selected for Phase II empirical testing agree to negotiate commercial licensing or joint venture agreements under pre-established fair-market milestone terms prior to hardware test-bench mounting.

---

## 3. Stage-Gate Milestones & Grant Disbursements

| Milestone | Gate Criteria | Verification Requirement | Action / Allocation |
| :--- | :--- | :--- | :--- |
| **Gate 0: Registration** | Completed solver registration | Eligibility and conflict verification | Access to benchmark files and forum |
| **Gate 1: Phase I Screening** | Composite score $\ge 85/100$ on evaluation rubric | Verified finite-element convergence and boundary compliance | Phase I Certification; selection for Phase II finalist pool |
| **Gate 2: Phase II Award** | Top-ranked verified finalist dossiers | Independent review board consensus | Phase II hardware prototyping grant disbursement |
| **Gate 3: Empirical Validation** | Successful 48-hour calorimeter burn-in | Physical test data confirming $T_j \le 65^\circ\text{C}$ at $\ge 1{,}200\text{ W/cm}^2$ | Final Challenge Grand Prize & commercial integration track |

---

## 4. Disqualification Criteria

Submissions will be disqualified immediately without recourse upon confirmation of:
1. **Hazardous Working Chemistries:** Use of PFAS, PFOA, persistent bioaccumulative toxins, or restricted ozone-depleting volatile agents.
2. **Boundary Violations:** Physical stack profiles exceeding the $4.5\text{ mm}$ absolute threshold or exceeding the $10\text{ mm} \times 10\text{ mm}$ footprint.
3. **Plagiarism or Data Fabrication:** Inclusion of synthetic or manipulated calorimeter logs, non-converged simulation snapshots, or uncredited prior work.
4. **Interference Hazards:** Generation of unshielded parasitic electromagnetic fields exceeding $-60\text{ dBm}$ within $0.5\text{ mm}$ of the die interface plane.

---

## 5. Review Board Consensus & Dispute Resolution

* All Phase I dossiers are scored independently by three appointed technical examiners (Thermodynamics Lead, Materials Specialist, and Manufacturing Hardware Engineer).
* In the event of a variance greater than 15 points across examiner scorecards, the submission undergoes an automated peer review reconciliation sprint with the Lead Investigator.
* Technical disputes regarding boundary condition interpretations must be submitted via the pinned repository Issue thread prior to Day 25 of the Phase I sprint.
