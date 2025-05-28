[![Review Assignment Due Date](https://classroom.github.com/assets/deadline-readme-button-22041afd0340ce965d47ae6ef1cefeee28c7c493a6346c4f15d667ab976d596c.svg)](https://classroom.github.com/a/oxMPd-Kw)

### Second laboratory work for course Robot Motion Planning and Control.

 <table>
  <tr>
    <td>jtraj Method</td>
    <td>mtraj method with the trapezoidal function</td>
    <td>mtraj method with the quantic function</td>
  </tr>
  <tr>
    <td><img src="puma_jtraj.gif" alt="jtraj plan" width="400"></td>
    <td><img src="puma_trap.gif" alt="trap plan" width="400"></td>
    <td><img src="puma_quin.gif" alt="quin plan" width="400"></td>
  </tr>
</table>
 

#### Joint Position/Velocity/Acceleration Profile of PUMA Robotic Arm

<table>
  <tr>
    <td>Joint Positions</td>
    <td>Joint Velocities</td>
    <td>Joint Accelerations</td>
  </tr>
  <tr>
    <td><img src="pos_profiles.png" alt="Position Profile" width="300"></td>
    <td><img src="vel_profiles.png" alt="Velocity Profile" width="300"></td>
    <td><img src="acc_profiles.png" alt="Acceleration Profile" width="300"></td>
  </tr>
</table>

### Tasks:
1. Load the manipulator model from the toolbox according to the selected robot kinematics option. Fill in all parameters of the robot model as specified in Laboratory Work No. 1.
2. Fill in all parameters of the robot model as specified in Laboratory Work No. 1.
3. Set an arbitrary initial robot configuration.
4. Solve the forward kinematics problem for the given generalized coordinates.
5. Construct the manipulator's workspace under the given joint constraints.
6. Select an end point within the workspace and solve the inverse kinematics problem for it.
7. Plan the trajectory between the initial and final positions of the manipulator's end-effector using at least three planning methods.
8. Plot graphs of position, velocity, and acceleration of the robot's joints during trajectory motion.
9. Prepare a report in .ipynb format with detailed comments. 
10. Conclusions should be drawn based on the results of the work.
