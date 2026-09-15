# 🌾 Seasonal Agriculture Performance Analysis

## 📌 Project Overview

**Seasonal Agriculture Performance Analysis** is a data visualization and analysis project that studies agricultural performance across different **seasons, crops, geographical regions, environmental conditions, resource usage, and economic factors**.

The project aims to identify seasonal patterns, compare crop performance, understand resource utilization, and generate meaningful insights that can support better agricultural decision-making.

---

## 🎯 Objectives

* Analyze agricultural performance across different seasons.
* Compare crop-wise yield and production.
* Study the relationship between environmental conditions and yield.
* Analyze irrigation, fertilizer, pesticide, and other resource usage.
* Compare revenue, cost, and profit across seasons and crops.
* Analyze water efficiency.
* Study disease and pest risk.
* Identify unusual patterns and outliers.
* Generate data-driven conclusions and recommendations.

---

## 📊 Dataset

The dataset contains:

* **4,000 records**
* **28 features**

### Important Features

* Farm ID
* State
* District
* Crop
* Season
* Farm Area
* Rainfall
* Temperature
* Humidity
* Sunlight
* Soil pH
* Soil Moisture
* Nitrogen
* Phosphorus
* Potassium
* Irrigation Method
* Fertilizer Usage
* Pesticide Usage
* Seed Quality
* Yield
* Production
* Market Price
* Total Cost
* Revenue
* Profit
* Water Used
* Water Efficiency
* Disease/Pest Risk

---

## 🧹 Data Preprocessing

The following preprocessing steps were performed:

* Checked dataset dimensions and data types.
* Checked missing values.
* Checked duplicate records.
* Analyzed categorical and numerical variables.
* Handled missing values using **Season + Crop based median imputation**.
* Used overall median as a fallback where required.
* Detected potential outliers using the **IQR method**.

### Missing Values

| Column            | Missing Values |
| ----------------- | -------------: |
| Rainfall_mm       |             48 |
| Soil_Moisture_pct |             40 |
| Yield_Tonnes_Ha   |             32 |

**Duplicate rows:** 0

---

## 📈 Analysis Performed

### 1. Seasonal Performance Analysis

Compared:

* Kharif
* Rabi
* Zaid

based on yield, production, environmental conditions and profitability.

### 2. Crop Performance

Analyzed the performance of:

* Chilli
* Cotton
* Groundnut
* Maize
* Pulses
* Rice
* Sugarcane
* Wheat

across different seasons.

### 3. Environmental Analysis

Studied relationships between:

* Rainfall
* Temperature
* Humidity
* Sunlight
* Soil pH
* Soil moisture

and agricultural performance.

### 4. Resource Utilization

Analyzed:

* Irrigation methods
* Fertilizer usage
* Pesticide usage
* Water consumption
* Nutrient usage
* Seed quality

### 5. Economic Analysis

Compared:

* Market price
* Total cost
* Revenue
* Profit

across seasons and crops.

### 6. Water Efficiency

Analyzed water usage and:

**Water Efficiency = Yield / Water Used**

to identify more efficient farming conditions.

### 7. Disease & Pest Risk

Studied disease/pest risk and its relationship with agricultural performance.

### 8. Statistical Analysis

Statistical techniques included:

* Descriptive statistics
* Correlation analysis
* One-way ANOVA
* Kruskal-Wallis test
* IQR-based outlier detection
* Coefficient of variation

---

## 📊 Visualizations

The project includes visualizations such as:

* Seasonal yield comparison
* Crop-wise yield comparison
* Season × Crop analysis
* Production comparison
* Environmental condition plots
* Resource utilization charts
* Profit and revenue comparison
* Water efficiency analysis
* Disease/pest risk analysis
* Correlation heatmap
* Scatter plots
* Regional/state analysis
* Outlier analysis

---

## 🛠️ Technologies Used

* **Python**
* **Pandas**
* **NumPy**
* **Matplotlib**
* **Seaborn**
* **SciPy**
* **Jupyter Notebook**

---

## 📁 Project Structure

```text
Seasonal-Agriculture-Performance-Analysis/
│
├── dataset/
│   └── seasonal_agriculture_performance_dataset.csv
│
├── notebook/
│   └── Seasonal_Agriculture_Performance_Analysis.ipynb
│
├── presentation/
│   └── Seasonal_Agriculture_Performance_Presentation.pptx
│
├── README.md
│
└── requirements.txt
```

---

## 🚀 How to Run the Project

### Step 1: Clone the Repository

```bash
git clone https://github.com/yourusername/Seasonal-Agriculture-Performance-Analysis.git
```

### Step 2: Open the Project

```bash
cd Seasonal-Agriculture-Performance-Analysis
```

### Step 3: Install Required Libraries

```bash
pip install pandas numpy matplotlib seaborn scipy jupyter
```

### Step 4: Start Jupyter Notebook

```bash
jupyter notebook
```

### Step 5: Open

```text
Seasonal_Agriculture_Performance_Analysis.ipynb
```

Run the notebook cells sequentially.

---

## 🔍 Key Findings

The analysis helps identify:

* Seasonal differences in agricultural performance.
* Crop-wise variations in yield.
* Differences in soil moisture and environmental conditions across seasons.
* Relationship between agricultural resources and yield.
* Differences in revenue, cost and profit.
* Water-efficient farming conditions.
* Crops/seasons with comparatively higher disease and pest risk.
* Unusual observations and performance variations.

---

## 💡 Recommendations

Based on the analysis, agricultural decisions can be improved by:

* Selecting suitable crops according to seasonal conditions.
* Optimizing irrigation and water usage.
* Monitoring soil moisture and nutrient levels.
* Improving seed quality.
* Using fertilizers and pesticides efficiently.
* Monitoring disease and pest risks.
* Comparing profitability before selecting crops.
* Using historical agricultural data for better planning.

---

## 🔮 Future Scope

The project can be further improved by:

* Adding real-time weather data.
* Integrating satellite and remote-sensing data.
* Building crop yield prediction models.
* Applying Machine Learning algorithms.
* Developing an interactive **Power BI/Tableau dashboard**.
* Creating a crop recommendation system.
* Adding real-time market-price data.
* Developing a web-based agricultural decision-support system.

---

## 👨‍💻 Author

**Shivansh Mishra**

**B.Tech – FGIET Raebareli**

---

## ⭐ Project

If you find this project useful, consider giving the repository a ⭐.

**#DataAnalysis #Agriculture #Python #DataVisualization #Pandas #Matplotlib #Seaborn #JupyterNotebook #DataScience**
