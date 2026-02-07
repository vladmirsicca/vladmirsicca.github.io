---
title: "Newclid: A User-Friendly Replacement for AlphaGeometry"
collection: preprints
category: manuscripts
permalink: /publication/newclid_user_friendly_replacement_for_alphageometry
excerpt: 'Description of the first release of Newclid and review of the functioning of AlphaGeometry 1.'
date: 2024-11-18
venue: 'ArXiv'
paperurl: 'https://arxiv.org/abs/2411.11938'
citation: 'Sicca, V., Xia, T., Fédérico, M., Gorinski, P.J., Frieder, S., & Jui, S. (2024). Newclid: A User-Friendly Replacement for AlphaGeometry. ArXiv, abs/2411.11938.'
---

Abstract: We introduce a new symbolic solver for geometry, called Newclid, which is based on AlphaGeometry. Newclid contains a symbolic solver called DDARN (derived from DDAR-Newclid), which is a significant refactoring and upgrade of AlphaGeometry's DDAR symbolic solver by being more user-friendly - both for the end user as well as for a programmer wishing to extend the codebase. For the programmer, improvements include a modularized codebase and new debugging and visualization tools. For the user, Newclid contains a new command line interface (CLI) that provides interfaces for agents to guide DDARN. DDARN is flexible with respect to its internal reasoning, which can be steered by agents. Further, we support input from GeoGebra to make Newclid accessible for educational contexts. Further, the scope of problems that Newclid can solve has been expanded to include the ability to have an improved understanding of metric geometry concepts (length, angle) and to use theorems such as the Pythagorean theorem in proofs. Bugs have been fixed, and reproducibility has been improved. Lastly, we re-evaluated the five remaining problems from the original AG-30 dataset that AlphaGeometry was not able to solve and contrasted them with the abilities of DDARN, running in breadth-first-search agentic mode (which corresponds to how DDARN runs by default), finding that DDARN solves an additional problem. We have open-sourced our code under: [this https URL](https://github.com/Newclid/Newclid)
