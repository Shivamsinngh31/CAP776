# CAP776 - My Data, My Story

## Project Overview

This project is a Personal Activity Intelligence tool that analyzes daily activity logs from a student to generate a comprehensive activity report. The project reads data from an Excel file tracking various daily activities like sleep, fitness, study, coding, and classes, and calculates various performance indices.

## Features

- **Data Parsing & Validation**: Automatically reads daily log entries from `Shivam_Singh_12603250.xlsx` and validates entries for completeness, accurate total time tracking, and data continuity.
- **Activity Indices**:
  - **Tech Productivity Index (TPI)**: Measures average coding time.
  - **Academic Activity Index (AAI)**: Combines study and class time.
  - **Physical Activity Index (PhAI)**: Tracks fitness activities.
  - **Sleep and Recovery Index (SRI)**: Tracks average sleep time.
  - **Activity Balance Index (ABI)**: Tracks unaccounted/free time.
  - **Time Utilization Index (TUI)**: Tracks total tracked time.
  - **Data Continuity Index (DCI)**: Measures consistency of logging data.
  - **Personal Activity Index (PAI)**: A weighted metric combining all the above indices to give an overall score of productivity and wellbeing.
- **Correlation Analysis**: Computes statistical correlations between different metrics, such as:
  - Sleep & Energy
  - Study & Satisfaction
  - Coding & Energy
- **Backdated Commits**: Includes a script (`backdate_commits.py`) to accurately represent the history of the data collection process by backdating Git commits to the dates the daily logs were recorded.

## Usage

1. Ensure you have Python installed.
2. Install required dependencies:
   ```bash
   pip install openpyxl
   ```
3. Run the main analysis script:
   ```bash
   python main.py
   ```
