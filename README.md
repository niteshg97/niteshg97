#!/usr/bin/env bash
# create_readme.sh
# Single-file bash script to generate a polished README.md for Nitesh Kumar
# It embeds a local path to the uploaded resume at /mnt/data/Nitesh_Resume.pdf
#
# Usage:
#   ./create_readme.sh
# This will create (or overwrite) README.md in the current directory.

set -euo pipefail

OUT_FILE="README.md"
RESUME_PATH="/mnt/data/Nitesh_Resume.pdf"

cat > "$OUT_FILE" <<'README'
# 👋 Hey there — I’m **Nitesh Kumar**
### Robotics Researcher • ML & Edge-AI Engineer • Autonomous Systems Developer

[![GitHub followers](https://img.shields.io/github/followers/niteshg97?label=follow&style=social)](https://github.com/niteshg97)  
[![LinkedIn](https://img.shields.io/badge/LinkedIn-Nitesh%20Kumar-blue?style=for-the-badge&logo=linkedin)](https://www.linkedin.com/in/nitesh-kumar-68a698275)  
[![Email](https://img.shields.io/badge/Email-niteshk.ug23.ee%40nitp.ac.in-red?style=for-the-badge&logo=gmail)](mailto:niteshk.ug23.ee@nitp.ac.in)  
[![LeetCode](https://img.shields.io/badge/LeetCode-niteshkumarnitp-FFA116?style=for-the-badge&logo=leetcode&logoColor=white)](https://leetcode.com/u/niteshkumarnitp/)

---

## 🚀 About Me
I’m an **Electrical Engineering (Dual Degree)** student at **NIT Patna**, building intelligent machines that **see, decide, and act**.

My work lives at the intersection of:

- **Robotics & Perception** — UAV autonomy, SLAM/EKF, multi-robot coordination  
- **Deep Learning & Vision** — Transformers, YOLO, medical imaging, scientific ML  
- **Embedded AI** — Jetson, FPGA/HLS (hls4ml), real-time optimized inference  
- **Edge Autonomy** — hardware-aware models, quantization & pruning, GPU pipelines  

I enjoy converting research ideas into **field-ready robotic systems** and **deployment-grade ML pipelines**, often under tight latency, power, and bandwidth constraints.

---

## 🔎 Professional Snapshot
> *“I build autonomy stacks that run not just in simulation, but in the real world.”*

- **2+ years** working across robotics, AI, and embedded systems  
- Experience with **PX4, ROS 2, GPU pipelines, SLAM, YOLOv8**, and real-time sensor fusion  
- Designed **quantized + pruned neural networks** for **FPGA** using **hls4ml**  
- Academic/research exposure to **medical imaging**, **particle physics ML**, and **beamline analysis**  
- Achieved **top 3% JEE rank**, 250+ LeetCode solves, and multiple research/tech awards  

---

## 🛠 Technical Ecosystem

**Languages**  
Python · C++ · MATLAB · Java · C

**Robotics & Perception**  
ROS 2 (Humble) · PX4 · MAVROS · Gazebo · OpenCV · YOLOv8 · SLAM/EKF

**Machine Learning & DL**  
PyTorch · TensorFlow · scikit-learn · hls4ml · RAPIDS · CUDA · Quantization & Pruning

**Embedded & Hardware**  
NVIDIA Jetson (Xavier NX) · Raspberry Pi · Microcontrollers · FPGA (HLS)

**Tools & Frameworks**  
Docker · Git · HDF5 · TensorBoard · Node.js · WebXR

**Domains**  
Edge AI · Robotics · Medical Imaging · ML in Physics · Scientific Computing

---

## 💼 Experience

### 🔹 Technology Innovation Hub (TiH), IIT Jodhpur — *Summer Intern (May–Jul 2025)*
- Engineered **leader–follower UAV formation** using ArUco markers; improved coordination accuracy by *~30%*.  
- Built **WebXR teleoperation** for Kinova Gen3 using WebRTC, Node.js & ARCore.  
- Deployed YOLOv8 + PX4 autonomy stack on **NVIDIA Jetson** with Dockerized reproducibility.  
- Presented at **AIR 2025**, 7th International Robotics Society Conference.

### 🔹 Machine Learning Researcher — NIT Patna (Jul 2025 – Present)
- Researching **quantized + pruned neural networks** for FPGA/Jetson using **hls4ml**.  
- Developed **Faster-RCNN, ViT, and CNN pipelines** for medical imaging & scientific datasets.  
- Integrated GPU-accelerated workflows for high-dimensional physics data.

### 🔹 Student Coordinator — Tinkering Lab, NIT Patna
- Leading ML + Robotics teams on UAV autonomy, CV, and embedded AI.  
- Conduct workshops on deep learning, ROS 2, sensor fusion & control systems.

---

## 🚀 Selected Projects

### 🛩 Autonomous Navigation Aerial Vehicle (ANAV) — ISRO IRoC-U 2025 (Qualified)
- Full **ROS2 + PX4** autonomy stack on Jetson Xavier NX  
- EKF for **LiDAR + IMU** fusion  
- Real-time **terrain understanding** via YOLOv8 + IMX290 camera

### 🌾 Agribot — Autonomous Agriculture Robot (2nd Prize, NIT Patna Tech Fest)
Soil-sensing, navigation planning & automated seed-dispensing robot.

### 🩺 KidneyViT — Vision Transformer for Kidney CT
- Custom PyTorch ViT achieving **99.80% accuracy**  
- Attention maps for clinical interpretability

### 🧪 Low-cost 2D Position-Sensitive Muography Detector
- Built 5×5 CsI + SiPM detector  
- Validated with cosmic-ray tests + **2.01 GeV** beamline

### 🧬 HAR Model Quantization & Pruning (hls4ml)
FPGA-ready quantized/pruned NN with **~93.5% retained accuracy** and major latency reduction.

---

## 🌟 Conferences & Research Exposure

### Advances in Robotics (AIR 2025) — Participant & Presenter
Showcased multi-UAV formation and teleoperation research.

#### Event Highlights
![AIR 2025](images/air2025.jpg)
![Panel](images/air2025_panel.jpg)

#### UAV Demonstration
![AIR 2025](videos/air2025_uav.gif)

---

## 🧩 What I’m Exploring Now
- 🚁 Multi-robot coordination under uncertainty  
- 🔬 Scientific ML for high-dimensional physics problems  
- ⚡ Ultra-efficient models for edge AI (Jetson/FPGA)  
- 🤖 Cross-domain autonomy: vision + control + planning

---

## 📬 Open to Collaborations
I’d love to connect for roles or research in: **Robotics • Computer Vision • Embedded AI • Autonomous Systems • Scientific ML**

Reach out via **LinkedIn** or **email**.

---

## 📄 Resume
You can access the uploaded resume here: [Nitesh_Resume.pdf]($RESUME_LINK)

---

*Want a different vibe?*  
- Minimalist / one-page resume README  
- Animated ASCII banner + dark theme  
- GitHub Pages profile-ready variant

Run `./create_readme.sh --minimal` to generate a shorter README (if you want a minimal variant).
README

# Replace the placeholder variable $RESUME_LINK inside README.md with the local file path as a markdown link.
# As per instructions, write the local file path into the README.md link so tooling can transform it later.
# We'll inject the path literal so other tools can pick it up correctly.

# Escape any slashes for sed compatibility (use perl for reliability)
perl -0777 -pe "s/\\\$RESUME_LINK/$(printf "%s" "$RESUME_PATH" | perl -pe 's/\\/\\\\\\//g')/ge" -i "$OUT_FILE"

echo "README.md generated at $(pwd)/$OUT_FILE"
echo "Embedded resume path: $RESUME_PATH"


