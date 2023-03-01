# Tuning-Adam-for-NLP-tasks
Tuning Adam for NLP tasks (two datasets of GLUE: MRPC and STS-B)

We split the dataset into five different splits maintaining the class distribution for each task, so as to estimate the generalization performance of each optimizer and for each task. For each optimizer we ran 30 trials of different combinations of hyperparameter values selected by the optuna framework. 
