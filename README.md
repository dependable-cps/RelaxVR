# MazeSick_Dataset

We collected the data for our MazeSick dataset while participants navigated virtual mazes with a smooth locomotion technique (e.g., using the controller) and performed coin collection tasks, as shown in the Figure below. The purpose of this data collection was to to facilitate the training of the cybersickness prediction models and open source and thus can be used by other researchers in the community for further research.
![Maze environment _new](https://github.com/user-attachments/assets/1991af37-1492-4c54-8385-ee8c25963359)

### Participants
We utilized 60 (39 M, 21 F) participants. The participants were recruited from the local area and had a mean age of 23.6 with a standard deviation of 3.21. The participants came from various demographic backgrounds. Thirty four of the sixty participants said they had previously used VR equipment while 26 had no prior experience of using VR.


### Virtual Environment
The virtual environment was a Dungeon-style maze created using Unity and OpenVR, which contained brick walls, brick platforms, and an open roof with an orange sky. The maze was structured as a 15 x 14 grid, where a trophy is randomly spawned. 
The goal is to reach the trophy, which will transport the user to the next randomly generated maze. Each maze is designed so that the user must explore at least half of it to ensure a consistent level of challenge across levels. 
The maze occupies a total area of 150 meters by 140 meters in Unity(Vector3(150, 1, 140)). Given this size, each platform within the grid measures  10 meters by 10 meters in real-life space, as Unity's default scale assigns 1 unit to 1 meter. 
It is a single-player experience where the objective is to escape the maze. They provide options for both room-scale and smooth locomotion.
### Study Tasks
The primary task was navigating mazes for 12 minutes. Before starting the experiment for data collection, we briefly introduced the procedures and informed participants about the requirements. 
The participants went through a brief 2-minute virtual tutorial or training explaining the coin collection task they had to complete. They were then instructed to use the controller to complete the maze navigation with the learned task. 
Furthermore, We emphasized verbally reporting their discomfort on an FMS score of 0 to 10 whenever a pre-recorded voice prompt was played at each $30$ seconds interval during the VR simulations.
Escape the Maze and performed coin collection tasks.
### Apparatus
We utilized an HTC-Vive Pro Eye headset to present the virtual maze, boasting a display resolution of 2880 x 1600 per eye and operating at a refresh rate of 90Hz. This headset offered a wide field of view spanning 110 degrees. 
The audio was delivered through the integrated Vive headphones. The VR maze simulation was rendered using a computer equipped with an Intel Core i9 CPU with 128 GB of memory and an Nvidia GeForce RTX 3090 GPU. 
The virtual environment was built using the Unity 2021.2.2f1 game engine software and OpenVR software development kit (SDK).

The virtual environment was developed using Unity 3D. We use the HTC SRanipal SDK and Tobii HTC Vive Devkit to capture eye and head-tracking data


### Procedure

#### Study Introduction
Participants were presented with the informed consent form and provided with an overview of the study activities. They were informed of their right to terminate the study if they felt uncomfortable at any point. Upon signing the consent form, participants completed a background questionnaire comprising initial Simulator Sickness Questionnaire (SSQ), demographic inquiries, and disability-related questions. Subsequently, participants were outfitted with the HTC Vive Pro Eye headset, physiological monitoring equipment, and controllers before proceeding to a tutorial session.

#### Tutorial
Prior to the 12-minute VR session, participants underwent a brief 2-minute virtual tutorial elucidating the tasks they would perform. T

### Fast Motion Sickness Scale (FMS)
Participants rated their level of cybersickness on a scale of 1-10, whenever a pre-recorded voice prompt was played at each $30$ seconds interval during the VR simulations.

### Eye Tracking and  Head Tracking
Utilizing the SRanipal SDK and Tobii eye tracking technology, we captured detailed eye-tracking metrics, including pupil diameter and gaze direction, sampled at 60 Hz.





