# Project Overview 
This project investigates the relationship between aperiodic neural activity and sleep microarchitecture, with a focus on K-complexes (KCs) and sleep spindles (SS) during NREM sleep. Both electrophysiological events have been implicated in memory consolidation, sensory gating, and sleep maintenance. However, substantial variability exists in how these events are detected. 

The primary goal of this project is to examine whether variability in KC and SS detection is partially explained by underlying aperiodic dynamics. 

# Conceptual Motivation
Recent work has suggested that sharp-wave ripple-like events may primarily reflect broadband aperiodic fluctuations rather than true oscillatory bursts. This raises the possibility that other sleep microevents may be influenced by underlying spectral slope changes. 

To address this, we incorporate sensitivity analyses examining whether detection outcomes persist after controlling for aperiodic parameters and whether algorithmic detections are disproportionately driven by broadband spectral shifts. 

# Data 
Data were obtained from the SS2 subset of the Montreal Archive of Sleep Studies (MASS), consisting of whole-night polysomnography (PSG) recordings from 19 healhty adults. Expert-annotated KC and SSs are included. 

The MASS dataset is publicly available for research purposes and can be accessed through the official project website:
(https://borealisdata.ca/dataverse/MASS)

Researchers must request access and agree to the dataset’s terms of use prior to downloading.

# Ethical Considerations 
Although MASS is a de-identified public dataset, all analyses conducted in this project were performed under institutional research oversight. An IRB determination was obtained confirming that the use of this de-identified archival dataset qualifies as non-human subjects research. All data handling procedures comply with institutional and ethical guidelines for secondary data analysis.

No personally identifiable information (PII) is included in this repository.

# Analysis Details 
To determine whether KC and SS detections reflect true oscillatory events or may be partially driven by broadband spectral structure, we conducted simulation-based sensitivity analyses. 

Specifcally, 
- Simulated time series were generateed containing purely aperiodic structure with no embedded oscillatory bursts.
- Published KC and SS detection algoritms were applied to both simulated and real EEG data.

These analyses allow us to test whether certain waveform detections could emerge from underlying aperiodic fluctuations alone, rather than reflecting discrete oscillatory phenomena. Additionally, we examine whether variability in detection across algroithms is associated with differences in aperiodic parameters, helping determine whether broadband dynamics systematically influence event detectoin probability. 

# Repository Structure 



# Overall Aim 
The long-term goal of this project is to clarify how aperiodic neural dynamics shape sleep microarchitecture and to establish a framework linking cortical aperiodic dynamics, sleep-stage physiology, and memory-relevant electrophysiological events.
