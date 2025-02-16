# To be DONE

Check MORSE Simulater for buoyancy. \
Why Episode_Reward/prog is capped. \
Check glider simulator. \
Improve Buoyancy. \
Check Added mass sim dt. \
Download all interesting lectures from ETHZ-robotics. \
How to handle the mass change of the water tank. \
Implement Coriolis. \
Try ANSYS Fluent. \
Update the exact force applying points. \
Think about what is the best way to take into account the medium while calculating the forces. \
Wind/Water Current. \
### Low Priority
Read all robotics papers above 1000? citations. \
save_code for .py files, WandB. \
non-fixed energy harvesting underwater. ballon? \
Watch "Soft and Biohybrid Robotics - Robert Katzschmann". \

# DONE
### 2025.Feb.16
Watch "Soft and Biohybrid Robotics - Robert Katzschmann". 2nd Lecture. \

### 2025.Feb.14
Skim "A high maneuvering motion strategy and stable control method for tandem twin-rotor aerial-aquatic vehicles near the water surface." \
Skim "Review of hybrid aquatic-aerial vehicle(HAAV): Classifications, current status, applications, challenges and technology perspectives." \

### 2025.Feb.13
Check if the problem is CA. \
Separate the lift force from the root rigid body center. \
Find Lift force working version. \
Skim "MEDUSA: A Multi-Environment Dual-Robot for Underwater Sample Acquisition." \
Apply surface tension. -> Surface tension neglected for robot > 100g. \
Read "Encyclopaedia of Robotics: Bioinspired Aerial Robots." \

### 2025.Feb.12
Check lift force and torque components. \
Check why lift force[3] is the same as lift force[5]. \
Skim "Undulatory Swimming Performance Explored With a Biorobotic Fish and Measured by Soft Sensors and Particle Image Velocimetry." \
Skim "Omni-Drone: on the Design of a Novel Aerial Manipulator with Omni-directional Workspace." \
Change buoyancy, hydrodynamic, aerodynamic force calculation function input. \

### 2025.Feb.11
Lab guide for Prof. Lee. \
Add moment, etc., for lift force. \
Read "Aerial-aquatic robots capable of crossing the air-water boundary and hitchhiking on surfaces." \

### 2025.Feb.10
Make files to save themselves if running training. \
Check the data acquisition and visualization. \
Weekly Update with PhD. Pham. \

### 2025.Feb.07
Check Added mass applied agent. \
Read "Bioinspiration review of Aquatic Unmanned Aerial Vehicle (AquaUAV)." \
Read "Use of an unmanned aerial-aquatic vehicle for acoustic sensing in freshwater ecosystems." \
Skim "PX4: A Node-Based Multithreaded Open Source Robotics Framework for Deeply Embedded Platforms." \
Read "Features characterizing safe aerial-aquatic robots." \
Skim "Camber-changing flapping hydrofoils for efficient and environmental-safe water propulsion system." \
Read "UUV Simulator: A Gazebo-based Package for Underwater Intervention and Multi-Robot Simulation." \
How to print. \

### 2025.Feb.06
Read "The grand challenges of Science Robotics. \
Added Mass. \
Read "Challenges in Control and Autonomy of Unmanned Aerial-Aquatic Vehicles." \

### 2025.Feb.05
Read "How to fly" paper. \
Learn Soft and Biohybrid Robotics - Robert Katzschmann. \

### 2025.Feb.04
The lift coefficient was adjusted to be more realistic. \
Lift force takes into account the stall effect. \
Adjust the center of gravity and check in the simulation. \

### 2025.Feb.03
Prepare weekly updates. \
Check IsaacSim 4.5 updates. \
Check IsaacLab 2.0 updates. \
Read the papers from Dr. Pham. \

### 2025.Jan.31
Practice the presentation. \
Play with Stamp Fly. Open-source Quadrotor. \

### 2025.Jan.30 
Prepare 1-page slide for Jan.31st. \ 
Check the Isaac Sim Camera viewpoint control. \
Make a video about the squidbot migration. \
Consider the state for the medium and implement it if needed. \
Mass change. -> self._asset.root_physx_view.set_masses(self._current_mass.to("cpu"), self._ALL_INDICES_CPU). \

### 2025.Jan.29
Implement lift force. \
Implement lift-induced drag. \
Check what happens if we change the translation/orientation of the robot default frame. -> No change. \
Kevin welcome party. \
### 2025.Jan.28
Lift force - MIT ocw. \
Drone prototyping guid. \
Picture the lift force implementation. \

### 2025.Jan.27
Cover the ideas got from the weekend. \
Review the meeting - CTD, sensors for ocean observation. \
Implement water tank observation and use and charge of it. \
Update Squidbot with upper body and bottom body. \
Pegasus simulator review. \
Weekly update with PhD. Pham. \
Read Safety Doc. \

### 2025.Jan.24
Check the training and parameters. \
Implement drag in the air. \
Understand the hyperparameters for SKRL. \
Check the effect of clip_action. \
Check if current setting is working well with WandB. \
Find proper hyperparameters for SKRL. \
What is SKRL? \
SKRL version updated to 1.4.0. \
Make SKRL work! convert code compatible with RSL-RL -> SKRL
Update Key events. \
Check the RANS framework, and how it is handling the discrete action. \

### 2025.Jan.23
Lab Meeting. \
Implement jet propulsion, discrete action. \
Check if the set_mass function works in the GPU pipeline. -> It did not work with GPU. \
Think about the super easy prototype to use as a test robot. To deploy a trained model on a real robot. \

### 2025.Jan.22
Divide Squid into upper/lower body. \
Add visualization for thrust. \
Make an immigrant task for squid. \
Check Gym spaces for the action space. \

### 2025.Jan.21
Check IsaacLab action examples. \
Make thruster to one, add 2DOF revolute joint. \
Check UUV simulator detail. \
Implement Drag. \

### 2025.Jan.20
Check force field extension for isaac sim. \
Finish NVIDIA training course 1, Learn OpenUSD. \
Finish NVIDIA training course 2, Learn OpenUSD. \
Proteus Meeting. \
Safety Instruction leaning. \

### 2025.Jan.19
Watch CES 2025 Keynote. \
Understand Added Mass. \
Learn OpenUSD from Nvidia Traning. \

### 2025.Jan.16
Make a figure explaining agent and isaac lab framework. \
Have fun with Genesis Simulator. \
Check Reference Architecture of Isaac Lab. \
Isaac Lab Explanation in Korean maybe? \
Read the TEAMS comment by Prof. Mirko. It was about squid evolution, to adapt itself for flight. \

### ~ 2025.Jan.15
random waypoint task, active - 291. \
random waypoint task, rigid - 289. \
square task, 1m, x bar configuration active better trained- 279. \
square task, 1m, x bar configuration active - 278. \
Active joint general task. \
Thesis submission. \
upfold rigid - 272. \
upfold programmable - 271. \
foldabledrone fix - 267. \
foldabledrone active - 266. \
upfold 0.2 0.5 m terminate - 259. \
upfold rigid 0.5m terminate - 258. \
upfold rigid 1m terminate back and forth RE - 257. \
Make a symmetric upfold design. \
upfold 0.2 1m terminate back and forth - 256. \
upfold rigid 1m terminate back and forth - 255. \
Generate reverse-programmable joint model of Bucki. \
Seesaw fixed range compete. \
Prepare for the weekly update. \
Novel design, to tilt without baselink. \
Make real rigid twin with fixed joints. \
Minor task selection in Waypoints. \ 
upfold rigid changed to y axis RE - 241 \
upfold 0.2 changed to y axis RE - 240 \
upfold rigid changed to y axis - 239 \
upfold 0.2 changed to y axis - 238 \
upfold 0.2 - 237, 1m\
upfold rigid - 236, 1m\
seesaw rigid - 231, 11-12-00-10 \
seesaw passive 0.04, 0.04 - 229, 11-11-21-00 \
thrust to weight ratio 2.0 upfold - 226, 11-11-08-55 \
thrust to weight ratio 2.0 rigid - 225 \
Find best joint setting for Up-Fold drone. \
LOR check. \
Reward modified rigid - 223 \
Reward modified 0.20 - 222 \
Training with 0.35 - 219 \
Training with rigid twin - 220 \
Waypoint Task. \
Participate the SPEAR integration meeting. \
Send email to Andreas. \
Do not forget to record failure vidoes. \
Change Progress reward. \
Train Hovering+Yaw Task, and check the validity of acquired data. \
Check which part of the code prevents a smooth shutdown. \
Change to Norm of everything (Position, Orientation). \
Get some research ideas at IROS2024. \
Add benefits to cross the gap. \
External Disturbance. \
IROS 2024 taxi fee for rui. \
Make action smooth. \
More realistic servomotor. \
Morph Hovering Task. \
Morph Trajectory Tracking. \
Update Prof. Cedric on the current situation. \
Update Prof. Raphael on the current situation. \
Connect WandB to rl_games. This approach was canceled, and still using rsl-rl. \
Watch MIT-WHOI Info Video. \
Update the Issac Lab to 1.2.0 \
Check the rsl_rl, if it is possible to clip action inside the framework. \
Check the rl_games performance after matching parameters with rsl_rl. \
CS6515 HW 5. \
Prepare for the Lunch meeting. \
CS6515 Quiz 4. \
Read the paper "Agri-fly: simulator for uncrewed aerial vehicle flight in agricultural environments." \
Change the name of the graph axis. \
Read paper "Learning Quadruped Locomotion Using Differentiable Simulation". \
Meeting with Luis for IROS Poster. \
Book IELTS or TOEFL. \
Add the rotor motor state and twist to the log. \
Check the trained data and visualize it with an ipynb file. \
Make the active joint realistic. \
Make a 2-page slide for the SPEAR meeting. \
Make a brief Introductory PPT/Video. \
ICRA@40. \
Check the one-page summaries of all keynotes @ ICRA40. \
Check the schedule of ICRA@40 and make proper plan. \
Save log files, such as ROSBAG, with isaac sim. - This was done, but to record actions as well, anyway, I had to write a code for saving a CSV.\
Request Meetings for the Swiss Robotics Day. \
CS6515 writes a working version of the code for HW4. \
Make Action smooth. - First, try using a simple action-prev_action difference penalty. \
Review Steffen's PhD defense preparation slides. \
Check joint control options in Isaac Lab. (set_effort, set_velocity, set_pos) \
Get Official Transcripts. \
Check HW4 for Graduate Algorithms \
Check if there is a provided way to log variables during play.py - DONE by connecting ROS2, and foxglove., Simulation Data Visualizer \
Book ICRA@40 Accommodation. \
Summarize ICRA@40 interesting session. \
DREAM Lab Meeting (24.09.17) \
Check the narrow gap passage task with a simple setting. (Run 115, FoldableDrone) \
Check the Diagonal motor distance of models. (Reconfigurable ~44, Foldable > 60)
