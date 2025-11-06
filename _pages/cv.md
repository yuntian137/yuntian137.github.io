---
layout: archive
title: "CV"
permalink: /cv/
author_profile: true
redirect_from:
  - /resume
---

{% include base_path %}

Contact
======
* Phone: +86 139-1916-3168
* Email: s408378183@outlook.com

Education
======
* **South China University of Technology**, Guangzhou, China  
  B.Eng. in Automation, School of Automation Science and Engineering, Sep 2022 – Jun 2026  
  *Selected for the Super Robot “Everest” honors program (30 students per cohort), focusing on control theory, AI applications, and robotic system design, Jul 2024 – present.*

Technical Skills
======
* ROS 2 application development (topics, services, actions, launch pipelines).
* Embedded software on STM32/FreeRTOS with UART, CAN, SPI, I²C, timers, and DMA.
* Hardware bring-up: schematic interpretation, datasheet reading, use of oscilloscopes and logic analyzers.
* C/C++ with templates, inheritance, and polymorphism; clean code and review practices.
* Linux toolchain usage for robotics and embedded workflows.
* Machine learning fundamentals: data preprocessing, SGD-based optimization, reinforcement learning basics.
* Control methods: PID tuning for motor control, MPC/LQR design, Isaac Sim/Mujoco/Webots simulation experience.
* Project planning, cross-team communication, and mentoring for 10+ member technical teams.

Industry Experience
======
* **Embedded Software Intern**, Insta360 (Arashi Vision Co., Ltd.) — Camera Engineering Division, Dec 2024 – Mar 2025, Guangzhou  
  * Validated Wi-Fi/Bluetooth functionality and performance on embedded Linux platforms; analyzed driver and protocol stack logs to identify root causes of connectivity issues.  
  * Maintained Git branches for regression fixes, accelerating turnaround on testing defects.

Projects
======
* **Dual-Arm Manipulation Research**, Visiting Student, Hong Kong University of Science and Technology (Guangzhou), Aug 2025 – present  
  * Reproduced the open-source OpenArm robot hardware platform and delivered ROS 2 interfaces for whole-body control.  
  * Integrated multiple dexterous hands (BrainCo Revo2, LeapHand) to enable grasping and teleoperation workflows.

* **RoboMaster 2025 Sentry Platform**, Technical Advisor, Sep 2024 – Aug 2025  
  * Led miniaturization strategy for the autonomous sentry robot to navigate complex tunnel terrain.  
  * Enhanced quadruped-wheel hybrid state estimation and implemented an MPC-based motion controller tailored to wheel-legged kinematics.  
  * Planned roadmaps for the electrical control team, coordinated with mechanical, perception, and hardware squads, and mentored junior members.

* **RoboMaster 2024 Sentry Robot**, Electrical Control Lead & Chassis Lead, Sep 2023 – Aug 2024  
  * Built STM32F4/FreeRTOS firmware driving drivetrain, gimbal, and peripheral modules through CAN, UART, I²C, and SPI.  
  * Designed cascaded PID with feedforward and IMU fusion, delivering 40% faster gimbal response with ≤0.5° steady-state error.  
  * Architected layered state-machine software to streamline debugging and drastically reduce testing time.  
  * Authored onboard communication protocol bridging perception (auto-aim, navigation, decision) with motion control, keeping packet loss below 1%.  
  * Developed tactical testing scenarios and manual control fallbacks to stabilize decision logic outside of competition conditions.  
  * Implemented weapon switching control and collaborated on mechanical tuning to raise firing accuracy by ~40% and rate-of-fire by 70%.  
  * Managed a 10-member cross-functional team, defining technical requirements and aligning milestones.

Honors & Awards
======
* RoboMaster 2025 University Competition — National First Prize (Finished third nationally), Jun 2025
* RoboMaster 2024 University Competition — National First Prize (Finished second nationally), Aug 2024
* RoboMaster 2025 University Competition — South China Regional First Prize (Regional Champion), Jun 2025
* RoboMaster 2024 University Competition — Central China Regional First Prize (Regional Top 8), Jun 2024

Publications
======
  <ul>{% for post in site.publications reversed %}
    {% include archive-single-cv.html %}
  {% endfor %}</ul>
  
Service and leadership
======
* Lead and mentor for a 10-member cross-functional RoboMaster electrical control team (mechanical, electrical, and vision) during the 2024 season.
* Technical advisor guiding RoboMaster electrical control roadmap planning for the 2025 season.
