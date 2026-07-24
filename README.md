# laptop-data-project
# read my project 
# Laptop Market & Price Analysis

An exploratory data analysis (EDA) project focusing on laptop hardware specifications, pricing structures, and brand positioning in the consumer electronics market.

## 📌 Project Overview
This project uncovers patterns in laptop manufacturing and retail pricing using Python. By analyzing hardware variables, the project provides actionable insights into how brands package their tech specs and price their devices.

## 📊 Core Business Questions
* **Market Share:** Which brands have the highest volume of unique laptop models?
* **Pricing Tiers:** What are the minimum, maximum, and average price floors for each brand?
* **Value Drivers:** How significantly do specifications like RAM, CPU, Storage, and Screen Resolution drive up the final cost?
* **Physical Attributes:** Is there a premium placed on thin-and-light form factors (Weight vs. Price)?

## 📁 Dataset Features
The dataset contains information on the following attributes:
* `Company` - Manufacturer brand (e.g., Dell, Lenovo, Apple, HP)
* `TypeName` - Category of laptop (e.g., Notebook, Gaming, Ultrabook)
* `Inches` - Physical screen size
* `ScreenResolution` - Display quality and resolution
* `Cpu` / `Ram` / `Memory` - Core hardware performance metrics
* `OpSys` - Operating System installed
* `Weight` - Physical weight of the device
* `Price` - Retail price point

## 🛠️ Requirements & Installation
To run this project locally, clone the repository and install the required data science packages:

```bash
pip install pandas numpy matplotlib seaborn
```

## 🚀 Getting Started
1. Place your dataset (`LAPTOPDATA.csv`) in the root directory.
2. Open your Jupyter Notebook runner environment.
3. Execute the cells in your notebook to generate the summaries and statistical groupings.

## 📈 Initial Findings
* **Volume Leaders:** Lenovo (290 variants) and Dell (286 variants) offer the widest variety of hardware configurations.
* **Niche Players:** Premium brands like Apple (21 variants) and Razer (7 variants) maintain highly consolidated, specialized product lines.
