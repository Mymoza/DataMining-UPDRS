# DataMining-UPDRS
This repo is for MTI830 - Data mining class followed in Summer 2020



## Dataset

A Tsanas, MA Little, PE McSharry, LO Ramig (2009)'Accurate telemonitoring of Parkinson's disease progression by non-invasive speech tests',IEEE Transactions on Biomedical Engineering 

Downloaded from [Data.world](https://data.world/uci/parkinsons-telemonitoring/workspace/project-summary?agentid=uci&datasetid=parkinsons-telemonitoring)

### Attribute information 

subject# - Integer that uniquely identifies each subject
age - Subject age
sex - Subject gender '0' - male, '1' - female
test_time - Time since recruitment into the trial. The integer part is the number of days since recruitment.
motor_UPDRS - Clinician's motor UPDRS score, linearly interpolated
total_UPDRS - Clinician's total UPDRS score, linearly interpolated
Jitter(%),Jitter(Abs),Jitter:RAP,Jitter:PPQ5,Jitter:DDP - Several measures of variation in fundamental frequency
Shimmer,Shimmer(dB),Shimmer:APQ3,Shimmer:APQ5,Shimmer:APQ11,Shimmer:DDA - Several measures of variation in amplitude
NHR,HNR - Two measures of ratio of noise to tonal components in the voice
RPDE - A nonlinear dynamical complexity measure
DFA - Signal fractal scaling exponent
PPE - A nonlinear measure of fundamental frequency variation
