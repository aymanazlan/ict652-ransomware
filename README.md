# ICT652 Case Study 19: Ransomware and Service Continuity

Live 3D web presentation for the ICT652 (Ethical, Social and Professional Issues in ICT) case study at UiTM Kedah, Group 3, class 6B.

A ransomware attack has encrypted a fictional Sungai Petani clinic's appointment and patient-record systems. The slides cover the main issues, the ethical analysis (utilitarianism, duty ethics, amanah and ihsan), the recommended response, the agreed action record and each role's protocol.

**Live:** https://aymanazlan.github.io/ict652-ransomware/

## Group 3

| Member | Role |
|---|---|
| Arief Najib | Clinic Owner |
| Muhammad Aiman | IT Incident Officer |
| Muhammad Syazwan | Clinical Operations Representative |
| Muhammad Haziq Rahimi | Patient Representative |

## Using it

Arrow keys, Space, the on-screen buttons or a swipe move between slides. **N** shows speaker notes, **F** goes full screen, and **1–4** switch roles on the protocol slide. On the dialogue slide, each click brings in the next speaker before moving on. The timer in the bar starts on the first move and turns amber at 8:00 and red at 9:00 (target 8 to 9 minutes); speaker notes give a time target for every slide. Each slide has its own link (`#slide-1` to `#slide-14`).

The slides follow the assessment's five required parts: main issues (Q1), analysis (Q2–Q3), readings and Malaysian context, solutions and the agreed action record (Q4), and creativity of solutions (Q5 protocols).

It is a single `index.html` with no build step. The 3D scene (1,000 instanced "patient record" cubes that morph between shapes, with bloom, plus stylised low-poly stakeholder and patient figures that act out each scene) uses three.js r128 from cdnjs and jsDelivr, so it needs an internet connection; without it the slides still work without the moving background.
