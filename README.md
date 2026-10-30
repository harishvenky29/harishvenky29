# Hi, I'm Harish 👋

**Robotics & Computer Vision Engineer** · MSc Intelligent Robotics, University of York · York, UK (open to relocation)

I build autonomous robots end to end — from embedded control on Arduino and Raspberry Pi to ROS 2 navigation stacks, state estimation and deep-learning perception.

- 🤖 Latest: a **6-DOF igus ReBeL arm** in ROS 2 + Gazebo that follows my hand through a real webcam (MediaPipe) and picks, places and stacks cubes on hand gestures, with closed-form 6-DOF IK
- 🛰️ Also new: an **INS/GNSS Extended Kalman Filter** for a drone that keeps navigating through a 30 s GNSS outage (0.93 m position RMSE)
- 🔭 Recently built: a **voice/LLM-commanded home robot** (Whisper + Ollama + YOLO), an office mapping & patrol robot (**frontier exploration + SLAM + Nav2**) and a **UR5 computed-torque controller**
- 🎓 MSc project: an autonomous rescue robot that navigates mazes and detects victims with YOLOv5
- 💼 Open to robotics / ROS, computer vision / ML and software engineering roles across the UK

---

### 🛠️ Tech stack

- **Robotics:** ROS 2 (Jazzy), ros2_control, Nav2, SLAM, Gazebo (Harmonic), inverse kinematics, Arduino, Raspberry Pi, Mecanum drive
- **Perception / ML:** Python, PyTorch, YOLO, OpenCV, MediaPipe, Whisper, Ollama (local LLMs)
- **Estimation & control:** Extended Kalman Filter, sensor fusion (IMU / GNSS / magnetometer), computed-torque and PID control, MATLAB, Simulink
- **Engineering:** Fusion 360, Autodesk Inventor, 3D printing
- **Software:** Python, NumPy, pytest, C/C++, Linux (Ubuntu), Git

---

### 📌 Featured projects

| Project | What it does | Stack |
|---|---|---|
| [6-DOF ReBeL Hand-Controlled Pick & Place](https://github.com/harishvenky29/ros2-rebel-hand-pick-place) | igus ReBeL arm with a custom 3-finger gripper follows my hand from a webcam: pinch to grab, open to drop, turn your hand to turn the wrist. Closed-form IK (spherical wrist), plus an auto mode that moves cubes tray to tray | ROS 2 Jazzy, Gazebo Harmonic, ros2_control, MediaPipe, OpenCV, Python |
| [UXV INS/GNSS Navigation EKF](https://github.com/harishvenky29/uxv-ekf-navigation) | EKF fusing IMU, GNSS and magnetometer to estimate position, velocity, heading and gyro bias; 0.93 m position RMSE, and 10.8 m max error through a 30 s GNSS outage vs >70 m for dead reckoning | Python, NumPy, Matplotlib, pytest |
| [LLM_Robot](https://github.com/harishvenky29/LLM_Robot) | Voice-commanded home robot: Whisper turns speech into text, a local LLM (Ollama) turns it into actions, and YOLO handles perception for following people and avoiding obstacles, with Nav2 for navigation | ROS 2 Jazzy, Gazebo, Nav2, Whisper, Ollama, YOLO, Python |
| [ROS 2 Office Mapping & Patrol](https://github.com/harishvenky29/ros2-office-slam-nav2) | TurtleBot3 explores an unknown office on its own with a custom frontier-exploration node, builds a LIDAR-only map with SLAM Toolbox, then localises with AMCL and runs a Nav2 patrol between rooms | ROS 2 Jazzy, Nav2, SLAM Toolbox, Gazebo, Python |
| [UR5 Computed-Torque Control](https://github.com/harishvenky29/ur5-computed-torque-control) | 6-DOF UR5 arm with inverse kinematics and quintic trajectory planning; computed-torque control cuts tracking error by ~70% vs PID under payload and model error | MATLAB, Simulink |
| [Rescue-Robot](https://github.com/harishvenky29/Rescue-Robot) | Autonomous maze-navigating rescue robot with multi-Arduino communication, Mecanum wheels and YOLOv5 victim detection | Python, Arduino, Raspberry Pi, YOLOv5 |

---

### 🏆 Highlights

- Virtusa **NeuralHack Season 5 Grand Finalist** — top 252 of 100,000+ participants
- 1.5 years as Associate Engineer – Technology at **Virtusa**
- Taught robotics as a volunteer with **SP Robotics**

---

### 📫 Get in touch

[Portfolio](https://harishvenky29.github.io/) · [LinkedIn](https://linkedin.com/in/harish-venkatesan-m-r-833173191) · [Email](mailto:mrharishv29@gmail.com)
