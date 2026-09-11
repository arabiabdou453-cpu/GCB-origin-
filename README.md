# 🏗️ GCB - Société Nationale de Génie Civil et Bâtiment (100% Fidelity Web Clone)

[![Vercel Deployment](https://img.shields.io/badge/Vercel-Live%20Demo-black?style=for-the-badge&logo=vercel)](https://gcbdz.vercel.app)
[![React](https://img.shields.io/badge/React-19.0-61DAFB?style=for-the-badge&logo=react&logoColor=black)](https://react.dev)
[![Vite](https://img.shields.io/badge/Vite-Bundled-646CFF?style=for-the-badge&logo=vite&logoColor=white)](https://vitejs.dev)
[![License](https://img.shields.io/badge/Status-100%25%20Verified%20Fidelity-success?style=for-the-badge)]()

> A high-performance, pixel-perfect, 100% fidelity clone of the official corporate portal of the **Société Nationale de Génie Civil et Bâtiment (GCB)**, subsidiary of the Sonatrach Group ([gcb.dz](https://gcb.dz)).

🌐 **Live Production URL:** [https://gcbdz.vercel.app](https://gcbdz.vercel.app)  
📁 **GitHub Repository:** [https://github.com/arabiabdou453-cpu/GCB-origin-](https://github.com/arabiabdou453-cpu/GCB-origin-)

---

## 📑 Table of Contents
- [Project Overview](#-project-overview)
- [Key Features & Modules](#-key-features--modules)
- [Technical Architecture](#-technical-architecture)
- [Project Directory Structure](#-project-directory-structure)
- [Automated Deployment & CI/CD](#-automated-deployment--cicd)
- [Local Development Setup](#-local-development-setup)
- [Verification & Quality Assurance](#-verification--quality-assurance)

---

## 🌟 Project Overview

This project provides a comprehensive, sub-pixel accurate standalone single-page application (SPA) replicating the official corporate website of **GCB (Société Nationale de Génie Civil et Bâtiment)**.

All assets, data feeds, PDF documentation, image galleries, and interactive multimedia elements have been verified and integrated to match the live portal byte-for-byte.

---

## 🚀 Key Features & Modules

### 1. 🏢 Corporate & Executive Sections
* **Mot du PDG (`/Mot_pdg`):** Executive address matching the latest official corporate revisions, including verified ISO 9001:2015, ISO 45001:2018, and ISO 14001:2015 certifications.
* **Présentation GCB & Organisation:** Deep interactive organizational structure and corporate history.
* **QHSE Policies:** Complete Quality, Health, Safety, and Environment compliance sheets.

### 2. 🏗️ Comprehensive Activity Galleries (10 Domains)
Full high-resolution photographic galleries across all of GCB's strategic infrastructure domains:
* **Ouvrages Hydrauliques & Dessalement (`/Ouvrages_Hydrauliques`):** Including the award-winning *Cap Blanc* seawater desalination plant.
* **Pipelines & Hydrocarbures (`/Pipeline`):** Oil and gas line works and concentrated facilities.
* **Génie Civil Industriel (`/GC_industriel`):** Major refinery and petrochemical facilities.
* **Voies Ferrées (`/Voies_Ferrées`):** Strategic mining and national railway lines (e.g. Tindouf – Oum Laouadlat).
* **Routes, Autoroutes & Pistes:** Heavy civil transportation infrastructure.
* **Montage & Exploitation Industrielle:** Mechanical assembly and heavy maintenance.
* **Bâtiment & VRD:** Urban planning and tertiary facilities.

### 3. 🎬 GCB Media Center (`/media`)
* **19 Unique High-Definition Videos:** Completely audited with zero duplicates.
* **Dual-Engine Video Architecture:**
  - **Embedded HTML5 Video Player (`WE` Engine):** Dedicated streaming interface with interactive scrubber, volume control, full-screen playback, and keyboard controls (Spacebar/Escape).
  - **Verified YouTube Integration:** Embedded modal player for external documentary assets.

### 4. 🔍 Advanced Real-Time Search (`/SearchPage`)
* **Dynamic Floating Hero Canvas:** Mathematical CSS keyframe animations (`float 15s`, `float 18s reverse`, `pulse 8s`) with three animated background geometry elements (`.shape-1`, `.shape-2`, `.shape-3`).
* Instant multi-category content filtering across documents, news, and services.

### 5. 📚 Official Document Center (`/Documents`)
* **12 Full-Text Official Publications & Reports:**
  - Annual Reports 2022, 2023, 2024, and 2025.
  - Multilingual Corporate Brochures (العربية, Français, English).
  - Technical Data Sheets (*Fiches Techniques*) for Heat Exchangers, Separators, and Scraper Stations.
  - Official ISO Certifications (ISO 9001, 14001, 45001).

---

## 🛠️ Technical Architecture

| Technology | Role | Details |
| :--- | :--- | :--- |
| **React 19** | UI Runtime | Modern virtual DOM with concurrent features |
| **Vite** | Build Tooling | Optimized production bundling and tree-shaking |
| **CSS3 Animation Engine** | Styling & Canvas | Sub-pixel keyframe floating physics |
| **Vercel Edge Network** | Production Hosting | Global CDN with automatic SSL & zero-config rewrite rules |
| **Git / GitHub** | Version Control & CI/CD | Automated deployment webhook triggers |

---

## 📂 Project Directory Structure

```text
gcb.dz/
├── assets/                  # Compiled JS & CSS bundles, official logos, certificates
│   ├── index-AsGqYFNN.js    # Verified production React application bundle
│   └── index-rS3FB5sd.css   # Main stylesheet bundle
├── data/                    # Dynamic JSON data stores
│   ├── documents.json       # Reports, brochures, and technical sheets metadata
│   ├── newsData.json        # News feed and article index
│   ├── newsDetailData.json  # Comprehensive article galleries and editorial content
│   └── specialites.json     # Corporate activities taxonomy
├── media_img/               # Media center assets
│   ├── media.json           # Catalog of all 19 video entries
│   └── videos/thumbnails/   # High-resolution video preview thumbnails
├── news/                    # Over 130 article detail gallery images
├── pdf/                     # Official annual reports, brochures, and technical sheets
├── ConstructionM/           # Metal construction gallery
├── GC_industriel/           # Industrial civil engineering gallery
├── Route/                   # Roads and runways gallery
├── Voieferree/              # Railway projects gallery
├── dcp/                     # Drill sites gallery
├── dessalement/             # Desalination plants gallery
├── engineerring/            # Engineering & procurement gallery
├── montage/                 # Industrial assembly gallery
├── oil&gaz/                 # Oil & Gas equipment gallery
├── vrd/                     # VRD & Building infrastructure gallery
├── index.html               # Main HTML5 entry shell with base routing
├── vercel.json              # Vercel SPA rewrite configuration
├── _redirects               # Netlify / Cloudflare Pages routing fallback
└── .htaccess                # Apache / cPanel URL rewrite configuration
```

---

## 🔄 Automated Deployment & CI/CD

This repository is permanently linked to **Vercel** via GitHub Webhooks.

Any code committed and pushed to the `main` branch:
```bash
git add .
git commit -m "feat: your update message"
git push origin main
```
Automatically triggers an instant production build and deployment at:  
👉 **[https://gcbdz.vercel.app](https://gcbdz.vercel.app)**

---

## 💻 Local Development Setup

To run the project locally on your machine:

### Option 1: Using the Included Python Server
A lightweight multi-threaded server (`server.py`) is provided in the parent directory:
```bash
python server.py
```
Then open your browser at:
```text
http://localhost:5000
```

### Option 2: Using Any Static HTTP Server
```bash
# Using Node.js serve
npx serve gcb.dz -s -p 5000

# Using Python http.server
python -m http.server 5000 --directory gcb.dz
```

---

## 🧪 Verification & Quality Assurance

The repository has been verified using an automated auditing suite testing:
- [x] **Zero Broken Links:** All SPA routes respond with HTTP 200.
- [x] **Zero Duplicate Videos:** 19 distinct, unique media entries.
- [x] **Zero Missing Assets:** All 12 PDF publications and 130+ project gallery images verified on disk.
- [x] **Pixel-Perfect Typography:** Sub-pixel alignment of headers, typography, and footer coordinates verified via Chrome DevTools.

---

## 📄 License & Attribution
* Original brand identity, logos, and corporate media content belong to **GCB - Société Nationale de Génie Civil et Bâtiment (Sonatrach Group)**.
* Developed for portfolio, benchmarking, and high-fidelity web engineering demonstration purposes.
