# LAB | Evaluation Dashboard — Louise Plessis

**Tool used:** Tableau Public

**Dashboard overview:** An interactive "Model Evaluation Score Dashboard" showing evaluation score distributions across 5 categories (reasoning, knowledge, code, instruction_following, tool_calling) and 4 model versions, with filters for category, model version, and date so stakeholders can drill down without touching the underlying data.

**Data source:** Sample data generated with the provided Python script (see `data_source.md` for details).

## File map

| File | Purpose |
|---|---|
| `generate_evaluation_data.py` | Script that generates the sample evaluation dataset |
| `evaluation_data_clean.csv` | Cleaned data imported into Tableau Public |
| `evaluation_score_dashboard.twbx` | Final Tableau Public dashboard workbook (packaged) |
| `dashboard_screenshot.png` | Screenshot of the final dashboard |
| `data_source.md` | Brief note on where the data came from |
| `reflection.md` | Reflection on applying communication layer principles |
| `README.md` | This file |

## Notes

- Scores are on a 0-100 scale.
- No statistical jargon (p-values, confidence intervals, etc.) appears on the dashboard — only conclusions ("what" and "so what"), per the communication layer principles from the lesson.
