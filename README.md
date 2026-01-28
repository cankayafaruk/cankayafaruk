# Computer Science Student | Systems & Applied Logic

> *"Understand the input, trace the logic, verify the result."*

Focusing on how systems behave under real-world conditions. I work on building **predictable and reliable systems** by identifying where assumptions fail and correcting the underlying logic.

---

## 🔬 Engineering Case Studies

### 🛸 [YOLO Benchmark](https://github.com/cankayafaruk/Drone-Detection-Benchmark) | Detection Reliability Analysis  
*Applied research on object detection for small and distant targets in aerial environments.*

- **Problem:** Standard models failed in real scenarios due to a **~90% negative/background sample imbalance**.
- **Engineering Fix:** Corrected data distribution and increased input resolution (**640px → 1280px**) to improve feature extraction for distant objects.
- **Outcome:** Established a unified benchmarking pipeline across **YOLO v5–v11**, enabling reproducible comparison of **Precision / Recall / mAP / mAP@50** metrics for defense-oriented use cases.

---

### 🛡️ [AeroGuard-CV](https://github.com/cankayafaruk/AeroGuard-CV) | Perception & Control Logic  
*Developing consistent tracking behavior for autonomous systems.*

- **Problem:** Hardware-dependent frame rates caused unstable PID control behavior.
- **Engineering Fix:** Decoupled control logic from FPS using a **`delta_time (dt)`-based update mechanism**.
- **Logic:** Designed pixel-to-coordinate space mapping and **intent-driven target selection**, allowing full-scene perception while responding only to explicitly requested targets.

---

## 🔐 Security & System Auditing  
*Using security research to understand internal system boundaries and protocol behavior.*

- **Program Analysis:** Experience with **Ghidra** (static) and **GDB** (dynamic) for observing memory state and execution flow.
- **System Auditing:** Identifying logical weaknesses in state handling, authentication, and trust boundaries.
- **Low-Level:** Practical exposure to **x86 assembly** through reverse engineering.
- **Approach:** Focused on understanding system behavior rather than tool-driven exploitation.

---

## 🛠️ Technical Literacy

| Category | Skills & Tools |
| :--- | :--- |
| **Primary Stack** | Python, Linux (Bash), SQL |
| **Exposure** | C++, JavaScript, PHP (analysis & modification) |
| **AI & Perception** | PyTorch, OpenCV, YOLO architectures, metric evaluation |
| **Workflow** | Git/GitHub, Ubuntu, iterative experimentation |

---

## 📝 Ongoing Research

- **Comparative Study on Modern Object Detection Architectures**  
  *A systematic analysis of performance trade-offs in YOLO-based models.*  
  **Status:** Study completed; **currently awaiting official publication**

---

### 🎯 Core Philosophy

I treat engineering as the process of making systems **explainable**.  
If a system fails, I fix the underlying assumption—not just the symptom.
