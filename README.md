# 3-DOF Robotic Arm (ROS2 + MoveIt + Arduino)

A custom-built **3-DOF robotic manipulator** created with **3D printed parts**, Arduino for servo control, and ROS2/MoveIt for kinematics and trajectory planning. This project was inspired by [this Udemy course](https://www.udemy.com/course/robotics-and-ros-2-learn-by-doing-manipulators/) by Antonio Brandi, but extended with custom design and teleoperation features.

---

## 📌 Features
- **Hardware**
  - 3D-printed links and joints  
  - Arduino-controlled servo motors for actuation  
  - Serial communication between Arduino and ROS2  

- **Software**
  - **ROS2 integration** with custom URDF/Xacro description of the manipulator  
  - **Gazebo simulation** for validation before real deployment  
  - **MoveIt integration** for forward & inverse kinematics, trajectory planning, and teleoperation  

---

## 🛠️ Tech Stack
- **Languages:** C++, Python, Arduino C++  
- **Frameworks/Tools:** ROS2, MoveIt, Gazebo, RViz, Arduino IDE, 3D printing (Fusion360/SolidWorks for design)  
- **Hardware:** Arduino, MG996R servos, 3D printed joints and links  

---

## 🚀 How It Works
1. **Arduino** receives serial commands to actuate the servo motors.  
2. **ROS2** provides the robot description (URDF/Xacro) and publishes joint states.  
3. **MoveIt** handles trajectory planning and sends commands to the arm.  
4. **Gazebo simulation** allows testing of kinematics and motion planning before physical execution.  

---

## 📷 Demo
*(Insert photos or GIFs of the arm and simulation once available)*

---

## 📚 Learning Outcomes
- Gained hands-on experience in **ROS2/MoveIt integration for manipulators**  
- Applied **control systems concepts** to real hardware  
- Practiced **simulation-to-reality transfer** using Gazebo → Arduino  

---

## 🔗 References
- [Robotics and ROS2: Learn by Doing – Manipulators (Udemy)](https://www.udemy.com/course/robotics-and-ros-2-learn-by-doing-manipulators/)  
