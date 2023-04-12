---
permalink: /software/
title: "Software"
excerpt: ""
author_profile: true
---

{% include base_path %}

# callsync

`callsync` is an R packaged developed by me. It has five main functions: (1) alignment and partitioning of drifting microphones using signal compression and cross correlation, (2) call detection using an amplitude envelope, (3) fine-scale alignment and call assignment across recordings using cross correlation and energy content, (4) fundamental frequency tracing and (5) analysis of the resulting traces and wav clips. To read the preprint describing its functions and testing it on a real data set go [here](https://www.biorxiv.org/content/10.1101/2023.02.07.527470v1). If you just want to install the package you can do so directly from CRAN or go to [this repository](https://github.com/simeonqs/callsync).

# ANIMAL-SPOT

ANIMAL-SPOT is a convolutional neural network developed by Christian Bergler and others. It has two main functions: (1) signal detections and (2) signal classification, and can be used for any animal species. To read the paper describing the functions and testing its performance on several species go [here](https://www.nature.com/articles/s41598-022-26429-y). If you just want to download the source code and user code go [here](https://github.com/ChristianBergler/ANIMAL-SPOT).

