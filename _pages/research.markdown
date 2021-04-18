---
layout: single
title: Research
permalink: /research/
header:
  overlay_image: /assets/images/global-vgg.png
---

## Marine gravity recovery from satellite

<figure class="align-right">
  <img src="/assets/images/Sat-altimetry.png" style="width:250px;"/>
  <figcaption>Basic measurements of a satellite altimeter</figcaption>
</figure>

Prediction of marine gravity from satellite altimeter data is a process that emerged with the Seasat mission in the late 1970s. Essentially, the time-invariant height of the ocean surface relative to a reference ellipsoid is a signal related to the topography of the ocean floor (the bathymetry). Because the ocean surface (when the waves, tides, and currents are subtracted out) is a gravitational equipotential, "bumps" in the surface correspond to excess mass (gravity anomalies) on the ocean floor.

In the Topex lab, I help to process incoming data from active satellite altimeters which we compile to re-estimate the global gravity and vertical gravity gradient (VGG) grids. The most recent publication can be found [here](/files/Sandwell_et_al-2019.pdf).

**Work in Progress**: I will link to a more detailed description of the gravity recovery process with relevant code, etc...

In 2022, NASA will be launching the new SWOT satellite. This is a brand new type of satellite altimeter that will sense entire swaths of the sea surface rather than the single "ping" of nadir-looking altimeters. We will use the 1-day repeat data from the first 90 days of the mission to evaluate the short-wavelength accuracy and resolution of the data over sharp bathymetric features.

{% include figure image_path="/assets/images/global-faa.png" caption="The global marine free-air anomaly." %}{: .align-center}

## Marine tectonics
<figure class="align-right">
  <img src="/assets/images/SSPs.png" style="width:250px;"/>
  <figcaption>A seesaw propagator flanking the SE Indian Ridge</figcaption>
</figure>

The recovered gravity anomalies and VGG over the oceans reveal details of and provide context to ocean floor features that may be previously unexplored.

In early 2021, we published [*Marine vertical gravity gradients reveal the global distribution and tectonic significance of "seesaw" ridge propagation*](/files/Harper_et_al-2021.pdf) in JGR: Solid Earth. Seesaw propagators (SSPs) are a feature at the margins of plate tectonic theory where plates can't be modeled as rigid. We see w-shaped ridge-flanking scars along the mid-Atlantic and southeast-Indian ridges showing back-and-forth (seesaw) motion of ridge offsets. [Here](/files/SSPs-ridges.kmz) is a Google Earth kmz file with our digitized SSPs.

<br/>

## Global bathymetry
In the past, the Topex lab has produced global topography/bathymetry grids which combine shipboard echosounder measurements with predictions from satellite altimetry (e.g., Tozer et al., 2019; Becker et al., 2014). Currently, we're working to improve these products in a few different ways.

* Editing multibeam data with machine learning models

  Shipboard echosounder data is notoriously error-prone-- anyone who has been on a scientific cruise can attest to this. As a result, depth soundings must be "cleaned" by a human editor to remove bad pings and ensure quality in the data. Traditional quality control algorithms can flag lots of the erroneous pings and help ease the work load, but they are far from perfect.

  When we have compiled echosounder data in the past, there has always been a major time investment in editing to remove bad pings. But now, we can make use of those bad data. With this large set of flagged bathymetry, we use the machine learning technique of "boosting" to develop a model that will detect bad data with a higher accuracy than traditional flagging algorithms. *More to come soon.*

* Synthetic "high resolution" bathymetry

  The global bathymetry grids have differing degrees of precision depending on the spatial density of echosounder data. A well-mapped area may show finer details of the seafloor that are not available in areas only constrained by satellite gravity measurements. For modelling purposes, we might desire a model with more detail-- that's where synthetics come in.

  Using spatial properties of real bathymetry, we can generate instances of higher resolution bathymetry with the expected statistical properties of bathymetry in a given region. *More to come soon.*

***

# Older projects
## The 2002 Mw7.9 Denali, AK earthquake
At the University of Alaska Fairbanks, I worked with [Prof. Jeff Freymueller](https://freymuel.msu.domains/jeff.html) (now at Michigan State University). I developed coseismic and postseismic models of the 2002 Denali fault earthquake.

We haven't gotten around to publishing this research, but [here](/files/harper_MS_thesis.pdf) is my Master's thesis.


## 3D mechanical modeling of fault slip rates in the Los Angeles basin
As an undergraduate, I worked with [Prof. Scott Marshall](https://www.appstate.edu/~marshallst/) at Appalachian State University. We didn't published any research, but [here](/files/hugh_BS_thesis.pdf) is my undergraduate thesis.
