# Event-based Motion Capture System for Online Multi-Quadrotor Motion Planning

by
Craig Iaboni,
Deepan Lobo,
Ji-won Choi,
Pramod Abichandani

This paper has been submitted for review in MDPI Sensors.

## Abstract
Motion capture systems are crucial in developing multi-quadrotor systems due to their ability to provide fast and accurate ground truth measurements for tracking and control. This paper presents the implementation details and experimental validation of a relatively low-cost motion-capture system for multi-quadrotor motion planning using a fixed event camera. The real-time, multi-quadrotor detection and tracking tasks are performed using a deep learning network You-Only-Look-Once (YOLOv5) and a k-dimensional (k-d) tree, respectively. An optimization-based decentralized motion planning algorithm is implemented to demonstrate the effectiveness of this motion capture system. Extensive experimental evaluations were performed to 1) compare the performance of 4 deep-learning algorithms for high-speed multi-quadrotor detection on event-based data, 2) study precision, recall, and F1 scores as functions of lighting conditions and camera motion, and 3) investigate the scalability of this system as a function of the number of quadrotors flying in the arena. Comparative analysis of the deep learning algorithms on a consumer-grade GPU demonstrates a 79.2% sampling rate advantage over representative one and two-stage detectors and a 12.5% advantage over YOLOv4. In terms of precision and recall, YOLOv5 performs 15% to 18% and 27% to 41\% stronger than representative state-of-the-art object detectors. A graceful detection and tracking performance degradation were observed in the face of progressively darker ambient light conditions. Despite severe camera motion, precision and recall values of 94\% and 98\% were achieved, respectively. Finally, experiments involving up to 6 indoor quadrotors demonstrated the scalability of this approach. This paper also presents the first in the literature, open-source event camera dataset featuring multiple quadrotors operating in indoor and outdoor environments.
