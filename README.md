# Robustness-of-Seqeunce-Models
Investigating the Robustness of Sequence models in Deep Learning. Masters Thesis at Warwick 20/21 supervised by Martin Lotz with project partner Peter Fazekas.
Peter and myself were sponsored by the Warwick Physcics department to present at the British Conference for Undergraduate Research (BCUR) 2021 on 13/04/21

While the accuracy of ML models have improved for a variety of applications, the
reliability of these models have been put into question. A classifier that predicts the
correct label of a datapoint with high confidence can be fooled into making a wrong classification with high confidence too. Corruptions of a data set imperceptible to the
human eye have been shown to repeatedly fool state-of-the-art image classifiers. In
addition, there exist universal adversarial perturbations which result
in misclassification when applied to every datapoint. This significant shortcoming casts
doubt on the practicality of applying machine learning models to safety-critical systems.
The consequence of a false negative in a medical diagnostic tool or a false prediction in a
self-driving system could possibly result in the loss of a life.

The robustness, or resilience of ML models to adversarial attack has been extensively
studied in the context of image classification systems. This project aims to extend this
work to sequence models trained on temporally variable or highly ordered data. Widely
used deep learning sequence models include recurrent neural networks (RNNs), Long Short
Term Memory networks (LSTMs) & transformers. Applications of these models include
making predictions of trends in financial time series data and predicting exoplanets with
light curve data from satellite missions.

The aims of this project include:

1.  Determining the robustness of sequence models in a deterministic and probabilistic
setting, investigating upper and lower bounds for adversarial robustness in the deterministic
case & identifying the probability of misclassification on the sphere of
radius ρ for the probabilistic case.

2.  Characterising the geometric properties of the decision boundary & loss surface of
robust sequence models. It has been shown that decision boundaries which are
less curved result in more robust models for image classification systems. We
investigate if this holds for sequence models, providing theoretical justification.

3.  Investigate the effect of Jacobian & Hessian regularisation on the robustness of
sequence models. If these regularisation techniques improve robustness, it would
support the hypothesis that sequence models with less curved decision boundaries
achieve greater robustness.

4.  Develop a framework based on the theory of condition numbers in numerical analysis
and optimization to identify & characterise robustness.
