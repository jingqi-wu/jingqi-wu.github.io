---
title: "A Reinforcement Learning-Based Automatic Video Editing Method Using the Knowledge from Vision-Language Model"
collection: publications
category: manuscripts
permalink: /publication/2023-10-27-paper-title-number-1
excerpt: ''
date: 2023-10-27
venue: 'October 27'
slidesurl: 'http://jingqi-wu.github.io/files/paper1.pdf'
paperurl: 'https://dl.acm.org/doi/10.1145/3581783.3611878'
---

Research assistant
===
*	Engineered a distributed Python data-collection service (WebSockets + RabbitMQ) that streamed ≈ 18k annotated editing actions from 40 volunteers to a 4-GPU EC2 cluster in under 10 hours.

*	Containerized training and inference with Docker/TorchServe and shipped them as micro-services on an Ubuntu cloud node; a REST/gRPC backend and a WebSocket client scale independently, supporting rolling updates.

*	Authored an RTSP-decoder micro-service that resolves camera IPs, decodes multi-channel streams, and exposes a control API so the server can remotely open client video windows – maintaining ≤ 300 ms end-to-end latency.
