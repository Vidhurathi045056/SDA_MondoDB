# Violence Dataset in US

Dataset sourced from Kaggle: [Gun Violence Data](https://www.kaggle.com/datasets/whisperingkahuna/gunviolence1)

### Introduction

The dataset provides an in-depth analysis of violence incidents in the U.S., examining various aspects such as the distribution of incidents, casualties, arrests, and affected locations. Through charts and visual representations, the data offers valuable insights into trends, patterns, and areas of concern, aiding in understanding the scope and impact of violence across states and cities.
This project provides a detailed analysis of incidents across North America, focusing on various dimensions like geolocation, casualty types, and incident distribution. Below is an overview of the key insights derived from the analysis.

## 1. Plot of Incidents
### **Objective**
The heatmap visualizes the distribution and intensity of incidents across North America, focusing on the number of victims killed, based on geolocation data.

### **Inference**
The southeastern United States emerges as the hotspot for incidents with the highest fatality rates, as indicated by the intense red zone, representing over 150 victims killed. Surrounding areas in the U.S. show moderate densities, marked by yellow and green zones, with casualty numbers between 50 and 100. The density of incidents diminishes significantly as we move towards Mexico and Canada, where fatalities are minimal (<50), shown by blue regions. This highlights the southeastern U.S. as the region with the most severe and frequent fatal incidents.

![Heatmap](https://drive.google.com/drive/folders/1RhnqNFEP0IjhsYP-ht54myhSycBdse5c)

---

## 2. Incidents with Exact Coordinates
### **Objective**
To analyze whether incidents reported have exact geolocation coordinates available.

### **Inference**
The chart shows that the vast majority of incidents (over 95%) have geolocation coordinates available, as represented by the dominant green section. A negligible proportion lacks coordinates, shown by the small blue segment, while the null values (yellow) are virtually absent. This indicates highly reliable geolocation data for incident reporting.

![Pie Chart](path/to/piechart.png)

---

## 3. Total Victims by State

> *(Add a description or visual here if necessary)*

---

## 4. Incidents Distribution by Date
### **Objective**
To track the number of reported incidents over time.

### **Inference**
The line chart reveals a steep decline in the number of incidents over time. Initially, on March 31, 2024, the incident count was at its peak (16 incidents). This steadily decreased, with significant drops by April 30, 2024, and eventually plateaued at 2 incidents by February 12, 2024. This indicates a clear reduction in reported incidents as time progressed.

![Line Chart](path/to/linechart.png)

---

## 5. State-by-State Comparison of Average Fatalities: Victims vs. Suspects

> *(Add a description or visual here if necessary)*

---

## 6. Total Casualties Over Time
### **Objective**
To illustrate the cumulative number of casualties over time, categorized by victims killed, injured, and suspects involved (killed and injured).

### **Inference**
The chart highlights a sharp rise in casualties initially (June 21, 2024), followed by a gradual decline in numbers over time. Victims injured (blue) consistently form the majority of casualties. Suspects contribute minimally, and fatalities (both victims and suspects) remain low compared to injuries. This pattern suggests the initial phase of incidents was more intense, with a tapering off as time progressed.

![Cumulative Casualties Chart](path/to/casualties_chart.png)

---

## 7. Cities with the Highest Casualty Numbers
### **Objective**
To display the top 10 cities or counties with the highest combined casualty numbers, categorizing victims killed and injured.

### **Inference**
Chicago records the highest combined casualty count, with victims injured (blue bar) forming the majority. Philadelphia and Washington follow, also with significant injury counts. The remaining cities like Kansas City and Saint Louis show relatively smaller numbers. The data indicates that large urban centers are hotspots for incidents leading to casualties, with injuries dominating over fatalities.

![Bar Chart](path/to/cities_chart.png)

---

## 8. Analysis of Arrests Across Cities
### **Objective**
To show the total number of suspects arrested across different cities, identifying cities with the highest and lowest arrests.

### **Inference**
Houston has the highest number of suspects arrested (22), indicating a significant concentration of arrests relative to other cities. Adelanto and Round Rock follow, but their arrest numbers are notably lower. On the other end, cities like South Bend and Brooklyn exhibit minimal arrest figures. This suggests a possible variation in crime rates, enforcement efficiency, or reporting across these locations.

![Arrest Analysis Chart](path/to/arrests_chart.png)

---

## 9. Proportion of Casualty Types
### **Objective**
To compare the proportions of victims killed versus injured using a focused, simplified breakdown.

### **Inference**
The chart reveals that Victims Killed constitute a significantly larger proportion (blue) than Victims Injured (green). This indicates that incidents involving casualties are more likely to result in fatalities than injuries among victims. The data underlines a stark disparity, suggesting a higher fatal impact on victims in these scenarios.

![Casualty Proportion Chart](path/to/casualty_proportion.png)

---

## 10. Incident Details Table
### **Objective**
To provide a detailed summary of incident counts by date, along with other associated fields like location and casualties.

### **Inference**
The table records 854 total incidents, with daily counts ranging from 2 to 6 incidents on specific days (e.g., April 1, 2024, and April 13, 2024). Some entries lack dates, labeled as “null,” indicating either missing data or incidents without precise timestamps. This highlights the need for improved data completeness while providing an overview of incident frequency over time.

> *(Add a detailed table visualization here if necessary)*

---

## 11. Additional Analyses
### **Distinct Houses Attacked**
A total of **426 distinct houses** were attacked, reflecting the widespread nature of the incidents across various locations.

### **Number of Incidents per City**
The chart shows a highly skewed distribution of incidents across cities. **Chicago** leads by a large margin, with nearly 50 incidents, significantly more than any other city.

### **Population Distribution Across Varying Density Levels**
The population displayed is approximately **331 million**, which contrasts starkly with the number of incidents or casualties reported.
