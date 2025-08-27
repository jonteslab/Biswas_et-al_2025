# Biswas_et-al_2025
Summary Data

Matlab files containing traces, trial averaged traces and neural modes

each data file Data-xxxx-xx.mat contains the following:

  data = N (neurons) x T (time) calcium traces for visually responsive neurons
  
  trial = N (neurons) x T (time) x 3 calcium traces divided into the three trials
  
  trial_avg = N (neurons) x T (time) trial averages (average of data in trial)
  
  L_trial = k (modes) x T (time) x 3, neural modes calculated for each trial
  
  L_avg = k (modes) x T (time), neural modes generated from trial averaged data.

a summary .mat file is provided with cell arrays for the trial averaged calcium traces
and the neural modes generated from these trial averages.  Each cell contains the data
from one larva.
