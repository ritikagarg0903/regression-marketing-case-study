# Case Study: Digital Marketing Performance  
**Simple Linear Regression Assignment**

## Background

You are a **marketing analyst at ClickConvert**, a digital marketing agency.  
Your client is an **e-commerce retailer** running Facebook advertising campaigns and wants to understand the relationship between:

- **Weekly advertising spend**
- **Website conversions**

The client’s **Chief Financial Officer (CFO)** believes that the marketing budget is only justified if the company receives **at least 5 additional conversions for every 1% increase in advertising spend**.

You have been provided with **5 years of historical data (260 weeks)** to analyze and evaluate this claim.

---

## Dataset Information

- **File Name:** `MiniCase2_MarketingPerformance`
- **Sample Size:** 260 weekly observations (5 years)

### Variables

1. **Week**  
   - Unique identifier for each observation

2. **AdSpend**  
   - Weekly advertising spend  
   - Measured in **thousands of dollars**

3. **Conversions**  
   - Number of website conversions during the week

---

## Assignment Tasks

### Task 1 (10 points)
Create a **scatterplot** of **AdSpend vs. Conversions**.

- Describe what you observe.
- Assess whether a **linear relationship** appears to exist between the two variables.

---

### Task 2 (10 points)
Build a **simple linear regression model** with:

- **Dependent Variable:** Conversions  
- **Independent Variable:** AdSpend (in thousands)

Include:
- The regression model specification
- The estimated regression equation with coefficients
- Interpretation of the coefficient estimates

---

### Task 3 (10 points)
Assess the **model fit** using:

- Standard error of the model
- R²
- *t*-test for the slope coefficient

---

### Task 4 (5 points)
Apply **Tukey’s Bulging Rule** and determine an appropriate **variable transformation** for this scenario.

---

### Task 5 (10 points)
Build a **new simple linear regression model** using the transformed variable.

Include:
- The new regression model specification
- The estimated regression equation
- Interpretation of the coefficient estimates

---

### Task 6 (15 points)
Assess the **model fit of the transformed model** using:

- Standard error of the model
- R²
- *t*-test for the slope coefficient

---

### Task 7 (10 points)
Compare the **original model** and the **transformed model**.

- State which model is more suitable
- Justify your choice using statistical evidence

---

### Task 8 (10 points)
Interpret the **95% confidence interval for the slope** in the **transformed model**.

---

### Task 9 (10 points)
Test the claim:

> *A 1% increase in AdSpend results in at least 5 additional conversions.*

Clearly state:
- Hypotheses
- Test conclusion
- Business interpretation

---

### Task 10 (10 points)
If the client plans to spend **$15,000 next week** (`AdSpend = 15`):

- Create a **95% prediction interval** for conversions
- Create a **95% confidence interval** for the **mean conversions** at this spending level

---

### Task 11 (5 points)
Explain the difference between the two intervals created in **Task 10**.

- Which interval is wider?
- Why?
- Provide **specific business scenarios** where each type of interval would be used

---

### Task 12 (5 points)
Based on your analysis:

- Should the CFO approve the marketing budget?
- Support your recommendation using evidence from your regression results

---

## Deliverables

### A) Technical Analysis Report  
**Format:** R Markdown (knitted to HTML or PDF)

**Requirements:**
- Complete R Markdown file
- All tasks clearly labeled
- Code chunks visible and commented
- All statistical output included
- Visualizations where appropriate
- Professional formatting

---

### B) Executive Summary  
**Length:** Maximum 2 pages (excluding appendices)  
**Format:** PDF only

**Audience:** Executives with limited statistical background

**Required Sections:**
- **Business Problem** (few sentences)
- **Key Findings** (1–2 paragraphs, include R² and significance)
- **Recommendation** (1 paragraph)
- **Supporting Evidence** (3–5 bullet points)
- **Limitations** (2–3 sentences)

**Guidelines:**
- Professional business writing style
- May include key visualizations
- **No statistical jargon**
- Use clear, business-focused language

---

*Course: BAX 441: Statistical Exploration and Reasoning*  
*University of California, Davis*