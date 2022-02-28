# CHOSEN
Description: *Using Python to automate the COVID Home Safely Now (CHOSEN) Risk Score for COVID-19 developed by David Levine, MD, and colleagues at Brigham and Women's Hospital and Harvard Medical School, Boston, MA, USA.*

## About the Tool
CHOSEN is a clinical risk scoring system that was [developed](https://pubmed.ncbi.nlm.nih.gov/33274414/) to predict whether a patient with COVID in a monitored setting will need oxygen, need the ICU, or die in the next 14 days. 

While *not yet externally validated* for its original purposes, [one study](https://pubmed.ncbi.nlm.nih.gov/34799814/) suggests that CHOSEN may predict suitability for discharge in COVID-19 patients citing that CHOSEN scores: 
*   were significantly associated with mortality
*   allowed reliable identification of patients at low risk, making them suitable for outpatient management.

Data inputs should be the most recent available data.

**Acknowledgements**

CHOSEN was developed by David Levine, MD, and colleagues at Brigham and Women's Hospital and Harvard Medical School, Boston, MA, USA.

This code was developed by [Eden Shaveet](mailto:eden.shaveet@tufts.edu) as a deliverable for HIA 225: Python for Health Informatics & Analytics at Tufts University School of Medicine in Spring 2022.

An existing [CHOSEN calculator](https://www.mdcalc.com/covid-home-safely-now-chosen-risk-score-covid-19#evidence) developed by David Levine, MD, was used for cross-checking this code.

## CHOSEN Tool Instructions
#### *When prompted by the tool, provide the following information as free-text:*

**Is the patient's albumin lab value available?** 
*   Enter "yes" or "no"

**Patient's Age (in years)** 
*   Enter a whole number over 18

**Patient's SpO2 (as percent)** 
*   Enter a whole number *without percent symbol (%)*

**Patient's albumin level (g/dL)** (only if albumin lab value is available)
*   Enter exact measurement, including decimals (i.e. 2.8)

**Patient's respiratory rate (breaths per minute)** (only if albumin lab value is *NOT* available)
*   Enter a whole number
