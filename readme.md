# Building NextG Resilient Wireless Systems from Untrusted Hardware

The design, manufacturing, and deployment of next generation (NextG) cellular networks (5G and beyond) is increasingly relying on specialized, high-performance baseband and radio
frequency (RF) hardware components, often supplied by third parties across the globe. The use of
these components can accelerate innovation, improve network performance, and reduce the cost of
network operation. Yet, the reliance of critical of hardware components sourced from diverse man-
ufacturers introduces formidable security vulnerabilities into critical network infrastructure. The
broad goal of this project is to develop methods to build resilient and secure NextG wireless systems
from these potentially unsecure hardware components.
This project focuses on a particularly important class of attacks called hardware Trojans, where
hardware components supplied by a third party are maliciously altered to launch an attack from
within a network node, such as a cellular base stations. Once triggered, these attacks can degrade
or disable service, transmit signals to disrupt other nodes, or snoop or leak sensitive data. The
project combines theory in hardware security and communications theory to detect and mitigate
these attacks in four closely related thrusts. Thrust 1 develops computationally efficient methods to
detect the presence of hardware Trojans in both the baseband and RF. Thrust 2 provides rigorous
bounds to estimate the capacity of undetected hardware attacks and enables a critical optimization of
the power and computation on hardware verification and potential throughput degradation. Thrust
3 extends these methods to network settings including jamming and multi-user attacks. Thrust 4
develops a novel and powerful evaluation platform to experiment with hardware security methods
in both the baseband and RF in a high throughput mmWave SDR.

This project is funded by [NSF RINGS Award](https://www.nsf.gov/awardsearch/showAward?AWD_ID=2148293).
