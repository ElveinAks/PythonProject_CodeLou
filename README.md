# PythonProject_CodeLou

## Overview
The dataset was obtained from kaggle. This analysis is by no means an in-depth or detailed analysis, but is only a bit involved
with statistics terms and amateur hypothesizing.

## Objective
The objective here is to see the relationships (correlations) between the columns in the dataset, and to see if the value 
of the integrated profile determines which entry can be classified as a Pulsar, or if there is more to determining the 
classification of a data entry. Another objective is to see which value is the most common for the mean of the integrated profile,
along with seeing what kind of relationship exists between the mean of the integrated profile and the mean of the dm-snr curve.

## Methods
The method used to explore these questions is primarily visualization, but a SQL query was also used to answer one of the questions.
For the visualizations, matplotlib and seaborn were used, particularly scatter plots and a correlation heat map to answer the questions.

## Explanation of terms
<ul>
  <li>DM-SNR Curve: DM stands for 'Dispersion Measure', which increases as the distance from the Pulsars to
  the Earth increases and as electron density between the Pulsar and the Earth increases. SNR stands for 'Signal
  to Noise Ratio', which describes the strangth of a signal to random noise. This value is sensitive to the state
  of the equipment used to measure signals.</li>
  <li>Kurtosis is like a measure of how thick the tails are in the normal distribution.</li>
  <li>Skewness is a measure of where the mean is in relation to the median: if the mean is to the right of the median, then
  it's positive skew.</li>
  <li>A normal distribution is a bell-curve.</li>
</ul>

## Sources:
http://www.jb.man.ac.uk/distance/frontiers/pulsars/section4.html

https://www.kaggle.com/pavanraj159/predicting-a-pulsar-star
