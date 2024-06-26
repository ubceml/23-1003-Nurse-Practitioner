# 23-1003-Nurse-Practitioner-

This project's version control will be hosted on Perforce. However, this Github contains relevant documentation and development. 

## Objective
The project aims to develop a VR application that utilizes Large Language Learning Models (LLM), and realistic 3D modeling/animation techniques to create an immersive learning experience where student Nurse Practitioners can engage in interactive consultations with virtual patient avatars, all the while mitigating real-world instructional hazards.

These avatars will exhibit and describe real signs and symptoms, allowing students to practice their clinical skills in various simulated patient care situations. Ultimately, it is hoped that integrating VR technology into pedagogical practices used in nursing programs will aid students’ transition from fragmented textual knowledge to competency-oriented application.

## Format and Versioning
This project uses Unreal Engine 5.3.2, Meta Quest Virtual Reality Headsets, various motion capture techniques, Metahumans for realistic avatar animations, and NVIDIA audio-to-face technology for accurate lip-syncing. Integration with LLMs enables dynamic, lifelike conversations with virtual patients, moving beyond pre-configured responses whilst still allowing core concepts to be controlled to ensure parity between users.  

## Getting Started with Unreal Engine 
1) Visit [Download Unreal Engine - Unreal Engine](https://www.unrealengine.com/en-US/download)  and install the Epic Games Launcher 

2) After following the steps to install the launcher, make sure that you are set to Unreal Engine.
   ![image](https://github.com/ubceml/23-1003-Nurse-Practitioner/assets/76148419/5137e220-c7c6-4a3b-b6f1-39a524bd25cf)


4) Go to the Library Tab and press the “+” Icon. Choose Unreal Engine 5.3.2 
![image](https://github.com/ubceml/23-1003-Nurse-Practitioner/assets/76148419/808e2e85-a66a-47c6-9046-643db51562eb)

5) After pressing install, we’ll make some modifications to our installation to ensure the optimization of our installation
   ![image](https://github.com/ubceml/23-1003-Nurse-Practitioner/assets/76148419/a4f07e0f-5488-4044-a269-20b64d9d5dcf)

6) In Folder, choose where to install unreal engine. It is recommended not to change this if you have the space on your primary drive.  

7) In path, click on options, and unselect the Android, IOS, and Linux platforms. This will save you about 22 GB in installation.  

8) Let the install happen, and then run. The first time you run Unreal Engine, it will take a while so be patient! 

## Plugins Installation 

1) We need to install a few plugins. The list is as below:
   - Metahuman
   - Runtime Speech Recognizer
   - Runtime Audio Importer
   - TCP Socket Plugin
   - VaRest 

2) To find these plugins and download them, go to the Epic Games Launcher, and ensure you are tabbed into Unreal Engine on the left-hand side of the screen. 
![image](https://github.com/ubceml/23-1003-Nurse-Practitioner/assets/76148419/24166ef0-8539-4282-8ebe-6a29aec57802)

3) Go to Marketplace  
![image](https://github.com/ubceml/23-1003-Nurse-Practitioner/assets/76148419/7fe9057f-7dfe-4885-a06b-b003ed70cc1e)

4) Then search for the plugin, and purchase (they are all free). 

5) Once all plugins have been purchased and added to your library, click on the library tab next to Marketplace.
   ![image](https://github.com/ubceml/23-1003-Nurse-Practitioner/assets/76148419/5da7a967-a5b5-421e-96e5-80e7586aed91)

6) Scroll down through your vault to find the plugin of interest and press on install to Engine.  
![image](https://github.com/ubceml/23-1003-Nurse-Practitioner/assets/76148419/fb1e6254-8517-403e-aa7f-a385501031f6)

7) Choose to install to Unreal Engine 5.3.2  
![image](https://github.com/ubceml/23-1003-Nurse-Practitioner/assets/76148419/2465e091-3db0-4892-b7e7-d85d2f9f435a)

8) Repeat for all plugins needed.  

## Getting Started with Oculus 

1) Visit https://www.meta.com/ca/quest/setup/ and scroll down to Quest 2, press download software.  
![image](https://github.com/ubceml/23-1003-Nurse-Practitioner/assets/76148419/3c72e302-f1ad-4c91-b74e-0fdaea0940c1)


2) After pressing download Software, follow through with the instructions to install it.  

3) On your mobile phone as well, install the oculus app.  

4) After logging into the headset, the mobile app, and the PC app with the same Meta account, connect the headset to the PC via a USB-C link cable.  

5) Accept the prompt to enable Quest Link 
![image](https://github.com/ubceml/23-1003-Nurse-Practitioner/assets/76148419/b2c417db-8a69-445b-8f01-17c0e6a2efe3)

6) If that prompt does not appear, go to the Menu, then press on Quest Link, then choose the connection to launch.   
![image](https://github.com/ubceml/23-1003-Nurse-Practitioner/assets/76148419/4290f947-b830-46e0-99d7-172e09c21a10)

7) After doing so Return to the phone app.  

8) Click on the Headset that is connected to your PC then click on Headset settings under manage your device 
![image](https://github.com/ubceml/23-1003-Nurse-Practitioner/assets/76148419/294d8e8f-bc8c-457e-85f0-0617ca0947d0)

9) Click on Developer Mode 
 ![image](https://github.com/ubceml/23-1003-Nurse-Practitioner/assets/76148419/4799b7d8-15fb-4633-968b-f644a9da4c24)

10) Then enable debug  
![image](https://github.com/ubceml/23-1003-Nurse-Practitioner/assets/76148419/ff7f6ea9-e7aa-433d-813d-d6b336e165d9)
 
11) Restart the Oculus app on the PC and restart the connection with the headset. 

12) On the left-hand side of the Oculus app, click on settings, then go to the beta tab.  

13) Enable developer runtime features 
![image](https://github.com/ubceml/23-1003-Nurse-Practitioner/assets/76148419/b7111989-7d16-42e4-b1dc-f5c6899dc9d6)
 

## Launching the program 

1) Click on the executable file
![image](https://github.com/ubceml/23-1003-Nurse-Practitioner/assets/76148419/9d729418-8b42-46d0-9b7b-203dfc52fe9f)

2) In /Content/Levels/, select and load WaitingRoom.

3) Initialize server by launching the executable.
![image](https://github.com/ubceml/23-1003-Nurse-Practitioner/assets/76148419/1976d2c9-a56e-4e9c-9f67-9d860bd74174)

4) After ensuring the headset is properly connected, Click on the button “Launch in VR” 
![image](https://github.com/ubceml/23-1003-Nurse-Practitioner/assets/76148419/02bd47ab-c373-4210-8c9d-c0dc747af7a4)

5) To trigger the OSCE score/results screen, click “Enter” on the keyboard. 

6) To close the program, click “Esc” on the keyboard.
   
## Headset Setup
![image](https://github.com/ubceml/23-1003-Nurse-Practitioner/assets/76148419/a60784b2-ccf6-4da9-8287-62bc5c74a9a9)

## Controller Setup
![image](https://github.com/ubceml/23-1003-Nurse-Practitioner/assets/76148419/acffc5da-fba2-447d-bef8-1129fc0e9a08)

## Team

Principal Investigators

Ashley Scott,
Associate Professor of Teaching,
UBC School of Nursing,
University of British Columbia

Dr. Fairleth McCuaig,
Associate Professor of Teaching,
UBC School of Nursing,
University of British Columbia

Current Team

Victoria Lim, Project Lead, UI/UX Designer (September 2023 - May 2024),
Work Learn at the Emerging Media Lab at UBC,
Undergraduate in Bachelor of Science in Cognitive Systems,
University of British Columbia

Jerry Wang, Software Developer (September 2023 - May 2024),
Work Learn at the Emerging Media Lab at UBC,
Undergraduate in Bachelor of Science in Cognitive Systems,
University of British Columbia

Graydon Strachan, Software Developer (January 2024 - May 2024),
Work Learn at the Emerging Media Lab at UBC,
Undergraduate in Bachelor of Applied Science in Computer Engineering,
University of British Columbia

William Watkins, Software Developer (September 2023 - December 2023),
Work Learn at the Emerging Media Lab at UBC,
Undergraduate in Bachelor of Science in Biology,
University of British Columbia

## Documentation
* Project wiki link: https://wiki.ubc.ca/Documentation:23-1003_Nurse_Practitioner 
 
