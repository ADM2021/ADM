# ADM

Hii, Welcome to the central repository. This project serves as a modern personal hub, portfolio showcase, and a testing ground for integrating advanced machine learning models with secure, high-performance web development.

Built with a heavy emphasis on sleek, intuitive UX/UI, this hub acts as the gateway to my active engineering projects—most notably an ongoing proprietary **Boxing Computer Vision Model**.

---

## 🎨 UX/UI Design Philosophy

The interface of this site is designed from the ground up to offer a seamless, immersive user experience. 
* **Minimalist Aesthetics:** Deep contrast dark modes combined with striking accents to keep user focus on critical data points.
* **Responsive Fluidity:** Leverages modern layout architectures (Flexbox/Grid) to ensure pixel fidelity across mobile devices, tablets, and ultrawide monitors(still working throught some bugs such as viewing the data visualization my be off on mobile and tablets).
* **Component-Driven Architecture:** Clean, modular UI components built for fast rendering cycles and micro interactions that elevate the overall user feel.

---

## 🥊 Featured Project: Boxing Computer Vision Model

One of the flagship integrations showcased through this hub is my custom, end-to-end **Boxing Vision Model**(not shown yet, well intergrate soon).

### **The Vision**
Traditional sports analytics relies heavily on manual tagging. This project aims to automate open source time boxing metrics using deep learning object detection, pose estimation, and temporal sequence processing.

### **Key Features Under Development:**
* **Punch Classification:** Real time differentiation between jabs, crosses, hooks, and uppercuts.
* **Fighter Tracking & Pose Estimation:** Mapping structural biomechanics to track footwork, guard positioning, and head movement.
* **Analytics Dashboard:** A planned interface extension for this site to visualize punch volume, accuracy landing rates, and defensive slip-efficiencies.

---

## 🔒 Security Architecture & Integration

A beautiful (in my humble opinion lol) w/ security concepts (cant really do much with a static site but attempted to display concepts within gitpages limitations). The site integrates web security concepts directly into its deployment structure to ensure host integrity and data protection:

* **Content Security Policy (CSP):** Mitigates Cross Site Scripting (XSS) and data injection attacks by strictly defining which dynamic resources are allowed to load.
* **Secure Header Management:** Enforces HTTPS transmission using HTTP Strict Transport Security (HSTS), prevents clickjacking via `X-Frame-Options`, and secures user privacy with restrictive `Referrer-Policy` headers.
* **Secure Environment Agnosticism:** Keeps API endpoints and webhook handshakes safe from client side exposure via environment variable isolation(still working on this).

---

## 🛠️ Built With

* **Front-End Framework:** HTML5, CSS3 (Custom Properties/Variables), JavaScript (ES6+)
* **Styling Paradigm:** Responsive Frameworks / Tailwind CSS 
* **Hosting & Security Engine:** GitHub Pages / Cloudflare edge routing with SSL/TLS encryption.
