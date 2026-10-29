<div align="center">

<img width="100%" src="https://capsule-render.vercel.app/api?type=waving&height=230&color=0:050816,35:0B2545,70:007F9E,100:00E5FF&text=DANIEL%20CHARLES%20C%20J&fontColor=FFFFFF&fontSize=44&fontAlignY=38&desc=MECHATRONICS%20%7C%20ROBOTICS%20%7C%20EMBEDDED%20SYSTEMS&descSize=14&descAlignY=58&animation=fadeIn" />

### ENGINEER IN PROGRESS. BUILDER BY HABIT.

*I build robots end to end, from firmware and motor drivers to control and power, and I debug them from the hardware up.*

<a href="https://github.com/danielcharles12210-dot">
  <img src="https://readme-typing-svg.demolab.com?font=Fira+Code&weight=600&size=18&pause=1400&color=FFC857&center=true&vCenter=true&width=760&lines=Open+to+Robotics+%7C+Embedded+%7C+Automation+internships;Design+%3E+Build+%3E+Test+%3E+Improve;I+debug+from+the+hardware+up;Claims+backed+by+evidence%2C+not+adjectives" alt="typing intro" />
</a>

<br/>

[![Email](https://img.shields.io/badge/EMAIL-FFC857?style=for-the-badge&logo=gmail&logoColor=050816&labelColor=050816)](mailto:danielcharles12210@gmail.com)
[![LinkedIn](https://img.shields.io/badge/LINKEDIN-00E5FF?style=for-the-badge&logo=linkedin&logoColor=050816&labelColor=050816)](https://www.linkedin.com/in/daniel-charlescj)
[![GitHub](https://img.shields.io/badge/GITHUB-FFFFFF?style=for-the-badge&logo=github&logoColor=050816&labelColor=050816)](https://github.com/danielcharles12210-dot)

</div>

---

### `00 // RECRUITER QUICK SCAN`

- 🎓 **B.E. Mechatronics Engineering**, SNS College of Technology (Anna University), graduating **2028**
- 🎯 **Open to:** internships in robotics, embedded systems and industrial automation
- 🦾 **Flagship build:** 6-DOF autonomous robotic arm, designed and programmed from scratch
- 🏭 **Industry exposure:** 3 internships and trainings across 3D-printed prosthetics and manufacturing
- 🏆 **Proof of execution:** Clemovate Hackathon winner, Smart India Hackathon 2025 participant
- 📬 **Fastest way to reach me:** [danielcharles12210@gmail.com](mailto:danielcharles12210@gmail.com)

---

### `01 // ABOUT ME`

I am a third-year Mechatronics student who builds working hardware instead of only reading about it. My projects cover the full stack of a machine: mechanical layout, motor drivers, sensors, firmware, control theory and power safety.

- 🤖 Robotic arms, autonomous mobile robots and assistive devices
- 🔌 Embedded systems on Arduino, Arduino Mega and ESP32, written in C/C++
- 🎛️ PID control, tuning and reinforcement learning
- 🏭 Industrial exposure through internships in 3D-printed prosthetics and manufacturing
- 🧠 My habit: test one subsystem at a time, prove it works, then integrate

---

### `02 // FLAGSHIP PROJECT`

## 🦾 6-DOF Autonomous Robotic Arm

- 🎯 **Goal:** a 6-axis arm benchmarked against the open-source AR2/AR3 architecture, with a long-term aim of a commercially viable industrial arm
- 🧱 **Built so far:** dual-ESP32 I2C master/slave architecture, TB6600 stepper drivers and a full GPIO map for all six axes
- 💾 **Firmware:** AccelStepper trapezoidal acceleration, limit-switch homing and software travel limits
- 🔍 **Debugged:** stepper coil pairing and TB6600 current settings, using bottom-up incremental testing
- 🔄 **Now working on:** PC ↔ Arduino Mega 2560 serial communication for a single-controller variant
- 🚀 **Next:** inverse kinematics (DH parameters), ROS2 and ISO 10218 safety
- 🟡 **Status:** in progress
- 📎 **Evidence:** [video of axes moving] · [wiring diagram] · [repo link]

`ESP32` `ARDUINO MEGA` `TB6600` `ACCELSTEPPER` `I2C`

> **An engineering decision:** I concluded that open-loop steppers aren't enough for a production-grade industrial arm and that closed-loop servos are the right path, so this build is how I learn the full stack before choosing that hardware.

---

### `03 // MORE PROJECTS`


**🏁 Autonomous Line Follower (e-Yantra)** 
- 5-sensor reflective array with tuned PID (Kp, Ki, Kd) for stable, fast line tracking
- Q-learning for intelligent action selection, developed in CoppeliaSim + Python
- Tested on S-curves, zig-zag paths and dashed lines
- Worked through drifting, sharp turns and speed optimisation

**🚚 Autonomous Mobile Robot (AMR)** 
- Two Rhino IG32 12 V geared DC motors on a Cytron MDD10A 10 A dual driver
- 12.8 V 30 Ah LiFePO4 power system with a 5 V 10 A DC-DC converter
- Compute and sensing stack: Raspberry Pi 5, ESP32-S3, D500 sensor, camera and MPU6050
- Safety chain by design: main fuse → emergency stop → main switch → power distribution
- Entire build planned within a ₹50,000 budget, around a 30 kg target mass

**🎛️ Closed-Loop DC Motor Speed Control (PID + Encoder)** 
- Holds a target RPM using encoder feedback and a PID controller adjusting motor-driver PWM
- Plan: prototype on Arduino Uno, then port to ESP32
- Python plotting of logged data for response analysis
- Results will be published only after real testing

**🖐️ Prosthetic Hand** 🟢
- Servo-driven hand with sensors and 3D-printed fingers
- Multiple grip patterns, as an affordable assistive concept

**🌾 Crop Drop Bot** 🟢
- Autonomous delivery robot with DC motors and sensor-based navigation
**💪 EMG Gesture Control** 
- ESP32-based muscle-signal processing to recognise gestures and drive a servo

---

### `04 // TECH STACK`

**💻 Languages**

<img src="https://skillicons.dev/icons?i=py,c,cpp,matlab" />

**🔌 Embedded and hardware**

<img src="https://skillicons.dev/icons?i=arduino" />
<img src="https://img.shields.io/badge/ESP32-E7352C?style=for-the-badge&logo=espressif&logoColor=white" />
<img src="https://img.shields.io/badge/TB6600-Stepper_Drivers-555555?style=for-the-badge" />

**🧪 Tools and simulation**

<img src="https://skillicons.dev/icons?i=git,github,linux,vscode,blender" />
<img src="https://img.shields.io/badge/CoppeliaSim-1687FF?style=for-the-badge" />

**📚 Learning now**

<img src="https://skillicons.dev/icons?i=ros" />
Inverse kinematics (DH parameters) · ISO 10218 robot safety

**🧭 Where I have used these**
- ⚙️ **Embedded C/C++:** arm firmware, prosthetic hand, Crop Drop Bot, Maze Solver
- 🔩 **Stepper and DC motor drivers:** TB6600 arm, AMR drivetrain, delivery and maze robots
- 🔗 **I2C multi-controller design:** dual-ESP32 arm architecture
- 🎛️ **PID tuning and Q-learning:** line follower
- 📡 **Sensor integration:** line follower, Maze Solver, prosthetic hand
- 🐍 **Python:** Certify Secure, line follower control and data plotting
- 🎨 **Design tools:** AutoCAD, Blender and Canva for mechanical and visual work

---

### `05 // EXPERIENCE`

- 🛠️ **Intern, BTouch Technologies:** contributed to the design and development of 3D-printed prosthetic devices
- 🏭 **Intern, Tony Engineering:** hands-on industrial engineering exposure
- ⚙️ **Industrial Trainee, Kiwi Cottonspin Mill (3 weeks):** plastic injection moulding processes

---

### `06 // ACHIEVEMENTS`

- 🏆 **Winner, Clemovate Hackathon**
- 🇮🇳 **Participant, Smart India Hackathon (SIH) 2025**
- 🚁 **Participant, Yugam Drone Hunt**
- 🥤 **Participant, Astranova Safe Sips**
- 🧑‍🤝‍🧑 **Executive Member, TRONEXUS** (Mechatronics Engineering Association, SNS College of Technology)
- ☁️ **Certified:** Microsoft Azure AI Fundamentals
- 💼 **Job simulations (Forage):** IBM, HP and BCG
- 📄 **Research:** Water Quality Monitoring System

---

### `07 // HOW I WORK`

- 🔬 **Hardware first:** I verify power, wiring and motion before I trust any code
- 🪜 **Incremental:** one subsystem at a time, then integrate
- 📏 **Evidence over claims:** results are listed only after they are tested
- 🧾 **Documented:** wiring diagrams, pin maps and READMEs in every repo
- 🛡️ **Safety-minded:** fuses, emergency stops and travel limits are designed in from the start



### `09 // LANGUAGES`

- 🗣️ **English** (fluent) · **Tamil** (native) · **German** (basic) · **French** (basic)

---

### `10 // LET'S BUILD`

- 💬 Hiring for robotics, embedded or automation? I would like to talk.
- 📧 [danielcharles12210@gmail.com](mailto:danielcharles12210@gmail.com)
- 🔗 [linkedin.com/in/daniel-charlescj](https://www.linkedin.com/in/daniel-charlescj)

---

<div align="center">

**BUILD WITH PURPOSE. ENGINEER WITH EVIDENCE.**

<img width="100%" src="https://capsule-render.vercel.app/api?type=waving&height=100&section=footer&color=0:00E5FF,50:007F9E,100:050816" />

</div>
