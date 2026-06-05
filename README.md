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
7. Hierarchical clustering of average class representations.
8. Training and evaluation of linear read-outs on input pixels, H1, H2 and H3.
9. Analysis of normalized confusion matrices across hidden representations.
10. Construction of psychometric curves with Gaussian noise and salt-and-pepper noise.
11. Training of a fully supervised feed-forward neural network baseline.
12. Evaluation of robustness under white-box FGSM adversarial attacks.
13. Analysis of transfer attacks from the FFNN to the DBN read-out.
14. Simple noisy-data augmentation strategy and robustness evaluation.
15. Final discussion of the main results, limitations and possible improvements.

Important style constraint:
- The writing should remain clear, student-like, technically correct, but not overly polished.
- Comments and explanations up to section 8 should remain almost unchanged.
- don't mind the section where student id, name, surname is absent 

Main goal:
- Improve the notebook from a code/methodological point of view while staying coherent with the course labs and project guidelines.
