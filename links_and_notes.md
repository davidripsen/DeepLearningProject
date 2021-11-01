# Links

## Synopsis
 https://docs.google.com/document/d/1Kv2oJFXl1sun8ImcSSIqaj1Ppg_PvurGyAZWsT6z4-Y/edit?usp=sharing

## zoom 
https://dtudk.zoom.us/j/69875410401#success

## slack
https://app.slack.com/client/T02BRU50ZQD/C02H8EXNVB8

## Blog posts

https://curiousily.com/posts/credit-card-fraud-detection-using-autoencoders-in-keras/


# Meeting notes
## Milena meetings notes no.1
sequence data
1 sample data 100 meter sequence.
not independent
sample, assume independence.

real data, errors, bigger error due to gps 30 meter, in between 100 meter sections.

dense neural network not good. autocorrelation, oscilation. 

neglegting sample correlation.

try dense not good.

lstm. recurrent neural network.

varying length because of speed.

acceleration z, and speed.

training example by example. problem in 1 batch they must have equal length. pad the sequence. two sequences as input perhaps.

interpolation. upsampling. instead of padding.

take all normal samples. define less than 4.5 rr mean. good section.

autoencoder map input to itself. one sequence, reconstruct sequence. optimize size of latent representation, hyperparameter.

anomaly really bad road. detect as anomaly, unsupervised. train on normal samples.
autoencode output is sequence.

develop model that reconstruct normal sequence well, on all good data. reconstruction error is squared distance.

anomaly large error. 

test on both, plot. threshhold for.

4.5 zero above 1. binary. true value 0/1. be able to say if good and bad.

mean value vs reconstruction error as baseline.


LSTM, or gate recurrent unit. pytorch. try first with one gated unit.
