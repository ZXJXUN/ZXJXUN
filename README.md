# Hi, I'm ZXJXUN (孙迅) 👋

**Beihang University** · School of Automation Science and Electrical Engineering · Robotics Engineering (Class of 2027)
Ph.D. student (admitted) @ Renmin University of China — Engineering Doctorate Program, AI & Big Data (2027.9)

🌐 **Personal site:** [zxjxun.github.io](https://zxjxun.github.io)

- 🛩️ **CUADC 2025** (China Universities Aircraft Design Competition) — Fixed-Wing UAV Reconnaissance & Strike, **National 2nd Prize**
- 🏆 **ROBOCON** — National 1st Prize · 🚗 National Intelligent Car Contest — Regional 2nd Prize
- 🧠 On-board vision: **YOLO11-OBB/CLS cascade + TensorRT FP16 + CUDA multi-stream** on Jetson Orin NX — 91.8% recognition @ 26 FPS
- 🔭 Currently looking for: research opportunities in **embodied intelligence & edge-side deployment**

## 📂 Portfolio

| | |
|---|---|
| [![Portfolio](https://img.shields.io/badge/📖-Personal_Portfolio-1e6bb8?style=flat-square)](./portfolio/README.md) | Slide-style portfolio — self introduction, publications, skills, awards |
| [![Report](https://img.shields.io/badge/🛩️-CUADC_Design_Report-2e8bc0?style=flat-square)](./uav-design-report/README.md) | Full design report of the fixed-wing UAV reconnaissance & strike system (2025 CUADC) |

### System at a glance

| Vision (Jetson Orin NX 16GB) | Flight Control | Airframe |
|---|---|---|
| YOLO11-OBB / CLS / det cascade, 91.8% digit accuracy @ 26 FPS; CUDA 4-stream concurrency (+158% FPS); TensorRT FP16 (4.73 ms/img) | Self-built **BLink** (pymavlink) comms module; Lua aerobatic scripts (35° steep climb, half-roll); autonomous aerobatic waypoint planning (103 s → 67 s) | N11 airfoil, 1.74 m span, 2.4 kg AUW, folding wing, full-flying tail; crosswind-compensated drop trajectory (RK4) |

➡️ Details: [Personal Portfolio](./portfolio/README.md) · [Design Report (CN)](./uav-design-report/README.md)
