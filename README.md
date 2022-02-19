# NN-heart-beat-classification
This notebook features the progressive training of a feed-forward neural network to classify 5 different classes of heart arrhythmias.

## Data Source
ECG Heartbeat Categorization Dataset: https://www.kaggle.com/shayanfazeli/heartbeat

This dataset contains two collections of heartbeat signals:
1.	MIT-BIH Arrhythmia Dataset
  - 109446 examples
  -	5 categories: ['N': 0, 'S': 1, 'V': 2, 'F': 3, 'Q': 4]
    -	0 = normal (N)
    -	1 = supraventricular ectopic beat (SVEB) … extra heartbeat originating in the higher chamber of the heart (atria)
    - 2 = ventricular ectopic beat (VEB) … extra heartbeat originating in the lower chamber of the heart
    - 3 = fusion beat (F) …  when a supraventricular and a ventricular impulse coincide to produce a hybrid complex.
    - 4 = unknown beat (Q)
2.	PTB Diagnostic ECG Database _(Unused in this project)_
  - 14552 examples
  - 2 categories (normal vs. abnormal)
