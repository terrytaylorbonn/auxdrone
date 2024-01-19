# Simulation concepts

The Gdrive ([drive.google.com/drive/folders/1HrzLExPTAL5PIKx\_j\_y0GJ6\_RANR8Tjm](https://drive.google.com/drive/folders/1HrzLExPTAL5PIKx\_j\_y0GJ6\_RANR8Tjm)) document 0\_sim\_concepts\_.docx (draft) explains the major AI and drone concepts.  The content and organization are my own.

This document is currently low priority. I will be better able to create the conceptual documentation after I have finished building and testing a drone. The only reason created this document was because I could find no such document in the internet that provided a good presentation of the subject.

The diagram below (which needs to be updated) sums up the drone build process.

* 1\_drone\_sim highlights all of the simulated components described in document #1 (chapter 1 of this site).
* 2\_object\_recognition (AI) highlights the camera and CC (companion computer, Nvidia Jetson Nano or PI4) that perform object recognition in document #2 (chapter 2 of this site).
* I need to update this diagram to include AI controlled simulation in document #3 and flight plan controlled simulation in document #4 (chapters 3 and 4 of this site).
* 3\_drone\_build highlights the components of the basic drone to be built in February 2024 from a Holybro kit ("DRONE + GC" below the dashed line shows the drone and ground control components of the basic non-AI drone to be built).  This process will be described in document #5 (chapter 5 of this site).
* 4\_drone\_flight highlights the ground control software and components use to fly the drone manually or with a flight plan. To be described in document #4 (chapter 4 of this site).&#x20;
* 5\_autonomous  highlights the Pymavlink (Python) program that runs on the CC and sends flight commands to the FC based on AI outputs (autonomous flight). This process will be described in document #5 (chapter 5 of this site).
* Document #6 AI-controlled flight is not shown in the diagram. The (outdated) diagram shows 6\_ROS. I recently discovered that I could build the autonomous drone without using the complex ROS installation.

<figure><img src="https://lh7-us.googleusercontent.com/RLYg8SNc8G7cuq0Z8n9E0l7Mv6GSt36QFpyB7id7H1ugreGj0LRAci1a55cBafiUOiwc-C2w6jW71e7_HFdFePvEhhG3V1_bNisw5fYhzkDslTNJQ22rAAoN8SIwqGcGeyvOGE9WEiE-WspyOuSMEA" alt="" width="375"><figcaption><p>A conceptual diagram of my drone from the simulation concepts document</p></figcaption></figure>
