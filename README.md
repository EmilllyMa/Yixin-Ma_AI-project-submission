
# Employee Sentiment Analysis – Summary

## ✅ Project Deliverables

This project analyzed employee message data to derive sentiment insights and assess engagement risk.

### 📌 Tasks Completed:
1. **Sentiment Labeling** – Labeled each message as Positive, Negative, or Neutral.
2. **Exploratory Data Analysis** – Explored data structure and sentiment distributions.
3. **Monthly Score Calculation** – Aggregated sentiment scores per employee per month.
4. **Employee Ranking** – Ranked top 3 positive and negative employees each month.
5. **Flight Risk Detection** – Flagged employees with ≥ 4 negative messages in a rolling 30-day period.
6. **Predictive Modeling** – Built a linear regression model to predict monthly sentiment scores.

---

## 📊 Key Outputs

- **Top 3 Positive Employees** (Simulated):
  - alice@example.com
  - erin@example.com
  - bob@example.com

- **Top 3 Negative Employees** (Simulated):
  - carol@example.com
  - dave@example.com
  - frank@example.com

- **Flight Risk Employees** (Simulated):
  - alice@example.com

- **Model Metrics** (Simulated):
  - MAE: 3.33
  - RMSE: 4.48
  - R²: -19.11

---

## 📁 File Structure

```
├── test.csv                        # Original dataset (provided)
├── test_with_sentiment.csv        # Dataset with sentiment labels (generated in Task 1)
├── final_report.txt               # Final project report
├── task1_sentiment_labeling.py    # Python script for Task 1
├── sentiment_distribution.png     # EDA sentiment distribution chart
├── monthly_message_count.png      # EDA monthly message count chart
├── README.md                      # This file
```

---

## 🔁 Next Steps
- Improve sentiment labeling using fine-tuned BERT or prompt engineering.
- Integrate topic modeling for deeper analysis.
- Build an HR dashboard for real-time monitoring and alerting.

---

## 👤 Author
- **[Your Name Here]**
- Submit to: `jbirch@glynac.ai`
