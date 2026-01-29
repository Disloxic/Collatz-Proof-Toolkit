[![DOI](https://zenodo.org/badge/DOI/10.5281/zenodo.18406397.svg)](https://doi.org/10.5281/zenodo.18406397)

# Supporting Material for: The Sextant Matrix System: A Structural Resolution of the Collatz Conjecture

**Author:** David Potts [![ORCID](https://img.shields.io/badge/ORCID-0009--0008--1403--8962-A6CE39?logo=orcid&logoColor=white)](https://orcid.org/0009-0008-1403-8962)
**Date:** January, 2026 


## Overview
This repository contains the interactive source code and data visualizations associated with the paper listed above.
The files are provided as standalone HTML documents containing embedded JavaScript.
They allow the user to see how the data is generated and navigated as described in the manuscript.


Collatz-Proof-Toolkit/
│
├── README.md               
├── LICENSE.txt
│             
├── 01-Odds-Matrix.html
├── 02-Trajectory-Analysis-Tool.html
├── 03-Derivation-of-Predecessor-Coordinates.html
├── 04-Derivation-of-Successor-Coordinates.html
├── 05-The-Sextant-Matrix-System.html
├── 06-Node-State-Machine.html
│  
└── lib/ (Contains MathJax and styles.css for display purposes)



## ⚠️ Instructions for Viewing
**Please Note:** Zenodo does not render HTML files directly in the browser. To view the interfaces:

1.  **Download** this repository (click the "Download" button on Zenodo).
2.  **Unzip** the folder.
3.  **Open** the `.html` files locally by double-clicking them (or right-click > Open With > [Chrome/Firefox/Safari]).

*No internet connection or server installation is required to run these simulations.*


## File Descriptions


01-Odds-Matrix.html
-------------------
Proves completeness. Uniquely generates all of n, categorised by S. Calculates all displacements and therefore all successors.
Reveals the structural relationship between 4n+1 and 6k+3. See section 2.


02-Trajectory-Analysis-Tool.html
--------------------------------
Proves that we can use the structural relationship betwen 4n+1 and 6k+3 to calculate the predecessors for any n.
Reveals 3 possible ascending pathways and their conditions. See section 3.


03-Derivation-of-Predecessor-Coordinates.html
---------------------------------------------
Proves how we can use ascending pathway cycles, in conjunction with a Sextant Matrix System,
to deterministically derive the correct Coordinate of any predecessor for any n. See sections 5.1 to 5.4.


04-Derivation-of-Successor-Coordinates.html
-------------------------------------------
Proves how we can use 3 separate lookup matrices for M,i,j, using a series of shifts and patterns that adhere to periodicities of the powers of 2,
in conjunction with a Sextant Matrix System and  to deterministically derive the correct Coordinate of any Successor for any n. See sections 5.5 to 5.6.


05-The-Sextant-Matrix-System.html
---------------------------------
The complete system, using six matrices: A,B,C and D,E,F. See sections 4 & 5.
Each matrix has five layers:

1) Layer 1  - The unique values of all n
2) Layer 2  - Predecessor values for all n
3) Layer 2i - Predecessor coordinates for all n
4) Layer 3  - Successor values for all n
5) Layer 3i - Successor coordinates for all n


06-Node-State-Machine.html
--------------------------
Uses the Sextant Matrix System to navigate the Node Logic Circuit. See sections 6 to 7.2.
Proves that the Generalised State Machine logic is correct.
The numeric value of any n and the coordinate of any n are interchangeable, yet fully independant of eachother.
Proves via structural induction that the integer sets form a Generative Graded Tree, which we can navigate deterministically.
Proves that all n has a finite rank within the tree (no non-trivial loops/cycles), assuring convergence to the root at E,1,1 for all n.


## System Requirements
These files are built using standard HTML5 and JavaScript.
* **Browsers:** Tested and verified on [Chrome / Firefox / Safari].
* **Dependencies:** All necessary libraries are embedded within the files; no external downloads are needed.


## License

The manuscript is released under the CC BY-NC-ND 4.0 license.

The source code and datasets are released under the MIT License.



## Citation
If you use this code or the associated paper in your research, please cite the work as follows:

> Potts, D. (2026). The Sextant Matrix System: A Structural Resolution of the Collatz Conjecture. Zenodo. https://doi.org/10.5281/zenodo.18406397

**BibTeX:**

```bibtex
@misc{potts2026sextant,
  author       = {Potts, David},
  title        = {The Sextant Matrix System: A Structural Resolution of the Collatz Conjecture},
  year         = {2026},
  publisher    = {Zenodo},
  doi          = {10.5281/zenodo.18406397},
  url          = {[https://doi.org/10.5281/zenodo.18406397](https://doi.org/10.5281/zenodo.18406397)}
}



