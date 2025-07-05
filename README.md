# **Football Data Analysis Repository**  

This repository contains various **codes and tutorials** focused on **football event data analysis**, using Python and popular data science libraries. Whether you're a **data scientist, analyst, or football enthusiast**, this repository will help you **manipulate, analyze, and visualize football data** effectively.  

## **Contents**  


# 📊 From Data to Social Media

This notebook is part of the **QuantStats Data Analysis in Football Course**  
🎯 **Objective**: Learn how to turn raw event data into meaningful, shareable visualizations for social media.

---

## 💡 What You'll Learn

- How to filter and prepare football event data  
- How to create captivating visualizations with `mplsoccer`  
- How to highlight key actions like defensive events or goals  
- How to export and save your visuals  
- ⚠️ Final Challenge: Build your own **defensive heatmap** for Ali Abdi!

---

## 🏆 Challenge

📌 **Create a heatmap of Ali Abdi’s defensive actions** and post your result on LinkedIn with the hashtag  
`#BentelliChallenge` and **tag me (@Sara Bentelli)** — I’ll feature selected works!

Need help? Check the notebook for guidance and examples.

---

## 📁 Files Included

- `From_Data_to_Social_Media.ipynb`: The full tutorial notebook used in the live demo session  
- `ali_abdi.csv`: The dataset for the visualizations  
- `From_Data_to_Social_Media.pdf`: The PDF guide that explains the methodology  
---

## 🛠 Libraries Used

- `pandas`  
- `mplsoccer`  
- `matplotlib`  
- `seaborn`  
- `highlight_text`  
- `FontManager`, `PIL`, `cmasher`...

---

## 🚀 Let's Build Together

Don’t hesitate to fork, play with the code, and share your creations.  
This is just the beginning — bring your own creativity, and let’s push the limits of football analysis together!

### **1️⃣ Data Manipulation Techniques**  
- **Concatenation & Splitting**: Efficient methods for merging and breaking down large datasets.  
- **Grouping & Filtering**: Advanced techniques to group data and retrieve meaningful subsets, crucial for focusing on specific players, teams, or match events.  

### **2️⃣ Visualization of Event Data (Heatmap Styles)**  
📌 **Tutorial: "Different Heatmap Styles for Football Event Data"**  
- **Kernel Density Estimation (KDE)**: Visualizing player activity areas on the pitch with smooth density plots.  
- **Hexbin Plot**: A grid-based heatmap providing detailed spatial insights.  
- **Custom Colormaps**: Explore how to create visually appealing colormaps for better data storytelling.  

👉 **Explore the tutorial here**: [Heatmap Styles Notebook](https://github.com/sara1621/Football-Data-Analysis/blob/main/Heatmap_Styles.ipynb)  

---

### **4️⃣ Convex Hull Styles for Pass Clustering**  
📌 **New Tutorial: "Using Convex Hulls to Analyze Passing Structures"**  
- Implements **Convex Hull visualization** to outline passing clusters.  
- Helps in understanding **positional structures** and the **spread of passes within clusters**.  
- Applied to **Final Third Entry Passes**, highlighting passing lanes and patterns.  

📷 **Check out the implementation** [here](https://github.com/sara1621/Football-Data-Analysis/blob/main/ConvexHull_Style.ipynb).  

---

### **3️⃣ Clustering Passes by Corridor**  
📌 **New Tutorial: "Clustering Final Third Entry Passes in Football"**  
This tutorial focuses on **segmenting passes into three vertical corridors (Left, Center, Right)** and applying **K-Means clustering** to identify passing patterns.  
- 🔹 **Filters Argentina's passes** that start in their own half and enter the final third.  
- 🔹 **Uses K-Means clustering** to classify passes into different clusters within each corridor.  
- 🔹 **Visualizes passing trends** with color-coded clusters and structured pitch separation.  

📷 **See the visualization in action** and explore the code [here](https://github.com/sara1621/Football-Data-Analysis/blob/main/Clustering_passes.ipynb).  

---

# 🎯 How to Use `goal-plot` to Visualize Penalty Shots

`goal-plot` is my first Python package – simple and easy to use! It lets you draw a clean 2D goal and plot events like penalties on it.

This tutorial shows you how to visualize penalty shots using your own data.

👉 **Explore the tutorial here**: [draw_goal Notebook](https://github.com/sara1621/Football-Data-Analysis/blob/main/draw_goal.ipynb)  


---

## 🧩 Installation

```bash
pip install goal-plot
```


## **🚀 How to Use This Repository?**  
Simply clone the repository and explore the Jupyter notebooks:  
```bash
git clone https://github.com/sara1621/Football-Data-Analysis.git
cd Football-Data-Analysis
