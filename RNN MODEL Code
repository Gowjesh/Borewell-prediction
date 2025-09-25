import matplotlib.pyplot as plt

# Extract and prepare data
names = [loc['name'][:20] for loc in locations_data]
depths = [loc['depth_ft'] for loc in locations_data]
elevs = [loc['elevation_m'] for loc in locations_data]
rates = [loc['rate'] for loc in locations_data]
costs = [loc['cost'] for loc in locations_data]
times = [loc['time'] for loc in locations_data]  # Assuming 'time_hr' is present

# ------------------------------
# 1️⃣ Elevation Bar Chart
# ------------------------------
plt.figure(figsize=(10, 6))
plt.bar(names, elevs, color='skyblue')
plt.title("Elevation Across Locations")
plt.ylabel("Elevation (m)")
plt.xticks(rotation=30, ha='right')
plt.tight_layout()
plt.show()

# ------------------------------
# 2️⃣ Depth Bar Chart
# ------------------------------
plt.figure(figsize=(10, 6))
plt.bar(names, depths, color='green')
plt.title("Predicted Borewell Depth")
plt.ylabel("Depth (ft)")
plt.xticks(rotation=30, ha='right')
plt.tight_layout()
plt.show()

# ------------------------------
# 3️⃣ Drilling Rate Bar Chart
# ------------------------------
plt.figure(figsize=(10, 6))
plt.bar(names, rates, color='orange')
plt.title("Drilling Rate per Foot")
plt.ylabel("Rate (₹/ft)")
plt.xticks(rotation=30, ha='right')
plt.tight_layout()
plt.show()

# ------------------------------
# 4️⃣ Cost Bar Chart
# ------------------------------
plt.figure(figsize=(10, 6))
plt.bar(names, costs, color='red')
plt.title("Estimated Drilling Cost")
plt.ylabel("Cost (₹)")
plt.xticks(rotation=30, ha='right')
plt.tight_layout()
plt.show()

# ------------------------------
# 5️⃣ Time Series Bar Chart
# ------------------------------
plt.figure(figsize=(10, 6))
plt.bar(names, times, color='purple')
plt.title("Estimated Drilling Time")
plt.ylabel("Time (hrs)")
plt.xticks(rotation=30, ha='right')
plt.tight_layout()
plt.show()


plt.suptitle("📊 DeepWell Agent – Borewell Feature Analysis Across Locations", fontsize=16)
plt.tight_layout(rect=[0, 0, 1, 0.95])
plt.show()

