# Grab-Estimated-Time-of-Arrival-analysis-and-improvement

## Problem
Grab Holdings Inc., commonly known as Grab, is a Southeast Asian technology company headquartered in Singapore and Indonesia. Much of their business is centred around transporting people and food from place to place. As most online delivery and transportation apps do, the Grab application provides an Estimated Time of Arrival (ETA) to their customers about the arrival of their products or services. 

However, recently there has been a growing number of complains about inaccurate ETAs around Jakarta, Indonesia. As a result, this analysis seeks to find possible causes of this inaccuracy by analysing differences between within and outside of Jakarta.

For this analysis, the Grab-Posisi dataset<sup>[1](https://engineering.grab.com/grab-posisi)</sup>, Southeast Asia’s First Comprehensive GPS Trajectory Dataset, will be used.

## Motivation behind a rural vs urban analysis of Jakarta
The main motivation behind this is as Grab uses average values of speed and ETA to predict ETAs of vehicles in and around Jakarta. However, these values would be skewed by values from within the city.

This would then result in inaccurate ETAs outside the city. This is inline with Grab's problem of a substantial minority complaining about inaacurate ETAs. Through my analysis, I suggest that the ETAs outside of the cities are underestimated. This underestimation is driven by differences in speeds and GPS accuracy within and outside Jakarta.

## Findings
You can see the findings and conclusions within the [notebook](https://colab.research.google.com/github/jjasim/Grab-Estimated-Time-of-Arrival-analysis-and-improvement/blob/main/Analysis%20of%20Grab%20Posisi%20Dataset%20to%20improve%20ETA.ipynb#scrollTo=iWMfR8rO7Ixc).

## References
1. Huang, X., Yin, Y., Lim, S., Wang, G., Hu, B., Varadarajan, J. & Zimmermann, R. (2019, November). Grab-Posisi: An Extensive Real-Life GPS Trajectory Dataset in Southeast Asia. In Proceedings of the 3rd ACM SIGSPATIAL International Workshop on Prediction of Human Mobility (pp. 1-10). DOI: https://doi.org/10.1145/3356995.3364536
