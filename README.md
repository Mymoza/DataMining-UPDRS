# DataMining-UPDRS
This repo is for MTI830 - Data mining class followed in Summer 2020

Marie-Philippe Gill & Félix Blier

## Abstract

Although the Unified Parkinson's Disease Rating Scale (UPDRS) is the de-facto gold standard to evaluate the progression of Parkinson's disease (PD) in patients, it is constrained to just providing a snapshot for how the patient feels on a given day. In this work, we propose alternative methods to help clinicians and patients gauge this progression and make decisions. Our method relies on using 16 vocal (or speech) features recorded on at-home devices over six months and worn by 42 subjects to predict UPDRS scores. The subjects enrolled were newly diagnosed and not taking any medication. The objective is to understand and analyze the course of PD, through techniques such as observing the central tendency measures, box plots, etc. To study the feasibility of using speech features from sustained vowels, we use a Support Vector Regressor (SVR) and a multilayer perceptron to predict the motor and total UPDRS scores. Preliminary results show that this method of using sustained vowels can provide promising results to assess the severity of PD symptoms. We observe that the condition of 15 subjects improve over the time of the 6-month study, suggesting that the activities performed daily with the device served as therapy. Furthermore, we find that four different groups of patients naturally emerge on clustering the speech features after dimensionality reduction using linear discriminant analysis (LDA). Further analysis could be interesting to obtain insights about the relation between the different groups.

[Read full article about this project](https://github.com/Mymoza/DataMining-UPDRS/blob/master/MTI830-MPGILL-FBLIER.pdf)

## Dataset

A Tsanas, MA Little, PE McSharry, LO Ramig (2009). Accurate telemonitoring of Parkinson's disease progression by non-invasive speech tests, IEEE Transactions on Biomedical Engineering

Downloaded from [Data.world](https://data.world/uci/parkinsons-telemonitoring/workspace/project-summary?agentid=uci&datasetid=parkinsons-telemonitoring)

### Attribute information 

`subject#` - Integer that uniquely identifies each subject

`age` - Subject age

`sex` - Subject gender '0' - male, '1' - female

`test_time` - Time since recruitment into the trial. The integer part is the number of days since recruitment.

`motor_UPDRS` - Clinician's motor UPDRS score, linearly interpolated

`total_UPDRS` - Clinician's total UPDRS score, linearly interpolated

`Jitter(%)`,`Jitter(Abs)`,`Jitter:RAP`,`Jitter:PPQ5`,`Jitter:DDP` - Several measures of variation in fundamental frequency

`Shimmer`,`Shimmer(dB)`,`Shimmer:APQ3`,`Shimmer:APQ5`,`Shimmer:APQ11`,`Shimmer:DDA` - Several measures of variation in amplitude

`NHR`,`HNR` - Two measures of ratio of noise to tonal components in the voice

`RPDE` - A nonlinear dynamical complexity measure

`DFA` - Signal fractal scaling exponent

`PPE` - A nonlinear measure of fundamental frequency variation
