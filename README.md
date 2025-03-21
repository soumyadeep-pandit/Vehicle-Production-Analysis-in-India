# **Vehicle Production Analysis in India (2001-02 to 2012-13)**

## **1. Project Overview**
This project analyzes the production trends of different vehicle categories in India from 2001-02 to 2012-13. Using a dataset containing vehicle production statistics, various visualizations and insights are generated to understand growth patterns, market trends, and key takeaways from the Indian automobile industry.

## **2. Objectives**
- Analyze the overall production trend of vehicles in India.
- Compare the growth of Passenger Vehicles (PVs), Commercial Vehicles (CVs), Two-Wheelers, and Three-Wheelers.
- Identify segment-wise production trends within Passenger Vehicles, Two-Wheelers, and Three-Wheelers.
- Visualize the data using appropriate charts and interpret the findings.
- Understand the factors influencing the growth or decline in production.

## **3. Dataset Details**
- **Source:** Dataset contains vehicle production figures across different categories.
- **Time Period:** 2001-02 to 2012-13.
- **Key Columns:**
  - **Category** (Passenger Vehicles, Commercial Vehicles, Two-Wheelers, Three-Wheelers)
  - **Segment** (e.g., Passenger Cars, Multi-Utility Vehicles, Scooters, Mopeds)
  - **Yearly Production Data** (e.g., 2001-02, 2002-03, etc.)

## **4. Data Preprocessing**
- Loaded the dataset using Pandas.
- Checked for missing values and handled them using mean imputation.
- Converted categorical columns to appropriate formats for analysis.

## **5. Analysis & Visualization**

### **5.1 Passenger Vehicle Production Analysis**
- Segmented data into **Passenger Cars, Multi-Utility Vehicles (MUVs), and Total Passenger Vehicles**.
- Used **line charts and stacked area charts** to compare growth trends.
- **Key Findings:**
  - Passenger vehicle production increased by **382.82%** from 2001-02 to 2012-13.
  - Passenger Cars saw the highest growth (**433.41%**).
  - A significant surge was observed post-2009-10.

### **5.2 Two-Wheeler vs Three-Wheeler Production Comparison**
- Used a **line chart with markers** to compare growth trends.
- **Key Findings:**
  - Two-wheeler production grew steadily from **4M to nearly 16M units**.
  - Three-wheeler production remained relatively stable.
  - The demand for two-wheelers surged around 2008-09.

### **5.3 Segment-Wise Two-Wheeler Production Analysis**
- Used **stacked area charts** to visualize the contribution of Scooters, Motorcycles, Mopeds, and Electric Two-Wheelers.
- **Key Findings:**
  - **Motorcycles dominated** production (grew by **309.60%**).
  - **Scooter production increased steadily**.
  - **Moped production declined** towards later years.

### **5.4 Three-Wheeler Production Analysis**
- Used **stacked area charts** to analyze Passenger Carriers and Goods Carriers.
- **Key Findings:**
  - Passenger Carriers grew by **2891.88%**.
  - Goods Carriers showed **11802.61% growth**, indicating increased commercial use.

### **5.5 Total Vehicle Production Trends**
- Used **bar charts and pie charts** to analyze total vehicle production across all categories.
- **Key Findings:**
  - Two-wheelers had the largest production share.
  - Passenger vehicles saw steady growth after 2005-06.
  - Commercial vehicles had a sharp rise post-2009-10.

## **6. Insights & Conclusion**
- The Indian automobile industry saw **significant growth** from 2001-02 to 2012-13.
- Two-wheelers dominated the market, followed by passenger vehicles.
- The **2009-10 period marked a major shift**, likely due to **government policies, economic factors, or demand increase**.
- Commercial vehicle production had the **highest percentage growth**, but overall production was lower compared to other categories.

## **7. Tools & Technologies Used**
- **Python (Pandas, NumPy, Matplotlib, Seaborn, Scikit-learn)** for data analysis and visualization.
- **Jupyter Notebook** for running the analysis.
