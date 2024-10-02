# 2024 21st May Day Mathematical Modeling Competition

## Problem C: Prediction of Dynamic Pressure Hazard in Deep Coal Mining

### Overview
Coal is a primary energy source and essential industrial material in China. However, as mining depth increases, underground stress rises, significantly elevating the risk of dynamic disasters, particularly dynamic pressure incidents, which pose severe threats to safety and efficiency in coal mining operations. Despite improvements in safety measures, dynamic pressure accidents still occur, highlighting the urgent need for effective monitoring and warning systems.

### Background
In deep mining operations, Acoustic Emission (AE) and Electromagnetic Radiation (EMR) signals are monitored. These sensors collect data every 30 seconds, and analyzing these trends can indicate potential hazards of dynamic pressure. The data is categorized into five classes:
- **(A)** Normal Working Data
- **(B)** Precursory Feature Data
- **(C)** Interference Signal Data
- **(D)** Sensor Disconnection Data
- **(E)** Downtime Data

Attached documents provide data collected from January 9, 2019, to January 7, 2020, with labels for each category.

### Objectives
The goal is to establish a mathematical model to address the following problems:

#### Problem 1
Analyze interference signals present in the AE and EMR data:
1.1 Establish a model to identify characteristics (minimum of three) of interference signals in both EMR and AE data.
1.2 Using identified characteristics, model the time intervals of interference signals between May 1, 2022, and May 30, 2022, for EMR, and from April 1, 2022, to May 30, 2022, and October 10, 2022, to November 10, 2022, for AE.

| **Table 1: EMR Interference Signal Time Intervals** |
|:---|:---|:---|
| **No.** | **Start Time** | **End Time** |
| 1 | | |
| 2 | | |
| 3 | | |
| 4 | | |
| 5 | | |

| **Table 2: AE Interference Signal Time Intervals** |
|:---|:---|:---|
| **No.** | **Start Time** | **End Time** |
| 1 | | |
| 2 | | |
| 3 | | |
| 4 | | |
| 5 | | |

#### Problem 2
Analyze precursory feature signals before dynamic pressure hazards:
2.1 Establish a model to analyze trends in the precursory feature signals (minimum of three) for both EMR and AE.
2.2 Identify the time intervals of precursory features from April 8, 2020, to June 8, 2020, and November 20, 2021, to December 20, 2021, for EMR, and from November 1, 2021, to January 15, 2022, for AE.

| **Table 3: EMR Precursory Feature Time Intervals** |
|:---|:---|:---|
| **No.** | **Start Time** | **End Time** |
| 1 | | |
| 2 | | |
| 3 | | |
| 4 | | |
| 5 | | |

| **Table 4: AE Precursory Feature Time Intervals** |
|:---|:---|:---|
| **No.** | **Start Time** | **End Time** |
| 1 | | |
| 2 | | |
| 3 | | |
| 4 | | |
| 5 | | |

#### Problem 3
To promptly identify precursory signals, issue warnings at the first instance of detection:
Establish a model to compute the probability of precursory features occurring at each collection time from the non-continuous data segments provided in Attachment 3.

| **Table 5: Probability of Precursory Features Occurring at Collection Times** |
|:---|:---|:---|
| **EMR Timestamp** | **Probability of Precursory Feature** | **AE Timestamp** | **Probability of Precursory Feature** |
| 2023-01-24 23:58:36 | | 2023-01-24 23:58:36 | |
| 2023-02-11 23:59:20 | | 2023-02-11 23:59:20 | |
| 2023-02-26 23:59:27 | | 2023-02-26 23:59:27 | |
| 2023-03-10 23:58:14 | | 2023-03-10 23:58:14 | |
| 2023-03-30 23:58:13 | | 2023-03-30 23:58:13 | |

### Conclusion
This project aims to develop effective predictive models for dynamic pressure hazards in deep coal mining, thereby enhancing safety protocols and reducing risks associated with mining operations.

### Attachments
- **Attachment 1**: Data of EMR and AE from January 9, 2019, to January 7, 2020.
- **Attachment 2**: Additional data required for analysis.
- **Attachment 3**: Non-continuous time segment data for EMR and AE signals.
