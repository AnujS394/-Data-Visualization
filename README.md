# 📊 Data Visualization

A curated collection of Python notebooks, scripts, and dashboards that turn raw data into clear, compelling stories.  
From quick exploratory plots to fully–interactive web apps, this repo showcases multiple visualization libraries—**Matplotlib**, **Seaborn**, **Plotly Express**, and **Altair**—to highlight the strengths of each tool.

> **Goal:** Serve as a one‑stop reference (and template) for anyone who wants to learn or demo modern data‑viz techniques in Python.

---

## ✨ Key Highlights

| Category              | Libraries                    | What you’ll find                                     |
|-----------------------|------------------------------|------------------------------------------------------|
| **Exploratory (EDA)** | `pandas`, `matplotlib`, `seaborn` | Histograms, pair‑plots, correlation heat‑maps        |
| **Storytelling**      | `plotly.express`, `altair`   | Interactive line / bar charts, drill‑down dashboards |
| **Geospatial**        | `plotly.express`, `geopandas`| Choropleths, density mapbox heat‑maps                |
| **Dashboards**        | `streamlit` (optional)       | One‑click web apps wrapping the notebooks            |

---

## 🖼️ Gallery

| Snapshot | Description |
|----------|-------------|
| ![heatmap](assets/corr_heatmap.png) | Correlation heat‑map with Seaborn |
| ![map](assets/density_map.png) | Accident hotspot density map (Plotly Mapbox) |
| ![dashboard](assets/streamlit_demo.gif) | Interactive dashboard built with Streamlit |

*(Screenshots live in the **`assets/`** directory; replace with your own if filenames differ.)*

---

## 🗂️ Repository Layout
├── notebooks/
│ ├── 01_basic_eda.ipynb
│ ├── 02_seaborn_tutorial.ipynb
│ ├── 03_plotly_interactive.ipynb
│ └── 04_geospatial_visuals.ipynb
├── dashboards/
│ └── streamlit_app.py
├── data/ # (tiny sample CSVs; real data stays outside Git)
├── assets/ # screenshots / GIFs
├── requirements.txt
└── README.md

yaml
Copy
Edit

---

## 🛠️ Quick Start

```bash
# 1. Clone
git clone https://github.com/AnujS394/-Data-Visualization.git
cd -Data-Visualization

# 2. Create environment & install deps
python -m venv venv
source venv/bin/activate          # Windows: venv\Scripts\activate
pip install -r requirements.txt

# 3. Launch notebooks
jupyter lab
