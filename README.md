# Context summary for Codex

This repository contains a Cognition and Computation student project on EMNIST Letters using a Deep Belief Network.

The main notebook is:
- `emnist_letters_project_clean.ipynb`

The project should follow this structure:
1. Setup of the DBN code, libraries, device, random seeds, and loading of the EMNIST Letters dataset.
2. Preliminary comparison of different DBN architectures.
3. Selection and training of the final DBN architecture.
4. Visualization of receptive fields and projected receptive fields.
5. Extraction of hidden representations from H1, H2 and H3.
6. Computation of reconstruction errors as a sanity check for RBM pre-training.
7. Standardization of input and hidden representations before linear read-outs.
8. Hierarchical clustering of average class representations.
9. Training and evaluation of linear read-outs on input pixels, H1, H2 and H3.
10. Analysis of normalized confusion matrices across hidden representations.
11. Construction of psychometric curves with Gaussian noise and salt-and-pepper noise.
12. Training of a fully supervised feed-forward neural network baseline.
13. Evaluation of robustness under white-box FGSM adversarial attacks.
14. Analysis of transfer attacks from the FFNN to the DBN read-out.
15. Simple noisy-data augmentation strategy and robustness evaluation.
16. Final discussion of the main results, limitations and possible improvements.

Important style constraint:
- The writing should remain clear, student-like, technically correct, but not overly polished.
- Comments and explanations up to section 8 should remain almost unchanged.

Main goal:
- Improve the notebook from a code/methodological point of view while staying coherent with the course labs and project guidelines.
