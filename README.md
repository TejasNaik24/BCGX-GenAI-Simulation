# Financial Data Chatbot

This chatbot reads financial data from an Excel file, computes revenue and income growth, and responds to predefined queries.

## 📌 Supported Queries
- What is the total revenue?
- How has net income changed over the last year?
- Show average growth rates
- List companies

## ⚠️ Limitations
- Only responds to a fixed set of questions (not an AI or natural language model).
- Requires the Excel file to be in the correct format with expected columns.

## 🛠 How It Works
1. Loads financial data from an `.xlsx` Excel file.
2. Calculates:
   - Year-over-year **Revenue Growth (%)**
   - Year-over-year **Net Income Growth (%)**
3. Matches user input with predefined commands and returns the appropriate result.

## ✅ Requirements
- Python 3.x
- pandas
- openpyxl (for reading Excel)

Install dependencies with:

```bash
pip install pandas openpyxl
```