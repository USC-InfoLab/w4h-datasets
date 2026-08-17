# W4H Datasets (legacy layout)

**Prefer one-repo-per-contribution sample packages** and the in-app **Contributions** catalog (ADR-018).

| Location | Contents |
|----------|----------|
| [w4h-sample-fitbit-csv](https://github.com/USC-InfoLab/w4h-sample-fitbit-csv) | Fitbit CSV samples + `manifest.yaml` |
| [w4h-sample-fitbit-csv-importer](https://github.com/USC-InfoLab/w4h-sample-fitbit-csv-importer) | Notebook + CLI to load that package via the W4H API |
| [w4h-load-json](https://github.com/USC-InfoLab/w4h-load-json) | Notebook to load JSON via the W4H API |

## Files still in this repo

- `fitbit_subjects.csv` / `fitbit_subjects.json` — sample subjects
- `fitbit_weight.csv` / `fitbit_weight_sample.json` — sample weight rows
- `synthetic_subject_data.csv` — synthetic subjects

JSON files are arrays of objects (same columns as the CSV). Use them with **w4h-load-json**. Keep data synthetic — no real PHI.

Do not add new vendor dumps here — create a `w4h-sample-<vendor>-<format>` repo per [ADR-016](https://github.com/USC-InfoLab/w4h-docs/blob/main/dev/ADR-016-paired-sample-importer-repos.md).
