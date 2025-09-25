# Borewell-prediction
---

# 📊 DeepWell Agent – Borewell Feature Analysis

This project visualizes **borewell drilling features** such as **elevation, predicted depth, drilling rate, cost, and estimated time** across different locations.

The script uses **Matplotlib** to generate multiple bar charts for easy comparison of features.

---

## 📂 Project Structure

```
DeepWell-Agent/
│── borewell_analysis.py   # Visualization script
│── locations.json         # (Optional) Data file containing borewell info
│── README.md              # Documentation
```

---

## ⚙️ Requirements

Install the required Python libraries:

```bash
pip install matplotlib
```

---

## 🗂️ Input Data

The script expects a variable `locations_data` in the format:

```python
locations_data = [
    {
        "name": "Village A",
        "depth_ft": 450,
        "elevation_m": 320,
        "rate": 250,
        "cost": 112500,
        "time": 36
    },
    {
        "name": "Village B",
        "depth_ft": 520,
        "elevation_m": 280,
        "rate": 260,
        "cost": 135200,
        "time": 42
    }
]
```

Each dictionary should contain:

* `name` → Location name
* `depth_ft` → Predicted borewell depth (feet)
* `elevation_m` → Ground elevation (meters)
* `rate` → Drilling rate per foot (₹/ft)
* `cost` → Estimated total drilling cost (₹)
* `time` → Estimated drilling time (hrs)

---

## 🚀 How to Run

1. Save the script as `borewell_analysis.py`.
2. Define your `locations_data` list as shown above.
3. Run the script:

```bash
python borewell_analysis.py
```

4. The script will generate the following charts:

   * Elevation Across Locations
   * Predicted Borewell Depth
   * Drilling Rate per Foot
   * Estimated Drilling Cost
   * Estimated Drilling Time

---

## 📊 Visualization Output

* **Elevation Bar Chart** → Compares elevation of each location.
* **Depth Bar Chart** → Shows predicted borewell depth in feet.
* **Drilling Rate Bar Chart** → Cost per foot for drilling.
* **Cost Bar Chart** → Estimated total drilling cost per location.
* **Time Bar Chart** → Estimated drilling time in hours.

At the end, all graphs are presented with a project title:

> **📊 DeepWell Agent – Borewell Feature Analysis Across Locations**

---

## 🔮 Future Scope

* Export charts to PDF/PNG reports automatically
* Integrate ML-based depth prediction models
* Add interactive dashboards with **Plotly/Dash/Streamlit**

---
## Output
<img width="921" height="777" alt="Screenshot 2025-08-25 092508" src="https://github.com/user-attachments/assets/a6718c8d-f700-4253-9e7c-17d9d6ae4022" />
