---
layout: page
title: moving plots
subtitle: for the poster "MeV-GeV Counterparts to Fast Radio Bursts with VERITAS"
---


### Angular dependence is minimal out to ~3 degrees

Here is what VERTIAS sees if it looks directly at the center of a wavefront coming from the zenith direction
<video width="100%" controls>
  <source src="{{ '/assets/video/N4E6W0_variance_timeseries.mp4' | relative_url }}" type="video/mp4">
  Your browser does not support the video tag.
</video>

the same wavefront coming 1.5 degrees tilted relative to VERITAS looks like this:

<video width="100%" controls>
  <source src="{{ '/assets/video/N4E6W1.5_variance_timeseries.mp4' | relative_url }}" type="video/mp4">
  Your browser does not support the video tag.
</video>

While these look very different visually, the camera-wide variance caused by each is roughly the same: 

<img src="{{ '/assets/img/variance_timeseries.png' | relative_url }}" alt="Image could not load: a plot of the average variance ~0.1 ADC counts^2 for 0 degrees and 1.5 degrees offset">

### Variance of a wavefront appears with the same geometry across four cameras, but different strengths

This is what VERITAS sees with all four of its cameras during a wavefront that lasts 500 microsseconds and contains 3 million photons, against a typical winter night sky:

<video width="100%" controls>
  <source src="{{ '/assets/video/camera_variance_frames_added.mp4' | relative_url }}" type="video/mp4">
  Your browser does not support the video tag.
</video>

This is a plot of the average variance over each camera for that same burst:
<img src="{{ '/assets/img/variance_timeseries_frames_added.png' | relative_url }}" alt="Image could not load: a plot of the average variance increasing during the wavefront relative to NSB">

You will likely notice that the fourth camera (labelled T3 in my simulations but reffered to as T4 in VERTIAS documentation) always appears brighter than the other three. This is because the telescope has the highest electonic gain of the four. 

An open question for my research is this: why does this higher relative gain does not also cause a higher relative signal? Is this a physically accurate result or a defect of the simulation? I am currently in communication with Nepomuk Otte, designer of the CARE software, about this issue

