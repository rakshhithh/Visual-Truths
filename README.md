Detecting and Correcting Perceptual Bias in Inflation Data Visualizations

**📌 Project Overview**

Visual Truths is a data science case study that explores how misleading graphical design choices—particularly improper y-axis scaling—can distort the interpretation of economic data. Using real-world inflation data, this project demonstrates how the same dataset can lead to very different conclusions depending on visualization practices.

The case study emphasizes ethical data visualization, perceptual bias, and responsible communication of economic indicators.

**🎯 Problem Statement**

Correct misleading inflation graphs by recreating them with a proper y-axis, draw comparative bar charts, insert a caption on perceptual bias, and justify ethical visualization standards.

This project addresses how truncated axes and poor visual scaling can exaggerate inflation trends, potentially misleading viewers despite accurate data.

**📂 Dataset**

+ Source: World Bank
+ Indicator: Inflation, consumer prices (annual %)
+ Format: CSV (downloaded as a ZIP containing data + metadata files)

Coverage: Multiple countries, multiple decades

Why this dataset?

Official and globally trusted

Frequently used in academic and policy analysis

Ideal for studying visualization ethics without altering raw data

🛠️ Tools & Technologies

Platform: Google Colab

Language: Python

Libraries:

pandas – data handling

matplotlib – visualization

Version Control: GitHub

📈 Methodology
1️⃣ Data Loading & Preparation

Extracted the main inflation CSV from the World Bank ZIP file

Skipped metadata rows

Selected a recent time window (2015–2022) for clarity

No global data imputation or deletion was performed

Missing values (NaNs) were preserved to maintain data integrity and were excluded only at the visualization stage where necessary.

2️⃣ Misleading Visualization (Intentional)

Line graph with a truncated y-axis

Same data, distorted scale

Inflation changes appear exaggerated

📌 Purpose: To demonstrate how perceptual bias can be introduced through visual design rather than data manipulation.

3️⃣ Corrected Visualization (Ethical)

Same inflation data

Y-axis starts at zero

Consistent scaling

📌 Result: Inflation trends appear gradual and proportional to actual values.

4️⃣ Comparative Bar Chart

Comparison of inflation rates across countries (India, USA, China)

Same y-axis scale for all bars

Clear labels and units

📌 Why bar charts?
They reduce perceptual distortion and improve absolute comparison.

🧠 Perceptual Bias Caption

Perceptual Bias in Visualization
Truncating the y-axis exaggerates perceived inflation changes, making minor numerical differences appear significant. Ethical visualizations must align visual scale with actual magnitude to prevent misleading interpretation.

⚖️ Ethical Visualization Principles Applied

This project follows key ethical standards in data visualization:

Accuracy: Visual proportions reflect true numerical relationships

Transparency: No hidden scaling or deceptive design choices

Non-manipulation: Visualization informs rather than persuades

Cognitive Responsibility: Avoids exploiting human perceptual biases
