# A Priority Map for Vision-and-Language Navigation with Trajectory Plans and Feature-Location Cues

This repository contains source code and sample data for the priority map module (PM-VLN) and feature-location framework (FL<sub>PM</sub>) introduced in the paper "A Priority Map for Vision-and-Language Navigation with Trajectory Plans and Feature-Location Cues". Our PM-VLN module is inspired by priority maps - a mechanism described in neurophysiological research that modulates sensory processing on cues from the environment. We propose a computational implementation of cross-modal prioritisation that combines high-level trajectory estimation and feature-level localisation to optimise the prediction of actions for Vision-and-Language Navigation (VLN). The PM-VLN is integrated into the FL<sub>PM</sub> to enhance the performance a cross-modal transformer-based main model in VLN. In experiments, the FL<sub>PM</sub> with PM-VLN doubles the task completion rates of standalone transformers on the Touchdown benchmark.

**PM-VLN module in the FL\textsubscript{PM} Framework**

![system](/fig_flpm_git.png)
