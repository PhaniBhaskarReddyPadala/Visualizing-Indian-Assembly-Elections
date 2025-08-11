---

# Visualizing Indian Assembly Elections

---

## 📌 Description

This project focuses on analyzing and visualizing Indian Assembly Election data to uncover trends in voter behavior, party performance, NOTA voting patterns, and constituency-level statistics. It leverages Python for data cleaning, processing, and visualizations using statistical and exploratory analysis methods.

---

## 📄 Project Overview

The aim of this project is to process large-scale election data from multiple states across India, detect anomalies, and present meaningful insights through visualizations.
The analysis includes state-level, party-level, and constituency-level perspectives, with a deep focus on Andhra Pradesh for comparative studies between key political parties.

---

## 🎯 Objectives

* Clean and preprocess raw election data for analysis.
* Detect and highlight outliers in voting patterns.
* Explore state-wise and party-wise voting trends.
* Compare performance of major political parties in targeted regions.
* Visualize statistical patterns such as NOTA vote share, vote margins, and candidate participation.

---

## 📂 Dataset Source and Attributes

**Source:** [Official Election Commission dataset (Assembly segment details of Parliamentary Constituencies).
](https://www.data.gov.in/resource/stateut-wise-details-assembly-segment-pc-parliamentary-constituency-during-2024)

**Attributes:**

* **State/UT Name** – Name of the state or union territory.
* **PC No** – Parliamentary Constituency number.
* **PC Name** – Parliamentary Constituency name.
* **Total Electors in PC** – Number of registered voters in the PC.
* **AC No** – Assembly Constituency number.
* **AC Name** – Assembly Constituency name.
* **Total Electors in AC** – Number of registered voters in the AC.
* **Total Valid Votes in State** – Total number of valid votes cast in the state.
* **NOTA Votes EVM in AC** – Number of NOTA votes in the AC.
* **Candidate Name** – Name of the candidate.
* **Party** – Political party affiliation.
* **Votes Secured EVM** – Votes received by the candidate via EVM.

---

## 🛠 Tools & Libraries

* **Python 3**
* **pandas** – Data manipulation and cleaning
* **numpy** – Numerical operations
* **matplotlib** – Data visualization
* **seaborn** – Statistical plotting
* **scipy** – Z-score method for outlier detection

---

## 📊 Key Analyses & Visualizations

* Data cleaning, handling missing values, and removing duplicates.
* Outlier detection using the **Z-score method**.
* Party performance comparison across states.
* Andhra Pradesh-focused analysis for **YSRCP** vs **TDP**.
* Statistical insights on NOTA voting trends, candidate participation, and vote margins.

---

## 📈 Results & Insights

* Clear identification of outliers in voting patterns.
* Top political parties’ dominance visualized across states.
* Andhra Pradesh data shows distinct competition between YSRCP and TDP.
* NOTA voting percentage varies significantly between states.
* Strong correlations observed between elector count and votes secured in some states.

---

## 🖼 Sample Visualizations

### 1. Distribution of Total Valid Votes in Each State

<img width="1325" height="742" alt="{D47059C8-AC87-4833-AE1B-689BBCBF2973}" src="https://github.com/user-attachments/assets/c4e93415-c22f-4dfd-b921-a5afd5704748" />


### 2. Vote Share of Top 10 Parties (Pie Chart)

<img width="998" height="793" alt="{331038B3-39EF-4A12-930B-7EC32E3E254D}" src="https://github.com/user-attachments/assets/9ebb0f1a-2f69-49ad-9cd7-5ce5692d5ee0" />


### 3. Party-wise Vote Share Across Andhra Pradesh Constituencies (Scatter Plot)

<img width="1192" height="632" alt="{81B03DA4-11A7-4055-986F-B8A817410AE4}" src="https://github.com/user-attachments/assets/2d23ce25-645e-47e8-b35f-70db39e8ff73" />


### 4. Seats Won by Each Party Across Different States (Stacked Bar Chart)

<img width="1259" height="756" alt="{A9B634F0-EABF-4A42-890C-6BCDA0CA7E25}" src="https://github.com/user-attachments/assets/fe589dce-7405-435e-aae5-e5374d76369b" />


### 5. YSRCP vs TDP Votes by Parliamentary Constituency in Andhra Pradesh (Comparative Bar Chart)

<img width="1294" height="618" alt="{FF7B3110-BF6A-40EE-A921-13D8817242A8}" src="https://github.com/user-attachments/assets/9f3478b4-3cc7-46b6-907d-cd639a4abe48" />


### 6. Average Percentage of NOTA Votes Compared to Total Valid Votes in Each State (Bar Chart)

<img width="815" height="801" alt="{3D7959FD-C307-4B33-AF86-94055B0153A7}" src="https://github.com/user-attachments/assets/a2f5e7fa-eccb-43d0-b7b3-74c28938703f" />


### 7. Correlation Heatmap

<img width="1045" height="795" alt="{807DF5D8-1E92-49CA-BDC9-06D6F971C0AA}" src="https://github.com/user-attachments/assets/312b66bd-fb9b-4bbd-bbb9-5feb5003af34" />

### 8. Distribution of Vote Margins Across States

<img width="1100" height="736" alt="{77367241-10C6-4361-A123-C9B043389C5D}" src="https://github.com/user-attachments/assets/d94c2cc9-fffb-4251-9566-574d3a55ea1d" />


### 9. Number of Candidates Contesting from Each State

<img width="1108" height="459" alt="{347456C1-AC27-4D25-8DB1-873BAAFAA420}" src="https://github.com/user-attachments/assets/3c80caca-bf0d-46f5-ab94-9e0f3336bc1d" />


---

## 🙏 Acknowledgments

This project was undertaken as part of my academic curriculum at **Lovely Professional University**. I sincerely thank the university for providing the platform and resources to undertake this project.
Special thanks to my mentor **Dr. Karan Bajaj Sir** for his continuous guidance, encouragement, and valuable insights.

---
