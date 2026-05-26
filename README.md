# Jelly Slide

> A GPU-accelerated soft-body interactive slider built with **TypeScript**, **WebGPU**, and **TypeGPU**, exploring next-generation browser-native rendering, shader-driven animation systems, and physically inspired UI interactions.

---

## Overview

**Jelly Slide** is an experimental real-time interactive UI system that reimagines conventional sliders through **soft-body deformation**, **GPU-assisted rendering**, and **shader-driven visual dynamics**.

Unlike traditional DOM-based sliders, Jelly Slide leverages the emerging **WebGPU** standard alongside **TypeGPU** abstractions to create fluid, physically inspired interface motion with high-performance rendering pipelines.

The project investigates how modern browser graphics architectures can support:

* Soft-body UI simulation
* Hybrid CPU-GPU animation systems
* Real-time shader-based rendering
* Interactive physically inspired interfaces
* GPU-native UI experimentation
* Advanced visual feedback systems

---

# Preview

The slider dynamically deforms and reacts during interaction, creating a jelly-like motion behavior driven by hybrid animation logic and shader pipeline processing.

### Features demonstrated:

* Real-time jelly deformation
* Dynamic lighting direction
* Interactive color manipulation
* Blur/glow rendering
* Percentage-based animated loading
* Soft-edge physically inspired transitions
* GPU-rendered visual interpolation

---

# Research Motivation

Modern web interfaces remain largely constrained by:

* DOM-based rendering limitations
* CPU-heavy animation systems
* Limited physically expressive interaction models

Jelly Slide explores an alternative paradigm:

> **GPU-native interface rendering for emotionally expressive and physically reactive UI systems.**

The project acts as both:

* a rendering experiment, and
* a prototype for future interactive design systems powered by WebGPU.

---

# Core Architecture

```text
User Interaction
        │
        ▼
Animation Controller
        │
        ▼
Soft-Body Simulation Layer
(Hybrid CPU-GPU Logic)
        │
        ▼
Shader Pipeline (WGSL)
        │
        ▼
WebGPU Rendering Engine
        │
        ▼
Interactive Jelly Visualization
```

---

# Technical Highlights

## Soft-Body Inspired Motion System

The slider uses a visually driven soft-body deformation approach that simulates:

* elasticity,
* tension,
* damping,
* and fluid transitional movement.

This creates the jelly-like response during loading progression and interaction.

---

## Hybrid CPU-GPU Rendering Pipeline

Jelly Slide adopts a **hybrid rendering architecture**:

| Component         | Execution |
| ----------------- | --------- |
| Interaction Logic | CPU       |
| Animation State   | CPU       |
| Shader Processing | GPU       |
| Lighting Effects  | GPU       |
| Blur/Glow Effects | GPU       |
| Final Rendering   | GPU       |

This separation allows efficient rendering while maintaining responsive interaction handling.

---

# Shader Pipeline

The rendering system utilizes custom shader pipelines through:

* WebGPU
* TypeGPU abstractions
* WGSL shader execution

The shader system controls:

* soft gradients,
* light diffusion,
* glow effects,
* edge blending,
* dynamic color interpolation,
* and animated visual transitions.

---

# Technologies Used

| Technology | Purpose                     |
| ---------- | --------------------------- |
| TypeScript | Application architecture    |
| WebGPU     | GPU-native rendering        |
| TypeGPU    | Typed GPU abstraction layer |
| WGSL       | Shader programming          |
| Vite       | Development and bundling    |

---

# Interactive Controls

The system currently supports:

* Quality adjustment
* Dynamic light direction
* Jelly color customization
* Blur toggling
* Real-time progress animation (1–100%)

---

# Performance Characteristics

The project is designed for:

* low-latency rendering,
* smooth animation interpolation,
* and responsive GPU-assisted interaction.

Performance benefits include:

* reduced DOM overhead,
* shader-based visual computation,
* and efficient rendering execution through WebGPU.

---

# Browser Compatibility

## Recommended

* Google Chrome Canary
* Microsoft Edge Canary

with:

```bash
--enable-unsafe-webgpu
```

## Requirements

* WebGPU-enabled browser
* Node.js v18+
* Modern GPU drivers

---

# Installation

```bash
git clone https://github.com/rahulkiran2222/jelly-slide.git

cd jelly-slide

npm install

npm run dev
```

---

# Project Structure

```text
src/
│
├── shaders/          # WGSL shader modules
├── renderer/         # WebGPU rendering pipeline
├── animation/        # Soft-body animation logic
├── controls/         # Interactive parameter controls
├── gpu/              # GPU abstraction utilities
├── ui/               # Interface components
└── main.ts           # Application entry point
```

---

# Experimental Focus Areas

This project explores research directions in:

* GPU-native UI systems
* Real-time browser graphics
* Physically expressive interfaces
* Soft-body interaction models
* Human-computer interaction (HCI)
* WebGPU rendering architectures
* Interactive shader systems

---

# Future Work

Planned extensions include:

* Fully GPU-driven physics simulation
* Compute shader integration
* Multi-object soft-body interaction
* Advanced fluid dynamics
* Adaptive haptic-inspired animation
* WebXR interaction support
* AI-assisted motion synthesis
* Procedural material systems

---

# Academic Relevance

Jelly Slide can serve as a prototype system for research involving:

* computational interaction design,
* browser graphics systems,
* physically inspired UI rendering,
* and next-generation GPU-assisted interface engineering.

---

# License

MIT License

---

# Citation

If referencing this work in research or academic projects:

```bibtex
@software{jellyslide2026,
  title={Jelly Slide: A WebGPU-Based Soft-Body Interactive UI System},
  author={Rahul Kiran G},
  year={2026},
  url={https://github.com/rahulkiran2222/jelly-slide}
}
```

---

# Acknowledgements

Inspired by:

* GPU-native rendering research
* Physically based interaction systems
* Experimental motion design
* Modern shader-driven interfaces
* Next-generation browser graphics architectures
