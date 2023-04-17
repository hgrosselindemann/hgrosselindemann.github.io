---
layout: archive
title: "Research"
permalink: /research/
author_profile: true
---

# Marine Heatwaves

I have investigated marine heatwaves and their depth structure on the Northeast US continental shelf using a high resolution ocean model (VIKING20X, nemo-configuration). I validated the model against satellite surface measurements as well as against a long-term temperature and velocity transect across the gulf stream path. This ensured us that we can rely on the model output to do analysis about the regional ocean dynamics. Marine heatwaves have been detected and  investigated about their spatial and temporal characteristics with a focus on the vertical structure. We found various depth structures, with some heatwaves not having a surface signal while large anomalies at depth. The highest anomalies were found at depth at the shelf break with up to $7\text{\textdegree}C$. These events could be linked to warm core rings of the Gulf Stream. This shows the importance of the local dynamics for marine heatwave formation. More information can be found in Grosselindemann and Ryan et al. 2022 (Publications).

# Eddy Tracking

I applied an eddy tracking algorithm to high-resolution model data in the Gulf Stream region. The used algorithm was the pyeddytracker, which uses an SSH-contour approach combined with geostrophic velocities. The goal was to compare the models ability to resolve mesoscale eddies to AVISO satellite altimetry. AVISO provides an eddy tracking product based on the same algorithm. The main outcome was that the resolution in AVISO is too low to properly detect eddies which led to oversized and weird structures. The algorithm itself is a good tool to detect and track eddies in model data with high enough resolution.

# Radar Surface Currents

I looked at surface current data around Taiwan based on CODAR high-frequency radar measurments. The focus was on their structure and spatio-temporal variability as well as the relation to the windfield and satellite-based geostrophic velocities. I applied spectral analysis and statistical approaches like EOF analysis, vector-cross correlation and coherence. Tides are very present oround the whole island, while the dominating frequency varies regionally between diurnal and semidiurnal. The seasonal varying monsoon winds have a strong forcing in the Taiwan Strait and lead to current reversals. The eastern side is dominated by Kuroshio Current all year round.

# Lagrangian Particle Tracking

I will apply the lagrangian particle tracking algorithm, oceanparcels, to a multi-centenniel high-resolution climate model to investigate the importance of Agulhas Leakage transport for the AMOC and the global overturning circulation.
