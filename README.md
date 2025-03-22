## **Overview:**
- **Total Records (Participants):** 60
- **Total Features (Variables):** 14
- **No Missing Values:** All columns have **0** missing values.

---

## **Dataset Structure:**
- **Categorical Variables:**  
  - `Participant_ID` (Unique Identifier)  
  - `Gender` (Male/Female)  
- **Numeric Variables:**  
  - Sleep metrics, cognitive performance, emotional regulation, and lifestyle factors.

---

## **Feature Description:**

| **Feature Name**                | **Description**                                   | **Data Type**   |
|----------------------------------|---------------------------------------------------|-----------------|
| `Participant_ID`                 | Unique ID for each participant                   | Categorical     |
| `Sleep_Hours`                    | Total hours of sleep per night                   | Float           |
| `Sleep_Quality_Score`            | Subjective sleep quality score (0-20)            | Integer         |
| `Daytime_Sleepiness`             | Self-reported daytime sleepiness (0-24)          | Integer         |
| `Stroop_Task_Reaction_Time`      | Cognitive task reaction time in seconds          | Float           |
| `N_Back_Accuracy`                | Accuracy in N-Back working memory task (%)       | Float           |
| `Emotion_Regulation_Score`       | Score for emotion regulation (Higher = Better)   | Integer         |
| `PVT_Reaction_Time`              | Psychomotor Vigilance Task reaction time (ms)    | Float           |
| `Age`                            | Age of the participant (years)                   | Integer         |
| `Gender`                         | Gender (Male/Female)                             | Categorical     |
| `BMI`                            | Body Mass Index (kg/m²)                          | Float           |
| `Caffeine_Intake`                | Daily caffeine intake (cups)                     | Integer         |
| `Physical_Activity_Level`        | Self-reported physical activity level (0-10)     | Integer         |
| `Stress_Level`                   | Perceived stress level (0-40)                    | Integer         |

---

## **Summary Statistics:**

| **Metric**                      | **Mean** | **Std Dev** | **Min** | **Max** |
|----------------------------------|--------:|------------:|-------:|-------:|
| **Sleep Hours**                  | 5.81    | 1.83        | 3.12   | 8.82   |
| **Sleep Quality Score**          | 8.32    | 5.64        | 0.00   | 20.00  |
| **Daytime Sleepiness**           | 12.00   | 7.58        | 0.00   | 24.00  |
| **Stroop Task Reaction Time (s)**| 3.24    | 0.83        | 1.60   | 4.49   |
| **N-Back Accuracy (%)**          | 75.01   | 13.67       | 50.90  | 99.73  |
| **Emotion Regulation Score**     | 38.15   | 17.13       | 10.00  | 67.00  |
| **PVT Reaction Time (ms)**       | 332.54  | 87.80       | 201.56 | 494.55 |
| **Age (Years)**                  | 29.52   | 8.17        | 18.00  | 43.00  |
| **BMI (kg/m²)**                  | 27.33   | 4.54        | 18.74  | 34.93  |
| **Caffeine Intake (Cups)**       | 2.38    | 1.69        | 0.00   | 5.00   |
| **Physical Activity Level**      | 4.12    | 3.11        | 0.00   | 10.00  |
| **Stress Level**                 | 17.87   | 11.02       | 0.00   | 40.00  |

---

## **Sample Data (First 5 Records):**

| **Participant_ID** | **Sleep_Hours** | **Sleep_Quality_Score** | **Daytime_Sleepiness** | **Stroop_Task_Reaction_Time** | **N_Back_Accuracy** | **Emotion_Regulation_Score** | **PVT_Reaction_Time** | **Age** | **Gender** | **BMI** | **Caffeine_Intake** | **Physical_Activity_Level** | **Stress_Level** |
|--------------------|----------------|--------------------------|-------------------------|-------------------------------|----------------------|-----------------------------|------------------------|-------|----------|--------|---------------------|----------------------------|------------------|
| P1                 | 5.25           | 15                        | 12                      | 1.60                          | 64.2                 | 12                          | 365.85                 | 35    | Female   | 30.53  | 2                   | 1                           | 33               |
| P2                 | 8.70           | 12                        | 14                      | 2.54                          | 65.27                | 21                          | 288.95                 | 20    | Male     | 27.28  | 3                   | 8                           | 37               |
| P3                 | 7.39           | 17                        | 10                      | 3.40                          | 74.28                | 35                          | 325.93                 | 18    | Male     | 30.00  | 1                   | 2                           | 32               |
| P4                 | 6.59           | 14                        | 3                       | 3.54                          | 72.42                | 25                          | 276.86                 | 18    | Male     | 34.47  | 5                   | 0                           | 23               |
| P5                 | 3.94           | 20                        | 12                      | 3.09                          | 99.72                | 60                          | 383.45                 | 36    | Male     | 29.70  | 3                   | 4                           | 14               |

---

## **Key Insights:**
- **Sleep Patterns:**  
  - Participants report an average of **5.8 hours** of sleep per night, indicating prevalent sleep deprivation (ideal: 7-9 hours).
- **Cognitive Performance:**  
  - Stroop task and PVT reaction times show considerable variability, reflecting potential sleep deprivation effects.
  - N-Back task accuracy is relatively high, with a mean of **75%**.
- **Emotional Health:**  
  - Emotion regulation scores vary significantly, with a standard deviation of **17.13**, suggesting a wide emotional control range.
- **Lifestyle Factors:**  
  - Physical activity levels vary widely (0-10), with an average of **4.12**.
  - Average caffeine intake is moderate (**2.38 cups/day**), with a maximum of **5 cups/day**.

---
