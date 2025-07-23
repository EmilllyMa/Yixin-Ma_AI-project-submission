
# Employee Sentiment Analysis – Summary

## ✅ Project Objectives

Analyze employee message data to:
- Extract sentiment using a suitable model
- Identify patterns in employee engagement
- Detect potential flight risk behavior
- Apply predictive modeling on sentiment trends

---

## 🛠️ Tasks Completed

1. **Sentiment Labeling** – Used VADER to assign Positive, Negative, or Neutral labels to each message.
2. **Exploratory Data Analysis** – Visualized message frequency and sentiment distribution.
3. **Monthly Score Calculation** – Calculated per-employee sentiment scores each month.
4. **Employee Ranking** – Ranked the most positive and negative employees monthly.
5. **Flight Risk Detection** – Flagged employees with ≥ 4 negative messages in any rolling 30-day window.
6. **Predictive Modeling** – Built a regression model using message activity features.

---

## 🧠 Model Selection and Threshold Justification

We used the VADER sentiment analysis tool because it is optimized for short and informal texts like employee messages. To classify sentiment:

- `compound` score > 0.05 → **Positive**
- `compound` score < -0.05 → **Negative**
- Between -0.05 and 0.05 → **Neutral**

These thresholds follow the recommended VADER defaults and were validated on a hand-labeled sample of internal communication to ensure alignment with domain tone and vocabulary.

---

## 🔁 Next Steps

- Enhance model features using department metadata or topic modeling
- Apply classification models instead of regression
- Build a dashboard for HR to monitor sentiment and engagement

---

## 👤 Author
- **Yixin Ma**
- Submit to: `jbirch@glynac.ai`

