# A Priority Map for Vision-and-Language Navigation with Trajectory Plans and Feature-Location Cues

This repository contains source code and sample data for the priority map module (PM-VLN) and feature-location framework (FL<sub>PM</sub>) introduced in the paper "A Priority Map for Vision-and-Language Navigation with Trajectory Plans and Feature-Location Cues". Our PM-VLN module is inspired by priority maps - a mechanism described in neurophysiological research that modulates sensory processing on cues from the environment. We propose a computational implementation of cross-modal prioritisation that combines high-level trajectory estimation and feature-level localisation to optimise the prediction of actions for Vision-and-Language Navigation (VLN). The PM-VLN is integrated into the FL<sub>PM</sub> to enhance the performance a cross-modal transformer-based main model in VLN. In experiments, the FL<sub>PM</sub> with PM-VLN doubles the task completion rates of standalone transformers on the Touchdown benchmark.



![system](/fig_flpm_git.png)

### Requirements
Python version >= 3.7

PyTorch version >= 1.8.0

``` bash
# clone the repository
git clone https://github.com/JasonArmitage-res/PM-VLN.git
cd PM-VLN
pip install -r requirements.txt
```

### Steps to Run the Framework
This repository contains source code and data samples to run the FL<sub>PM</sub> framework with integrated PM-VLN. We tested and ran the code presented here on a single Tesla GPU with 16GB of RAM.   

### Data Samples
We present in this repository samples from the 3 following datasets:
 - VLN-Touchdown-sample - samples adapted from the Touchdown and StreetLearn datasets.
 - MC-10 - JSON file and 5 sample images for entities.
 - TR-NY-PIT-central - JSON and 5 sample images of path traces.
