# GR00T-training-pipeline-for-Unitree-G1
This repository contains ongoing work on fine-tuning the GR00T N1.5 model to automate a custom manipulation task using the Unitree G1 humanoid robot. The project focuses on setting up a custom task scene, collecting task-specific demonstrations, fine-tuning GR00T and deploying model checkpoints in simulation and the real robot.

NOTE: Currently only the simulation part is completed.

## Training Pipeline Overview 

The workflow followed in this project consists of five main steps:

1. **Set up simulation scene**  
   Create a custom task scene for the Unitree G1 humanoid in NVIDIA Isaac Sim.

2. **Data collection via teleoperation**  
   Collect task demonstrations by teleoperating the robot in the simulation environment.

3. **Convert data to LeRobot format**  
   Process and convert the collected demonstrations into the LeRobot dataset format required for model fine-tuning.

4. **Fine-tune GR00T N1.5**  
   Fine-tune the GR00T N1.5 model with the collected dataset.

5. **Deploy GR00T**  
   Deploy the fine-tuned model checkpoints for execution in simulation.
