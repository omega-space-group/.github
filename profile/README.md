# Ω-Space Group

**ORION Lab | National Technical University of Athens**

<div align="center">

[![Website](https://img.shields.io/badge/Website-ORION%20Lab-blue)](https://orionlab.space.noa.gr/)
[![Location](https://img.shields.io/badge/Location-Athens%2C%20Greece-green)]()
[![License](https://img.shields.io/badge/License-GPL--3.0-blue)]()

</div>

---

## 🛰️ About Us

The **Ω-Space (Omega-Space) Group** is part of the **ORION Lab** at the **National Technical University of Athens (NTUA)**. We focus on:

- 🤖 **AI Algorithms for Space Systems**
- 🛰️ **CubeSat Technology Development**
- 📡 **On-board Processing & Autonomy**
- 🔬 **Open-source Space Technology Research**

Our mission is to advance space technology through open-source innovation, hands-on education, and collaborative research.

---

## 🚀 Main Project: ORION CubeSat Flatsat Testbed

### [**orion-cubesat-testbed**](https://github.com/omega-space-group/orion-cubesat-testbed)

A comprehensive CubeSat flatsat testbed for deploying and testing AI algorithms, end-to-end processing pipelines, and avionics software/hardware.

**Key Features:**
- ✨ **Space ROS 2** integration for modern middleware
- 🤖 **Containerized AI** payload processing (NVIDIA Jetson + FPGA)
- 🔗 **Hybrid communication** (Space ROS DDS + CubeSat Space Protocol)
- 🎓 **Educational platform** for student research projects
- 🌍 **Fully open-source** (GPL-3.0)

**Architecture:**
```
┌─────────────────┐
│ Ground Station  │
└────────┬────────┘
         │ RF
    ┌────┴────┐
    │  Comms  │
    └────┬────┘
         │ GigE + CAN
    ┌────┴─────────────┐
    │   C&DH           │
    │  (RPi4/STM32)    │
    │   + Space ROS    │
    └─┬──────────────┬─┘
      │ CAN          │ GigE + CAN
  ┌───┴─────┐    ┌───┴─────────┐
  │   EPS   │    │  Payload    │
  │ (STM32) │    │(Jetson/FPGA)│
  └─────────┘    └─────────────┘
```

[**→ Explore the Testbed**](https://github.com/omega-space-group/orion-cubesat-testbed)

---

## 🎓 Student Research

We actively support Master's thesis projects related to space systems:

### [**student-projects**](https://github.com/omega-space-group/student-projects)

Current research areas:
- **Command & Data Handling Software** (Space ROS based)
- **AI Payload Processing Framework** (Containerized deployment)
- **Communication Infrastructure** (Hybrid ROS+CSP architecture)

[**→ View Student Projects**](https://github.com/omega-space-group/student-projects)

---

## 📚 Repositories

### Core Projects
| Repository | Description | Status |
|------------|-------------|--------|
| [**orion-cubesat-testbed**](https://github.com/omega-space-group/orion-cubesat-testbed) | Main CubeSat flatsat testbed | 🔄 Active Development |
| [**student-projects**](https://github.com/omega-space-group/student-projects) | Master's thesis projects | 🎓 Active Research |

### Coming Soon
- Ground segment tools
- Space ROS packages
- AI model deployments
- Hardware documentation

---

## 🤝 Collaboration & Contribution

We welcome collaboration from:
- 🎓 **Students** - Join us for thesis projects or research
- 🔬 **Researchers** - Collaborate on space technology
- 💻 **Developers** - Contribute to our open-source projects
- 🏢 **Industry Partners** - Explore technology transfer opportunities

**Interested?** Check our [Contributing Guidelines](https://github.com/omega-space-group/orion-cubesat-testbed/blob/main/CONTRIBUTING.md) or reach out!

---

## 🔬 Research Focus Areas

### AI & Machine Learning
- On-board AI inference optimization
- Edge computing for space applications
- TensorRT model deployment
- Resource-constrained ML algorithms

### Space Systems Engineering
- CubeSat subsystem integration
- Avionics software architecture
- Power management systems
- Communication protocols

### Modern Middleware
- Space ROS 2 for CubeSats
- Hybrid communication architectures
- Real-time operating systems
- Containerization for space

---

## 📖 Publications & Resources

### Related Technologies
- [Space ROS](https://space.ros.org/) - ROS 2 for space applications
- [CubeSat Space Protocol (CSP)](https://github.com/libcsp/libcsp) - Communication protocol
- [micro-ROS](https://micro.ros.org/) - ROS 2 for microcontrollers
- [FreeRTOS](https://www.freertos.org/) - Real-time operating system

### Publications
*Publications and papers from our research will be listed here*

---

## 🏢 About ORION Lab

**ORION Lab** focuses on cutting-edge research in AI, machine learning, and space technology. Part of the **National Observatory of Athens** and the **National Technical University of Athens**, we combine academic excellence with practical innovation.

**Key Areas:**
- Artificial Intelligence & Machine Learning
- Space Systems & Satellite Technology  
- Earth Observation & Remote Sensing
- Autonomous Systems

**Website:** [orionlab.space.noa.gr](https://orionlab.space.noa.gr/)

---

## 📧 Contact

**Ω-Space Group**  
ORION Lab  
National Technical University of Athens

**Website:** [https://orionlab.space.noa.gr/](https://orionlab.space.noa.gr/)  
**Location:** Athens, Greece

For inquiries about collaboration, student projects, or research opportunities, please visit our website or reach out through GitHub.

---

## 📜 License

All our projects are open-source under **GPL-3.0** license, promoting transparency, collaboration, and knowledge sharing in the space community.

---

<div align="center">

**Building the future of open-source space technology** 🚀

[![GitHub followers](https://img.shields.io/github/followers/omega-space-group?style=social)](https://github.com/omega-space-group)
[![GitHub stars](https://img.shields.io/github/stars/omega-space-group?style=social)](https://github.com/omega-space-group)
