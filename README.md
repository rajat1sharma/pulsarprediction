# pulsarprediction
A Machine Learning Project to predict: whether star is pulsar or not (1 means star is pulsar and 0 means star is not pulsar)

Dataset Description
Pulsars are a rare type of Neutron star that produce radio
emission detectable here on Earth. They are of considerable scientific
interest as probes of space-time, the inter-stellar medium, and states
of matter.
As pulsars rotate, their emission beam sweeps across the sky,
and when this crosses our line of sight, produces a detectable pattern
of broadband radio emission. As pulsars rotate rapidly, this pattern
repeats periodically. Thus, pulsar search involves looking for periodic
radio signals with large radio telescopes.
Each pulsar produces a slightly different emission pattern,
which varies slightly with each rotation. Thus, a potential signal 
detection known as a 'candidate', is averaged over many rotations of
the pulsar, as determined by the length of an observation.
Machine learning tools are now being used to automatically
label pulsar candidates to facilitate rapid analysis. Classification
systems in particular are being widely adopted.
Each candidate in the dataset(row) is described by 8 continuous
variables. The first four are simple statistics obtained from the
integrated pulse profile (folded profile). This is an array of continuous
variables that describe a longitude-resolved version of the signal that
has been averaged in both time and frequency. The remaining four
variables are similarly obtained from the DM-SNR curve. These are
summarized below:
1. Mean of the integrated profile. (Mean_Profile)
2. Standard deviation of the integrated profile. (SD_Profile)
3. Excess kurtosis of the integrated profile.(Excess_kurtosis_Profile)
4. Skewness of the integrated profile. (Skewness_Profile)
5. Mean of the DM-SNR curve. (Mean_Curve)
6. Standard deviation of the DM-SNR curve. (SD_Curve)
7. Excess kurtosis of the DM-SNR curve. (Excess_kurtosis_Curve)
8. Skewness of the DM-SNR curve. (Skewness_Curve)
To predict: whether star is pulsar or not (1 means star is pulsar and 0
means star is not pulsar)
The Training Dataset contains 12528 instances and Test Dataset
contains 5370 examples.
