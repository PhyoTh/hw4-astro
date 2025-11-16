---
title: 'My Journey in Robotics and Autonomous Systems'
description: 'From underwater ROVs to autonomous vehicles - my experience building real-world robotics systems'
pubDate: 'Jan 15 2025'
---

## Leading a NASA Robotics Team to World Championship

In 2024, I had the incredible opportunity to lead a 5-person software team for the NASA Robotics Alliance Project with Pasadena City College's Lancer Lumineers. We competed against 79 teams worldwide and secured **13th place at the world championship**.

### The Challenge

Our mission was to build and program a Remotely Operated Vehicle (ROV) capable of performing complex underwater tasks. The key challenges were:

- Real-time human-robot interaction
- Underwater navigation and manipulation
- Telemetry streaming and command processing
- 3D reconstruction of targets

### What We Built

I optimized the GUI for pilot feedback with real-time commands and telemetry streaming, which **improved ROV maneuverability by 30%** during operations. We also integrated 3D reconstruction capabilities to generate accurate real-world scaled models for engineering validation.

## Current Work: Network Systems for Culvert Inspection

Today, I'm working as a Robotics Engineer Intern at Caltrans, developing an end-to-end control stack for a culvert-inspection robot. The system operates over custom-made IP Manet radio and exposes a RESTful API built with FastAPI.

### Technical Highlights

- **WebSocket endpoints** running at 20-50 Hz for real-time control
- **Field-ready network topology** enabling simultaneous HoverMap and RaspberryPi access
- **Automated network bring-up** with Bash/Python scripts for health checks
- DHCP/static addressing, routing rules, and NAT/port-forwarding configuration

The automation scripts I developed cut on-site setup time significantly and accelerate fault isolation using ping, iperf3, and tcpdump logging.

## Machine Learning for Autonomous Vehicles

At UC San Diego's SEElab, I'm pushing the boundaries of trajectory prediction for autonomous vehicles. I'm developing and benchmarking novel models including:

- A dual-head Graph Neural Network (GNN)
- An LLM-based approach using LLaMA-Factory

### Data Engineering at Scale

I architected a Python ETL pipeline using pandas and NumPy to process **100k+ multimodal NuScenes records** including LiDAR, camera, and CAN bus data. This pipeline enables context-aware decision making for autonomous vehicles.

I'm also designing an agent-centric framework for 3D dense captioning in AVs, defining system requirements for dynamic scene understanding.

---

*These experiences have taught me that robotics isn't just about writing code—it's about building reliable systems that work in the real world, under real constraints.*