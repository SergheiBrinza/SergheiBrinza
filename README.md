# Serghei Brinza

AI engineer based in Vienna. I build scientific instruments where the sensor, the firmware, the signal pipeline, and the model all live in the same project.

## What I work on

Hardware-aware AI. I'm most useful when a problem needs someone who can design a PCB, flash a microcontroller, tune a neural network, and ship the whole thing as a product. Some of that in each project.

Current focus areas:

- Scientific instrumentation with integrated AI (microscopy, radio astronomy, sensor arrays)
- Multi-GPU inference infrastructure for local LLM stacks
- Computer vision for biological and medical signals
- Language model efficiency (quantization, parameter-constrained training)

## Selected projects

**[sovereign-ai-stack](https://github.com/SergheiBrinza/sovereign-ai-stack).** Self-hosted local AI stack on a 3-GPU workstation with Ollama, vLLM, API key routing, GPU mutex, and a noVNC web UI. For people who want to own their models and their data.

**[parameter-golf](https://github.com/SergheiBrinza/parameter-golf).** Personal case-study of my participation in the OpenAI Model Craft Challenge. Two submissions, 1.2421 and 1.1431 bits per byte on FineWeb, within 0.003 of the March 20 leaderboard top.

**[AI-Microscope](https://github.com/SergheiBrinza/AI-Microscope).** Computer vision and ML for optical microscopy: autofocus metrics, illumination analysis, specimen classification. Runs a ToupCam camera through a FastAPI backend with a React viewer and real-time WebSocket streaming.

**[HydrogenEye](https://github.com/SergheiBrinza/HydrogenEye).** Radio astronomy receiver built from a 28-euro RTL-SDR dongle. Detects the 21 cm hydrogen line with roughly 35 dB SNR. Raspberry Pi Zero W + Android app over Wi-Fi.

**[BioRNG](https://github.com/SergheiBrinza/BioRNG).** True random number generation from live fish behavior via computer vision. Entropy validated against the NIST SP 800-90B battery.

**[VRAM-Pressure-Scheduling](https://github.com/SergheiBrinza/VRAM-Pressure-Scheduling).** VRAM-aware GPU scheduling for multi-GPU AI workstations: priority preemption, NVLink topology constraints, thermal-aware placement. Six months of production results included.

**[api-tester-app](https://github.com/SergheiBrinza/api-tester-app).** Mobile tool for testing and managing API keys across AI inference providers. Works as a PWA and as an Android APK.

**[AI-Gas-Analyzer](https://github.com/SergheiBrinza/AI-Gas-Analyzer).** Neural classification of gas mixtures from metal-oxide sensor arrays. Inference on microcontroller hardware.

**[SO-101-LeRobot-Industrial-Swarm](https://github.com/SergheiBrinza/SO-101-LeRobot-Industrial-Swarm).** Multi-arm robotic swarm coordination through a WebSocket bus, built on the Hugging Face LeRobot SO-101 arm.

**[1420MHz-Feed-Horn](https://github.com/SergheiBrinza/1420MHz-Feed-Horn).** Waveguide feed horn design for 1420 MHz hydrogen line radio astronomy. Pairs with HydrogenEye.

## Stack

Python, C, C++, Rust when needed, TypeScript for UI, FastAPI and Flask for backends, React for frontends, PyTorch and ONNX for models, Docker for deployment, Linux everywhere.

Hardware side: KiCad for PCBs, STM32 and ESP32 for MCUs, standard bench instrumentation, CNC when needed.

## Contact

Open an issue on any of my repositories or reach out through the email on my GitHub profile.
