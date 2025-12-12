# A188-covid19-group
Team Research and Development

# COVID-19 Weekly Deaths: Comparing High-Income and Low-Income Countries

A statistical study comparing reported COVID-19 deaths between high-income and low-income countries.

**University of Hertfordshire | Group A188 | December 2025**

---

## What We're Studying

We wanted to know: **Do rich countries report more COVID deaths than poor countries?** And if so, why?

During the pandemic, wealthy nations reported way more deaths. But does that mean they actually had more deaths, or were they just better at counting them?

## Our Answer

**Rich countries reported 57 times more deaths per week** than poor countries (17,623 vs 305 deaths).

But this doesn't mean they had worse COVID. It probably means:
- They tested more people
- They have better death registration systems
- They could detect and record deaths more accurately

Poor countries likely had many deaths that were never counted.

---

## The Team

**Group A188**

- **Purna Satish Dasari** (23004891)
- **Harish Attaluri** (24083900)
- **Sowmya Kondam** (23040940)
- **Pallapolu Bhanu Prakash Reddy** (23035556)
- **Chandra Sekhar Chintapalli** (23032622)

## Quick Results

### The Numbers

| | Rich Countries | Poor Countries |
|---|---|---|
| Average deaths per week | 17,623 | 305 |
| Highest week | 60,026 deaths | 2,263 deaths |
| Number of weeks analyzed | 1,138 | 1,106 |

### Statistical Tests

- **t-test result:** p < 0.0001 (highly significant)
- **Effect size:** Huge difference between groups
- **Conclusion:** The difference is real, not by chance

---

## How We Did It

1. **Got the data** from Our World in Data
2. **Filtered** to only high-income and low-income countries (World Bank classification)
3. **Cleaned** the data (removed missing values)
4. **Analyzed** using R programming (t-tests, charts, statistics)
5. **Interpreted** what the numbers actually mean

### Tools Used

- **R programming** (ggplot2, dplyr, effsize)
- **Statistical tests** (Welch's t-test, Wilcoxon test)
- **Data visualization** (histograms, boxplots, bar charts)

---

## What This Means

The huge difference in reported deaths tells us more about **healthcare systems** than about the actual pandemic impact.

**Why rich countries reported more:**
- Better testing (found more cases)
- Complete death records (counted every death)
- Older populations (more vulnerable people)
- Transparent reporting systems

**Why poor countries reported less:**
- Limited testing capacity
- Incomplete death registration
- Many deaths never recorded
- Younger populations

---

## What Could Be Better

We compared total deaths, not deaths per population size. A better approach would adjust for:
- Population differences
- Age distribution
- Testing rates
- Different pandemic waves hitting at different times

## Running the Code

1. Make sure you have R installed
2. Install packages:
install.packages(c("ggplot2", "dplyr", "effsize", "scales"))
3. Load the data:
covid_data <- read.csv("full_data.csv")

Run the analysis script

