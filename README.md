<div align="center">
  <h1>⚙️ Puer Backend</h1>
  <p><b>Lightweight backend proxy and API service for the Puer music player</b></p>
  
  <p>
    <a href="https://github.com/YOUR_USERNAME/Puer-Backend/blob/main/LICENSE"><img src="https://img.shields.io/github/license/YOUR_USERNAME/Puer-Backend?style=flat-square&color=blue" alt="License"></a>
    <a href="https://github.com/YOUR_USERNAME/Puer-Backend/actions"><img src="https://img.shields.io/github/actions/workflow/status/YOUR_USERNAME/Puer-Backend/deploy.yml?style=flat-square" alt="CI/CD Status"></a>
  </p>
</div>

---

## 🌐 Overview

**Puer-Backend** is the companion server-side service for the [Puer-Android](https://github.com/YOUR_USERNAME/Puer-Android) music player. It handles artwork proxying, caching, and stream resolution to ensure fast and reliable playback without overloading external sources.

---

## 🚀 Key Features

* 🖼️ **Artwork Edge Proxy:** Securely fetches, compresses, and caches album covers with CDN support.
* ⚡ **Lightning Fast:** Built on edge-optimized infrastructure (Cloudflare Workers / Fastify) for minimal latency.
* 🛡️ **Rate Limiting & Security:** Protects API endpoints against abuse using token validation and rate limiting.
* 🔓 **Open Source:** Fully transparent and self-hostable backend code.

---

## 🛠️ Tech Stack

* **Runtime / Framework:** Node.js (TypeScript) / Cloudflare Workers
* **Deployment:** Docker / Serverless
* **Caching:** Redis (optional, for metadata and rate limiting)

---

## ⚙️ Getting Started (Self-Hosting)

If you want to run your own instance of the Puer backend, follow these steps:

1. Clone the repository:
   ```bash
   git clone [https://github.com/YOUR_USERNAME/Puer-Backend.git](https://github.com/YOUR_USERNAME/Puer-Backend.git)
