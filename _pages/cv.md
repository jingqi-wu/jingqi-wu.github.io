---
layout: archive
title: "Curriculum vitae of Jingqi Wu"
permalink: /cv/
author_profile: true
redirect_from:
  - /resume
---

{% include base_path %}

Education
======
* M.S. in Information Systems, Boston University
  * Relevant Coursework:  Web Application Development; Software Design; Java Programming; Database Design
* B.S. in Computer Science, Chinese University of Hong Kong, Shenzhen
  * Bo Wen Scholarship (Top 5% Students), Waterloo Math Fermat Contest (Perfect Score), AMC 10 (Top 1%), AMC 12 (Top 5%)
  * Relevant Coursework:  Machine Learning; Artificial Intelligence; Software Engineering; Parallel Programming

Work experience
======
* Feb. 2025 – Present: Data Analyst Intern – Hooli Home USA (Real-Estate Technology) in Boston, MA
  * Managed a 50 k + record database of property, sales, and customer data; improved the tool (Python) to import housing-listing data from Excel into the database; optimized schemas and queries with to reduce redundancy and shrink storage costs by 13 %.
  * Refined buy-sell-rent classifications (MySQL) that cut colleagues’ property-search time by 20 %.
  * Built a churn-prediction model (NumPy) that flagged at-risk tenants with 73 % precision, enabling targeted campaigns that improved retention by 8 %.

* Jul. 2022 – Sep. 2022: Software Engineer of Display Technology Group – Xiaomi Corporation in Shenzhen, Guangdong, China
  * Re-architected the Android SurfaceFlinger rendering pipeline (C/C++ · JNI · Android Studio/AOSP) to eliminate a VSync-thread bottleneck; restored refresh-rate stability from ~30 Hz to the target 120 Hz on flagship MIUI devices.
  * Diagnosed & patched one important critical display bug for upcoming flagship models; optimized framework-level display drivers for Qualcomm SoCs, collaborating with kernel, graphics, and QA teams to unblock release milestones.
  * Mapped and documented the Android SurfaceFlinger/Surface framework call-chain; produced a 20-page study report that was adopted as Excellent Onboarding Material and commended by the team lead.

Research experience
======
* Jan. 2025 – Present: Research Assistant - Boston University, Boston, MA
  * Port and configure SDL Core on Ubuntu 20.04; build a companion demo that streams real-time telemetry between smartphones and a simulated in-vehicle HMI (Node.js), enabling <200 ms round-trip latency in bench tests.
  * Author an Xposed-based hooking toolkit to spoof geolocation in third-party apps (Java / Android Studio).
  * Design and execute 2 penetration scenarios (Compromised Mobile System and Man-in-the-Middle Attack); uncover 7 critical vulnerabilities and propose counter-measures adopted in the paper.

* Sep. 2022 – Jun. 2023: Research Assistant - Chinese University of Hong Kong, Shenzhen
  * A Reinforcement Learning-Based Automatic Video Editing Method Using the Knowledge from the Vision-Language Model.                                                                 
  * Engineered a distributed Python data-collection service (WebSockets + RabbitMQ) that streamed ≈ 18k annotated editing actions from 40 volunteers to a 4-GPU EC2 cluster in under 10 hours.
  * Containerized training and inference with Docker/TorchServe and shipped them as micro-services on an Ubuntu cloud node; a REST/gRPC backend and a WebSocket client scale independently, supporting rolling updates.
  * Authored an RTSP-decoder micro-service that resolves camera IPs, decodes multi-channel streams, and exposes a control API so the server can remotely open client video windows – maintaining ≤ 300 ms end-to-end latency.


* Jun. 2022 – Sep. 2022: Participant - Chinese University of Hong Kong, Shenzhen
  * Development of reforming Autonomous Sailboat - Interest-Based Research Activity.                                                                            
  *	With the Arduino platform (C++), accelerometers, and other sensors, the sailboat automatically adjusted its sailing direction.
  *	Flask for the front end, through a Wi-Fi module, allowed manual control of the sailboat's sail angle and motor speed.

Skills
======
* Programming Languages: Python (Expert), C++ (Expert), Java (Expert), JavaScript, MATLAB, Verilog
* Machine Learning / Data: PyTorch (Expert), PostgreSQL (Expert), MySQL (Expert), NumPy, Pandas
* Frameworks / DevOps: Git (Expert), AWS EC2, Docker, Kubernetes, Node.js, Flask, gRPC, RabbitMQ, REST, RTSP
* Infra / Others: Ubuntu Server (Expert), WebSocket (Expert), HTML & CSS (Expert), Android (AOSP, JNI), Xposed, jQuery

You can also read my CV here: [Jingqi Wu's curriculum vitae](../assets/curriculum_vitae_of_Jingqi_Wu.pdf).
