# 📊 Financial Data Chatbot — BCG X NLP AI Project

This project was developed as part of a BCG X certification focused on building AI-driven prototypes using natural language processing (NLP) techniques. The goal was to design a **rule-based financial chatbot prototype** that interacts with structured financial data, simulating how AI can assist in business analysis.

While not a full-fledged AI model, this chatbot demonstrates **foundational principles of NLP systems**, including query recognition, structured data processing, and clear communication of financial insights.

## Check out my Certification [here](https://forage-uploads-prod.s3.amazonaws.com/completion-certificates/SKZxezskWgmFjRvj9/gabev3vXhuACr48eb_SKZxezskWgmFjRvj9_mGKMFkWbvxWi5DcWt_1749957582121_completion_certificate.pdf)!

## 💬 Chatbot Summary

This chatbot reads financial data from an Excel file, computes revenue and income growth, and responds to predefined queries using rule-based logic.

### 📌 Supported Queries
- What is the total revenue?
- How has net income changed over the last year?
- Show average growth rates
- List companies

### ⚠️ Limitations
- Only responds to a fixed set of questions (not a full AI or NLP model).
- Requires the Excel file to be in the correct format with expected columns (`Company`, `Year`, `Revenue`, `Net Income`, etc.).


## 🛠 How It Works

1. Loads financial data from an `.xlsx` Excel file using `pandas`.
2. Computes:
   - 📈 **Revenue Growth (%)**
   - 💰 **Net Income Growth (%)**
3. Matches user input to predefined commands using simple `if-elif` logic.
4. Returns easy-to-understand insights based on financial data.

Example logic:
```python
if user_query.lower() == "what is the total revenue?":
    # compute and return total revenue
```

## ✅ Requirements
- Python 3.0x
- pandas
- openpyxl (for reading Excel)

Install dependencies with:

```bash
pip install pandas openpyxl
```
