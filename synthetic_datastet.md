# W4H Datasets

## Synthetic Dataset

Includes synthetic data about subjects involved in the study and their corresponding time series activity data collected from wearable devices.

### 1. synthetic_subject_data.csv

This file provides demographic information about the subjects involved in the study and identifiers of the wearable devices they use.

**Columns:**

- id: Unique identifier for the subject.
- device_id: Unique identifier for wearable device.
- state: State where subject resides
- age: Subject's age
- height: Subject's height
- weight: Subject's weight

### 2. synthetic_timeseries_data.csv

This file provides timeseries data about the activity of subjects including the time of the record and the associated METs (Metabolic Equivalent of Task) value.

**Columns:**

- id: Unique identifier for the subject.
- timestamp: Time of the activity 
- heart_rate: Heart rate of the subject
- calories: Calories burned by the subject
- mets: METs value at the moment when the resource was recorded.
- distances: Distance covered by the subject while being active
- steps: Steps taken by the subject
- sleep: 
- weight: Weight of the subject
- location: Location where the actvity was recorded

