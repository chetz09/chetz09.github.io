---
title: "Machine learning-driven pH quantification via acidoCEST MRI in preclinical animal models"
collection: publications
category: manuscripts
permalink: /publication/2025-ml-acidocest
excerpt: 'A machine-learning framework for extracellular pH quantification from acidoCEST MRI, validated in preclinical models. (Under review)'
date: 2025-01-01
venue: 'Magnetic Resonance in Medicine (under review)'
citation: '<b>Dhakan CB</b>, Khaled AS, McCullum L, de la Cerda J, Schuler FW, Li T, Pagel MD. <i>Magn Reson Med</i> (under review).'
---

![Representative figure](/images/publications/ml-acidocest.png){: .align-center style="max-width:560px;"}

### Hypothesis
Supervised machine-learning models trained on simulated and experimental Z-spectra can quantify tumor extracellular pH from acidoCEST MRI more accurately and rapidly than conventional Lorentzian fitting.

### Approach
- Generated a large training set of Z-spectra spanning physiologic pH, B0/B1 inhomogeneities, and tissue parameters.
- Trained ML regressors (neural networks / tree-based models) to map Z-spectra → pH.
- Validated against conventional Lorentzian fitting on phantoms and *in vivo* preclinical tumor data.

### Key findings / conclusion
ML-based pH quantification matched or outperformed conventional fitting in accuracy and noise robustness, with order-of-magnitude speed-ups — enabling voxel-wise pH maps suitable for routine preclinical acidoCEST workflows.
