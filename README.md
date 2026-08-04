readme_content = """<div align="left">

# <font color="#1D4ED8">🚗 ADS Car Crash Data Analysis Report</font>

---

### <font color="#2563EB">📌 Executive Summary</font>

<blockquote>
<font color="#1E40AF" size="3">
We analyzed the <b>ADS Car Crash Dataset</b> containing information from <b>1,115 NHTSA reports</b>. The findings indicate that daily road accidents occur predominantly on city streets during normal conditions and clear weather, with pre-crash movements mostly involving vehicles proceeding straight.
</font>
</blockquote>

---

### <font color="#2563EB">📍 Roadway Distribution & Work Zones</font>

<font color="#1E3A8A">

Analyzing the distribution of roadway accidents shows that the vast majority occur on city streets rather than highways or work zones:

</font>

| Location | Share of Accidents (%) |
| :--- | :--- |
| **City Streets** | `68.97%` |
| **Intersections** | `21.52%` |
| **Parking Lots** | `7.35%` |
| **Highways** | `1.97%` |
| **Traffic Circles** | `0.18%` |

<font color="#1E3A8A">

* **Existing Road Conditions:** <b>92.56%</b> of accidents occurred during normal conditions, demonstrating that existing road conditions do not play a primary role in collisions.
* **Work Zones:** Out of 1,115 reports, only <b>23 accidents</b> occurred within work zones.

</font>

---

### <font color="#2563EB">🌤️ Weather & Environmental Factors</font>

<font color="#1E3A8A">

We analyzed weather conditions including clear, cloudy, partly cloudy, rain, and snow:

* <b>74.41%</b> of all incidents occurred in **clear weather**.
* **Conclusion:** Weather conditions do not play a significant contributing role in the majority of accidents in this dataset.

</font>

---

### <font color="#2563EB">🚘 Vehicles Involved & Pre-Crash Movement</font>

<font color="#1E3A8A">

* **Top Vehicle Types:** Passenger Cars (<b>361 reports</b>) and SUVs (<b>257 reports</b>).
* **Pre-Crash Movement:** The leading category preceding collisions was <b>"Proceeding Straight"</b>, topping all other categories with <b>398 reports</b>.

</font>

---

### <font color="#2563EB">🩺 Injury Severity & Impact</font>

<font color="#1E3A8A">

* <b>82%</b> of accidents resulted in **property damage only** without injury.
* Only a few incidents required hospitalization, and **only one fatality** was reported in the entire dataset.

</font>

</div>
"""

with open("README.md", "w", encoding="utf-8") as file:
    file.write(readme_content)

print("README.md created successfully!")
