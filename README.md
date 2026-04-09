# MazeSick Dataset: An Open-Source VR Cybersickness Dataset for Deep Learning-Based Detection and Mitigation

<p align="center">
  <img src="https://github.com/user-attachments/assets/1991af37-1492-4c54-8385-ee8c25963359" alt="Maze Environment" width="1000">
</p>

**MazeSick** is an open-source dataset collected to support training and evaluation of cybersickness prediction models in immersive virtual reality. Participants navigated virtual mazes using smooth locomotion and performed coin collection tasks, with continuous cybersickness severity ratings and eye/head tracking data recorded throughout.

## Table of Contents
* [Introduction](#introduction)
* [Participants](#participants)
* [Dataset Access](#dataset-access)
* [Virtual Environment](#virtual-environment)
* [Study Tasks](#study-tasks)
* [Apparatus](#apparatus)
* [Procedure](#procedure)
* [Data Collection](#data-collection)
* [RelaxVR Demo](#relaxvr-demo)
* [Citation](#citation)
* [Contacts](#contacts)
* [License](#license)
* [Acknowledgements](#acknowledgements)

---

## Introduction

We collected the MazeSick dataset while participants navigated virtual mazes using a smooth locomotion technique (via controller) and performed coin collection tasks. The dataset was developed to facilitate the training of cybersickness prediction models for the [RelaxVR]([https://ieeexplore.ieee.org/document/10908054](https://ieeexplore.ieee.org/document/10985746)) framework and is open-sourced to support further research in the cybersickness and VR community.

---

## Participants

We recruited 60 participants (39 M, 21 F) from the local area. The mean age was 23.6 years (SD = 3.21). Participants came from various demographic backgrounds. Thirty-four of the sixty had prior VR experience, while the remaining 26 had none.

---

## Dataset Access

To request access to the MazeSick dataset:

1. Fill out the request form: **[MazeSick Dataset Access Form](https://forms.gle/jvbiqP87az2xSJdm7)**
2. Send an email to [hoquek@missouri.edu](mailto:hoquek@missouri.edu).

---

## Citation

If this dataset is useful for your work, please cite our paper:

<div class="highlight highlight-text-bibtex"><pre>
@ARTICLE{10985746,
  author={Kumar Kundu, Ripan and Anuarul Hoque, Khaza},
  journal={IEEE Access}, 
  title={RelaxVR: Cybersickness Reduction in Immersive Virtual Reality Through Explainable AI and Large Language Models}, 
  year={2025},
  volume={13},
  number={},
  pages={84689-84712},
  keywords={Cybersickness;Gaze tracking;Solid modeling;Real-time systems;Heart rate;Explainable AI;Engines;Feature extraction;Pupils;Large language models;Cybersickness;explainable AI;virtual reality;large language model},
  doi={10.1109/ACCESS.2025.3566958}}
</pre></div>

---

## Virtual Environment

The virtual environment was a Dungeon-style maze created using Unity and OpenVR, featuring brick walls, brick platforms, and an open roof with an orange sky. The maze was structured as a 15 × 14 grid, with a trophy randomly spawned as the level objective. Reaching the trophy transports the user to the next randomly generated maze. Each maze is designed so that the user must explore at least half of it to ensure a consistent level of challenge.

The maze occupies 150 × 140 meters in Unity (Vector3(150, 1, 140)), with each grid platform measuring 10 × 10 meters. It is a single-player experience supporting both room-scale and smooth locomotion modes.

---

## Study Tasks

The primary task was maze navigation over a 12-minute session. Before starting, participants were briefly introduced to the procedure and requirements. They then completed a 2-minute virtual tutorial explaining the coin collection task, and were instructed to use the controller to navigate and collect coins.

Participants were asked to verbally report their discomfort on an FMS scale of 0–10 whenever a pre-recorded voice prompt was played at 30-second intervals during the VR simulation.

---

## Apparatus

- **HMD:** HTC Vive Pro Eye — 2880 × 1600 resolution per eye, 90 Hz refresh rate, 110° field of view
- **Audio:** Integrated Vive headphones
- **Workstation:** Intel Core i9 CPU, 128 GB RAM, Nvidia GeForce RTX 3090 GPU
- **Software:** Unity 2021.2.2f1, OpenVR SDK, HTC SRanipal SDK, Tobii HTC Vive Devkit

---

## Procedure

### Study Introduction

Participants were presented with the informed consent form and given an overview of study activities. They were informed of their right to withdraw at any time. After signing, participants completed a background questionnaire including an initial Simulator Sickness Questionnaire (SSQ), demographic questions, and disability-related questions. They were then equipped with the HTC Vive Pro Eye headset, physiological monitoring equipment, and controllers before proceeding to the tutorial.

### Tutorial

Prior to the 12-minute VR session, participants completed a brief 2-minute virtual tutorial explaining the tasks they would perform during the experiment.

---

## Data Collection

### Fast Motion Sickness Scale (FMS)

Participants rated their level of cybersickness on a scale of 1–10 at 30-second intervals, prompted by a pre-recorded voice cue during the VR simulation.

### Eye Tracking and Head Tracking

Using the HTC SRanipal SDK and Tobii eye tracking technology, we captured detailed eye-tracking metrics including pupil diameter and gaze direction, sampled at 60 Hz. Head-tracking data was also recorded throughout the session.

---

## RelaxVR Demo

- **Automatic mode:** [Watch on Google Drive](https://drive.google.com/file/d/1mzK4MxbSnwvOyPSL7omY_IU0VqXAoGr1/view?usp=sharing)
- **Interactive mode:** [Watch on Google Drive](https://drive.google.com/file/d/1DN3EUEXb9wSHj1EyFrFksQTMWoP2qqQT/view?usp=sharing)

---


## Contacts

Maintained by [Khaza Anuarul Hoque](mailto:hoquek@missouri.edu).

---

## License

MIT License

---

## Acknowledgements

- HTC SRanipal and Tobii HTC Vive Devkit for eye and head tracking support
- Unity and OpenVR for virtual environment development
- All participants who contributed their time to this study
