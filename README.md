Mobile Device Specifications Data Analysis (Python)
## Project Overview
This project involves an in-depth data analysis of a mobile device specifications dataset. The primary goal was to uncover trends in device releases, identify key market players, understand the evolution of hardware specifications like RAM, and analyze the distribution of operating systems. This analysis was performed using Python with libraries such as Pandas, Matplotlib, and Seaborn.

## Dataset
The analysis utilizes a sampled version of a larger dataset (originally `2025-06-21-SmartDevices.csv`) containing mobile device specifications. Due to GitHub's file size limits, a subset of the data (`device_specs_sampled.xls`, ~10 MB) was generated for this repository.

**Key Columns Analyzed:**
* `Released Year`: Year of device release.
* `Brand`: Device manufacturer.
* `RAM Capacity`: Random Access Memory capacity.
* `Operating System`: The installed operating system.

## Key Questions Addressed & Insights:

1.  **Device Release Trends Over Time:**
    * **Question:** How has the volume of mobile device releases changed year-over-year?
    * **Insight:** The analysis revealed a significant increase in device releases over the years, with a notable acceleration in the 2010s and early 2020s, indicating rapid growth in the mobile device market.

2.  **Top Brands by Device Count:**
    * **Question:** Which manufacturers have produced the most devices in the dataset, indicating their market presence?
    * **Insight:** **Samsung** emerged as the overwhelmingly dominant brand by volume, significantly outpacing other manufacturers like Huawei and Xiaomi in the dataset.

3.  **Evolution of Average RAM Capacity:**
    * **Question:** How has the average RAM capacity in mobile devices progressed over time?
    * **Insight:** A clear **exponential growth** in average RAM capacity was observed, demonstrating rapid advancements in device performance and the increasing demands of modern mobile applications.

4.  **Operating System Market Share:**
    * **Question:** What is the distribution of different operating system categories among the devices?
    * **Insight:** The market is overwhelmingly dominated by **Android** across its various versions, with other operating systems like Windows Phone/Mobile and iOS holding much smaller shares in this dataset.

## Tools and Libraries
* **Python:** Programming language for data manipulation and analysis.
* **Pandas:** For data loading, cleaning, manipulation, and aggregation.
* **Matplotlib:** For basic plotting.
* **Seaborn:** For advanced and aesthetically pleasing data visualization.
* **Jupyter Notebook:** Interactive environment for conducting and presenting the analysis.

## Project Structure
* `device_specs_sampled.xls`: The sampled dataset used for the analysis (Excel format).
* `device_analysis_python.ipynb`: The Jupyter Notebook containing all Python code for data loading, cleaning, analysis, and visualization.

## How to Run the Analysis
1.  Clone this repository to your local machine.
2.  Ensure you have Python (preferably with Anaconda distribution) and Jupyter Notebook installed.
3.  Open the `device_analysis_python.ipynb` file in Jupyter Notebook.
4.  Ensure `device_specs_sampled.xls` is in the same directory as the notebook.
5.  Run the cells sequentially to reproduce the analysis.

---
*This project showcases skills in data loading (handling messy real-world data), data cleaning, feature engineering (OS categorization), exploratory data analysis, and effective data visualization using Python for a portfolio context.*
