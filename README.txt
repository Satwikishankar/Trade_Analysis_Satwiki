
# SIDDHARTH ASSOCIATES - DATA ANALYST ASSIGNMENT
## Submission Package - Trade Data Analysis

---

## 📦 DELIVERABLES

This package contains:

1. **Trade_Analysis_Siddharth_Associates_Complete.xlsx** - Main Excel workbook with complete analysis
2. **Analysis_Summary_Report.txt** - Executive summary and key findings
3. **README.txt** - This file with submission instructions

---

## 📊 EXCEL WORKBOOK STRUCTURE

The main workbook contains 11 professionally formatted sheets:

### 1. Raw Data
- Original unmodified data from sample file
- 2,079 rows × 20 columns
- All original fields preserved

### 2. Cleaned Data
- Parsed GOODS DESCRIPTION fields
- Added computed columns:
  * Year
  * Grand Total_INR
  * Parsed_Model_Name
  * Parsed_Qty
  * Parsed_Unit_Price_USD
  * HSN_Description
  * Main_Category
  * Sub_Category
  * Per_Unit_Cost metrics
  * Duty_Percentage

### 3. Year Summary
- Annual totals from 2017-2025
- Year-over-Year (YoY) growth percentages
- Peak year: 2023 (₹1.19 Billion)

### 4. HSN Summary
- Breakdown by HSN Code
- Percentage contribution analysis
- Top 3 HSN codes identified

### 5. Category Summary
- Main category and sub-category breakdowns
- 18 distinct sub-categories identified
- Top performers by value

### 6. Model Summary
- Year-wise model performance
- Top 30 models by total value
- Quantity and pricing trends

### 7. Per Unit Cost Analysis
- Average costs by model (INR & USD)
- Duty per unit calculations
- Total cost with duty included

### 8. Exceptional Duty Analysis
- Records with above-average duty (65.9% of data)
- Average duty: 32.71%
- Top 100 high-duty transactions

### 9. Supplier Analysis
- IEC-wise year trends
- Annual contribution analysis
- (Note: Dataset has single IEC: 301049751)

### 10. Lookup Tables
- HSN code mappings
- Sub-category keyword references
- For VLOOKUP formulas

### 11. Notes & Methodology
- Complete documentation
- Assumptions and formulas
- Data limitations
- Key insights summary

---

## 🎯 KEY ANALYSIS COMPLETED

✅ **Year-wise Summary**: Annual totals, YoY growth, trend analysis
✅ **HSN Code Analysis**: Top 25 codes (only 3 in dataset), % contribution
✅ **Category Classification**: Main categories and sub-categories
✅ **Model-wise Metrics**: Quantity, pricing, capacity analysis
✅ **Per-Unit Economics**: Cost analysis with and without duty
✅ **Duty Structure**: Average duty %, exceptional cases flagged
✅ **Supplier Trends**: Year-wise IEC analysis
✅ **Data Parsing**: 100% model names, 57.7% quantities, 57.2% prices

---

## 📈 HIGHLIGHTS

- **Total Import Value**: ₹4.19 Billion (2017-2025)
- **Total Duty Paid**: ₹1.43 Billion
- **Average Duty Rate**: 32.71%
- **Peak Year**: 2023 (₹1.19B)
- **Recent Trend**: Declining (-50.8% in 2024, -8.0% in 2025)
- **Top Categories**: Bottles, Lunch Boxes, Scrubbers, Cloth Stands
- **Data Period**: January 2017 - October 2025 (9 years)

---

## 🔧 TECHNICAL DETAILS

**Data Processing:**
- Python pandas for data manipulation
- Regex for GOODS DESCRIPTION parsing
- openpyxl for Excel generation
- Advanced Excel formulas in sheets

**Parsing Methods:**
- Model Names: `^([A-Za-z0-9\-]+)` pattern
- Quantities: `QTY[:\s]*([0-9,]+)\s*(PCS|SETS?|NOS|NUM|KGS?)` pattern
- Unit Prices: `USD[:\s]*([0-9.]+)\s*PER` pattern

**Key Formulas Used:**
- `Grand Total = TOTAL VALUE_INR + DUTY PAID_INR`
- `YoY Growth % = (Current - Previous) / Previous × 100`
- `Duty % = DUTY PAID_INR / TOTAL VALUE_INR × 100`
- `Per Unit Cost With Duty = Unit Cost + (Duty / Quantity)`

---

## 📤 SUBMISSION INSTRUCTIONS

### Step 1: Upload to Google Drive
1. Go to https://drive.google.com
2. Click "+ New" → "File upload"
3. Upload: **Trade_Analysis_Siddharth_Associates_Complete.xlsx**
4. Wait for upload to complete

### Step 2: Set Sharing Permissions
1. Right-click the uploaded file
2. Select "Share" or "Get link"
3. Change access to: **"Anyone with the link can view"**
4. Click "Copy link"

### Step 3: Submit the Link
1. Open the submission form
2. Paste the Google Drive link in ALL THREE fields:
   - GitHub Link field
   - Deployment Link field
   - Screen Recording Link field
3. Submit the form

**IMPORTANT**: The assignment instructions state to add the Drive link in all three fields regardless of the field names.

### Step 4: Verify Access
1. Open an incognito/private browser window
2. Paste your Google Drive link
3. Confirm the file opens without requesting permissions
4. If access denied, return to Step 2

---

## ✅ CHECKLIST BEFORE SUBMISSION

- [ ] Excel file has 11 sheets with proper formatting
- [ ] All formulas are working (test a few calculations)
- [ ] Year Summary shows YoY growth percentages
- [ ] HSN Summary shows % contribution
- [ ] Category breakdowns are complete
- [ ] File uploaded to Google Drive
- [ ] Sharing set to "Anyone with the link can view"
- [ ] Link tested in incognito mode
- [ ] Link pasted in submission form (all 3 fields)
- [ ] Form submitted successfully

---

## 📞 ANALYSIS SUMMARY

**Dataset**: 2,079 shipment records
**Period**: Jan 2017 - Oct 2025 (9 years)
**Total Value**: ₹4.19 Billion + ₹1.43 Billion duty = ₹5.62 Billion
**HSN Codes**: 3 codes (73239990, 73231000, 73239390)
**Products**: Household steel articles (cutlery, containers, scrubbers, etc.)
**Supplier**: Single IEC (301049751)
**Port**: INNSA1

**Key Insights**:
- Consistent growth 2017-2023 (peak ₹1.19B in 2023)
- Sharp decline 2024-2025 (-50.8% and -8.0%)
- Scrubbers have highest duty rates (~44%)
- Bottles and lunch boxes dominate recent imports
- Average duty across all products: 32.71%

---

## 🎓 SKILLS DEMONSTRATED

✅ Data cleaning and transformation
✅ Text parsing with regular expressions
✅ HSN code mapping and categorization
✅ Time-series analysis and YoY calculations
✅ Cost and duty structure analysis
✅ Excel formula mastery (VLOOKUP, IF, TEXT functions)
✅ Data visualization preparation
✅ Professional report formatting
✅ Documentation and methodology notes

---

**Prepared by**: Data Analytics Candidate
**Date**: November 2025
**For**: Siddharth Associates - Data Analyst Position

---

## ❓ QUESTIONS OR ISSUES?

If you encounter any issues:
1. Check that the Excel file opens correctly
2. Verify all sheets are present
3. Ensure formulas calculate properly
4. Confirm Google Drive link is publicly accessible
5. Re-upload if necessary

---

Thank you for reviewing this analysis!
