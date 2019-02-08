# JointModelsClinicalPractice_OsloPresentation

**Assessing Risk Indicators in Clinical Practice with Joint Models of Longitudinal and Time-to-Event Data**

Studies in life course epidemiology often involve different types of outcomes and exposures being collected on individuals, 
who are followed over time. The data include longitudinally measured responses (e.g., biomarkers), and the time until an event 
of interest occurs (e.g., death, intervention). In many epidemiologic studies, these outcomes are separately analysed, although 
it may be of public health interest to study their association while including key exposures. To that end, it is desirable to 
employ methods that examine the associations of exposures with longitudinal measurement outcomes simultaneously. This method is 
referred in the statistical literature as joint modelling of longitudinal and survival data. The idea behind these models is 
usually to couple linear mixed effects models for longitudinal measurement outcomes and Cox models for censored survival outcomes. 
Extensions of these models, motivated by real-life applications, will be furthermore presented. 

*Bayesian Variable Selection with Joint Modeling of Longitudinal and Survival Outcomes Assuming Different Association Structures:*
In common practice, it is assumed that the underlying value of the longitudinal outcome is associated with the survival outcome. 
However, in some cases different characteristics of the patients' longitudinal profiles may influence the hazard, such as how fast 
the biomarker progresses. The choice of the functional form is important and needs to be investigated since it could influence the 
results. The motivation comes from a dataset consisting of patients with a chronic liver disease where it is important to investigate 
which characteristics of the biomarkers influence survival. We use a variable selection method under the Bayesian framework, and 
propose a joint model including different association structures. In particular, we assume informative priors for the regression 
coefficients that correspond to the terms of the longitudinal process. We investigate different Bayesian priors, such as Bayesian 
lasso and ridge regression, that shrink small effects to zero. 

*Bayesian Joint Models of Longitudinal and Survival Outcomes with Time-Varying Effects using P-splines:*
One of the characteristics of standard joint models is that they assume a constant regression coefficient for the effect of the 
longitudinal covariates. However, in some cases this may be a restrictive assumption. The motivation comes from a study which 
includes patients who received a human tissue valve in the aortic position. These patients are followed prospectively over time by 
standardized echocardiographic assessment of valve function. Since the human tissue degenerates, the main focus is to investigate 
whether the effect of the echocardiographic measures on survival varies in time. Specifically, we develop a Bayesian joint model 
that allows for time-varying effects for the coefficients that link the longitudinal and the survival processes by assuming P-splines. 
