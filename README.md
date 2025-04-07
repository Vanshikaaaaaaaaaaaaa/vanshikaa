# vanshikaa
Cleaning Steps Performed:
Removed duplicate rows to ensure unique appointment records.

Handled date formatting:

Converted scheduledday and appointmentday columns to proper datetime format.

Removed appointmentday since it had a constant value across all records.

Standardized column names:

Renamed all headers to be lowercase with underscores (e.g., PatientId → patientid) for consistency.

Sorted and reindexed Patient IDs:

Sorted data alphabetically by gender and neighbourhood.

Reassigned patientid to a sequential numeric ID starting from 1.

Checked for missing values
