## PhagoTrack - Automatic microscopy quantification of phagocyte responses
<img align="left" width="256" height="192" alt="PhagoTrack_onWhite_Shaded (1)" src="https://github.com/user-attachments/assets/9277d8b4-e64f-401e-937b-0c8902c1c826" />

PhagoTrack is an automated image analysis pipeline developed as a Fiji plugin or an executable python script to quantify phagocyte responses from fluorescence time-lapse microscopy. Using a custom trained StarDist model, PhagoTrack uses StarDist/Trackmate to segment phagocytes and target cells and generate independent "cell" tracks as per user-indicated fluorescent channels. By using relevant frame-wise measurements of the cell-track region-of-interests, the pipeline uses a coordinate-based approach for spatial overlap analysis to detect engulfment events.

<br clear="left"/>

## Workflow overview
<img width="4952" height="2732" alt="phagotrack workflow" src="https://github.com/user-attachments/assets/1d1f300e-3a14-4097-8c5d-d6d717f91aea" />

## Example of classified events
### 20x Magnification - High Content Imaging and visual annotation
<img width="1843" height="922" alt="Supplemental Video 2 - 20x classification" src="https://github.com/user-attachments/assets/aca609ed-aeb0-4add-b064-3f801ca6253a" />

### 40x magnification 
| Phagocytosis | Trogocytosis | Non-internalizing |
|:---:|:---:|:---:|
| <img width="250" alt="phagocytosis-40x" src="https://github.com/user-attachments/assets/a6436e51-37f4-4a66-bac3-24b981a9e1c0" /> | <img width="250" alt="trogocytosis-40x" src="https://github.com/user-attachments/assets/926b45d5-4d38-4710-a025-391af407ebde" /> | <img width="250" alt="NIC-40x" src="https://github.com/user-attachments/assets/68eaf5e0-2219-4273-9dd6-341d64662f4e" /> |
## Installation
### Fiji installation

## Authors 
This project was led by Rasool Khaef Panah in the group of Valentin Jaumouillé located in the Department of Molecular Biology and Biochemistry, Simon Fraser University in collaboration with Dr. Damon Poburko in the Department of Biomedical Physiology and Kinesiology. The plugin was developed by Rasool Khaef Panah along with additional training data from Mansehaj Kaur Sadhu.
