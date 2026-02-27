<!-- ========================= HERO SECTION ========================= -->

<h1 align="center">
  <img src="https://readme-typing-svg.herokuapp.com?font=Orbitron&weight=600&size=28&duration=3000&pause=800&color=00F7FF&center=true&vCenter=true&width=800&lines=Hi+I'm+Praveen+Kumar+M;Robotics+%7C+AI+Systems+Engineer;ROS2+%7C+Autonomous+Robots+%7C+Perception;Building+Intelligent+Machines+for+Real+World" />
</h1>

<h3 align="center">⚙️ AI + Robotics Systems Innovator | Architecting Autonomous Machines at Scale</h3>

<p align="center">
Designing real-world robotics systems that move, perceive, and decide — reliably, intelligently, autonomously.
</p>

---

<!-- ========================= ABOUT ME ========================= -->

## 🧠 About Me

I am a Robotics Engineer specializing in **ROS2-based autonomous systems**, currently pursuing the **Erasmus Mundus Joint Master in Intelligent Field Robotic Systems (IFRoS)**.

My work focuses on **autonomy, perception, and deployment-ready robotics systems** — going beyond simulations into real-world execution.

I have engineered **AGVs and AMRs**, integrating **LIDAR perception, Navigation Stack 2, and AI-driven decision pipelines** for dynamic environments.

I bring a **systems-level mindset**, combining **embedded control, robotics architecture, and AI integration** into cohesive, scalable solutions.

With experience across **industrial robotics (YASAKAWA, FANUC)** , I understand both **research depth and production constraints**.

I have also led **20+ innovation projects** and delivered training sessions to **2000+ learners**, translating complex systems into actionable engineering.

---

<!-- ========================= TECH STACK ========================= -->

## ⚡ Technical Architecture Stack

### 🤖 Robotics & Autonomy
![ROS2](https://img.shields.io/badge/ROS2-22314E?style=for-the-badge&logo=ros&logoColor=white)
![Navigation2](https://img.shields.io/badge/Nav2-Autonomous%20Navigation-blue?style=for-the-badge)
![SLAM](https://img.shields.io/badge/SLAM-LIDAR%20Mapping-green?style=for-the-badge)
![AMR](https://img.shields.io/badge/AMR-Autonomous%20Robots-orange?style=for-the-badge)

### 🧠 AI & Perception
![Python](https://img.shields.io/badge/Python-AI%20%26%20ML-yellow?style=for-the-badge&logo=python)
![Computer Vision](https://img.shields.io/badge/Computer%20Vision-OpenCV-red?style=for-the-badge)
![Machine Learning](https://img.shields.io/badge/ML-Random%20Forest-purple?style=for-the-badge)

### ⚙️ Embedded & Control
![Embedded Systems](https://img.shields.io/badge/Embedded-C%20%2F%20Microcontrollers-grey?style=for-the-badge)
![Control Systems](https://img.shields.io/badge/Control-Real--Time-blueviolet?style=for-the-badge)

### 🏭 Industrial Robotics
![KUKA](https://img.shields.io/badge/KUKA-Industrial%20Automation-orange?style=for-the-badge)
![FANUC](https://img.shields.io/badge/FANUC-Robotics-yellow?style=for-the-badge)

### 🛠️ Tools & Systems
![Linux](https://img.shields.io/badge/Linux-Ubuntu-black?style=for-the-badge&logo=linux)
![Git](https://img.shields.io/badge/Git-Version%20Control-red?style=for-the-badge&logo=git)
![Docker](https://img.shields.io/badge/Docker-Containerization-blue?style=for-the-badge&logo=docker)

---

<!-- ========================= IMPACT ========================= -->

## 🏆 Industry & Leadership Impact

- 🚀 Led **20+ robotics innovation projects** across multiple domains  
- 🏭 Collaborated with **Ashok Leyland & industrial partners** on applied robotics systems  
- 👨‍🏫 Delivered technical sessions to **2000+ students**, simplifying complex robotics systems  
- ⚙️ Strong experience across **end-to-end robotics product lifecycle**  
- 🔌 Expertise in **hardware–software integration and system orchestration**  
- 📦 Built and deployed **AGVs & AMRs** for real-world applications  

---

<!-- ========================= RESEARCH ========================= -->

## 🔬 Research & Future Focus

- Field Robotics in **unstructured and harsh environments**  
- Scalable **ROS2-based autonomy architectures**  
- AI-driven perception for **real-time decision making**  
- Multi-robot systems & distributed intelligence  
- Intelligent navigation beyond structured environments  

Currently advancing through **IFRoS (Erasmus Mundus)** with a focus on **globally deployable robotics systems**.

---

<!-- ========================= GITHUB STATS ========================= -->

## 📊 GitHub Analytics

<p align="center">
  <img src="https://github-readme-stats.vercel.app/api?username=YOUR_USERNAME&show_icons=true&theme=tokyonight&hide_border=true" height="160"/>
  <img src="https://github-readme-streak-stats.herokuapp.com/?user=YOUR_USERNAME&theme=tokyonight&hide_border=true" height="160"/>
</p>

<p align="center">
  <img src="https://github-readme-stats.vercel.app/api/top-langs/?username=YOUR_USERNAME&layout=compact&theme=tokyonight&hide_border=true"/>
</p>

---

<!-- ========================= CONTRIBUTION SNAKE ========================= -->

## 🐍 Contribution Animation

```yaml
name: Generate Snake

on:
  schedule:
    - cron: "0 0 * * *"

jobs:
  build:
    runs-on: ubuntu-latest
    steps:
      - uses: Platane/snk@v3
        with:
          github_user_name: YOUR_USERNAME
          outputs: |
            dist/github-contribution-grid-snake.svg

      - uses: crazy-max/ghaction-github-pages@v3
        with:
          target_branch: output
          build_dir: dist
