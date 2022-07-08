# DNN-Identifier-for-Dynamic-Systems-with-Time-Varying-State-Constraints
The repository is created to show results in the convenient form for reproducing.

*Abstract - In this paper, an identification problem for uncertain nonlinear systems with time-varying state constraints was solved. When designing the identifier, Differential Neural Networks (DNNs) and Barrier Lyapunov Functions (BLFs) techniques were used. The obtained solution requires solving differential continuous-time Riccati equation as well as nonlinear differential equations for the learning laws. In this problem statement, time-dependent state constraints are supposed to be known in advance continuous functions of time. Such type of constraints naturally occurs in different types of mechatronic systems, i.e. a robotic arm system, the behavior of which was identified in the numerical example.*

![ezgif com-gif-maker](https://user-images.githubusercontent.com/33436181/163841256-bd904bed-5521-4128-9816-ecf1ed400b37.gif)

## Matlab implementation:
You have to have the Simulink(Matlab) software with the following packages:
1. Control System Toolbox
2. DSP System Toolbox
3. Signal Processing Toolbox
4. Simscape
5. Simscape Multibody
6. Simulink
7. Simulink Control Design

*Use Multilink_arm/DNN_x3D_M_2000iA900L_with_6_rev.slx or -//-rev_21a.sxl file to start the system
**In case of several problems with Simulink Data workspace files, please, redefine path at <user_folders>/Multilink_arm/x3D_M_2000iA900L_OLGA_DataFile8.m in Modeling -> Design -> Repositories -> Model Workspace
