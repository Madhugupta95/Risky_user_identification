# Risky User Identification Microservice

**Can raw SMS and bank messages tell us who is likely to miss a loan payment?**
This project turns messy text into clear risk signals that help lenders spot high-risk users early.

> Note: The original project was built at work on about 500,000 records. This repository uses synthetic data only, with no company or customer data.

## What It Does

- Reads raw SMS and banking transaction data and cleans it
- Extracts risk signals, such as bounce charges, using Python and regex
- Flags high-risk users for lending decisions
- Proves the signals work with hypothesis testing
- Measures accuracy, precision and recall
- Tracks signal patterns and user risk in Redash dashboards
- Cross-checks results by hand in Excel

## How It Works

1. **Ingest:** load raw SMS and banking data
2. **Clean:** remove noise and standardise the format
3. **Extract:** pull out risk signals with regex
4. **Score:** apply risk logic to flag high-risk users
5. **Validate:** test the logic with statistics
6. **Monitor:** track results in dashboards

## Tech Stack

Python | SQL | Regex | Redash | Excel

## Key Learnings

- Turning unstructured text into reliable signals
- Writing regex patterns that work across different message formats
- Using hypothesis testing to prove a signal is useful
- Choosing between precision and recall for lending risk
- Documenting rules so a team can reuse and trust them

- How I built regex patterns for different message formats
- Why I checked precision and recall, not only accuracy
- How hypothesis testing showed risky and non-risky users really differ
- How I validated results by hand before trusting them
</details>

## About Me

**Madhu Gupta** | Data Analyst | FinTech
LinkedIn: https://www.linkedin.com/in/madhu-gupta-0953a0209
Email: 98madhugupta@gmail.com

