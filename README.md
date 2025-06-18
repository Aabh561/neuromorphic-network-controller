# 🧠 Neuromorphic Network Controller
## Simulating Spiking Neural Networks for Adaptive, Resilient Traffic Routing

---

### 🔬 Overview

This project builds a **brain-inspired digital twin of a computer network** where each router behaves like a spiking neuron.  
It simulates **real-time adaptive routing**, resilience to failures, and autonomous decision-making using **Spiking Neural Networks (SNNs)** — the third generation of neural networks.

> Designed for cutting-edge AI-driven network management research, this system reflects how biological intelligence can optimize digital infrastructure.

---

### 💡 What Makes It Unique?

| 🔍 Feature | 🧠 Neuromorphic Edge |
|-----------|-----------------------|
| **Routing with spikes** | Decisions are triggered by neuron-like activity (no static tables) |
| **Self-adaptive** | System reacts instantly to link failures or node delays |
| **Live control** | Interactive dashboard simulates traffic, failures, and routing |
| **Digital Twin** | Models a realistic ring topology (6-node) — extendable to N |
| **Biological realism** | Neuron spikes governed by membrane potential and time constants |

---

### 🧪 Core Technologies

- `Brian2` → Spiking neuron simulation (Leaky Integrate-and-Fire model)
- `NetworkX` → Ring topology and path computation
- `Matplotlib` → Real-time routing and neural activity plots
- `IPyWidgets` → Interactive simulation controls (failures, reset, activity pulse)
- `Jupyter Notebook` → Research-first platform (no web deployment clutter)

---

### 🖥️ How It Works

1. **Network Topology**: A 6-node ring is created — similar to a router mesh.
2. **Neuron Mapping**: Each node gets a neuron with spiking behavior.
3. **Traffic Pulse**: A packet is simulated as a spike from a source node.
4. **Failure Simulation**: Random link failure is injected using widget controls.
5. **Neural Routing**: Neuron responses determine path rerouting dynamically.

---

### 🧬 Why Spiking Neural Networks?

Unlike traditional neural networks, **SNNs process information over time using spikes**, just like the brain.  
This makes them:
- ⚡ Ultra-fast
- 💡 Energy efficient
- 🔁 Naturally asynchronous (perfect for distributed networks)

---

### 🎓 Research Use Case

This simulation serves as a **foundation for neuromorphic SDN (Software Defined Networking)** and can evolve into:

- Intelligent routers with embedded spiking chips (Loihi, SpiNNaker)
- AI-driven 5G edge routing
- Autonomous recovery systems for critical infrastructure

---

### 📷 Preview

> Visualization of the ring network and neural pulse routing

![Demo Preview](assets/neuromorphic-routing-demo.gif)

---

### 📁 Folder Structure
## 🚀 Launch Notebook

[![Open in Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/Aabh561/neuromorphic-network-controller/blob/main/Neuromorphic_Network_Controller.ipynb)




