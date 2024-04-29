# 23-1003-Nurse-Practitioner-

This project's version control will be hosted on Perforce. However, this Github contains relevant documentation and development. 

## Objective
The project aims to develop a VR application that utilizes Large Language Learning Models (LLM), and realistic 3D modeling/animation techniques to create an immersive learning experience where student Nurse Practitioners can engage in interactive consultations with virtual patient avatars, all the while mitigating real-world instructional hazards.

These avatars will exhibit and describe real signs and symptoms, allowing students to practice their clinical skills in various simulated patient care situations. Ultimately, it is hoped that integrating VR technology into pedagogical practices used in nursing programs will aid students’ transition from fragmented textual knowledge to competency-oriented application.

## Format and Versioning
This project uses Unreal Engine 5.3.2, Meta Quest Virtual Reality Headsets, various motion capture techniques, Metahumans for realistic avatar animations, and NVIDIA audio-to-face technology for accurate lip-syncing. Integration with LLMs enables dynamic, lifelike conversations with virtual patients, moving beyond pre-configured responses whilst still allowing core concepts to be controlled to ensure parity between users.  

## Getting Started with Unreal Engine 
1) Visit [Download Unreal Engine - Unreal Engine](https://www.unrealengine.com/en-US/download)  and install the Epic Games Launcher 

2) After following the steps to install the launcher, make sure that you are set to Unreal Engine 

3) Go to the Library Tab and press the “+” Icon. Choose Unreal Engine 5.3.2 

4) After pressing install, we’ll make some modifications to our installation to ensure the optimization of our installation

5) In Folder, choose where to install unreal engine. It is recommended not to change this if you have the space on your primary drive.  

6) In path, click on options, and unselect the Android, IOS, and Linux platforms. This will save you about 22 GB in installation.  

7) Let the install happen, and then run. The first time you run Unreal Engine, it will take a while so be patient! 

## Plugins Installation 

1) We need to install a few plugins. The list is as below:
   - Metahuman
   - Runtime Speech Recognizer
   - Runtime Audio Importer
   - TCP Socket Plugin
   - VaRest 

2) To find these plugins and download them, go to the Epic Games Launcher, and ensure you are tabbed into Unreal Engine on the left-hand side of the screen. 

3) Go to Marketplace  

4) Then search for the plugin, and purchase (they are all free). 

5) Once all plugins have been purchased and added to your library, click on the library tab next to Marketplace.  

6) Scroll down through your vault to find the plugin of interest and press on install to Engine.  

7) Choose to install to Unreal Engine 5.3.2  

8) Repeat for all plugins needed.  

## Getting Started with Oculus 

1) Visit https://www.meta.com/ca/quest/setup/ and scroll down to Quest 2, press download software.  

 

2) After pressing download Software, follow through with the instructions to install it.  

3) On your mobile phone as well, install the oculus app.  

4) After logging into the headset, the mobile app, and the PC app with the same Meta account, connect the headset to the PC via a USB-C link cable.  

5) Accept the prompt to enable Quest Link 

 

6) If that prompt does not appear, go to the Menu, then press on Quest Link, then choose the connection to launch.   

7) After doing so Return to the phone app.  

8) Click on the Headset that is connected to your PC then click on Headset settings under manage your device 

 

9) Click on Developer Mode 

 

10) Then enable debug  

 

11) Restart the Oculus app on the PC and restart the connection with the headset. 

12) On the left-hand side of the Oculus app, click on settings, then go to the beta tab.  

13) Enable developer runtime features 

 

## Launching the program 

1) Click on the executable file

2) In /Content/Levels/, select and load WaitingRoom.

3) Initialize server by launching the executable

4) After ensuring the headset is properly connected, Click on the button “Launch in VR” 

5) To trigger the OSCE score/results screen, click “Enter” on the keyboard. 

6) To close the program, click “Esc” on the keyboard. 

Toggle Poster subsection
Documentation:23-1003 Nurse Practitioner
Documentation
Discussion
Read
View source
View history
Emerging Media Lab
UBC Emerging Media Lab Signature.png
About EML
A collaborative space for UBC faculty, students and staff for exploration of emerging technologies and development of innovative tools and solutions. This wiki is for public-facing documentation for our projects and procedures.
Subpages
Main EML wiki page
Public EML website
EML Resources
EML Onboarding
EML Offboarding
EML Operations
EML Projects

Introduction
Background
In healthcare, nurse-patient interaction is of paramount importance. Student Nurse Practitioners’ understanding of theoretical concepts could be improved with a tool that models clinical decision-making through automation. Through virtual reality (VR) technology, students will be able to participate in realistic learning experiences and enhance their communication and clinical skills in a safe and controlled environment.

“Our goal was to transform the education of future Nurse Practitioners by merging the cutting-edge realms of virtual reality and large-language models. We wanted to create a ground-breaking learning environment where students can hone their communication, diagnostic and clinical-decision making skills through realistic, interactive simulations. This project isn’t just about teaching; it’s about immersing students in an authentic clinical experience, where every virtual patient encounter is a step closer to excellence in patient care. We are committed to bridging the gap between theory and practice, ensuring our Nurse Practitioners are not only knowledgeable but also profoundly skilled in the art of healing.” - Ashley Scott, Principal Investigator

An OSCE (Objective Structured Clinical Examination) is a performance examination which evaluates student NPs on their ability to interact with and diagnose/manage a specific patient’s medical concern. Student Nurse Practitioners describe the experience as a nerve-wracking and stressful process, with great fear of the unknown as they never know what to expect. They expressed sentiments that it is hard to practice for these OSCEs as the only way is to learn by doing the real thing, as traditional peer-to-peer or online practice methods fall short. Real-world instructional hazards like time constraints, scheduling conflicts with practice partners, as well as the lack of realism from existing web-based solutions are mitigated by the usage of this tool.  

Prior to coming to EML, existing web-based solutions which were primitive in its animations and visual design were investigated. However, the tools were not customized for an OSCE setting, and those that were, included a text-based simulation which involves the user having to talk to or type out their responses to a written chatbot-like interface. The text-based chat interface lacked realism, as in actual OSCE, the student Nurse Practitioner would not be typing on a keyboard to communicate with the patient.  Hence, the interactions in existing solutions are lack realism and similarity to the actual OSCE scenario, failing to prepare the students effectively for their examinations. There is no current existing VR tool for simulating the OSCE experience for student Nurse Practitioners.  

Hence, the challenge was to develop that realistic VR solution by leveraging realistic Metahuman avatars, facial and body animations, and a LLM to enable contextually appropriate conversations between the student NP and the patient.  

Objective
The project aims to develop a VR application that utilizes Large Language Learning Models (LLM), and realistic 3D modeling/animation techniques to create an immersive learning experience where student Nurse Practitioners can engage in interactive consultations with virtual patient avatars, all the while mitigating real-world instructional hazards.

These avatars will exhibit and describe real signs and symptoms, allowing students to practice their clinical skills in various simulated patient care situations. Ultimately, it is hoped that integrating VR technology into pedagogical practices used in nursing programs will aid students’ transition from fragmented textual knowledge to competency-oriented application.

Format and Versioning
This project uses Unreal Engine 5.3.2, Meta Quest Virtual Reality Headsets, various motion capture techniques, Metahumans for realistic avatar animations, and NVIDIA audio-to-face technology for accurate lip-syncing. Integration with LLMs enables dynamic, lifelike conversations with virtual patients, moving beyond pre-configured responses whilst still allowing core concepts to be controlled to ensure parity between users.  

Primary Features
Platform
The application will have two main components - a tutorial that will introduce students to the interface and the mechanics of working in virtual reality, and a simulation exercise.

Simulation
The tutorial and simulation will include two avatars, an avatar performing the role of examiner, observing the student’s performance during their virtual OSCE and providing post-simulation feedback, and a virtual patient avatar. The virtual patient avatar is programmed to give realistic variable responses of pertinent content, allowing multiple students to engage in practice consultations mirroring real life, but crucially, key information required for decision-making will remain unchanged. This design ensures consistency in training and evaluation, while preparing students for both clinical practice and licensing board OSCEs.

Our current prototype consists of one OSCE scenario where the student NP can conduct a focused history and brief counseling of a pregnant patient with headache and swelling. The patient avatar describes realistic signs and symptoms when prompted by the student NP. Our scenario matches the traditional OSCE experience, providing a realistic training ground for the student NP. It includes the OSCE patient situation scenario brief and the examinee instructions. The student NP examinee is then able to practice conversing with the patient avatar and performing their OSCE, coming up with a diagnosis at the end. At the end of the simulation, students will received a personalized results screen, scoring them on how well they followed the OSCE structure. Hence, by utilizing our tool, they gain confidence in practicing for their OSCE.  

We produced a significant increase in the authenticity of interactions and practice by utilizing a realistic clinical virtual reality environment, purchased through Unreal Engine Marketplace. By utilizing Metahuman Creator, we designed two realistic avatars, an examiner avatar, and a patient avatar, which the user would primarily interact with and be able to communicate with. This allowed the avatars to resemble real people, exhibiting lifelike appearances, facial expressions, and body language, through realistic facial and body animation using  

A Large Language Model (LLM), OpenAI, was used to enable dynamic and contextually appropriate discussions between the students and the patient avatars, that would help facilitate the scenario to resemble a templated OSCE. This is a key feature of this project, as other clinically focused software currently available lacks this aspect of authenticity and realism to an OSCE.  

FUNCTIONALITIES  

Here is a table of all the existing features that were proposed at the start of term and what was achieved.

No.	Task	Priority	Status
F1	Metahuman avatars (patient and examiner)	Must have	Complete
F2	User can converse with patient avatar on contextually appropriate material in real time	Must have	Complete
F3	Realistic hospital environment setting  	Must have	Complete
F4	Realistic facial and body animations	Must have	Complete
F5	Distinct tutorial and scenario levels	Should have	Complete
F6	Scenario follows OSCE template (user can practice an OSCE)	Should have	Complete
F7	Basic menu screens, visual screens and GUIs designed and implemented into the prototype	Should have	Complete
F8	User is able to receive their OSCE score at the end (system is able to keep track of their responses and score it appropriately)	Nice to have	Complete
F9	Accurate lip sync of the patient and examiner avatar	Nice to have	Incomplete
F10	Scenario can host multiple OSCE templates	Nice to have	Incomplete
Tech Stack and Development Overview
Technical Components
Here is a table with all the tools used in the project's design and development.

Tool	Description
Mixamo	Source for models and animations
Unreal Engine	Game Engine used for development of this project
Runtime Speech Recognizer	Open-source plugin that enables real-time offline speech recognition, based on Whisper OpenAI
Runtime Audio Importer	Open-source plugin for importing audio for various formats at runtime
PoseAI LiveLInk	Livelink plugin for PoseCam for using an iPhone to motion capture actors.
MetaHuman	Highly realistic virtual humans created for use in Unreal Engine
VaRest	Plugin that assists in HTTP requests and REST server communication
TCP Socket Plugin	Plugin that facilitates communication with a TCP server
Convai	Conversational AI plugin (no longer in use)
Nvidia Audio2Face	Nvidia tool used to assist in making Facial animation using Audio files as inputs. Connected over Livelink.
EML Server	Custom EML server to communicate with OpenAI
OpenAI ChatGPT LLM	Facilitate speech to speech system and OSCE results scoring algorithm.
Figma	Design software used for wireframing and prototyping UX/UI designs  
Miro  	Mind map visualization software used for architecture diagrams and UX related work
Trello	Project management software used for team and project organization  
Qualtrics	Survey software used for gathering quantitative user research findings
In fall 2023, Metahuman Creator was leveraged to bring to life a patient and examiner avatar. Convai was used to provide speech to speech functionality and body and face animations for our OSCE patient avatar. For the examiner, we utilized Unreal Engine’s Text to Speech sub engine, with its own animation blueprints for body and face that sourced animations from Mixamo, Livelink, and Nvidia Audio2Face. The environment used was purchased from the Epic Games Marketplace and created by Blue Dot Studios. At this point of the project, there were no functioning user interfaces, but simple buttons were used as placeholders. VR actions implemented included an interactable laser pointer for pressing buttons, and a button for talking into the microphone. To implement the OSCE scenario into the patient metahuman, we made use of Convai’s knowledge bank feature.  

At our internal showcase in December, we demoed a prototype that featured user-patient avatar interaction facilitated by Convai on Meta Quest 3. This prototype had much of the functionality already working, as the user would be able to speak to the patient avatar and the scenario / conversation would resemble an OSCE, as the patient avatar had knowledge relevant to the OSCE facilitated by Convai. The demo prototype also featured a tutorial with an examiner avatar that was able to orient the user to the scenario.  

During the second term, we took Convai completely out of the project, and implemented speech to speech using an EML in-house server for making API requests to OpenAI API. The role of the OSCE patient was prompt engineered in the configuration setting of the GPT’s role. Transcription of user voice input was implemented using functions from Runtime Speech Recognizer. Fixes were made to the logic behind how the animation blueprints worked for the metahumans so that metahumans utilizing the power of Speech to Speech could use them as well. The Unreal Engine Text to Speech sub engine was also taken out due to its robotic voice. We generated audio files for the script of the examiner instead using OpenAI and had those audio files play during the tutorial. User interfaces were created using widgets and controlled using a switcher for the tutorial, and a server initializing button was created to start the OSCE examination.  

We also developed a scoring system that allows users to get instant feedback on their performance during the examination. To do this we effectively added a few more components into VRPawn that allowed it to record all of the text that was spoken by a nurse practitioner and then get OpenAI to score how well the practitioner did based on a template. There was also a UI for displaying the score of the user that was implemented.

Design Overview
User personas and character builds were created in Figma during the fall term to learn from target users’ needs and pain points. User flows and user journey maps were created in here and here to map out the OSCE and tutorial scenarios in the prototype. Character builds for the patient and examiner avatar helped visualize their role in the OSCE simulation.

Metahuman Creator was leveraged in the design of the patient avatar. Unreal Engine Editor was used to create the initial start menu for the prototype that was demoed at internal showcase in December. Tools like ShapesXR and Bezi were explored but ultimately not considered for the needs of the project at the time, and Figma was used instead for the design of all UI/UX design assets.  

Design Assets
The UI was designed using Figma. This included high fidelity wireframes that are in various stages of implementation (indicated on the file) and prototype flows of how a prototype would go.

A welcome flow consisting of a loading screen and start menu were designed.  
Menus (pause, tutorial)
Scenario brief UI  
UI for the OSCE score summary
Timer assets  
Visual indicators for listening and conversational AI interactions  
Visual indicators for usability and greater ease of use user interactions  
User Research
We started a user research initiative in early February, reaching out to current Nurse Practitioner students. After collecting consent forms, we conducted two user interviews with two current Nurse Practitioner students and collected responses to a usability questionnaire.  

The primary goals of the initiative are as follows:  

User Experience Evaluation: To understand and assess how intuitive and engaging the VR tool prototype is for nurse practitioner students. This includes navigation, interface design, and overall user satisfaction.
Subject Matter Expertise: Leverage the domain expertise of student nurse practitioners to gain insights into how well the VR tool aligns with actual clinical practices and educational standards.
Future Improvement Identification: Compile feedback and insights to guide the development of future iterations of the prototype, with an emphasis on improving user experience.
The structure of each interview aimed to reflect the goals of the initiative. For the full procedure, please refer to the appendix. Each interview was split into two sections – the first being a more typical user interview format, and the second being a usability test of the prototype demo at the time. After the usability test, there was an exit interview to get immediate feedback on the demo. There was also a usability questionnaire that individuals filled out asynchronously within a day.  

In the user interview format, we started out with background questions that aimed to leverage the domain knowledge of student nurse practitioners to better inform the future design and development of the OSCE simulation in the prototype. The next stage aimed to assess the technical experience students have with virtual reality and any accessibility concerns (e.g. history of motion sickness, visual impairment) so that we could be aware of them if they come up in the demo. If students indicated that they had less experience, the user interview practitioner would provide them with more guidance and instructions in using the demo. This would prove helpful in figuring out a key insight – which was that users would need guidance in basics like setting up a headset or how to hold controllers, which was later translated to a VR guide.  

Then, we headed into the usability test of the prototype demo. The student was asked to interact with the prototype and converse with the patient avatar as if they were conducting an OSCE. The interviewer could give the patient direction if they needed help, which proved useful in figuring out which areas or tasks the users struggled with. Afterwards, the interviewer asked the participant some closing questions and directed the participant to fill out a survey asynchronously within 24 hours. The survey consisted of questions based entirely on the System Usability Scale, which is a tool used to measure the usability of a system (like an app prototype).

The prototype demo at the time consisted of a tutorial and the scenario demo itself, which took place in a hospital room setting. Since then, the current prototype takes place in a clinical setting.  

Insights
A complete list of insights attained from the user research initiative can be found here: User Research Findings Summary

Some of the most key insights were immediately translated into user stories and then into high fidelity UI designs that aimed to “fix” the pain point. These included the insight that feedback was needed in communication, “As a user, I would like an indicator that the AI avatar registered the question that I asked.” This was translated into UI designs for a listening, processing, and error message popup indicator. Additionally, an average SUS score of 67.5 (barely below the average SUS score of 68) was achieved, but it is worth noting that the SUS score is usually measured on finished applications.  

First Time Setup Guide
This section will take you through an overview of the installation process. Note that this guide is not comprehensive as it is missing instructions regarding server setup and project launch which are specifics to the current requirements and versioning of the project.

Getting Started with Unreal Engine
Visit Download Unreal Engine - Unreal Engine and install the Epic Games Launcher
After following the steps to install the launcher, select Unreal Engine.
Go to the Library Tab and press the “+” Icon. Choose Unreal Engine 5.3.2
After pressing install, we’ll make some modifications to our installation to ensure the optimization of our installation (Unreal 5.2 used as example below but the process is exactly the same).  
In Folder, choose where to install unreal engine. It is recommended not to change this if you have the space on your primary drive.  
In path, click on options, and unselect the Android, IOS, and Linux platforms. This will save you about 22 GB in installation.  
Let the install happen, and then run. The first time you run Unreal Engine, it will take a while so be patient!
Plugins Installation
We need to install a few plugins. The list is as below:
Metahumans
Runtime Speech Recognizer
Runtime Audio Importer
TCP Socket Plugin
VaRest
To find these plugins and download them, go to the Epic Games Launcher, and ensure you are have selected Unreal Engine on the left-hand side of the screen.
Go to Marketplace  
Then search for the plugin, and purchase (they are all free).
Once all plugins have been purchased and added to your library, click on the library tab next to Marketplace.  
Scroll down through your vault to find the plugin of interest and click on "Install to Engine".
Choose to install to Unreal Engine 5.3.2  
Repeat for all plugins needed.  
Getting Started with Oculus
Visit the Meta Quest website and scroll down to Quest 2 and click on download software.  
After pressing download software, follow through with the instructions to install it.  
On your mobile phone as well, install the Oculus App.
Project Launch in VR
Ensure that the Meta Quest is linked.
Launch the project in Unreal Engine.
After ensuring the headset is properly connected, Click on the button “Launch in VR”
To trigger the OSCE score/results screen, click “Enter” on the keyboard.
To exit the program, click "Esc" on the keyboard.
Known Issues
There is one known issue as follows:

Bug with patient avatar responding as examiner
If the initialization by the user isn't correct (e.g. user doesn't mention that they are a student NP), the patient might assume its an examiner.
Challenges
No major challenges were encountered to produce the prototype, but there were multiple solutions and considerations employed in the development. For the speech to speech implementation, a custom algorithm was in the process of development but ultimately scrapped and replaced by ConvAI for demonstration purposes in December.

We also encountered issues regarding working with the EML in-house developed server, which was utilized for the conversational AI speech-to-speech integration of the project. There were also challenges faced that were realized by the development of the known issue listed above.

Future Plans
Moving forward, here are some of the recommendations our team has for future teams working on the project.

There should be a focus on integrating all high-fidelity user interface designs into the prototype, for increased usability and accessibility. A key priority would be the visual indicators for the voice user interface, as that is directly aimed to increase user friendliness, and optimization of existing implemented GUIs to match wireframes.  

Development should also focus on implementing multiple OSCE scenarios that the student Nurse Practitioners can practice with. As student NPs can be tested on a variety of different topics and scenarios, this is a crucial add to their preparation. Users should be able to select between multiple scenarios for practice and be able to be given a scenario at random.  

There should be a priority to further develop the result scoring algorithm by incorporating more robust testing, to ensure that it can score the user correctly according to the OSCE. This would involve putting up guardrails so the user can’t just get a higher score by simply stating key words and ensuring that the full functionality is working (e.g. no partial marks given, the scoring algorithm picks up what the user is saying correctly). Toggling the already-implemented OSCE score breakdown might help with this (it was hidden at this stage as typically a user would not have access to their OSCE score breakdown/rubric). Development allowing for stored data and multiple practice sessions using the same OSCE scenario, as well as multiple users would also aid the user’s preparation for their OSCE and allow users to track progress over time.

Also, development should allow for the user to be able to converse with the patient avatar on contextually appropriate material with exceptional realism (e.g. patient doesn’t volunteer information that hasn’t been asked). Additionally, fixes relating to more realistic and diverse body animation to fit a diversity of scenarios and multiple diverse patient avatars would aid to the refinement of the prototype.

## Team
Principal Investigator
Ashley Scott

Associate Professor of Teaching

UBC School of Nursing

University of British Columbia


Dr. Fairleth McCuaig

Associate Professor of Teaching

UBC School of Nursing

University of British Columbia

Current Team
Victoria Lim, Project Lead, UI/UX Designer (September 2023 - present)

Work Learn at the Emerging Media Lab at UBC

Undergraduate in Bachelor of Science in Cognitive Systems

University of British Columbia

Jerry Wang, Software Developer (September 2023 - present)

Work Learn at the Emerging Media Lab at UBC

Undergraduate in Bachelor of Science in Cognitive Systems

University of British Columbia

Graydon Strachan, Software Developer (January 2024 - present)

Work Learn at the Emerging Media Lab at UBC

Undergraduate in Bachelor of Applied Science in Computer Engineering

University of British Columbia

William Watkins, Software Developer (September 2023 - December 2023)

Work Learn at the Emerging Media Lab at UBC

Undergraduate in Bachelor of Science in Biology

University of British Columbia

## Documentation
* Project wiki link here: https://wiki.ubc.ca/Documentation:23-1003_Nurse_Practitioner 
 
