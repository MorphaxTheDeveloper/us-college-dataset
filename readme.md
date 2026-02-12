# US College Dataset

A structured dataset of American universities including detailed SAT, ACT, and admission statistics.

## Fields Included

- Total applicants
- SAT percentiles (25th / 75th)
- SAT section breakdown (Reading, Math)
- SAT submission rate
- ACT percentiles (Composite, English, Math, Writing)
- ACT submission rate
- Admission rate
- Early decision / early action indicators
- Application deadlines

## Example Record

```json
"Yale University": {
    "id": "yale-university",
    "name": "Yale University",
    "total_applicants": 47240,
    "sat_25th_percentile": 1480,
    "sat_75th_percentile": 1580,
    "sat_reading_25th_percentile": 730,
    "sat_reading_75th_percentile": 780,
    "sat_math_25th_percentile": 750,
    "sat_math_75th_percentile": 800,
    "sat_submission_rate": 54,
    "act_25th_percentile": 33,
    "act_75th_percentile": 35,
    "act_english_25th_percentile": 35,
    "act_english_75th_percentile": 36,
    "act_math_25th_percentile": 31,
    "act_math_75th_percentile": 35,
    "act_writing_25th_percentile": null,
    "act_writing_75th_percentile": null,
    "act_submission_rate": 35,
    "admission_rate": 5,
    "sat_act_offered": false,
    "early_decision_offere": false,
    "early_action_required": true,
    "application_deadlines": {
        "REA": "2024-11-01",
        "RD/Rolling": "2025-01-02"
    }
}
```
