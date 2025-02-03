# Hypothesis Testing - Mobile Internet Case Study

## **Context**
ExperienceMyServices reported that a **typical American** spends an average of **144 minutes (2.4 hours)** per day accessing the **Internet via a mobile device**, with a **standard deviation of 110 minutes**.

To test the validity of this claim, we collected a sample of **30 observations** from friends and family. The dataset **'InternetMobileTime.csv'** contains the recorded daily mobile internet usage times (in minutes) for these 30 individuals.

---

## **Key Question**
**Is there enough statistical evidence to conclude that the population mean time spent per day accessing the Internet via a mobile device is different from 144 minutes?**

We will use **hypothesis testing** with the **p-value approach** at a **0.05 significance level**.

---

## **Methodology**
To address this question, we will perform a **one-sample t-test** as the population standard deviation is unknown and the sample size is small (n = 30). The hypothesis test will be structured as follows:

### **Hypothesis Formulation**
- **Null Hypothesis (H₀)**: The mean daily mobile internet usage time is **144 minutes**.
  
  \[ H₀: \mu = 144 \]

- **Alternative Hypothesis (H₁)**: The mean daily mobile internet usage time is **not equal to** 144 minutes.
  
  \[ H₁: \mu \neq 144 \]

### **Statistical Test**
- **Test Used**: One-sample **t-test**
- **Assumptions**:
  - The sample is **randomly selected and independent**.
  - The population follows a **normal distribution** (given assumption).
  
- **Test Statistic**:
  
  \[ t = \frac{\bar{x} - \mu}{s/\sqrt{n}} \]
  
  where:
  - \( \bar{x} \) = sample mean
  - \( \mu \) = hypothesized population mean (144 minutes)
  - \( s \) = sample standard deviation
  - \( n \) = sample size (30)

### **Decision Criteria (P-Value Approach)**
- **Significance Level (α) = 0.05**
- Compute the **p-value** for the two-tailed test.
- If **p-value < 0.05**, we **reject** the null hypothesis (suggesting a significant difference in internet usage time).
- If **p-value ≥ 0.05**, we **fail to reject** the null hypothesis (not enough evidence to conclude a difference).

---

## **Dataset Information**
The dataset **'InternetMobileTime.csv'** contains the following column:
- `time_spent` - Time (in minutes) spent per day accessing the Internet via a mobile device.

---

## **Technologies Used**
- **Python** (NumPy, SciPy, Pandas, Matplotlib, Seaborn)
- **Statistical Analysis** (Hypothesis Testing, p-value calculations)
- **Data Visualization** (Histogram, normality check, p-value interpretation)

---

## **Expected Outcomes**
- Determine if there is **statistical evidence** that the population mean differs from 144 minutes.
- Use the **p-value approach** to draw conclusions.
- Provide **data-driven insights** on mobile internet usage patterns.

---

## **How to Use This Repository**
1. Clone the repository:
   ```bash
   git clone https://github.com/Sourena-Mohit/Mobile-Internet-Case-Study.git
   ```
2. Navigate to the project directory:
   ```bash
   cd Mobile-Internet-Case-Study
   ```
---

## **Contributing**
Contributions are welcome! If you have improvements or insights, feel free to submit a pull request.

## **License**
This project is licensed under the **MIT License**.

---


