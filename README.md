## 📊 My Streamlit Dashboard

🔗 **Check out my live dashboard here:** [Streamlit Dashboard](https://adidas-sales-dashboard-jkk8x56g4xtnyhj8wmytuk.streamlit.app/)

---

# 🏷️ Adidas Sales Dashboard

A dynamic and interactive **Streamlit dashboard** to visualize Adidas sales data across retailers, regions, and time periods using **Python, Plotly, and Pandas**.

---

## 📑 Table of Contents

- 🎯 Objective  
- 🛠️ Technologies Used  
- ⚙️ Steps in Project Workflow  
  - Step 1: Fetching Data  
  - Step 2: Data Cleaning  
  - Step 3: Exploratory Data Analysis (EDA)  
  - Step 4: Dashboard Development  
  - Step 5: Streamlit Layout  
  - Step 6: Deployment  
- ✨ Key Features  
- 📂 How to Use the Application  
- 🖼️ Dashboard Screenshots  
- ✅ Conclusion  
- 🔗 Live App  

---

## 🎯 Objective

To build an interactive sales dashboard for **Adidas** that provides insights into sales by **retailer**, **region**, and **monthly trends** using **Python** and **Streamlit**.

---

## 🛠️ Technologies Used

| Tool         | Purpose                          |
|--------------|----------------------------------|
| Python       | Core programming language        |
| Pandas       | Data manipulation and analysis   |
| Plotly       | Interactive visualizations       |
| Streamlit    | Web app and dashboard creation   |
| OpenPyXL     | Reading Excel files              |
| Pillow (PIL) | Displaying image/logo            |

---

## ⚙️ Steps in Project Workflow

### Step 1: Fetching Data  
- Loaded Excel data from `Adidas.xlsx`, specifically the **Sales** sheet.

### Step 2: Data Cleaning  
- Removed leading/trailing spaces from column names to ensure compatibility.

### Step 3: Exploratory Data Analysis (EDA)  
- Grouped data by **Retailer**, **State**, **Month-Year**, **Region**, and **City** for visualization.

### Step 4: Dashboard Development  
- Created visualizations using **Plotly**:
  - 📊 Bar chart for total sales by retailer  
  - 📈 Line chart for monthly sales  
  - 📉 Combo chart for sales and units sold by state  
  - 🌍 Treemap for region and city breakdown

### Step 5: Streamlit Layout  
- Used columns and markdown for a clean, responsive UI  
- Added logo, title, current date, and expandable data views  
- Included **CSV download buttons** for each chart

### Step 6: Deployment  
- Deployed the app using **Streamlit Cloud**

---

## ✨ Key Features

- 📊 Interactive Plotly charts  
- 🧾 Expandable data views with CSV download options  
- 📅 Dynamic "last updated" timestamp  
- 🗺️ Region and city-level sales breakdown using treemap  
- 🔄 Responsive layout using Streamlit columns  

---

## Dashboard Screenshots
📌 Total Sales and Monthly Trends
![Image](https://github.com/Welde-Dhanashri/Adidas-Sales-Dashboard/blob/main/Total%20Sales%20By%20Retailer%20ANd%20Monthly%20Trends.png?raw=true)
📌 Total Sales and Units Sold by State
![Image](https://github.com/Welde-Dhanashri/Adidas-Sales-Dashboard/blob/main/Total%20Sales%20and%20Units%20Sold.png?raw=true)
📌 Sales by Region and City
![Image](https://github.com/Welde-Dhanashri/Adidas-Sales-Dashboard/blob/main/Total%20Sales%20By%20Region%20And%20State.png?raw=true)

---

## Conclusion
This dashboard provides an intuitive way to navigate and visualize Adidas sales data. Whether you're a business stakeholder or a data analyst, it offers key performance insights, trends, and the ability to extract custom views of the data for decision-making.



