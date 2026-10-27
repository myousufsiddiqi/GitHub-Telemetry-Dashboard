# GitHub Developer Telemetry Dashboard

A fast, client-side rendered Single Page Application (SPA) designed to dynamically consume, parse, and visualize live developer profiles and repository telemetry from the GitHub REST API.

🚀 **Live Deployment:** [View Live Application](https://github-info-eight.vercel.app)

### Tech Stack
* **Frontend:** React 18, DOM manipulation, JavaScript (ES6+)
* **Build Tool:** Vite
* **Styling:** Tailwind CSS / CSS Modules
* **API & Networking:** GitHub REST API, Asynchronous Fetch, Promises
* **Deployment:** Vercel Edge Network

### Engineering Highlights
* **Asynchronous State Management:** Engineered deterministic loading states to handle unpredictable network latency when fetching cross-origin resources.
* **Dynamic JSON Parsing:** Implements real-time data extraction to populate UI cards (Avatar, Profile, Repositories, Followers) directly from raw GitHub API payloads.
* **Graceful Error Boundaries:** Built robust `try/catch` block logic to manage invalid GitHub handles and 404s without crashing the client interface.
