## **Analysis of Citi Bike Usage Patterns: Visual Analytics for Urban Mobility Optimization**  
### **Author:** Harsha Saketh Konjeti  

### Note: Uploaded all.pbix files and .csv files to google drive because of size issue. https://drive.google.com/drive/folders/1Jii7bndu_nYciMLVZbYBvy9NP3psFTQP?usp=sharing


### **Project Overview**  
This project explores CitiBike usage patterns to optimize **urban mobility**, improve **bike redistribution**, and provide actionable insights for **CitiBike operators, urban planners, and commuters**. The analysis integrates **Treemaps, Sankey Diagrams, and Heatmaps** to visualize high-demand stations, ride flow, and peak usage times.  

### **Stakeholders & Insight Needs**  
- **CitiBike Operators**: Require insights on **high-demand stations**, **peak hours**, and **ride durations** to optimize bike availability.  
- **Urban Planners**: Need **ride flow data** to improve **bike lane placements** and urban cycling infrastructure.  
- **Commuters**: Can benefit from insights on **bike availability patterns** for better trip planning.  

### **Dataset**  
- **Source:** CitiBike Open Data Portal  
- **Features:**  
  - **Ride timestamps** (start/end times)  
  - **Station names** (start and end)  
  - **Trip duration** (in minutes)  
  - **User types** (member/casual rider)  
- **Data Quality Considerations:**  
  - Missing values in station names (3,349 records) and geospatial data (713 records) handled via **filtering and interpolation**.  
  - Ride timestamps standardized for **peak usage analysis**.  
  - Ensured **categorical data cleaning** for station names.  

### **Data Analysis & Visualization**  
- **Tools Used:** Python (Pandas, NumPy) & Power BI  
- **Visualizations Implemented:**  
  1. **Treemap - Ride Distribution by Start Station**:  
     - **Larger blocks** indicate **high-demand stations**.  
     - Helps CitiBike operators **optimize bike redistribution**.  
     - **Example Insight**: "1 Ave & E 6 St" requires more frequent rebalancing.  
  2. **Sankey Diagram - Ride Flow Between Stations**:  
     - **Thicker lines** represent **more frequent travel routes**.  
     - Helps urban planners improve **connectivity & bike lane placements**.  
     - **Example Insight**: Heavy ride flow between "Grand Army Plaza" and "2 Ave & E 72 St".  
  3. **Heatmap - Peak Bike Usage by Hour & Day**:  
     - **Darker shades** indicate **higher ride demand**.  
     - Helps identify **rush hours** for increased bike availability.  
     - **Example Insight**: Peak hours are **8-10 AM & 4-7 PM** on weekdays.  

### **Key Findings**  
- **Peak ride demand** occurs **during morning (8-10 AM) & evening (4-7 PM) rush hours**.  
- **Business districts & transit hubs** experience the highest CitiBike usage.  
- **High-volume stations** need **frequent bike rebalancing** for optimal service.  
- **Some stations show imbalance in bike inflow vs. outflow**, requiring better allocation strategies.  
- **Commuter ride patterns differ on weekdays vs. weekends**, highlighting a mix of work and recreational usage.  

### **Use of AI in the Project**  
- **ChatGPT** helped recommend visualization techniques and summarize data trends.  
- AI-assisted pattern recognition improved **large dataset analysis efficiency**.  
- AI suggestions were refined to address **real-world data inconsistencies**.  

### **Project Links**  
- **GitHub Repository**: [CitiBike Visualizations](https://github.com/hkonjeti3/Visualisation_project-hkonjeti)  
- **Power BI Dashboards**:  
  - [Treemap Visualization](#) *(Add Power BI link)*  
  - [Sankey Diagram Visualization](#) *(Add Power BI link)*  
  - [Heatmap Visualization](#) *(Add Power BI link)*  

### **How to Run the Project**  
1. **Clone the repository**  
   ```bash
   git clone https://github.com/hkonjeti3/Visualisation_project-hkonjeti.git
   ```  
2. **Open Power BI** and load the dataset.  
3. **Explore interactive visualizations** in Power BI or view the **static exports** available in the repository.  

### **Future Improvements**  
- Implement **real-time demand forecasting** for dynamic bike reallocation.  
- Enhance **AI-driven anomaly detection** for unexpected usage spikes.  
- Improve **visual interactivity and filtering options** for deeper insights.  

### **Acknowledgments**  
Thanks to **CitiBike Open Data** for making real-world datasets available. Special thanks to **faculty members and peers** for their insights and discussions. AI-assisted tools like **ChatGPT** were instrumental in refining workflows and structuring this report.
