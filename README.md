# A Data-driven Machine Learning approach to predicting Stacking Fault Energy in Austenitic Steels

This repository is the supplemental data and code for the journal paper titled above. This paper is a description of our research to accomplish a materials discovery task using the techniques and algorithms in machine learning. The task at hand is to predict the SFE of any given untested austenitic steel composition, thereby aiding alloy design of austenitic steels with a requisite mechanical deformation behavior.

For this task, we collect all data available in literature on experimental determination of SFE for austenitic steels and then use machine learning algorithms for prediction of SFE. Essentially thus this a materials informatics or data science approach to prediction where we try to model a lower, workable representation of the composition-SFE relationship relying on soft, statistical modeling because the true, higher representation is too expensive to model or unrealistic to work out with the current knowledge.

The repository has the the original raw data collected from all research papers as well as the final transformed data used for the machine learning task. It also has the code for prediction which is written in Python and is put in an IPython notebook for easy of viewing and editing.

