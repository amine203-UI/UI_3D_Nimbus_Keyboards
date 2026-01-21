<div align="center">
  <img src="/public/image-for-readme.png" alt="Project Banner" width="800">

  <h1 align="center">Nimbus 3D Keyboards</h1>

  <p align="center">
    A premium, high-performance 3D landing page experience built with Next.js 15 and GSAP.
  </p>

  <div>
    <img src="https://img.shields.io/badge/-Next.js_15-black?style=for-the-badge&logo=nextdotjs&color=000000" alt="nextjs" />
    <img src="https://img.shields.io/badge/-Three_JS-black?style=for-the-badge&logo=threedotjs&color=000000" alt="three.js" />
    <img src="https://img.shields.io/badge/-GSAP-black?style=for-the-badge&logo=greensock&color=88CE02" alt="greensock" />
    <img src="https://img.shields.io/badge/-Tailwind_CSS-black?style=for-the-badge&logo=tailwindcss&color=06B6D4" alt="tailwindcss" />
    <img src="https://img.shields.io/badge/-TypeScript-black?style=for-the-badge&logo=typescript&color=3178C6" alt="typescript" />
  </div>

  <br />
</div>

---

## 📖 Table of Contents
* [Introduction](#introduction)
* [Tech Stack](#tech-stack)
* [Key Features](#features)
* [Project Architecture](#architecture)
* [Quick Start](#quick-start)

---

## <a name="introduction">🤖 Introduction</a>

**Nimbus 3D** is a modern, responsive landing page designed to showcase premium hardware through immersive web technology. By leveraging **Next.js 15** and **GSAP**, the project achieves fluid, high-performance animations that were previously reserved for high-end cinematic web experiences. 

This project goes beyond simple scrolling, featuring complex **parallax depth**, **scroll-triggered timelines**, and **physics-based easing** to create a tactile digital product showcase.

---

## <a name="tech-stack">⚙️ Tech Stack</a>

| Technology | Purpose |
| :--- | :--- |
| **Next.js 15** | React Framework with App Router & Server Components |
| **Three.js** | Rendering high-quality 3D models and environments |
| **GSAP** | Industry-standard animation engine for ScrollTrigger & Timelines |
| **Tailwind CSS** | Utility-first styling for rapid, responsive UI development |
| **TypeScript** | Ensuring type safety and scalable code architecture |
| **Vite** | Lightning-fast build tool and development server |

---

## <a name="features">🔋 Features</a>

### ✨ Immersive Visuals
* **3D Interactive Models:** Real-time 3D transforms with optimized geometry.
* **Physics-Based Easing:** Natural-feeling motion using GSAP's advanced easing functions.
* **Parallax Storytelling:** Multi-layered background and foreground motion as you scroll.

### 🚀 Performance Optimized
* **Next.js 15 Power:** Fully utilizing the latest App Router for optimized routing and loading.
* **GPU Acceleration:** Animations are offloaded to the GPU to ensure a steady 60 FPS.
* **Asset Lazy-Loading:** 3D models and high-res images load only when needed.

### 🛠 Professional Engineering
* **Responsive Design:** Seamless experience across Ultra-wide monitors, Laptops, and Mobile.
* **Clean Codebase:** Modular component structure with strict TypeScript definitions.

---

## <a name="architecture">🏗 Project Architecture</a>

```text
├── public/             # 3D Models and static assets
├── src/
│   ├── components/     # Reusable UI and 3D Canvas elements
│   ├── animations/     # GSAP timeline definitions
│   ├── hooks/          # Custom hooks for scroll/resize tracking
│   └── app/            # Next.js 15 App Router pages
