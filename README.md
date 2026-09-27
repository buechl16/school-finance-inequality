# School Finance Inequality in America

This project examines how school funding varies across states and school districts in the United States, and what those differences may imply for educational opportunity.

U.S. public schools are funded through a combination of local, state, and federal sources. In many states, local property taxes play a major role. Because of this, school funding can often reflect district wealth rather than individual student need.

As a result, students in lower-funded districts may have access to fewer educational resources than students in higher-funded districts.

The goal of this project was to look more closely at those differences and visualize how school funding is distributed across the country.

## Data

This analysis uses the **U.S. Census Bureau School District Finance Survey (F-33)** for the **2021–2022 school year**.

The dataset provides detailed financial information for public school districts across the United States.

Some of the main variables used in this project include:

- total district revenue
- local revenue
- state revenue
- federal revenue
- Title I revenue
- student enrollment
- per-pupil funding measures

## What I Looked At

The project focuses on four main areas:

### 1. Revenue Source Mix by State

States fund public schools through very different combinations of local, state, and federal revenue.

In some states, local funding makes up more than half of total school revenue.

This matters because heavy reliance on local property taxes can tie school funding more closely to district wealth.

### 2. Per-Pupil Revenue Gap

This visualization compares lower-funded and higher-funded school districts within each state.

Every state in the analysis showed a gap between its lower- and higher-funded districts.

In several states, the difference was tens of thousands of dollars per student.

This shows that students can receive very different levels of funding depending on the district they attend.

### 3. Highest- vs. Lowest-Funded Districts in the Midwest

Funding gaps are not just something that appears at the national level.

Even within the same region, states can show large differences between their lowest- and highest-funded districts.

This visualization focuses more closely on Midwestern states and compares districts at opposite ends of the funding range.

Michigan, for example, showed a particularly large gap between its higher- and lower-funded districts.

### 4. Cost of Equity

The final visualization looks at how much additional state funding would be needed to bring districts below their state's median funding level up to that median.

For districts below the median, I calculated the difference between their current per-pupil funding and the state median, then estimated how much additional funding would be needed based on district enrollment.

This made it possible to estimate the percentage increase in state education funding that would be required under this scenario.

## Key Findings

Some of the major findings from the project include:

- School funding structures vary significantly across states.
- Local property taxes make up a large portion of school funding in many states.
- Every state analyzed showed a noticeable gap between its lower- and higher-funded districts.
- In some states, the difference in per-pupil funding was tens of thousands of dollars.
- Even districts located within the same state can receive dramatically different levels of funding.
- In several states, bringing districts below the state median up to that median would require an estimated increase of less than 10% in state education funding.

Overall, the project suggests that school funding inequality is closely connected to the way states divide responsibility between local and state funding.

## Research Poster

The final results were presented through a research poster containing all four visualizations and the main findings from the project.

**[View the full research poster](school_finance_inequality_poster.pdf)**

## Project Files

```text
school-finance-inequality/
├── README.md
├── school_finance_analysis.ipynb
├── school_finance_inequality_poster.pdf
└── .gitignore
```

### `school_finance_analysis.ipynb`

Contains the data cleaning, calculations, analysis, and visualization code used for the project.

### `school_finance_inequality_poster.pdf`

Contains the final research poster and visual presentation of the project's findings.

## Tools Used

- Python
- pandas
- NumPy
- Matplotlib
- Jupyter Notebook

## Why I Made This Project

I wanted to use data visualization to take a complicated issue like public school finance and make the differences between states and districts easier to understand.

Rather than only looking at statewide averages, I wanted to show how funding can differ between individual districts and how the structure of school funding may contribute to those gaps.

The project also gave me experience working with a large public dataset, cleaning and transforming financial data, creating multiple types of visualizations, and presenting quantitative findings in a way that is easier to understand.
