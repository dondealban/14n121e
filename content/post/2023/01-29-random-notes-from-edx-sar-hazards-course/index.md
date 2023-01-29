---
authors:
- admin
categories:
- Research
date: "2023-01-29T00:00:00Z"
draft: false
featured: false
image:
  caption: ""
  focal_point: ""
  placement: 3
  preview_only: false
lastmod: "2023-01-29T12:00:00Z"
projects:
subtitle:
summary:
tags:
- ALOS PALSAR
- ALOS-2 PALSAR-2
- DInSAR
- #GoldenAgeOfSAR
- InSAR
- MOOC
- SAR
title: 'Random notes from edX Synthetic Aperture Radar: Hazards course.'
---
I thought I'd put together some random notes while learning from the [Synthetic Aperture Radar: Hazards course](https://courses.edx.org/courses/course-v1:AlaskaX+SAR-401+3T2020/89e9f34aa5d14551915c89e8443a8f6c/) taught by Dr Franz Meyer, the Chief Scientist of the Alaska Satellite Facility and Professor of Radar Remote Sensing at the Geophysical Institute at University of Alaska Fairbanks, through edX's massive open online course platform.

My main motivation for enrolling in the online course was to refresh my foundational knowledge and understanding of synthetic aperture radar (SAR), and enhance my skills on utilising more advanced techniques including interferometric SAR (InSAR), polarimetric interferometric SAR (PolInSAR), and SAR tomography—all of which are quite very exciting technologies to employ in my research.

To anyone else other than myself reading this post however, these notes might not really make any cohesive sense but I suppose each snippet would still be a valuable nugget of information for learning about synthetic aperture radar.

<div align="center">-oOo-</div><br/>

### Module 2: Introduction to Synthetic Aperture Radar Remote Sensing.

#### On the properties of microwaves.

{{< figure src="microwave_spectrum-s.jpg" title="An image of the electromagnetic spectrum that explains the weather-independence of radar imaging." >}}

This is a fantastic graphic showing the "radar window" where imaging radar systems utilise a window of high atmospheric transmittance to achieve surface imaging capabilities even during cloud cover. In contrast, notice the variable atmospheric opacities for the visible/optical and shorter infrared wavelengths, and the poor transmittance thereof of other parts of the EM spectrum such as the gamma/x/ultraviolet rays, most of the longer infrared signals, and long-wavelength radio waves. The image would be a good addition in my slidedeck for future talks on the topic too. <br/>

#### On geometric distortions in SAR images.

{{< figure src="foreshortening-layover-shadow.png" title="The typical geometric distortions in SAR images due to the oblique observation geometry inherent to all imaging radar systems." >}}

{{< figure src="match-image-distortions-to-sar-samples.png" title="Well, it seems I did well on visually matching the image distortions to the respective SAR image samples." >}}
