# Data

This repository uses **simulated, anonymised data**. It does not contain personal, confidential, unpublished or institution-owned research data.

## Dataset

- File: `survey_responses.csv`
- Records: 240 priority responses
- Stakeholder groups: Residents, Local businesses, Local authority
- Recovery categories: Housing, Infrastructure, Safety, Community facilities, Environmental resilience
- Random seed: 42

## Data dictionary

| Column | Meaning | Allowed values |
|---|---|---|
| `response_id` | Anonymous simulated respondent ID | `R001`, `R002`, ... |
| `stakeholder_group` | Type of stakeholder | Residents, Local businesses, Local authority |
| `priority_category` | Built-environment recovery priority | Housing, Infrastructure, Safety, Community facilities, Environmental resilience |
| `priority_score` | Relative priority score | 1.00 to 5.00 |
| `comments` | Optional anonymised qualitative response | Text or blank |

## Important limitation

The data are simulated for demonstration and portfolio purposes. The findings are illustrative and must not be used to make claims about any real community, organisation or recovery programme.
