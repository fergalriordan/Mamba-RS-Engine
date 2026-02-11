# Mamba-RS-Engine

High-throughput inference engine for Remote Sensing (RS) change detection, utilizing **State Space Models (RS-Mamba)** and optimized via **C++/TensorRT** for edge-constrained environments.

## Project Goals
- **Architecture:** Implement an omnidirectional State Space Model (RS-Mamba) to bypass the $O(N^2)$ complexity of Vision Transformers in high-res satellite imagery.
- **Domain:** Rapid identification of environmental changes (Wildfires/Flooding) using the LEVIR-CD or OSCD datasets.
- **Optimisation:** Develop a standalone C++ inference server achieving >2x throughput vs. PyTorch baselines.

---
*Developed by Fergal Riordan as part of ongoing upskilling in MLE focusing on Physical AI and Environmental Tech.*
