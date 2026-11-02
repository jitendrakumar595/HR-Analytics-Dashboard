# HR Analytics Dashboard | Power BI

An HR analytics dashboard built in **Microsoft Power BI** to explore employee attrition patterns across demographics, education, job roles, salary bands, experience, and departments.

> **Project preview:** The dashboard screenshot is included as `HR_Analytics_Dashboard_HD.png`.

## Contents
- [Dashboard Preview](#dashboard-preview)
- [Project Overview](#project-overview)
- [Key Metrics](#key-metrics)
- [Dashboard Analysis](#dashboard-analysis)
- [Key Observations](#key-observations)
- [Tools & Skills](#tools--skills)
- [How to Use](#how-to-use)
- [Notes](#notes)

## Dashboard Preview

![HR Analytics Dashboard](HR_Analytics_Dashboard_HD.png)

## Project Overview

The purpose of this dashboard is to turn employee data into clear, decision-friendly insights. It gives an at-a-glance view of workforce size and attrition, then breaks attrition down by key employee and organizational dimensions.

### Questions explored
1. How many employees are represented, and how many have left?
2. How does attrition vary across age groups and gender?
3. Which education fields and job roles account for the most attrition?
4. How is attrition distributed across salary slabs and departments?
5. How does attrition vary with total working years?

## Key Metrics

| KPI | Dashboard value |
|---|---:|
| Total Employees | 1.47K |
| Attrition | 237 |
| Attrition Rate | 16.12% |
| Average Age | 36.92 |
| Average Salary | 6.50K |
| Average Years at Company | 7.01 |

## Dashboard Analysis

<details>
<summary><strong>Attrition by age group</strong></summary>

| Age group | Attrition |
|---|---:|
| 26–35 | 116 |
| 18–25 | 44 |
| 36–45 | 43 |
| 46–55 | 26 |
| 55+ | 8 |

The 26–35 age group has the highest attrition count in the displayed data.
</details>

<details>
<summary><strong>Attrition by education</strong></summary>

| Education field | Attrition |
|---|---:|
| Life Sciences | 89 |
| Medical | 63 |
| Marketing | 35 |
| Technical Degree | 32 |
| Other | 11 |

Life Sciences and Medical together represent the largest portions of the education breakdown.
</details>

<details>
<summary><strong>Attrition by job role</strong></summary>

| Job role (as displayed) | Attrition |
|---|---:|
| Laboratory Technician | 62 |
| Sales Executive | 57 |
| Research Scientist | 47 |
| Manufacturing Director | 10 |
| Healthcare Representative | 9 |

Laboratory Technicians, Sales Executives, and Research Scientists are the largest categories shown.
</details>

<details>
<summary><strong>Attrition by salary slab</strong></summary>

| Salary slab | Attrition |
|---|---:|
| Up to 5K | 88 |
| 5K–10K | 26 |
| 10K–15K | 15 |
| 15K+ | 3 |

The largest attrition count is in the Up to 5K salary slab.
</details>

<details>
<summary><strong>Attrition by department</strong></summary>

| Department | Attrition |
|---|---:|
| Research & Development | 133 |
| Sales | 92 |
| Human Resources | 12 |

Research & Development has the highest attrition count among the departments shown.
</details>

<details>
<summary><strong>Attrition by total working years</strong></summary>

The line chart compares attrition counts across total working-year values. The plotted values visible in the screenshot include 9, 12, 16, 22, 18, 16, 10, 25, and 5 for the labeled points. The first point is visually clipped, so its exact value is not transcribed here.
</details>

<details>
<summary><strong>Attrition by gender</strong></summary>

| Gender | Attrition |
|---|---:|
| Male | 150 |
| Female | 87 |
</details>

## Key Observations

- The dashboard reports **237 attritions** and an **attrition rate of 16.12%**.
- The **26–35** age group has the highest attrition count (116).
- **Life Sciences** is the largest education category shown (89).
- **Laboratory Technician** is the leading job-role category shown (62).
- The **Up to 5K** salary slab has the highest attrition count (88).
- **Research & Development** has the highest department attrition count (133).
- Male attrition count (150) is higher than female attrition count (87) in this dataset view.

These are descriptive observations, not proof that any one factor causes employees to leave.

## Tools & Skills

- **Microsoft Power BI** — dashboard design and data visualization
- **Data analysis** — workforce and attrition breakdowns
- **KPI reporting** — headline workforce metrics
- **Visual storytelling** — translating HR data into readable insights

## How to Use

1. Open `HR_Analytics_Dashboard_HD.png` to view the high-resolution dashboard preview.
2. Open the `.pbix` file in Power BI Desktop if you have the original project file.
3. Use the report's filters and visuals to explore the underlying employee data.

## Notes

- This ZIP contains the README and an upscaled PNG preview created from the screenshot supplied for this project.
- The original Power BI `.pbix` file and source dataset were not included in the upload.
- Values and labels are transcribed from the supplied dashboard image; abbreviated labels are retained where the screenshot truncates them.
