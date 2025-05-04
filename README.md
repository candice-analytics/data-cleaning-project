# Excel Data Cleaning Project

This project demonstrates a structured Excel-based cleaning process on a fictional customer dataset. It’s part of my data analyst training and focuses on making raw data analysis-ready in a clear, auditable way.

---

## File Structure

- `customer_data_raw.xlsx` – Untouched original data  
- `customer_data_cleaned.xlsx` – Cleaned dataset, ready for analysis  
- `customer_data_audit_view.xlsx` – A 3-sheet workbook with:
  - **Sheet 1:** Raw Data  
  - **Sheet 2:** Cleaned Data  
  - **Sheet 3:** Audit View → raw + cleaned side-by-side, colour-coded, with step explanations

---

## Functions Used in Excel

This project used the following Excel functions to clean and restructure the data:

`TRIM`, `PROPER`, `UPPER`, `SUBSTITUTE`, `LEFT`, `MID`, `FIND`, `LEN`, `IF`, `IFERROR`, `AND`, `SEARCH`, `ISNUMBER`, `YEAR`

---

## Cleaning Steps Taken

- ✅ Removed duplicate entries using unique IDs  
- ✅ Fixed date formatting via Text to Columns  
- ✅ Separated “Suite” or “Apt” numbers from street addresses  
- ✅ Extracted and standardised phone number formats (removed `+`, `.`, `-`)  
- ✅ Added a new column for “Signup Decade” (1980s, 1990s, etc.) for better grouping in analysis.  

Each step is documented in the **Audit View workbook**, with side-by-side columns and formulas visible.

---

## Tools Used

- Microsoft Excel  
- Manual documentation and versioning  
- Colour coding and audit structure for clarity

---

## Project Goals

- Practice Excel-based data cleaning  
- Maintain auditability and transparency for every step  
- Build reusable structure for future datasets

---

## Next Steps

- Apply this same structure to healthcare-focused data (e.g., patient demographics)  
- Replicate in Python with `pandas`  
- Use cleaned output for charts and dashboards in Power BI

---

### Created by [Candice](https://github.com/candice-analytics)  
*Curious about the 'why' in healthcare. Using data to improve care, outcomes, and understanding.*

