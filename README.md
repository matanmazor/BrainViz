## BrainViz
[![Build Status](https://travis-ci.org/uwescience/shablona.svg?branch=master)](https://travis-ci.org/uwescience/shablona) [![Binder](https://mybinder.org/badge_logo.svg)](https://mybinder.org/v2/gh/matanmazor/BrainViz/master?filepath=scripts%2FNeuropythyTransparentBrain.ipynb)


This is a tool to create an interactive 3D brain in your browser. You can select points (or electrodes) on the brain to look at activity from those points. A dropdown menu will allow you to select the stimulus for which you are plotting a response.

## input 
Example Brain image is from https://zenodo.org/record/996814#.XU29UZNKi_s for 3D visualization. ECOG data is synthetic for demonstration, that is from a hf5 format file containing:
data['/ecog/condition1'] = numpy array of dim [elecs x time]
data['/ecog/condition2'] = numpy array of dim [elecs x time]
data['/times'] = vector of times

## interactive visualization
The electrodes of interest can be selected by mouse or dropdown menue. There is also a dropdown menue to select conditions. 

## output
3D brain with electrodes overlay. The color of selected electrodes changes. 
