# Healthcare Analytics Dashboard (Excel)

A five-page interactive Excel dashboard analyzing **54,966 simulated patient records** (2019-2024) across demographics, clinical outcomes, financials, operations, and predictive trends. Built during the Nexus Fellowship data analytics internship track.

> **Note:** All data is simulated. No real patient, hospital, or provider information was used. Patterns reflect how the dataset was generated and should not be read as real-world clinical or financial findings.

## Purpose
To demonstrate end-to-end healthcare analytics across five linked views - who the patients are, what's happening clinically, what it costs, how operations are running, and what the trend data suggests going forward.

## Dashboard pages

1. **Demographic Dashboard** - patient age, gender, and blood type distribution across 6 medical conditions.
2. **Clinical Dashboard** - condition prevalence, test result outcomes, recovery rates, and medication patterns.
3. **Financial Dashboard** - total and average billing by condition, admission type, insurance provider, and top hospitals/doctors.
4. **Operations Dashboard** - admission trends, length of stay, and admission type breakdowns (2019–2024).
5. **Predictive & Trend Analysis** - a 6-month admission forecast (Jun–Nov 2024) with resource planning recommendations.

## Key metrics
| Metric | Value |
|---|---|
| Total patients | 54,966 |
| Average age | 52 (range 13-89) |
| Gender split | 50.02% male / 49.98% female |
| Total billing | $1,404,174,863.40 |
| Average length of stay | 15.5 days |
| Most common condition | Arthritis |
| Most prescribed medication | Lipitor |

## What the dashboard shows

**Demographics**
- Patient ages span 13–89, fairly evenly distributed from the 20s through the 70s, with a drop-off in the 80–90 band.
- Blood type and gender distribution are near-identical across all six medical conditions — condition does not appear linked to either in this dataset.

**Clinical**
- Test results are split almost exactly three ways: Normal (33.35%), Abnormal (33.54%), Inconclusive (33.11%).
- All six conditions (Arthritis, Diabetes, Hypertension, Obesity, Cancer, Asthma) have near-identical patient counts (~9,000-9,220) and near-identical recovery rate splits — there is no standout high- or low-prevalence condition in this dataset.
- Medication distribution (Aspirin, Ibuprofen, Lipitor, Paracetamol, Penicillin) is similarly even across all six conditions.

**Financial**
- Total billing is highest for Diabetes ($236.5M); average billing per patient is highest for Obesity ($25,807).
- Elective admissions generate the highest total billing ($473.18M), narrowly ahead of Urgent and Emergency.
- Insurance provider volume is tightly clustered (Cigna highest at 11,139 patients, Aetna lowest at 10,822) — no provider dominates.

**Operations**
- Admission volume holds steady at roughly 800–1,000 patients/day from 2019 through early 2024; the visible drop at the end of the series reflects a partial final month of data (through 7 May 2024), not a real decline.
- Average length of stay is consistent across conditions (15.4–15.7 days) and admission types (15.4–15.6 days) - no condition or admission type drives meaningfully longer stays.
- August is the peak admission month (4,785), narrowly ahead of July (4,765).

**Predictive & Trend Analysis**
- The 6-month forecast (Jun-Nov 2024) projects a stable monthly average of ~904 admissions, with a marginal projected decline (905 → 902) - read as statistical stability rather than a meaningful trend.
- Patients aged 50–59 show the highest admission volume (8,263); patients aged 70–79 have the longest average stay (15.7 days).
- Diabetes and Hypertension are flagged as the conditions most likely to increase, based on current volume (~9,200 patients each) and typical age/lifestyle association.
- Seven resource-planning recommendations are included on this page, covering staffing, bed capacity, and stock levels for peak months.

## Data
- **Source:** a simulated dataset of 54,966 patient records and associated billing, clinical, and operational fields, used for this fellowship/portfolio project.
- **Doctor and hospital names** (e.g. "LLC Smith," "Michael Smith," "Johnson PLC") are clearly generated placeholders, not real entities.
- **Filters/breakdowns available:** medical condition, age group, admission type, insurance provider, and hospital.

## Tools
Microsoft Excel, including:
- **Pivot tables** - underlying all summary metrics and breakdowns
- **Pivot charts** - donut, stacked bar, clustered bar, and line/trend visuals across all five pages
- **Forecasting** - used for the 6-month admission projection on the Predictive & Trend Analysis page

## Files
- `healthcare_analytics_dashboard.xlsx`: the Excel workbook (all five dashboard sheets)
- `images/`: dashboard screenshots

## Limitations
- The data is simulated. The near-identical volumes across all six medical conditions, and the narrow spread across insurance providers, hospitals, and length-of-stay figures, suggest the dataset was generated with balanced/randomized distributions rather than reflecting real epidemiological or operational patterns.
- Doctor and hospital names are auto-generated and not representative of real providers or institutions.
- The Operations dashboard's final data point reflects a partial month (through 7 May 2024) and should not be read as a real decline in admissions.
- The forecast on the Predictive & Trend Analysis page is a simple projection based on historical averages, not a validated statistical or machine learning model.

## Author
Rita Orobosa Aiwuyo, PharmD, B.Pharm, R.Ph. | [LinkedIn](https://www.linkedin.com/in/rita-aiwuyo) | [Portfolio](https://rita-portfolio.onrender.com/)
