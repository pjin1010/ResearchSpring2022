# Research Spring 2022
Done under supervision of Professor Michael K. Tippett and Professor Chia-Ying Lee

#### Overview
Hurricane and Tropical Cyclone/Storm models/plots of precipitation with the eventual goal of risk assessment of these storms via consideration of precipitation, wind, and storm surge (see https://github.com/pjin1010/surge-examples/tree/master/Gustav).


#### Contents
(HWRFplots.ipynb)
1. Polar plots of storm precipitation at each given hour of a forecast
2. Superimposed polar plots of storm precipiation (all relative to the same center — i.e. ignoring storm track)
3. Plots of average storm-centered rainfall rate as a function of radius (conditional on categories of wind speed)
4. Superimposed plots of storm precipiation considering storm track (i.e. moving storm center), note: here we have a choice of interpolator according to available computing power; for our purposes, we use NearestNDInterpolator.
5. Comparisons of different forecasts of the same storm (via visual consideration of superimposed polar plots of storm precipitation)

(finalSpring2022.ipynb)
1. Plots of central pressure vs. wind speed (both for storm invest93s, and all storms)
2. Analysis of storm batsirai08s (all forecast tracks, central pressure as a function of forecast target date, average storm-centered rainfall rate as a function of radius, accumulated rainfall on lat-lon plot)
