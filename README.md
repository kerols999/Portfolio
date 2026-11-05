# Kerols Raafat - Data Analyst Portfolio

A modern, professional dark-themed portfolio website for **Kerols Raafat (Data Analyst & Business Intelligence)**, upgraded with a **solid black background, interactive WebGL fluid/smoke shader, Space Grotesk geometric typography, floating pill navigation, and 3x3 tech stack grid**.

---

## 🎨 New Design System & Architecture

### 1. 🌌 WebGL Interactive Fluid & Smoke Background
- **Solid Black Base (`#000000`)**: Deep pitch-black background.
- **Teal & Dark Blue Fluid Simulation**: Real-time WebGL fragment shader with domain-warped fractional Brownian motion (fBm) noise.
- **Full 2D Cursor Reactivity**: The gradient and smoke plumes dynamically shift and flow with both **vertical (up/down)** and **horizontal (left/right)** mouse movement.
- **Smooth 60 FPS on Scroll**: Highly optimized with canvas resolution downsampling, smooth velocity lerp, and zero scroll obstruction.

### 2. 🔤 Modern Geometric Typography
- **Primary Typeface**: **Space Grotesk** from Google Fonts, paired with Inter for readable body text.
- **Heading Styling**: Bold weight with tight negative letter-spacing (`letter-spacing: -0.04em`) for a sleek, data-driven, engineering aesthetic.

### 3. 💊 Centered Floating Pill Navigation
- **Floating Pill Bar**: Centered at the top of the viewport with a frosted-glass backdrop (`bg-[#0d121c]/85 backdrop-blur-xl border border-white/10`).
- **Links-Only**: Contains strictly navigation links (`About`, `Skills`, `Projects`, `Experience`, `Education`, `Contact`) with no name or title text.
- **Right-Side Icon Buttons**: Three rounded-square icon buttons on the right for **GitHub**, **LinkedIn**, and **Email** in a minimal line style with subtle hover highlights.
- **No CV Download Button**: Streamlined according to modern minimal portfolio principles.

### 4. ⚡ 3x3 Tech Stack & Tools Grid
A clean 9-card (3x3) layout of dark navy cards with teal accent labels, descriptions, and tag chips:
1. **Data Modeling** → Microsoft Excel *(Power Query, VBA/Macros, Pivot Architecture)*
2. **Database Queries** → SQL Systems *(PostgreSQL, Window Functions, CTEs)*
3. **Scripting & EDA** → Python *(Pandas, NumPy, Matplotlib)*
4. **Enterprise BI** → Power BI *(DAX, Star Schema, Interactive UX)*
5. **Visual Storytelling** → Tableau *(Parameters, Scorecards, LOD Calcs)*
6. **Notebook Computing** → Jupyter Notebooks *(Reproducibility, Markdown, SciPy)*
7. **Machine Learning** → Core ML Techniques *(Supervised Learning, Unsupervised Learning, Model Evaluation)*
8. **Deep Learning** → Neural Networks *(CNNs, RNNs, Neural Network Fundamentals)*
9. **Data Engineering & ETL** → Pipeline Architectures *(ETL Pipelines, Data Wrangling, Pipeline Orchestration)*

### 5. 📁 Sections Order
1. **Hero** (Name, Data Analyst title, tagline, 3 rounded-square icons, CTAs, and micro-metrics ribbon)
2. **About Me** (Narrative, Systematic Query Discipline philosophy, 4 core focus areas)
3. **Tech Stack & Tools** (3x3 grid)
4. **Featured Projects** (NVIDIA, Olist, HR Attrition with SVG charts and interactive case study modals)
5. **Experience** (NTI AI for Business, DEPI Data Analytics Track)
6. **Education** (HTI Business Information Systems, GPA 3.20, Coursework)
7. **Get in Touch** (Direct Email, LinkedIn, WhatsApp, GitHub, and Interactive Form)

---

## 🚀 How to View Locally

Double-click [`index.html`](file:///k:/OneDrive/Desktop/Portfolio/index.html) or run:

```powershell
python -m http.server 8000
```
Then open `http://localhost:8000`.
