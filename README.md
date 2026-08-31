# LAB | Evaluation Dashboard — Louise Plessis

**Tool used:** Tableau Public

**Dashboard overview:** An interactive "Model Evaluation Score Dashboard" showing evaluation score distributions across 5 categories (reasoning, knowledge, code, instruction_following, tool_calling) and 4 model versions, with quick filters for category, model version, and date so stakeholders can drill down without touching the underlying data.

**Data source:** Sample data generated with the provided Python script (see `data_source.md` for details).

## File map

| File | Purpose |
|---|---|
| `generate_evaluation_data.py` | Script that generates the sample evaluation dataset |
| `evaluation_data_clean.csv` | Cleaned data imported into Tableau Public |
| `evaluation_score_dashboard.twbx` | Final Tableau Public dashboard workbook (packaged): Score Distribution, Score per Category, and Category Comparison sheets plus a filter/context panel |
| `dashboard_screenshot.png` | Screenshot of the final dashboard |
| `data_source.md` | Brief note on where the data came from |
| `reflection.md` | Reflection on applying communication layer principles |
| `README.md` | This file |

## Notes

- Scores are on a 0-100 scale.
- No statistical jargon (p-values, confidence intervals, etc.) appears on the dashboard — only conclusions ("what" and "so what"), per the communication layer principles from the lesson.
- The dashboard includes a title/context panel and three quick filters (category, model version, date) in the right-hand sidebar.
- `dashboard_screenshot.png` predates a workbook cleanup pass (fixed a broken histogram, a mis-scaled color legend, mixed-language field labels, and added the missing quick filters) and should be re-captured from the current `.twbx` before this is presented to stakeholders.
