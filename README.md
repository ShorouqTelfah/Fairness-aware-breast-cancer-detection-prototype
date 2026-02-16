This repository contains the dissertation, full IT artefact (including source code and evaluation pipeline), 
and demonstration video for my MSc in Data Science and Artificial Intelligence at the University of Liverpool.

Artificial intelligence has recently been promoted as a promising tool for early breast cancer detection through automated mammogram analysis. 
However, previous studies have shown some challenges with AI in medical images, mainly the presence of bias in AI models that negatively affect underrepresented groups defined by age and breast density type; 
such bias leads to delayed cancer detection and unequal clinical outcomes.
The primary contribution is the development of an IT artefact that balances diagnostic accuracy, subgroup fairness, and clinical interpretability. 
The proposed IT artefact is based on a DenseNet-121 convolutional neural network trained on the VinDr-Mammo dataset, with data use aligned to ethical governance.
To mitigate bias, different fairness-aware interventions, such as reweighting and adversarial methods, were applied individually. 
Then the hybrid model was implemented to combine the strengths of both interventions. 
Model transparency and ethical application were integrated by using Gradient-weighted Class Activation Mapping (Grad-CAM) explainability,
ensuring equitable outcomes and supporting safe clinical use, and a comparative evaluation was conducted against base-line and single-intervention models. 
