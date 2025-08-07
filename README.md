# [DISCOUNT STRATEGY]

---

## Table of Contents

- [1. Introduction](#1-introduction)
- [2. Features](#2-features)
- [3. Getting Started](#3-getting-started)
    - [3.1. Prerequisites](#31-prerequisites)
    - [3.2. Installation](#32-installation)
- [4. Project Workflow](#4-project-workflow)
  - [4.1. Data Cleaning And Quality Assessment](#41-data-cleaning-and-quality-assessment)
  - [4.2. Data Analysis And Visualization](#42-data-analysis-and-visualization)
  - [4.3. Final Deliverable-The Presentation](#43-final-deliverable-the-presentation)
- [5. Project Components](#5-project-components)
- [6. Contributors](#6-contributors)

---

## 1. Introduction

This repository holds a portfolio project that demonstrates our team's ability to tackle a real-world business problem at Eniac, a growing e-commerce company. We were tasked with settling an ongoing debate: whether or not offering product discounts is a beneficial business strategy.

This project shows more than simple analysis, highlighting our hands-on skills in data quality assessment and cleaning of a "messy" internal dataset. Using Python with Pandas and Seaborn, we transformed chaotic data into a trustworthy source. Our final goal was to present a concise and compelling recommendation to the company's board, backed by solid analysis and clear data storytelling.

---

## 2. Features

- **Business-Oriented Problem-Solving**: Addresses a core business question with conflicting opinions from different stakeholders (Marketing vs. Board).
- **Strong Data Cleaning & Quality Skills**: Focuses on the crucial initial step of data analytics—transforming messy, inconsistent data into a usable format.
- **Python-Based Analytical Stack**: Showcases proficiency in Python, using Pandas for data manipulation and Seaborn for professional visualizations.
- **Data Modeling & Feature Engineering**: Demonstrates the ability to create new, meaningful data features, such as product categories, to enrich analysis.
- **Effective Data Storytelling**: Prepares a clear, engaging narrative for a non-technical audience to drive business action.
- **Collaborative Workflow**: Documents the process of a group project from initial data review to final presentation preparation.

---

### 3. Getting Started

To access and review these Python notebooks, you only need a Google account and internet access.

### 3.1. Prerequisites
- A Google Account (for Google Colab)
- Internet access

### 3.2. Installation

All project content is directly accessible via Google Colab links. No local Python environment setup is strictly required to review the notebooks, but you can clone this repository to keep a local copy of the links and README.

```bash
# Clone this repository
git clone https://github.com/Cebulva/discount_strategy.git

# Navigate into the cloned repository directory
cd discount_strategy
```

---

### 4. Project Workflow

![Project overview](https://github.com/Cebulva/discount_strategy/blob/main/Screenshots/Screenshot-2025-01-22-at-14.19.58.png)


### 4.1. Data Cleaning And Quality Assessment
We began by assessing the data quality of four interconnected CSV files. This phase was critical, as the data had several inconsistencies, including duplicate rows, corrupted price values, and missing information. We used Python with Pandas to perform extensive cleaning tasks and ensure data integrity before any analysis.

### 4.2. Data Analysis And Visualization
With a clean and trustworthy dataset, we moved on to the core analysis. Our work focused on answering key business questions, such as:

- How products are categorized.
- The distribution of product prices and discounts.
- How seasonality affects sales.

We used Pandas for data wrangling, including working with datetimes and grouping data, and created professional plots with Seaborn to visually represent our findings and uncover patterns.

### 4.3. Final Deliverable: The Presentation
The culmination of our analysis was a concise, 5-minute presentation for Eniac’s board. The goal was to provide a clear recommendation on the discount strategy, backed by our data-driven insights. Our preparation steps, including brainstorming and creating plots, were documented.

---

### 5. Project Components

<details>
<summary>Raw Data Files</summary>
<br>
Four CSV files: Orders, orderlines, products, and brands that served as the starting point for this project. The data is available directly in this repository.
<br>
<a href="https://github.com/Cebulva/discount_strategy/tree/main/Data">View Raw Data (GitHub Folder)</a>
</details>

<details>
<summary>Miro Board Documentation</summary>
<br>
This board served as our central hub for project documentation. It includes our analysis of the raw CSVs, data cleaning tasks, presentation preparation, and a collection of plots created with Seaborn.
<br>
<a href="https://miro.com/app/board/uXjVIGWwBlk=/?moveToWidget=3458764627190797131&cot=14">View Miro Board</a>
</details>

<details>
<summary>Google Colab Notebooks</summary>
<br>
A collection of notebooks documenting our full analysis workflow.
<br>
<a href="https://colab.research.google.com/drive/1aAYvGhXdi1mw8w695dcVIayeah3Bia9a?usp=sharing">Notebook: Initial Data Analysis</a>
<br>
<a href="https://colab.research.google.com/drive/1LgfzudnsQ1xHvFkObCboIU67a7I237Kh?usp=sharing">Notebook: Data Cleaning</a>
<br>
<a href="https://colab.research.google.com/drive/1Yu0yWph09mYPPUXZ7I_kA2Nh6X5SAku-?usp=sharing">Notebook: Creating Product Categories</a>
<br>
<a href="https://colab.research.google.com/drive/17J6IFqpUtL1oW3g0r0fJg0KKN0gVIIHA?usp=sharing">Notebook: Data Quality Checks</a>
</details>

<details>
<summary>Final Presentation</summary>
<br>
A 5-minute group presentation delivered to Eniac's board, providing a data-driven recommendation on the company's discount strategy.
<br>
<a href="https://docs.google.com/presentation/d/1oWJZdbTaJ6pnRssPuNzuK43yco6aUby22EJisaB-uW0/edit?usp=sharing">View Presentation Slides</a>
</details>

---

### 6. Contributors

This project was a collaborative effort. We would like to thank the following individuals for their valuable contributions:

- [@camontefusco](https://github.com/camontefusco/): Carlos Montefusco
- Asli Strollo
- Azumi Muhammed
