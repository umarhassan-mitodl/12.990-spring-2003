---
content_type: page
description: ''
learning_resource_types:
- Lecture Notes
ocw_type: CourseSection
title: Lecture Notes
uid: 323a05fc-67a8-d482-2765-6aa7a8709a05
video_files:
  video_thumbnail_file: null
video_metadata:
  youtube_id: null
---

{{< tableopen >}}
{{< theadopen >}}
{{< tropen >}}
{{< thopen >}}
SES #
{{< thclose >}}
{{< thopen >}}
CLASSROOM ACTIVITY
{{< thclose >}}
{{< thopen >}}
READINGS
{{< thclose >}}
{{< thopen >}}
KEY DATES
{{< thclose >}}

{{< trclose >}}

{{< theadclose >}}
{{< tropen >}}
{{< tdopen >}}
1
{{< tdclose >}}
{{< tdopen >}}
Sorted out class times and locations. Covered class expectations and syllabus. Long soliloquy attempting to show how the different topics to be covered in class evolved and are interrelated. Went over a list of possible class projects.
{{< tdclose >}}
{{< tdopen >}}

{{< tdclose >}}
{{< tdopen >}}

{{< tdclose >}}

{{< trclose >}}
{{< tropen >}}
{{< tdopen >}}
2
{{< tdclose >}}
{{< tdopen >}}
Plenty of definitions, including Dynamical System, State Space, Trajectory, Flow, Map, Conservative System, Nonconservative System, Attractor, Basin of Attraction, Fractal, Strange Attractor, Stable/Unstable Manifolds, Finite-time Stable/Unstable Sets, and Chaos.
{{< tdclose >}}
{{< tdopen >}}

{{< tdclose >}}
{{< tdopen >}}

{{< tdclose >}}

{{< trclose >}}
{{< tropen >}}
{{< tdopen >}}
3
{{< tdclose >}}
{{< tdopen >}}
Defined **ergodic** and explained how it pertains to dynamical systems. Defined and gave examples of the box counting dimension (fill the space with boxes of size \\epsilon and count the number of non empty boxes) and the correlation dimension (count the number of pairs of points within a distance \\epsilon of one another). Linked the two through the spectrum of dimensions defined with respect to the attractor's natural measure. Take home message: the system dynamics can live in a dimension that is less (in some instances far less) than the state space dimension.
{{< tdclose >}}
{{< tdopen >}}
Grassberger, P., and I. Procaccia. "Characterization of Strange Attractors." _Physical Review Letters_ 50, no. 5 (1983): 346-349.
{{< tdclose >}}
{{< tdopen >}}
Problem Set 1 out
{{< tdclose >}}

{{< trclose >}}
{{< tropen >}}
{{< tdopen >}}
4
{{< tdclose >}}
{{< tdopen >}}
Finished up the dimension discussion by modeling a 10d point vortex flow with a 65,000d barotropic model. The barotropic model requires a resolution of 256x256 to accurately reproduce the 10d point vortex motion. Introduced the concept of embedding, and went to great lengths to show that an embedding dimension of m > 2d\_0 is sufficient to guarantee (with probability 1) a one-to-one embedding. Discussed the form of the measurement operator, and made the case that a delay embedding from a single time series is permissible. Discussed choices for the delay time, and showed examples of the impact of a poor decision. Introduced the false nearest neighbor algorithm as an alternative method for choosing embedding dimension. Motivated keeping the embedding dimension as small as possible, while avoiding false near neighbors.
{{< tdclose >}}
{{< tdopen >}}


Sauer, T., J. A. Yorke, and M. Casdagli. "Embedology." _Journal of Statistical Physics_ 65 (1991): 579.


{{< tdclose >}}
{{< tdopen >}}

{{< tdclose >}}

{{< trclose >}}
{{< tropen >}}
{{< tdopen >}}
5
{{< tdclose >}}
{{< tdopen >}}
Spent the lecture talking about Lyapunov exponents. Derived an expression for the linear evolution of perturbations in a map, discussed how the linear uncertainty propagator maps circles into ellipses. Defined finite-time Lyapunov exponents and showed how they were a function of the location from which the linearization starts, the length of the linearization, and the initial orientation of the perturbation vector. Obtained global Lyapunov exponents by a) removing the time dependence by taking the limit as time goes to infinity, b) removing the initial perturbation orientation dependence by considering all possible initial orientations and only keeping the important ones, and c) removing the initial condition dependence through an ergodicity argument.
{{< tdclose >}}
{{< tdopen >}}
Ziehmann, C., L. A. Smith, and J. Kurths. "Localized Lyapunov Exponents and the Prediction of Predictability." _Physics Letters A_ 4 (2000): 237-251.
{{< tdclose >}}
{{< tdopen >}}
Problem Set 1 due
{{< tdclose >}}

{{< trclose >}}
{{< tropen >}}
{{< tdopen >}}
6
{{< tdclose >}}
{{< tdopen >}}
Corrected diagrams from class 5 that used Lyapunov numbers in a manner inconsistent with their definition. Reinforced correct definition of Lyapunov number, giving examples. Defined arithmetic and geometric means. Defined a system to be chaotic if \\lambda\_1>0. Used spectrum of Lyapunov exponents to identify strange attractors. Explained why flows need n=3 to be chaotic, and why reversible maps need n=2 to be chaotic. Defined and explained the Lyapunov dimension. Described how to (and how not to) estimate Lyapunov exponents numerically using a linearization of the model. Described how to estimate Lyapunov exponents numerically using the nonlinear evolution of the model. Demonstrated what can happen when the linearity assumption is violated.
{{< tdclose >}}
{{< tdopen >}}

{{< tdclose >}}
{{< tdopen >}}
Problem Set 2 out
{{< tdclose >}}

{{< trclose >}}
{{< tropen >}}
{{< tdopen >}}
7
{{< tdclose >}}
{{< tdopen >}}
Answered questions about problem set 2. Discussed the details of constructing the linear uncertainty propagator for a flow. Compared singular vectors to the local orientation of the global Lyapunov vectors to demonstrate that finite-time uncertainty dynamics are different from global uncertainty dynamics. Pointed out that this makes Lyapunov exponents useless from the point of view of any finite-time predictability study. Gave a brief primer on eigenvectors/values, singular vectors/values and their relationship.
{{< tdclose >}}
{{< tdopen >}}
Smith L. A., C. Ziehmann, and K. Fraedrich. "Uncertainty Dynamics and Predictability in Chaotic Systems." _Quarterly Journal of the Royal Meteorological Society_ 125 (1999): 2855-2886.
{{< tdclose >}}
{{< tdopen >}}
Problem Set 1 returned
{{< tdclose >}}

{{< trclose >}}
{{< tropen >}}
{{< tdopen >}}
8
{{< tdclose >}}
{{< tdopen >}}
Demonstrated that the pattern of state dependent growth factors related to singular vectors do not match the pattern of state dependent growth factors derived from random perturbations. This raised the question of what perturbation directions are relevant for predictability studies? Made the point that standard singular value decomposition assumes a hypersphere of initial uncertainty evolves into a hyper-ellipse of final uncertainty. In reality, the initial uncertainty is likely to take the form of a hyper-ellipse. Singular value decomposition can be modified to account for this distribution through the application of an initial time norm given by the inverse of the covariance matrix of the initial time hyper-ellipse. Derived the operator that must be decomposed using singular value decomposition, and began a discussion of the interpretation of the resulting singular vectors and singular values.
{{< tdclose >}}
{{< tdopen >}}

{{< tdclose >}}
{{< tdopen >}}
Problem Set 2 due
{{< tdclose >}}

{{< trclose >}}
{{< tropen >}}
{{< tdopen >}}
9
{{< tdclose >}}
{{< tdopen >}}
Split class into singular vector proponents and bred vector proponents. Recapped the impact of a norm on singular vector construction and interpretation. Showed many examples of how the structure of initial-time uncertainty can lead to unexpected singular vector behavior. Argued that the proper structure of the initial uncertainty is given by the local structure of the system attractor (assuming a perfect model exists), and compared singular values produced using the covariance norm with singular values produced using the isotropic norm.
{{< tdclose >}}
{{< tdopen >}}
Gilmour, I., L. A. Smith, and R. Buizza. "Linear Regime Duration: Is 24 Hours a Long Time in Synoptic Weather Forecasting?" _Journal of the Atmospheric Sciences_ 58 (2001): 3525-3539.
{{< tdclose >}}
{{< tdopen >}}

{{< tdclose >}}

{{< trclose >}}
{{< tropen >}}
{{< tdopen >}}
10
{{< tdclose >}}
{{< tdopen >}}
Discussed the pros and cons of different methods for determining to what degree the linearity assumption is valid. Methods included a) comparison of nonlinear and linear error magnitude, b) comparison of the angle between evolved plus and minus perturbations, c) the \\Theta index. Showed that the \\Theta index is a much stronger discriminant than the two alternatives. Showed that it can be and has been applied to geophysical models. Showed that even the \\Theta index can be misleading.
{{< tdclose >}}
{{< tdopen >}}

{{< tdclose >}}
{{< tdopen >}}
Problem Set 2 returned  
  
Problem Set 3 out
{{< tdclose >}}

{{< trclose >}}
{{< tropen >}}
{{< tdopen >}}
11
{{< tdclose >}}
{{< tdopen >}}
Began section on probabilistic forecasting. Introduced stochastic dynamic prediction and derived the probability continuity equation. Explained why it's solution is too computationally expensive, and derived the approximation of evolving only the first two moments of the PDF. Even this is too expensive for large models, motivating the Monte Carlo, or ensemble approximation.
{{< tdclose >}}
{{< tdopen >}}
Epstein, E. S. "Stochastic Dynamic Prediction." _Tellus_ 21, no. 6 (1969): 739-759.
{{< tdclose >}}
{{< tdopen >}}

{{< tdclose >}}

{{< trclose >}}
{{< tropen >}}
{{< tdopen >}}
12
{{< tdclose >}}
{{< tdopen >}}
Gave a probability primer: axioms of probability, frequentists vs. Bayesians, joint probability, conditional probability, multiplicative law of probability, law of total probability, and Bayes' Theorem. Used the conditional distribution of truth given observations, p(x|Y), to define and generate a perfect ensemble. Showed that if a perfect model does not exist, then a perfect ensemble does not exist.
{{< tdclose >}}
{{< tdopen >}}

{{< tdclose >}}
{{< tdopen >}}
Problem Set 3 due
{{< tdclose >}}

{{< trclose >}}
{{< tropen >}}
{{< tdopen >}}
13
{{< tdclose >}}
{{< tdopen >}}
Lecture on the predictability of the global climate system. Distinguished predictability of the 1st kind (initial condition uncertainty) from predictability of the 2nd kind (boundary condition uncertainty). Defined the goals of climate change uncertainty analysis. Described the fingerprinting method for detection and uncertainty estimation.
{{< tdclose >}}
{{< tdopen >}}

{{< tdclose >}}
{{< tdopen >}}
Problem Set 3 returned
{{< tdclose >}}

{{< trclose >}}
{{< tropen >}}
{{< tdopen >}}
14
{{< tdclose >}}
{{< tdopen >}}
**Debate:** This house believes "that bred vectors provide a superior basis for ensemble construction than singular vectors."
{{< tdclose >}}
{{< tdopen >}}

{{< tdclose >}}
{{< tdopen >}}

{{< tdclose >}}

{{< trclose >}}
{{< tropen >}}
{{< tdopen >}}
15
{{< tdclose >}}
{{< tdopen >}}
Continued discussion of climate prediction and uncertainties. Distinguished methods using AOGCMs from those using simpler models. Defined climate sensitivity and other major uncertainties for 50-100 year timescales. Discussed methodology of using climate change diagnostics and their natural variability to estimate model-observation goodness of fit statistics. Discussed estimation of posterior probability distributions for uncertain climate system properties.
{{< tdclose >}}
{{< tdopen >}}

{{< tdclose >}}
{{< tdopen >}}

{{< tdclose >}}

{{< trclose >}}
{{< tropen >}}
{{< tdopen >}}
16
{{< tdclose >}}
{{< tdopen >}}
A return to ensemble construction. Reviewed the concept of a perfect ensemble, and introduced the method of unconstrained ensemble construction. The difficulties associated with unconstrained ensemble construction motivate constrained ensemble construction. Described how bred vectors and singular vectors are operationally constructed and used for ensemble forecasting.
{{< tdclose >}}
{{< tdopen >}}

{{< tdclose >}}
{{< tdopen >}}

{{< tdclose >}}

{{< trclose >}}
{{< tropen >}}
{{< tdopen >}}
17
{{< tdclose >}}
{{< tdopen >}}
Distinguished between uncertainty in the response of the climate system to a given forcing and the uncertainty in the forcing itself. A previous lecture discussed the method for estimating PDF of climate model properties. Introduced Latin-Hypercube sampling (LHS) (a specific form of stratified sampling) for ensemble size reduction in Monte Carlo simulations. Discussed use of priors on Bayesian updating procedures and potential effects on posterior PDFs. Discussed propagation of uncertainty through MIT Integrated Global System Model (IGSM) for emissions uncertainty and model response uncertainty. Showed PDFs of climate model outputs for 250-member LHS ensemble. (temperature change, sea level rise, ...) see [Publications of the MIT Global Change Joint Program](http://web.mit.edu/globalchange/www/reports.html) 
{{< tdclose >}}
{{< tdopen >}}


Sivillo, J. K., J. E. Ahlquist, and Z. Toth. "An Ensemble Forecasting Primer." _Weather and Forecasting_ 12 (1997): 809-818.


{{< tdclose >}}
{{< tdopen >}}

{{< tdclose >}}

{{< trclose >}}
{{< tropen >}}
{{< tdopen >}}
18
{{< tdclose >}}
{{< tdopen >}}
Voted the date when the final papers are due and presentations will take place. Continued discussion on how ensemble forecasts are used: spread vs. skill, spaghetti plots, postage stamp plots, probability plots. Moved on to discuss methods for assessing forecasts. Distinguished between forecast quality and forecast value. Provided a forecast classification, and presented methods for assessing dichotomous, multi-category and continuous deterministic and probabilistic forecasts: scatter plot, root mean square error, mean error, mean absolute error, mean square error, anomaly correlation, contingency table (accuracy, bias, probability of detection, false alarm ratio, threat score), Brier score, relative operating characteristic, reliability diagram, ranked probability score, and rank histograms.
{{< tdclose >}}
{{< tdopen >}}
Murphy, A. H. "What Is a Good Forecast? An Essay on the Nature of Goodness in Weather Forecasting." _Weather and Forecasting_ 8 (1993): 281-293.
{{< tdclose >}}
{{< tdopen >}}

{{< tdclose >}}

{{< trclose >}}
{{< tropen >}}
{{< tdopen >}}
19
{{< tdclose >}}
{{< tdopen >}}
Derived the Kalman (and Extended Kalman) filter using the minimum error variance approach. Discussed how model error is traditionally handled in the EKF. Provided an observation operator example.
{{< tdclose >}}
{{< tdopen >}}
Talagrand, O. "Assimilation of Observations, an Introduction." _Journal of the Meteorological Society of Japan_ 75, no. 1B (1997): 191-209.
{{< tdclose >}}
{{< tdopen >}}
Problem Set 4 out
{{< tdclose >}}

{{< trclose >}}
{{< tropen >}}
{{< tdopen >}}
20
{{< tdclose >}}
{{< tdopen >}}
Derived the Kalman (and Extended Kalman) filter using the maximum likelihood approach. Described the spectrum of filtering approaches (ranging from replacement to the BLUE). Using maximum likelihood, showed where 3d-Var comes from, and stressed that it is a different method for obtaining the same answer as the Kalman filter. Introduced 4d-Var (both the strong and weak model constraint form), and the incremental approach to 4d-Var minimization.
{{< tdclose >}}
{{< tdopen >}}

{{< tdclose >}}
{{< tdopen >}}

{{< tdclose >}}

{{< trclose >}}
{{< tropen >}}
{{< tdopen >}}
21
{{< tdclose >}}
{{< tdopen >}}
Introduced and described the concept of a model's adjoint, and discussed how it could be used in data assimilation, sensitivity studies, and singular vector construction. Returned to the Bayesian expression for fully nonlinear, probabilistic data assimilation and introduced the particle filter. Used particle filter PDF evolution ideas to motivate an ensemble approach to the extended Kalman filter, the EnKF.
{{< tdclose >}}
{{< tdopen >}}
Whitaker, J. S., and T. M. Hamill. "Ensemble Data Assimilation without Perturbed Observations." _Monthly Weather Review_ 130 (2002): 1913-1924.
{{< tdclose >}}
{{< tdopen >}}

{{< tdclose >}}

{{< trclose >}}
{{< tropen >}}
{{< tdopen >}}
22
{{< tdclose >}}
{{< tdopen >}}
Explained the Ensemble Kalman filter, and showed why it is necessary to perturb observations when ensemble members are updated. Introduced ensemble filters that do not require perturbed observations: the ensemble square root filter (EnSRF), the ensemble transform Kalman filter (ETKF), and the ensemble adjustment filter (EAF). Demonstrated that they all employ transformations to ensemble forecast perturbations in order to generate ensemble analysis perturbations. Demonstrated the implications of perturbed observations vs. transformed ensemble perturbations in linear and nonlinear situations.
{{< tdclose >}}
{{< tdopen >}}
Hamill, Thomas M. "Ensemble-based Data Assimilation: A Review." University of Colorado and NOAA-CIRES Climate Diagnostics Center, Boulder, Colorado, USA, 14 February 2003.
{{< tdclose >}}
{{< tdopen >}}
Problem Set 4 due
{{< tdclose >}}

{{< trclose >}}

{{< tableclose >}}