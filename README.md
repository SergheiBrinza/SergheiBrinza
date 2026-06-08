# Serghei Brinza

**Quantum + AI · intelligent instruments, LLM fine-tuning, quantum-classical hybrids**

Physics and NMR background, sixteen years teaching quantum mechanics, now building
scientific instruments where the sensor, the firmware, the signal pipeline, and the
model live in one project — and, lately, small quantum subroutines that sit behind
stable classical interfaces in an LLM stack.

## Quantum Co-Processor program

Three open research projects asking where a small quantum routine can do real work
inside an LLM pipeline. Each ships a tested library, a live demo Space, and honest
benchmarks. These are research prototypes on quantum simulators (QVerify also runs
on real IBM hardware); **no quantum advantage is claimed** — the goal is working,
honestly measured quantum subroutines behind classical interfaces.

### QVerify — Grover verification on real IBM quantum hardware

Translates each LLM reasoning step to propositional CNF, grounds it over a finite
universe, and checks logical consistency with Grover's algorithm — on a CPU
simulator or IBM's 156-qubit Heron r2 processor.

[![GitHub](https://img.shields.io/badge/GitHub-Quantum--Labor%2Fqverify-181717?logo=github)](https://github.com/Quantum-Labor/qverify)
[![Live Space](https://img.shields.io/badge/Live%20Space-Laborator%2Fqverify-FFD21E?logo=huggingface&logoColor=000)](https://huggingface.co/spaces/Laborator/qverify)

`v1.0.1` · 485 tests · 14 verified IBM Heron r2 hardware runs.

### QAgent — QAOA tool selection for LLM agents

Picks the best subset of *k* tools from *N* with the Quantum Approximate
Optimization Algorithm, accounting for the tool-pair interactions a greedy ranking
ignores.

[![GitHub](https://img.shields.io/badge/GitHub-Quantum--Labor%2Fqagent-181717?logo=github)](https://github.com/Quantum-Labor/qagent)
[![Live Space](https://img.shields.io/badge/Live%20Space-Laborator%2Fqagent-FFD21E?logo=huggingface&logoColor=000)](https://huggingface.co/spaces/Laborator/qagent)

`v0.2` · approximation ratio 0.915 at N=16 (vs greedy 0.735).

### QRoute — VQC mixture-of-experts router for Gemma 4

A variational quantum circuit that routes tokens to experts in a Mixture-of-Experts
layer: *n* qubits give 2^n basis states, one per expert, so a tiny circuit scores an
exponential number of experts.

[![GitHub](https://img.shields.io/badge/GitHub-Quantum--Labor%2Fqroute-181717?logo=github)](https://github.com/Quantum-Labor/qroute)
[![Live Space](https://img.shields.io/badge/Live%20Space-Laborator%2Fqroute-FFD21E?logo=huggingface&logoColor=000)](https://huggingface.co/spaces/Laborator/qroute)

Phase 1 prototype (toy MoE) plus a full-scale 128-expert / 7-qubit design.

## What I work on

Hardware-aware AI. I'm most useful when a problem needs someone who can design a
PCB, flash a microcontroller, tune a neural network, and ship the whole thing as a
product. Current focus areas:

- Scientific instrumentation with integrated AI (microscopy, radio astronomy, sensor arrays)
- Quantum-classical hybrids: small quantum subroutines inside LLM pipelines
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

Python, C, C++, Rust when needed, TypeScript for UI, FastAPI and Flask for backends,
React for frontends, PyTorch and ONNX for models, Docker for deployment, Linux
everywhere. For the quantum work: PennyLane, Qiskit, IBM Quantum, Gradio, Hugging
Face, and GitHub Actions for CI and auto-deploy.

## Links

- GitHub organization for the quantum work: [Quantum-Labor](https://github.com/Quantum-Labor)
- Hugging Face: [Laborator](https://huggingface.co/Laborator)
- This profile: [github.com/SergheiBrinza](https://github.com/SergheiBrinza)
