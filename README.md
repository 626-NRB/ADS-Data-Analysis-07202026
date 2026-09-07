<div align="left">

# <font color="#1D4ED8">🚗 Automated Driving System (ADS) Car Crash Data Analysis Report</font>

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

<img width="586" height="418" alt="Screenshot 2026-09-05 214531" src="https://github.com/user-attachments/assets/7a5c0f17-806a-4a51-a93d-03e04378efcb" />

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
* From this analysis, we can assume that with additional signs and directions, vehicles might have been able to operate very well. Also, work zones usually have reduced speed which may favor the vehicles following the rules easily. On the other hand, it is concerning that most accidents occurred during normal road conditions while the vehicles were already trained with such road conditions. This indicates major upgrades are still needed for vehicles to operate with driverless mode.

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

<img width="929" height="298" alt="Screenshot 2026-09-05 214845" src="https://github.com/user-attachments/assets/64fcbc69-a8f5-4c8c-bacb-727f40ae897d" />

* **Top Vehicle Types:** Passenger Cars (<b>361 reports</b>) and SUVs (<b>257 reports</b>).
* **Pre-Crash Movement:** The leading category preceding collisions was <b>"Proceeding Straight"</b>, topping all other categories with <b>398 reports</b>.
* This is very surprising as a lot of accidents occur during turns at an intersection with human drivers. As the driverless vehicles are equipped with advanced sensors and AI technology, people expect them to be well trained to assess or analyze the road conditions very well, especially when they are going straight because that is probably a less complicated situation while driving.

</font>

---

### <font color="#2563EB">🩺 Injury Severity & Impact</font>

<font color="#1E3A8A">

<img width="803" height="251" alt="Screenshot 2026-09-07 093903" src="https://github.com/user-attachments/assets/625fed02-dcc1-46a0-9cdd-4dba4b7611ce" />

* <b>82%</b> of accidents resulted in **property damage only** without injury.
* Only a few incidents required hospitalization, and **only one fatality** was reported in the entire dataset.
* The data shows that mostly bodily vehicle damage occurred during accidents with a low rate of human injury. The major concern here is the property damage. However, a single fatality is too many. It does not rule out the human safety risk.

</font>

---

### <font color="#2563EB">Reference</font>

<font color="#1E3A8A">

* **Notebook:** https://colab.research.google.com/drive/1YyaVfWZ_FWeDAAQsl1ADfIqPAw_H8nCQ?usp=sharing
* **Notes:** Be sure to download the dataset (and upload it to Google Drive if neccesary) and place it in the notebook before running every operation. This will prevent most issues with reading the dataset.

</font>

</div>
