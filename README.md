# Hi, I'm Phongsakon Sithong (Sprites) 👋

AI Engineering and Data Science student at **Bangkok University**, focused on **robot perception**: making vision models run fast with **TensorRT** and integrating them into **ROS 2**.

Looking for a **6-month co-op placement (Jun–Nov 2027)** in robotics software or AI for robotics.

---

## 🔧 What I work with

**Languages** · Python · SQL

**AI / CV** · PyTorch · Ultralytics YOLO · ONNX Runtime · TensorRT (FP16/INT8) · CUDA · OpenCV

**LLM agents** · LangGraph · ChromaDB · Ollama

**Robotics** · ROS 2 Humble · Nav2 · TurtleBot3 · Isaac Sim

**DevOps & tools** · Docker · Nginx · GitHub Actions · Trivy · Linux (Ubuntu) · Git

---

## 📌 Projects

### ⚡ [YOLO Inference Optimization](https://github.com/Sprites-X/yolo-inference-optimization)
Benchmarked YOLOv8n across PyTorch, ONNX Runtime, TensorRT FP16 and INT8 on an RTX 5060.
- **TensorRT FP16: 702 FPS, 2.60× PyTorch** on the same GPU at baseline accuracy (mAP50-95 0.4006 vs 0.4008)
- 7 configurations on CPU and GPU, every export checked against the PyTorch baseline before timing
- Found INT8 slower *and* less accurate than FP16 on this model, and showed why

`PyTorch` `ONNX Runtime` `TensorRT` `CUDA` `Benchmarking`

### 🤖 TurtleBot3 Person Detection *(team of 3, Robotics course)*
A simulated TurtleBot3 calls a YOLO person-detection ROS 2 service every 0.5 m it travels and logs each result with the robot's position. I wrote the odometry distance client node and planned the project.

`ROS 2 Humble` `Python` `YOLO` `TurtleBot3`

### 🧾 [ERP Helpdesk Agent](https://github.com/Sprites-X/erp-helpdesk-agent)
Local multi-agent helpdesk (Thai) that answers ERP questions from the manual with a quoted evidence sentence, or opens a ticket when the manual has no answer.
- **19/20 correct decisions** on unseen questions; never answered one that needed a ticket
- Cut response time from 10.7 s to 2.8 s by timing each stage

`LangGraph` `ChromaDB` `Ollama` `pytest` `GitHub Actions`

### 🚀 [Chat AI Portfolio (ByteMind)](https://github.com/Sprites-X/chat-ai-portfolio) *(team of 3, Web Technology course)*
DevOps role: containerized the React and Express services and built a CI/CD pipeline that tests, builds, scans with Trivy and deploys only the side whose code changed.

`Docker` `Nginx` `GitHub Actions` `Trivy` `Render`

---

## 📫 Contact

- 📧 phongsakonsithong@gmail.com
- 💼 [LinkedIn](https://www.linkedin.com/in/phongsakon-sithong-275539430)
