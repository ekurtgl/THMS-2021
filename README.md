# ASL Trigger Recognition in Mixed Activity/Signing Sequences for RF Sensor-Based User Interfaces

This repository contains the source code of the following paper:

E. Kurtoğlu, A. C. Gurbuz, E. A. Malaia, D. Griffin, C. Crawford and S. Z. Gurbuz, `"ASL Trigger Recognition in Mixed Activity/Signing Sequences for RF Sensor-Based User Interfaces,"` in IEEE Transactions on Human-Machine Systems, vol. 52, no. 4, pp. 699-712, Aug. 2022, doi: 10.1109/THMS.2021.3131675.

The dataset consists of 15 ASL signs and 3 human daily activities and it is available in [here](https://github.com/ci4r/ASL-Sequential-Dataset).  

While MATLAB scripts are used for raw data processing to generate `range-Doppler`, `range-Azimuth` maps and `micro-Doppler` spectrograms, Python scripts are used for classification.

`Python/create_dataset*.ipynb` files are used to read the created videos and images and save them as pickle or .hdf5 files.

`Python/Final baseline 2.ipynb` is the main classification script which implements the STA/LTA motion detector and the JD-MTML model explained in the paper.

### Cite as:

```bibtex
@ARTICLE{9660776,
  author={Kurtoğlu, Emre and Gurbuz, Ali C. and Malaia, Evie A. and Griffin, Darrin and Crawford, Chris and Gurbuz, Sevgi Z.},
  journal={IEEE Transactions on Human-Machine Systems}, 
  title={ASL Trigger Recognition in Mixed Activity/Signing Sequences for RF Sensor-Based User Interfaces}, 
  year={2022},
  volume={52},
  number={4},
  pages={699-712},
  keywords={Radio frequency;Sensors;Gesture recognition;Radar;Kinematics;Assistive technologies;Chirp;American sign language (ASL);gesture recognition;human-computer interaction;sign language;trigger detection;wake word},
  doi={10.1109/THMS.2021.3131675}}

```
