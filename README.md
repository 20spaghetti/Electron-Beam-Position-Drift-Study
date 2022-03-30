﻿# Electron-Beam-Position-Drift-Study

The electron beam in the Australian Synchrotron is as narrow as a human hair (322.9 micrometers). It orbits inside a vacuum chamber, following the 215m circular tube. The narrow cross section of the vacuum tube is only 6.4mm wide in some places, which is why the beam is programmatically constrained to a 1mm radius window transverse to it's orbital path. Beam stability within this window is important for many reasons including, instrumentation sensitivity, keeping radiation levels low and enabling consistent x-ray flux for our beamline research stations.

The accelerator is made up of materials such as stainless steel and ceramics which are sensitive to thermal expansion, while coaxial cable (used for signal transfer along very long routes) is sensitive to moisture. Additionally, it is unknown whether the beam position monitoring (BPM) instrumentation is climate sensitive. So it is understandable that small changes in environmental conditions can cause either the appearance of, or real shifts in the beam position relative to the BPMs.

The purpose of this analysis is to take existing data and learn as much as possible about the environmental cause (temperature vs humidity) and location (vacuum chamber vs coaxial cables vs signal processing instrumentation) which is causing the beam to drift. Particularly, the question that I'm looking to answer is whether there is clear evidence to suggest that the electron beam can be further stabilised by adding climate control to the server racks which house the BPM instrumentation, as this is considered to be relatively cheap and achievable solution.
