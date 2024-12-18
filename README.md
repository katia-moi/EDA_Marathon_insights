# Marathon EDA Project

## 📖 Overview
This repository contains an exploratory data analysis (EDA) project focused on understanding marathon performance using the [Marathon Time Predictions dataset](https://www.kaggle.com/datasets/girardi69/marathon-time-predictions/data) from Kaggle. The dataset includes information on training history, pacing strategies, and marathon results. 

The goal of this project is to uncover key factors that influence marathon performance, analyze pacing strategies, and identify insights that differentiate elite runners from amateur participants. Through visualizations and statistical analysis, this project aims to provide actionable insights into what it takes to run a successful marathon.

---

## 📊 Dataset Description
The dataset contains data from marathon runners, with the following key columns:

- **`MarathonTime`**: Total time to complete the marathon (in decimal hours).
- **`Wall21`**: Time taken to complete the first half of the marathon (in decimal hours). Indicates pacing consistency; higher values may suggest runners "hit the wall."
- **`km4week`**: Average kilometers run per week in the 4 weeks before the marathon (including the marathon itself).
- **`sp4week`**: Average speed during training in the 4 weeks before the marathon (in kilometers per hour).
- **`CrossTraining`**: Whether the runner engaged in cross-training (e.g., cycling or swimming).
- **`Category`**: Runner category (e.g., age group).

---

## 🧠 Hypotheses
The project investigates the following hypotheses:

1. **Consistent pacing leads to better performance.**
   - Runners with `Wall21` values close to 1.00 (even pacing) are expected to have faster finishing times compared to those with higher values.

2. **Training mileage is positively correlated with performance.**
   - Higher `km4week` values are associated with faster marathon times.

3. **Training speed impacts marathon times.**
   - Runners with lower `sp4week` values (faster training speeds) are expected to have better marathon performance.

4. **Elite runners are better at pacing.**
   - Elite runners are expected to have `Wall21` values closer to 1.00 compared to amateurs.

---

## 🎯 Objectives
- Analyze the distribution of marathon times and training-related metrics.
- Investigate correlations between training metrics (`km4week`, `sp4week`) and marathon times.
- Test hypotheses related to pacing strategies and performance.
- Create visualizations to communicate key findings.

---

## ⚙️ Workflow
The project is structured into the following steps:

1. **Data Cleaning:**
   - Handle missing values (e.g., `Wall21` missing as `"-"`).
   - Ensure proper data types for numerical columns like `km4week`, `sp4week`, and `MarathonTime`.

2. **Exploratory Data Analysis:**
   - Analyze the distribution of key metrics (e.g., `MarathonTime`, `Wall21`).
   - Visualize relationships between variables (e.g., scatter plots for `km4week` vs. `MarathonTime`).
   - Identify and handle outliers.

3. **Hypothesis Testing:**
   - Use statistical methods (e.g., correlation analysis, comparisons of group means) to test hypotheses.
   - Analyze trends in pacing strategies (`Wall21`) and their impact on marathon performance.

4. **Visualization:**
   - Create charts (e.g., histograms, box plots, scatter plots) to summarize findings.
   - Highlight trends and relationships visually.

5. **Insights and Documentation:**
   - Summarize key findings.
   - Document limitations and potential extensions of the analysis.

---

## 🗂️ Repository Structure

EDA_Marathon_insights/
	src/
		data/ # contains the dataset
		notebooks/ # Jupyter notebooks for EDA
		img/ # images that I used for my project
		utils/ # modules/functions/clases used in the project
   Memoria.pdf
   Presentacion.pdf
   Presentacion_video.mp4



