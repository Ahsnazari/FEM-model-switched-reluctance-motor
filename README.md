# FEM-model-switched-reluctance-motor
Switched reluctance motor is a type of motor that runs on variable reluctance principle. In this motors power delivered to windings in stators and due to the lack of commutators (because the rotating part is not powered) a need raises for the switches to control the reluctance torque that moves the motor. This is mainly done in two methods, such as DC, and Current-control chopping. In this project DC voltage control method is utilized. In short, in this method the switches of each phase are closed after reaching to a certain voltage level. The equivalent circuit is shown in the figure below:
![equivalent circuit](https://github.com/Ahsnazari/FEM-model-switched-reluctance-motor/assets/118515566/3082a6e5-c201-44d2-8b60-54f1dc9bf52b)
The RMxprt module, a 12/8 1500 rpm motor is modelled, which is shown in the following figure:
![model](https://github.com/Ahsnazari/FEM-model-switched-reluctance-motor/assets/118515566/f7374222-4065-4fa0-8f56-ea7f910a0caf)
To decrease the simulation time the model is simplified to a quarter of its original size. The magnetic field, and magnetic flux in a random time step is shown in the following figures:
![A](https://github.com/Ahsnazari/FEM-model-switched-reluctance-motor/assets/118515566/9a3a084b-f690-47dd-82e3-e24edea2d884)
![B](https://github.com/Ahsnazari/FEM-model-switched-reluctance-motor/assets/118515566/2a294100-0f6b-45d7-a583-52aefe1fc27f)
Then, the simulation is repeated in three steps with different number of conductors. The simulation results for linkage flux, phase A to A inductance, induced voltage, winding currents, and torque in one cycle are as followed.
![linkage flux](https://github.com/Ahsnazari/FEM-model-switched-reluctance-motor/assets/118515566/2be465ae-7a02-451a-8a96-f953dc32210c)
![inductance](https://github.com/Ahsnazari/FEM-model-switched-reluctance-motor/assets/118515566/6083aa22-5cad-4659-9005-744f3fd5fd1c)

![induced voltage](https://github.com/Ahsnazari/FEM-model-switched-reluctance-motor/assets/118515566/92658a1f-7c7a-40d1-a505-ef036001a4b2)
![winding currents](https://github.com/Ahsnazari/FEM-model-switched-reluctance-motor/assets/118515566/acae23b2-f507-4708-a8e1-e6740d48b180)
![torques](https://github.com/Ahsnazari/FEM-model-switched-reluctance-motor/assets/118515566/ad4e9b1e-0b63-4334-9246-fe88e4ad2fab)

