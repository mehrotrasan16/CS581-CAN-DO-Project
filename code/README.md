# Our Code

We've worked on different stages of a machine learning problem in different jupyter notebooks. In this folder you will find scripts and notebooks illustrating our work in:
1. Data Preparation
2. Data Exploration
3. LSTM Experiments
4. TCN Experiments

## Data Preparation

Why are we doing this?
* This dataset is real CAN logs 
* The given format is not right for direct input to models.
* all ml experiments start with cleaning the dataset
* we plan to spend 80% of time understanding the data vs 20% actually modelling and predicting, because of the complexity of the networks and the problem that we're working with.

## Data Exploration

Why are we doing this?
* To check for biases
* to understand the data better
* to see if we can add labels ourselves for supervised training
* to see if we can merge the datasets for better understanding of data ( quote Dos 50:50 split and Attack free sets single label problem.)

* Also hinting that this dataset does not seem tuned for ml applications, since all the datasets are on different timestamp axes(differently collected) 
* So merging requires tossing the timestamp field i.e. temporality of the dataset
* but from our below analysis and reading and discussion, we cannot tell that timestamp is especially helpful and we plan to experiment the effect of the presence and absence of the 'Timestamp' field.
