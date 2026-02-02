<div align="center">
  <a href="https://rivalsvictory.com" target="_blank">
    <img src="https://cdn.jsdelivr.net/gh/rivalsvictory-assets/rivalsvictory-assets@main/public/favicon.svg" width="120" height="120" alt="Rivals Victory Logo">
  </a>

  <h1>Rivals Victory | Open Data & Assets</h1>

  <p>
    <strong>The tactical database & utility toolkit for Marvel Rivals.</strong>
  </p>

  <p>
    <a href="https://rivalsvictory.com">
      <img src="https://img.shields.io/badge/Website-Live-22c55e?style=for-the-badge&logo=google-chrome&logoColor=white" alt="Website Live" />
    </a>
    <img src="https://img.shields.io/badge/Data_Version-Patch_1.0-3b82f6?style=for-the-badge" alt="Data Version" />
    <img src="https://img.shields.io/badge/License-MIT-fbbf24?style=for-the-badge" alt="License" />
  </p>

  <br />
</div>

---

## ⚡ About

This repository acts as the open-source resource library for **[RivalsVictory.com](https://rivalsvictory.com)**.

We are dedicated to providing high-quality tactical data for the Marvel Rivals community. To support the developer ecosystem, we have open-sourced our core data (hero stats, ultimate economy, mechanic tags) and brand assets for use by community developers, content creators, and analysts.

### 🚀 Live Use Cases
This data currently powers the core features of Rivals Victory:
* **[Ultimate Economy Tracker](https://rivalsvictory.com/ult-economy)**: The most comprehensive ultimate charge and tempo calculator.
* **[Mechanic Finder](https://rivalsvictory.com/mechanic-finder)**: A hero filtering tool based on tactical mechanics (Stun, Shield, Hitscan).

---

## 📂 Open Data

You can fetch the latest JSON data directly via CDN for your projects.

| Data File | Description | CDN Link (Recommended) |
| :--- | :--- | :--- |
| **Heroes DB** | Contains basic hero stats, role definitions, and image paths. | [`heroes.json`](https://cdn.jsdelivr.net/gh/rivalsvictory-assets/rivalsvictory-assets@main/data/heroes.json) |
| *(Coming Soon)* | Ultimate costs and tempo/timing tags. | *Pending Update* |
| *(Coming Soon)* | Hero mechanics and counter-pick data. | *Pending Update* |

### Data Structure Example (`heroes.json`)

```json
[
  {
    "id": "hulk",
    "name": "Hulk",
    "role": "Vanguard",
    "ult_cost": 600,
    "tags": ["Tempo Driver", "Stun"],
    "image": "https://..."
  },
  ...
]
