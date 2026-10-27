# 📊 GitHub Telemetry Dashboard (SPA)

A fast, client-side rendered Single Page Application (SPA) designed to dynamically consume, parse, and visualize live developer profiles and repository telemetry from the GitHub REST API.

🚀 **Live Deployment:** [View Live Application](https://github-info-eight.vercel.app)

---

## 🏗️ Core Application Features

| 🌐 Live API Integration | ⚡ Async State Management | 🛡️ Error Boundaries | 🚀 Edge Deployment |
| :--- | :--- | :--- | :--- |
| **GitHub REST API** | **React Hooks & Promises** | **Try/Catch Fallbacks** | **Vercel Network** |
| Real-time fetching of cross-origin JSON payloads. | Deterministic UI loading states for unpredictable network latency. | Prevents React from crashing when users input invalid 404 handles. | Instant global caching and CI/CD Git integration. |

---

## 🧠 Engineering Highlights (Deep-Dive)

This SPA was engineered to demonstrate modern, side-effect-driven React architecture, moving beyond static data rendering into dynamic network consumption.

* **Asynchronous Network Handling:** Built robust `fetch` pipelines wrapped in ES6 Promises to handle network I/O. Implemented strict state transitions (Loading ➡️ Success ➡️ Error) to ensure a flawless UX regardless of API response times.
* **Dynamic JSON Parsing:** Instead of tightly coupling the UI to a database, the system executes real-time data extraction directly from raw GitHub API payloads, mapping nested JSON structures to atomic React UI cards (Avatar, Profile, Repositories, Followers).
* **Vite esbuild Optimization:** Utilized Vite to completely bypass the legacy Webpack build process, leveraging native ES modules for instant hot Module Replacement (HMR) and highly optimized production bundles.

---

## ⚙️ Enterprise Technology Stack

| Layer | Technologies Used |
| :--- | :--- |
| **Frontend Framework** | React 18, JavaScript (ES6+), DOM Manipulation |
| **Styling & UI** | Tailwind CSS (Utility-first responsive design) |
| **State & Networking** | React Hooks (`useState`, `useEffect`), Fetch API, Promises |
| **Build & Deployment** | Vite, Vercel Edge Network |
