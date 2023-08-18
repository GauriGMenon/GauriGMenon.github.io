---
name: Crop Production Analysis India 
tools: [Dashboard, Streamlit, Plotly, Geopandas, Pandas, VTK]
image: https://raw.githubusercontent.com/GauriGMenon/Big-Data-Visual-Analytics/main/assets/rainfall.png
description: An interactive visual dashboard for analysing crop production statistics and geographic trends along with rainfall correlation assessment and water resource strain assessment
# external_url: https://github.com/GauriGMenon/Big-Data-Visual-Analytics
---

<!-- # Big-Data-Visual-Analytics
A github repository for all the assignments and project done in the course(CS661A) in the even semester of 2022-2023 in IIT Kanpur -->

# Crop Data Visualisation

<!-- <p class="text-center">
{% include elements/button.html link="https://github.com/GauriGMenon/Big-Data-Visual-Analytics" text="Github" %}
</p> -->
An interactive visual dashboard for analysing crop production statistics and geographic trends along with rainfall correlation assessment and water resource strain assessment
<p class="text-center">
{% include elements/button.html link="https://crop-analysis-gaurigmenon.streamlit.app/" text="View App" style="primary" size="sm"%}
</p>

## Tasks
We have implemented the following tasks in the dashboard:
1. **Task 1:** To analyze crop production statistics across the nation (district-wise)  
2. **Task 2:** To analyze trends in crop production over the years
3. **Task 3:** To correlate rainfall pattern with crop production trends

### Task 1 Analysis
1. Punjab, Haryana, and Uttar Pradesh were the first Indian states to cultivate wheat.
2. Today, Madhya Pradesh and Rajasthan have joined the list of the largest Wheat-producing states. 
3. Govt. policies and missions like NFSM, RKVY, PMFBY, subsidies, and farmer knowledge caused the change.

<!-- ![preview](https://raw.githubusercontent.com/GauriGMenon/Big-Data-Visual-Analytics/main/assets/wheat_indo.png) -->
<img src="https://raw.githubusercontent.com/GauriGMenon/Big-Data-Visual-Analytics/main/assets/wheat_indo.png" width="400"/>

<!-- 4. Bajra was produced the most in Maharashtra during the early years. In recent years, production has dropped significantly. -->
<!-- ![preview](https://raw.githubusercontent.com/GauriGMenon/Big-Data-Visual-Analytics/main/assets/bajra_old.png) ![preview](https://raw.githubusercontent.com/GauriGMenon/Big-Data-Visual-Analytics/main/assets/bajra_new.png) -->
<!-- <p><img src="https://raw.githubusercontent.com/GauriGMenon/Big-Data-Visual-Analytics/main/assets/bajra_old.png" width="300"/> <img src="https://raw.githubusercontent.com/GauriGMenon/Big-Data-Visual-Analytics/main/assets/bajra_new.png" width="300"/></p> -->

### Task 2 Analysis

#### Cereals
- Rice and Wheat were cultivated most, over all the years
- Bajra production peaked in 2012 and decreased henceforth
- Jowar production decreased overall, and consistently after 2008
- Millet production has decreased over the years, especially since 2010. The proportion of other crops(crop diversity) has decreased

#### Pulses
- Proportion of moong has decreased over the years
- Moth and Horse-gram production has decreased

### Task 3 Analysis(Rainfall correlation)
- Bajra, and Gram are dry land crops and are hence, most grown in Rajasthan and Madhya Pradesh(low rainfall).
<img src="https://raw.githubusercontent.com/GauriGMenon/Big-Data-Visual-Analytics/main/assets/rainfall.png" width="400"/>

- Rice cultivation is also concentrated to high rainfall areas(like the East coast) owing to its water requirements
- The extensive rice cultivation in the Punjab-Haryana region in the absence of sufficient rainfall explains the rainfall issues faced there
<img src="https://raw.githubusercontent.com/GauriGMenon/Big-Data-Visual-Analytics/main/assets/rice.png" width="400"/>

<!-- <p class="text-center">
{% include elements/button.html link="https://crop-analysis-gaurigmenon.streamlit.app/" text="View App" block=true %}
</p> -->
<!-- <iframe seamless frameborder="0" src="https://github.com/GauriGMenon/Big-Data-Visual-Analytics/blob/main/assets/wheat.mp4" width = '900' height = '450' ></iframe>   -->

