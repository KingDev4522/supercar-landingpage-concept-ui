# 🏎️ Super Wheels | High-Performance Automotive UI

**[Solo Project - Lead UI/UX Engineer]**

![Status: Live Deployment](https://img.shields.io/badge/Status-Live_Deployment-brightgreen?style=for-the-badge)
![Tech: Vanilla JS & CSS](https://img.shields.io/badge/Tech-Vanilla_JS_%26_CSS-blue?style=for-the-badge)
![Animation: GSAP](https://img.shields.io/badge/Animation-GSAP_Powered-orange?style=for-the-badge)

**🚀 [CLICK HERE TO EXPERIENCE THE LIVE WEBSITE](https://supercar-landingpage-concept.vercel.app/) 🚀**

> ## 🏛️ Architectural Notice:
> This project is a high-fidelity front-end prototype. It was deliberately engineered without heavy UI frameworks (like React or Bootstrap) to build a rigorous foundational understanding of native DOM manipulation, advanced CSS rendering, and raw JavaScript state management.

---

## 👁️ The Vision: Engineering Digital Luxury
Super Wheels is an interactive landing page concept for a premium exotic car brand. The goal was to break away from static, template-based web design and build a tactile, cinematic experience. By combining advanced CSS easing with deep environmental lighting, the interface feels less like a standard website and more like a high-end digital showroom.

---

## ⚙️ Core Engineering Features

### 1. 🎨 Advanced CSS Rendering & Depth Lighting
* **Extruded 2.5D Typography:** Engineered a heavy, physical depth effect using solid chrome gradients and stacked pseudo-elements to entirely bypass standard WebKit rendering limitations.
* **Realistic Environment Blending:** Anchored transparent 2D assets into a faux-3D space using calculated `drop-shadow` filters, dense radial contact shadows, and fading glass floor reflections.
* **Advanced Easing Interactivity:** Implemented highly specific cubic-bezier CSS transitions to create satisfying, spring-loaded hover states and tactile button pop-outs.

### 2. 🎬 Cinematic Scroll Animations (GSAP)
* **Scroll-Triggered Reveals:** Utilized GSAP (GreenSock) to map opacity and Y-axis translations to the user's scroll position, ensuring elements reveal themselves with cinematic timing.
* **Parallax Depth:** Bound the physical position of the central vehicle to scroll-scrubbing, creating a deep parallax effect that separates the foreground subject from the background environment.
* **Continuous Replay:** Engineered the animation timeline to play and reverse seamlessly as the user navigates up and down the viewport.

### 3. 🔊 Global Dual-Audio State Management
* **Browser-Compliant Audio:** Built a custom Vanilla JavaScript audio controller designed to elegantly handle modern browser autoplay restrictions.
* **Master Mute Pipeline:** Engineered a global UI toggle that instantly pauses active environmental sounds (engine revs) and globally disables UI interaction sounds (clicks) via a master state variable.
* **Throttled Event Listeners:** Implemented JavaScript `setTimeout` throttling on the scroll-audio events to prevent event-spamming and memory leaks during rapid user scrolling.

---

## 🛠️ High-Level Tech Stack

* **Structure:** Semantic HTML5
* **Styling & Depth:** CSS3 (Flexbox, Transforms, CSS Variables, Advanced Gradients, Mix-Blend-Modes)
* **Logic & State:** Vanilla JavaScript (ES6+)
* **Animation Engine:** GSAP (GreenSock Animation Platform) & ScrollTrigger plugin

---

## 👨‍💻 The Architect

Engineered and designed by **[Debjeet Mazumder](https://github.com/KingDev4522)** 
*Built with raw code, precise mathematics, and an obsession for pixel-perfect UI.*
