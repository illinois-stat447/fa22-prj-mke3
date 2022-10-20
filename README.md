# fa22-prj-mke3

## Background
My lab primarily works with fMRI neuroimaging data, examing blood flow in the brain as a proxy for neural activity. Our group focuses on intrinsic functional connectivity, looking at various large-scale brain networks that allow for efficient and effective communication across brain regions. My personal work is on an experiment in which the subject has several "threshold" stimuli, in which the stimulus itself is titrated to be exactly 50% accuracy for that particular subject, and a long variable inter-stimulus interval to mimic the closest thing we can have to within-task "rest". 

## Proposed plan
There are several options for what processing software to use when analyzing fMRI data, most notably SPM in MATLAB and a toolkit that primarily uses FSL in Python, but both of these tools have packages in R. As luck would have it, we are just getting the subject number needed to do analyses on the data, so why not do it here and create a pipeline within R? I will take fMRI data from my experiment, extract time period prior to different stimulus type, and run basic statistical analysis (GLMs, predictive modeling if time permits) to see if there is a different in pre-stimulus neural activity between "hits" and "misses".
