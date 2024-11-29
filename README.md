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

![Heatmap](https://drive.google.com/uc?id=1iGeNJuKp9BBFBqPzMhvzBG0AFfCTmK42)

---

## 2. Incidents with Exact Coordinates
### **Objective**
To analyze whether incidents reported have exact geolocation coordinates available.

### **Inference**
The chart shows that the vast majority of incidents (over 95%) have geolocation coordinates available, as represented by the dominant green section. A negligible proportion lacks coordinates, shown by the small blue segment, while the null values (yellow) are virtually absent. This indicates highly reliable geolocation data for incident reporting.

![Pie Chart](https://drive.google.com/uc?id=1_myEP9VydODi87yNzmKLDztQX5Q-OYTw)

---

## 3. Total Victims by State

### **Objective**
To present the total number of victims (killed and injured) across different states, highlighting states with the highest and lowest total casualties

### **Inference**
The chart reveals that Illinois records the highest total number of victims, with a notable gap compared to other states, driven by a significant number of injuries and fatalities. Alabama, Ohio, and New York also report high numbers, though markedly lower than Illinois. On the lower end, states like Maine, Iowa, and West Virginia report minimal casualties, with totals under 10. This demonstrates a highly uneven distribution, with specific states contributing disproportionately to the total casualties, driven likely by urban density or localized factors

![Total Victims](https://drive.google.com/uc?id=1d3N9JAk5sVf1eHDxnm7sLWXGhCWx6d4R)

---

## 4. Incidents Distribution by Date
### **Objective**
To track the number of reported incidents over time.

### **Inference**
The line chart reveals a steep decline in the number of incidents over time. Initially, on March 31, 2024, the incident count was at its peak (16 incidents). This steadily decreased, with significant drops by April 30, 2024, and eventually plateaued at 2 incidents by February 12, 2024. This indicates a clear reduction in reported incidents as time progressed.

![Line Chart](https://drive.google.com/uc?id=10MAGAZLynH7p_1NG9g_V3vIsKlD8gwUS)

---

## 5. State-by-State Comparison of Average Fatalities: Victims vs. Suspects

### **Objective**
To compare the average number of fatalities among victims and suspects across states, emphasizing differences in fatality rates between these groups.

### **Inference**
The chart shows that Nevada has the highest average fatalities among victims, followed closely by New Mexico and Maryland, suggesting these states have incidents with a more fatal outcome for victims. On the other hand, fatalities among suspects are consistently lower across states, with negligible differences between them. States like Kansas, Wisconsin, and Louisiana exhibit the lowest averages for both victims and suspects. This highlights a consistent trend where victim fatalities dominate over suspect fatalities, suggesting incidents disproportionately affect victims over suspects across all states.

![Victims vs. Suspects](https://drive.google.com/uc?id=13Qp2nU7i-rpHQbw7lYBNI2yFSuK68--_)

---

## 6. Total Casualties Over Time
### **Objective**
To illustrate the cumulative number of casualties over time, categorized by victims killed, injured, and suspects involved (killed and injured).

### **Inference**
The chart highlights a sharp rise in casualties initially (June 21, 2024), followed by a gradual decline in numbers over time. Victims injured (blue) consistently form the majority of casualties. Suspects contribute minimally, and fatalities (both victims and suspects) remain low compared to injuries. This pattern suggests the initial phase of incidents was more intense, with a tapering off as time progressed.

![Cumulative Casualties Chart](https://drive.google.com/uc?id=1thSJxPvrcgnTDg-4f0VyjsAYuuDwv2RI)

---

## 7. Cities with the Highest Casualty Numbers
### **Objective**
To display the top 10 cities or counties with the highest combined casualty numbers, categorizing victims killed and injured.

### **Inference**
Chicago records the highest combined casualty count, with victims injured (blue bar) forming the majority. Philadelphia and Washington follow, also with significant injury counts. The remaining cities like Kansas City and Saint Louis show relatively smaller numbers. The data indicates that large urban centers are hotspots for incidents leading to casualties, with injuries dominating over fatalities.

![Bar Chart](https://drive.google.com/uc?id=1UL6XJKLUvICd_OEYt3TFvLaVsmhqU1Vi)

---

## 8. Analysis of Arrests Across Cities
### **Objective**
To show the total number of suspects arrested across different cities, identifying cities with the highest and lowest arrests.

### **Inference**
Houston has the highest number of suspects arrested (22), indicating a significant concentration of arrests relative to other cities. Adelanto and Round Rock follow, but their arrest numbers are notably lower. On the other end, cities like South Bend and Brooklyn exhibit minimal arrest figures. This suggests a possible variation in crime rates, enforcement efficiency, or reporting across these locations.

![Arrest Analysis Chart](https://drive.google.com/uc?id=1cAydySy7iomVUvFtMA6Ac5Tn8UTgK1-R)

---

## 9. Proportion of Casualty Types
### **Objective**
To compare the proportions of victims killed versus injured using a focused, simplified breakdown.

### **Inference**
The chart reveals that Victims Killed constitute a significantly larger proportion (blue) than Victims Injured (green). This indicates that incidents involving casualties are more likely to result in fatalities than injuries among victims. The data underlines a stark disparity, suggesting a higher fatal impact on victims in these scenarios.

![Casualty Proportion Chart](https://drive.google.com/uc?id=10dX_KOUkC1kqC7vnyqc1mxjucwzk0lYd)

---

## 10. Incident Details Table
### **Objective**
To provide a detailed summary of incident counts by date, along with other associated fields like location and casualties.

### **Inference**
The table records 854 total incidents, with daily counts ranging from 2 to 6 incidents on specific days (e.g., April 1, 2024, and April 13, 2024). Some entries lack dates, labeled as “null,” indicating either missing data or incidents without precise timestamps. This highlights the need for improved data completeness while providing an overview of incident frequency over time.

### **Table Visualization**

| **Incident Date**    | **Location** | **Victims Killed** | **Victims Injured** | **Total Casualties** |
|-----------------------|--------------|---------------------|---------------------|-----------------------|
| null                 | 0            | 0                   | 0                   | 0                     |
| April 1, 2024        | 1            | 0                   | 4                   | 4                     |
| April 10, 2024       | 1            | 1                   | 5                   | 6                     |
| April 13, 2024       | 2            | 2                   | 19                  | 21                    |
| April 14, 2024       | 1            | 1                   | 4                   | 5                     |
| April 16, 2024       | 3            | 3                   | 9                   | 12                    |
| April 19, 2024       | 2            | 0                   | 9                   | 9                     |
| April 22, 2024       | 3            | 8                   | 5                   | 13                    |
| April 27, 2024       | 1            | 0                   | 4                   | 4                     |
| April 28, 2024       | 3            | 3                   | 9                   | 12                    |
| April 29, 2024       | 2            | 4                   | 9                   | 13                    |
| April 5, 2024        | 2            | 2                   | 6                   | 8                     |
| April 6, 2024        | 1            | 1                   | 7                   | 8                     |
| August 11, 2024      | 2            | 4                   | 4                   | 8                     |
| August 14, 2024      | 2            | 0                   | 9                   | 9                     |
| August 17, 2024      | 2            | 2                   | 10                  | 12                    |
| August 18, 2024      | 2            | 0                   | 9                   | 9                     |
| **Total**            | **214**      | **222**             | **939**             | **1161**              |


---

## 11. Number of incident per city
### **Objective**
To compare the proportions of incidents per city.

### **Inference**
The chart shows that Chicago stands out with the highest number of incidents, reaching nearly 50. Other cities, such as Saint Louis, Minneapolis, and Montgomery, also have a relatively high count of incidents, ranging between 15 and 30. In contrast, the majority of cities show a significantly lower number of incidents, with most cities (e.g., Cleveland, Fort Wayne, Burlington) reporting fewer than 10 incidents. This indicates that incidents are concentrated in a few major cities, with a sharp drop-off in frequency in smaller or less populous areas.

![incident per city](https://drive.google.com/uc?id=1oiO04DAMcD1Wl0S_l0uurYEOu7gjFbpy)

---


## 12. Distinct Houses Attacked
A total of **426 distinct houses** were attacked, reflecting the widespread nature of the incidents across various locations.

---

## 13. Number of Incidents per City
The chart shows a highly skewed distribution of incidents across cities. **Chicago** leads by a large margin, with nearly 50 incidents, significantly more than any other city.

---

### 14. Population Distribution Across Varying Density Levels
The population displayed is approximately **331 million**, which contrasts starkly with the number of incidents or casualties reported.
