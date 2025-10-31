GMU (Growth Monitoring Unit)

The Growth Monitoring Unit (GMU) is a system designed to monitor and analyze the growth of plants using automation and embedded intelligence.  
It mainly consists of two parts:

1. Rail System – Handles the movement of the ESP32-CAM module for capturing plant images and controlling the lighting setup.  
2. TinyML Modeling – Processes the captured images using a trained TinyML model to identify and classify different stages of plant growth.

The GMU uses an **ESP32-CAM** module as its core controller for both monitoring and model execution.  
It captures images, sends them for TinyML inference, and coordinates motor control through drivers for the rail movement.

This unit forms an important part of the Seed Incubation Plant Project, enabling smart growth tracking and analysis with minimal human intervention.

