# Road Accident Data Analysis Project
![Dashboard Preview](dashboard.jpg)
## Solution File

You can access the solution file for this project [here](https://drive.google.com/drive/folders/1hh7-T1z6vgSy429HwF2vZ3Awgow-5X9Z?usp=sharing).

---

## 1. Problem Statement

Road traffic accidents are a major public safety issue, resulting in fatalities, injuries, and economic damage. Analyzing patterns and trends in road accidents is crucial to develop safety measures and reduce accidents. This project focuses on analyzing a comprehensive dataset to understand accident trends and suggest preventive measures to enhance road safety.

---

## 2. Stakeholders

### Internal Stakeholders:
- **Road Safety Authorities**: For improving traffic control and safety measures.
- **Urban Planners**: To design safer road infrastructures.
- **Emergency Services**: To optimize response time to accident-prone areas.
- **Policy Makers**: To develop regulations and policies for safer roads.

### External Stakeholders:
- **General Public**: Benefiting from improved road safety.
- **Insurance Companies**: To assess risks and set premiums.
- **Logistics Companies**: To ensure safer and more efficient transportation routes.

---

## 3. Data Dictionary

| Column Name                 | Description                                                            |
|-----------------------------|------------------------------------------------------------------------|
| **Accident_Index**           | Unique identifier for each accident                                    |
| **Accident Date**            | Date of the accident                                                   |
| **Month**                    | Month of the accident                                                  |
| **Year**                     | Year of the accident                                                   |
| **Day_of_Week**              | Day of the week when the accident occurred                             |
| **Junction_Control**         | Type of control at the junction (if any)                               |
| **Accident_Severity**        | Severity of the accident (Fatal, Serious, Slight)                      |
| **Number_of_Casualties**     | Number of casualties involved in the accident                          |
| **Light_Conditions**         | Light conditions (Daylight, Darkness) during the accident              |
| **Road_Surface_Conditions**  | Condition of the road surface (Dry, Wet, Snow/Ice)                     |
| **Road_Type**                | Type of road (Single carriageway, Dual carriageway, etc.)              |
| **Weather_Conditions**       | Weather conditions during the accident                                 |
| **Vehicle_Type**             | Type of vehicle involved (Car, Motorcycle, etc.)                       |
| **Speed_limit**              | Speed limit at the accident location                                   |
| **Urban_or_Rural_Area**      | Whether the accident occurred in an urban or rural area                |

---

## 4. Methodology

1. **Data Collection**: The data was collected from national road accident records.
   
2. **Data Cleaning**: The dataset was cleaned by removing null values and duplicates, and ensuring consistent date formatting.

3. **Exploratory Data Analysis (EDA)**: We explored key factors contributing to road accidents such as vehicle type, road conditions, light conditions, and accident severity.

4. **Visualization**: Visualizations were created to highlight trends using bar charts, heatmaps, and line graphs for easy interpretation.

5. **Statistical Analysis**: We applied statistical techniques to understand correlations between road types, vehicle involvement, and accident outcomes.

---

## 5. Tool Stacks

- **Python**: For data cleaning and analysis (`pandas`, `matplotlib`, `seaborn`).
- **Excel**: For basic data cleaning and pivot table analysis.
- **Power BI / Tableau**: For interactive data visualization.
- **Jupyter Notebook**: For documenting the step-by-step analysis.

---

## 6. Recommended Analysis

- **Accident Severity by Vehicle Type**: Analyzing the role different vehicles play in accident severity.
- **Weather and Light Conditions Impact**: Investigating how weather and light conditions influence accident rates.
- **Road Type Analysis**: Understanding how accidents vary across road types (e.g., dual carriageways vs. single carriageways).
- **Geographical Location Analysis**: Identifying urban and rural accident hotspots using geospatial data.

---

## Conclusion

This road accident analysis reveals several key insights into the causes of accidents:

- **Vehicle Types**: Most accidents involve vehicles in the "Others" category, with significant contributions from cars and motorcycles, pointing to the need for targeted safety campaigns.
- **Road Surface Conditions**: A majority of accidents occur on dry surfaces, showing that even under ideal conditions, road safety is a concern.
- **Light Conditions**: Most accidents happen during daylight, indicating a need for greater awareness and safety measures during peak traffic hours.
- **Geographical Impact**: Urban areas experience more accidents than rural areas, suggesting a need for stricter traffic control in cities.

By focusing on these factors, authorities can implement better road safety measures, ultimately reducing casualties and improving overall road safety.
