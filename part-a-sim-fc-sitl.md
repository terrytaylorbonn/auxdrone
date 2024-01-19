# PART A: Sim FC (SITL)

The flight controller (FC) is a small computer that is the brains that keeps a quad copter in the air. The only control surfaces a copter has are the 4 rotors. A human can not flight such a complex aircraft. That's the job of the FC.&#x20;

<figure><img src=".gitbook/assets/image (1).png" alt=""><figcaption><p>The PixHawk flight controller (FC)</p></figcaption></figure>

You can create flight plans that contain simple text commands that tell the FC where to fly the drone.  That's convenient, but also dangerous if your plan has mistakes. &#x20;

The solution: Simulate. Part A describes the following:

* &#x20;Ch 1: SITL (software in the loop). Rather than using a real copter, you use a simulated copter (with a sim FC) in a sim world with sim objects. This chapter describes the rather complex installation and configuration of a simulation system.
* Ch 2: AI (real camera/CC).  SITL simulation is good enough to verify the commands to the FC, but not for the AI computer/camera. The actual AI object recognition is performed on a "companion" computer (CC). In my docs I demonstrate how to do this with Nvidia Jetson Nano and Raspberry PI4.&#x20;
*



