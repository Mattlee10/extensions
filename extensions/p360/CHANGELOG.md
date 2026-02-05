# P360 Decision Readiness Changelog

## [Initial Release] - {PR_MERGE_DATE}

### Initial Release

- **Check Readiness Command**: Instantly view your decision readiness score (0-100)
- **Oura Integration**: Secure OAuth connection to your Oura Ring
- **Smart Algorithm**: Combines Sleep Score, Readiness Score, and HRV Balance
- **Clear Recommendations**: Get actionable advice based on your biometric state
- **Privacy-First**: No data stored on external servers

### How It Works

Your decision readiness is calculated from:

- Oura Readiness Score (primary)
- Sleep Score (fallback)
- HRV Balance (modifier)

### Score Guide

| Score    | Meaning                                   |
| -------- | ----------------------------------------- |
| 🟢 70+   | Excellent - Great for important decisions |
| 🔵 50-69 | Good - Proceed with everyday decisions    |
| 🟡 30-49 | Caution - Consider waiting                |
| 🔴 <30   | Poor - Focus on recovery                  |
