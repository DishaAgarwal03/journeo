
<h1 align="center">🧳 Journeo</h1>

<p align="center">
  <b>Your travel cart for the world.</b><br>
  Add flights, trains, and bus tickets to one cart — plan your journey just like shopping online.
</p>

<p align="center">
  <img src="https://img.shields.io/badge/Phases-3-blue?style=for-the-badge"/>
  <img src="https://img.shields.io/badge/Status-In_Progress-yellow?style=for-the-badge"/>
  <img src="https://img.shields.io/badge/License-MIT-green?style=for-the-badge"/>
</p>

---

## 🚀 Overview

**Journeo** simplifies multi-step travel planning by combining the features of aggregators (like Skyscanner) with the convenience of an online cart.

Users can:
- 🛒 Add travel tickets from different sources into one cart  
- 👥 Manage traveler profiles for quick booking  
- 💛 Save trips to a wishlist  
- 🧭 Visualize and optimize entire journeys in one glance  

---

## 🧩 Modular Architecture

Journeo is developed in **three phases**, each as its own sub-repository within this main repo:

| Phase | Module | Description | Tech Stack |
|:--:|:--|:--|:--|
| 🧱 **1** | [journeo-extension](https://github.com/DishaAgarwal03/journeo-extension) | Chrome extension to add travel tickets to a unified cart from a single website. | JavaScript, HTML, CSS |
| 🌐 **2** | [journeo-webapp](https://github.com/DishaAgarwal03/journeo-webapp) | Web app to aggregate travel data, sync carts, manage wishlists, and handle authentication. | React, Node.js, Express, MongoDB |
| 🤖 **3** | [journeo-planner](https://github.com/DishaAgarwal03/journeo-planner) | Smart planner that visualizes full itineraries and provides AI-based route suggestions. | Next.js, TypeScript, GraphQL, AI APIs |

---

## 🗂️ Repository Structure

```

journeo/
├── journeo-extension/   → Chrome Extension (Phase 1)
├── journeo-webapp/      → Aggregation Platform (Phase 2)
└── journeo-planner/     → Smart Journey Planner (Phase 3)

````

Each module is a **Git submodule** linked to its dedicated repository.

---

<details>
<summary><b>⚙️ Setup Instructions</b> (click to expand)</summary>

### 1️⃣ Clone the main repository with submodules

```bash
git clone --recurse-submodules https://github.com/DishaAgarwal03/journeo.git
````

If already cloned, initialize submodules manually:

```bash
git submodule update --init --recursive
```

---

### 2️⃣ Navigate into a specific module

```bash
cd journeo-extension   # Phase 1
# or
cd journeo-webapp      # Phase 2
# or
cd journeo-planner     # Phase 3
```

Each module has its own setup guide inside its `README.md`.

</details>

---

## 🌍 Vision

Journeo’s goal is to become the **“shopping cart for travel”** —
a single hub where travelers can plan, visualize, and book everything effortlessly.

🔮 *Future roadmap includes:*

* AI-powered trip recommendations
* Integration with major travel APIs (Skyscanner, Amadeus, IRCTC, RedBus, etc.)
* Personalized dashboards with trip summaries and analytics

---

## 💡 Tech Highlights

* Modular sub-repo design using Git submodules
* Cross-platform: Chrome extension + Web app + Planner
* Scalable backend architecture for API aggregation
* Clean UI/UX principles for seamless user flow

---

## 👩‍💻 Author

**Disha Agarwal**
🌐 [GitHub](https://github.com/DishaAgarwal03)  •  💼 [LinkedIn](https://linkedin.com/in/dishaagarwal03)

---

## 📜 License

This project is open-source and available under the **MIT License**.

---

<p align="center">
  Made with ❤️ by <b>Disha Agarwal</b><br>
  <sub>Journeo © 2025</sub>
</p>

---

