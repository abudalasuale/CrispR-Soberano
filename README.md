# Crispr-soberano | abu

this is a sovereign system for the simulation and analysis of crispr-cas9 gene editing, designed to operate in low-bandwidth environments with a focus on sub-saharan african population genomic data.

🧬 overview

crispr-soberano integrates computational biophysics, phenotype prediction, and augmented reality into a single immersive web dashboard. the project is structured as a decision-support tool for laboratories and clinical contexts (e.g., central hospital of maputo).

🛠️ architecture (18 modules)

the system is divided into a 5-stage pipeline:

input & design: grna definition.

biophysical analysis: calculation of gibbs free energy ($\Delta g$).

safety (core): off-target risk analysis based on vcf files.

impact prediction: quark-bc engine for mutation prediction (frameshift, nonsense).

interface & access: 3d visualization and ar (augmented reality) simulator.

🚀 how to run

online: access via github pages (instructions in guide_github.md).

local:

open the index.html file in any modern browser.

for advanced backend features, run app.py (requires fastapi and uvicorn).

📊 technical stack

frontend: three.js (3d engine), tailwind css (styling), webxr (ar).

backend: python 3.9+, fastapi, zlib (data compression).

biology: nearest-neighbor model for rna:dna thermodynamics.

⚖️ license

this project is licensed under the mit license - see the license file for details.

developed by abu | sovereign genetic technology for mozambique and the world.
