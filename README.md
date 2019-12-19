# Data-analysis
Simple example using python to analyse more than 600,000 data sets.

Firstly, the data points after the stretching force reaches its peak are discarded in order to reduce disruption of the noise at the end.

Secondly, a low pass filter is applied to smooth the raw data using third order polynomial function. The frequency of the data is reduced
by 800 times, resulting in 64 data points after applying the filter. 

Thirdly, we calculate the average of three repeated tests. 

Finally, force–displacement profiles are converted to stress–strain profiles 
