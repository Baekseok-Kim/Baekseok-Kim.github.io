---
layout: archive
title: "CV"
permalink: /cv/
author_profile: true
redirect_from:
  - /resume
---

{% include base_path %}

<p><a href="{{ base_path }}/files/CV.pdf" class="btn btn--primary">Download CV (PDF)</a></p>

Skills
======
* **RL & Control:** End-to-end RL, residual/hybrid policy learning, reward and observation design, sim-to-real, whole-body control, MPC, loco-manipulation
* **Programming:** Python, PyTorch, NumPy, C/C++, MATLAB
* **Simulation & Physics:** MuJoCo, Isaac Lab, legged robot dynamics modeling, MATLAB/Python simulators
* **Hardware:** Humanoid and bipedal legged platforms, force-augmented control, sensor integration, on-robot policy validation
* **CAD / CAE:** Creo, CATIA, SolidWorks, Inventor, AutoCAD, Ansys

Experience
======
* **PhD Research Assistant**, University of Nevada, Las Vegas — Las Vegas, NV  
  *Mar 2022 – Present*
  * Developed end-to-end RL pipelines for bipedal locomotion on a humanoid leg platform, including policy training in MuJoCo/Isaac Lab, reward design, and sim-to-real deployment on hardware ([demo](https://youtu.be/1LBIC1oepBM))
  * Designed hierarchical control architecture with pre-IK residual RL for humanoid loco-manipulation, integrating model-based whole-body control with learned residuals on custom bipedal hardware ([demo](https://youtu.be/I75s3yJ7FBw))
  * Built hybrid residual RL and model-based control stacks on the Stilt-bot underactuated bipedal platform for stable walking policies validated on physical hardware ([demo](https://youtube.com/shorts/ld92WOSXl5w))
  * Delivered whole-body humanoid motion control as lead control engineer on Team Avatar-Hubo for the ANA Avatar XPRIZE Finals, integrating locomotion and upper-body coordination on real hardware ([demo](https://youtu.be/pmdKos4IX24))
  * Evaluated learned and model-based controllers in simulation and on hardware, iterating on observation design, dynamics modeling, and disturbance recovery behavior

* **Robotics Engineer / Project Manager**, Global Zeus (ZEUS Co., Ltd.) — Republic of Korea  
  *Dec 2018 – Feb 2022*
  * Developed real-time robot dynamics, kinematics, and motion-control software with Python/OpenGL simulation tools for controller debugging and performance evaluation ([demo](https://youtu.be/H9TEUTbJVs0))
  * Spearheaded the company's first industrial parallel robot development project; led parallel robot, SCARA robot, and EtherCAT-based motion control system development

* **Research Assistant**, Hanyang University — Seoul, Republic of Korea  
  *Mar 2016 – Feb 2019*
  * Built MATLAB dynamics simulation and stability-analysis tools for a skiing humanoid robot and validated controllers on real-world slopes (IROS 2018)
  * Developed humanoid skiing robot platform, disaster rescue robot, and human–robot interaction exhibition robots

Teaching
======
* **Teaching Assistant**, University of Nevada, Las Vegas — *Aug 2022 – Present*
  * ME 425/625 – Robotics I (Mechanisms and Algorithms), Instructor — Jan 2024 – May 2024; Jan 2025 – May 2025
  * ME 423L – Instrumentation and Control Laboratory, Instructor — Aug 2022 – Dec 2024; Jan 2023 – May 2023
  * ME 302 – Material Mechanics, Instructor — Jul 2024 – Aug 2024

Education
======
* **Ph.D. in Mechanical Engineering**, University of Nevada, Las Vegas — Las Vegas, NV  
  *Aug 2022 – Present (expected Dec 2026)*  
  Advisor: Paul Y. Oh | GPA: 4.0/4.0

* **M.S. in Interdisciplinary Robot Engineering Systems**, Hanyang University — Seoul, Republic of Korea  
  *Mar 2017 – Feb 2019*  
  Thesis: *The Development of the Simulation for the Stability Analysis of the Skiing Humanoid Robot*  
  Advisor: Jeakweon Han | GPA: 4.0/4.0

* **B.S. in Mechanical Engineering**, Sungkyunkwan University — Suwon, Republic of Korea  
  *Mar 2012 – Feb 2017*  
  Thesis: *Research of Human Assistive Robot using Soft Actuator*  
  Advisor: Hyoukryeol Choi | Major GPA: 3.43/4.0

Publications
======
  <ul>{% for post in site.publications reversed %}
    {% include archive-single-cv.html %}
  {% endfor %}</ul>

Honors & Awards
======
* Humanoid Robot Autonomous Winner, *2023 IEEE-RAS International Conference on Humanoid Robots Competition*
* UKC 2023 Young Scholar Award, *US-Korea Conference on Science, Technology, and Entrepreneurship*
* Roy & Helen Kelsall Scholarship, University of Nevada, Las Vegas — 2023–2024, 2024–2025, 2026–2027
* UNLV Access Grant – Grad NN — 2023–2024, 2024–2025
* UNLV College of Engineering Graduate Differential Fees Fellowship — 2026

Patents
======
* Kim, Baekseok and Son, Jeongwon — *DELTA ROBOT ASSEMBLY INCLUDING ROBOT STAND AND DELTA ROBOT*, KR20210042030A, 2020.10.08
* Kim, Baekseok and Kim, Youngdae — *DELTA ROBOT, AND CONTROL APPARATUS AND METHOD*, 2021.04.01
