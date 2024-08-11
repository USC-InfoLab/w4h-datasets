# W4H Datasets

W4H sample datasets.

## Fitbit Dataset

Includes subject study period and timeseries fitbit data:

### 1. fitbit_subjects.csv

This file subjects unique ID and the study period during which their data was collected.

**Columns:**

- id: subject ID.
- start_date: The start date of the data collection period for the subject.
- end_date: The end date of the data collection period for the subject.

### 2. fitbit_calories.csv

This file provides details about the calories burned by subjects, including the time of the record and the associated METs (Metabolic Equivalent of Task) value, as provided by the [Fitbit Web API: Get Activity Intraday by Interval](https://dev.fitbit.com/build/reference/web-api/intraday/get-activity-intraday-by-interval/).

**Columns:**

- id: Unique identifier for the subject.
- date: The date of the recorded resource in the format yyyy-MM-dd.
- time: The time of the recorded resource.
- value: Calories burned.
- mets: METs value at the moment when the resource was recorded.

### 3. fitbit_heart_rate.csv

This file records the heart rate of subjects, as provided by the [Fitbit Web API: Get Activity Intraday by Interval](https://dev.fitbit.com/build/reference/web-api/intraday/get-activity-intraday-by-interval/).

**Columns:**

- id: subject ID.
- date: Date of the record.
- time: Time of the record.
- value: Heart rate measured in beats per minute (BPM).

### 4. fitbit_sample_weight.csv

This file contains weight measurements along with Body Mass Index (BMI) and body fat percentage, as provided by the [Fitbit Web API: Get Weight Log](https://dev.fitbit.com/build/reference/web-api/body/get-weight-log/).

**Columns:**

- id: subject ID.
- date: Date of the record.
- timestamp: Time of the record.
- weight: Weight in kilograms.
- bmi: Body Mass Index.
- fat_percent: Body fat percentage.
- source: Source of the data.
