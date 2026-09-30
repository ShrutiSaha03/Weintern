# E-Commerce Sales Data Analysis — Week 1

## Project Title
**E-Commerce Sales Data Analysis and Power BI Dashboard**

## Week Number and Objective
**Week:** 1

**Objective:** To clean and prepare raw e-commerce sales data and transform it into measurable business insights through KPI analysis and an interactive Power BI dashboard.

The main objectives were to:
- Clean and validate the raw sales dataset.
- Handle missing values, duplicates, inconsistent categories/cities, and invalid values.
- Calculate core sales KPIs.
- Analyse category, product, city, delivery-status, and customer patterns.
- Create visual representations using Power BI.
- Prepare a structured analytical report.

## Dataset Description

The project uses an **e-commerce sales transaction dataset** containing fields such as:
- Order ID
- Product Name
- Category
- Quantity
- Total Amount
- City
- Delivery Status
- Order Date and other transaction-related fields

Key results from the cleaned analysis:
- **219 valid unique orders**
- **777 total units sold**
- **₹2,424,305.38 total revenue**
- **₹11,069.89 average order value**

The dataset was cleaned using Microsoft Excel and then analysed and visualized using Microsoft Power BI.

## Tools and Libraries Used

### Microsoft Excel
Used for data cleaning and preparation:
- Missing-value review
- Duplicate checking
- Validation of quantity and amount fields
- Standardization of category and city values
- Preparation of the cleaned dataset

### Microsoft Power BI
Used for:
- KPI calculation
- Data analysis
- Dashboard development
- Category and product analysis
- City-level analysis
- Delivery-status visualization

**Primary tools used for this assignment: Microsoft Excel and Microsoft Power BI.**

The `notebooks/week1_analysis.ipynb` file is retained as part of the project structure, but the primary Week 1 workflow documented here was performed using Excel and Power BI.

## Key Steps Performed

### 1. Data Inspection
The raw dataset was reviewed to understand its columns, data types, missing values, duplicate records, categorical values, and numerical fields.

### 2. Data Cleaning
The dataset was cleaned in Excel by:
- Reviewing missing values
- Checking duplicate records
- Validating Quantity and Total Amount
- Checking inconsistent category and city names
- Standardizing values where required
- Preparing the cleaned dataset for Power BI

### 3. KPI Analysis
The following KPIs were calculated:

| KPI | Result |
|---|---:|
| Total Revenue | ₹2,424,305.38 |
| Total Orders | 219 |
| Average Order Value | ₹11,069.89 |
| Total Units Sold | 777 |
| Units per Order | 3.55 |
| Top-Selling Category | Sports |
| Top Revenue-Generating Product | Polo Shirt |

### 4. Power BI Dashboard
The cleaned data was imported into Power BI to create:
- KPI cards
- Revenue by Category
- Product performance analysis
- Delivery-status distribution
- Order volume by City
- Top Category and Best Product indicators

## Major Findings

### Revenue and Orders
- Total revenue was **₹2,424,305.38**.
- There were **219 valid unique orders**.
- Average Order Value was **₹11,069.89**.
- **777 units** were sold, equal to approximately **3.55 units per valid order**.

### Category Performance
- **Sports** was the highest revenue-generating category.
- Sports generated **₹436,393.57**, approximately **18.00% of total revenue**.
- Beauty generated **₹430,441.57**.
- Home & Kitchen generated **₹347,800.82**.
- Sports, Beauty and Home & Kitchen together contributed approximately **50.12% of total revenue**.

### Product Performance
- **Polo Shirt** was the highest revenue-generating product.
- It generated **₹154,229.41**, approximately **6.36% of total revenue**.
- Revenue leadership and demand leadership are different measures; the highest-demand product should be determined using Quantity Sold.

### City-Level Performance
- **Chennai** recorded the highest reported city-level revenue at **₹347,068.61**.
- Chennai and Pune each recorded **31 orders** in the city-level order analysis.

### Delivery Status

| Delivery Status | Count | Share |
|---|---:|---:|
| Delivered | 75 | 22.26% |
| Cancelled | 72 | 21.36% |
| Pending | 51 | 15.13% |
| Shipped | 51 | 15.13% |
| Returned | 46 | 13.65% |
| In Transit | 32 | 9.50% |
| Unknown | 10 | 2.97% |

The delivery-status records and the 219 unique orders use different counting bases and should not be treated as interchangeable.

### Customer Insight
- **60 repeat customers** were identified.
- Repeat customers contributed **63.5% of total revenue**.
- This corresponds to approximately **₹1.54 million** of the reported revenue.

## Folder Structure

```text
data-science-week1-assignment/
│
├── data/
│   ├── raw/
│   └── cleaned/
│
├── notebooks/
│   └── week1_analysis.ipynb
│
├── outputs/
│   ├── charts/
│   └── dashboard/
│
├── reports/
│   └── final_report.pdf
│
├── screenshots/
│
├── README.md
│
└── requirements.txt
```

### Folder Description

| Folder/File | Purpose |
|---|---|
| `data/raw/` | Original/raw dataset |
| `data/cleaned/` | Cleaned dataset prepared using Excel |
| `notebooks/` | Project notebook file |
| `outputs/charts/` | Exported analysis charts |
| `outputs/dashboard/` | Power BI dashboard/output files |
| `reports/` | Final analytical report |
| `screenshots/` | Dashboard and analysis screenshots |
| `README.md` | Project documentation |
| `requirements.txt` | Project dependency/reference file |

## Execution Instructions

### Step 1 — Prepare Raw Data
Place the original dataset inside:

```text
data/raw/
```

### Step 2 — Clean Data in Excel
1. Open the raw dataset in Excel.
2. Inspect columns and data types.
3. Check missing values.
4. Check duplicate records.
5. Validate Quantity and Total Amount.
6. Standardize category, city, and other categorical values.
7. Check invalid or inconsistent records.
8. Save the cleaned dataset in:

```text
data/cleaned/
```

### Step 3 — Import into Power BI
1. Open Power BI Desktop.
2. Select **Get Data**.
3. Import the cleaned Excel/CSV file.
4. Check data types.
5. Create the required measures/KPIs.
6. Build the dashboard visuals.

### Step 4 — Create Dashboard
The dashboard should include:
- Total Revenue
- Total Orders
- Average Order Value
- Total Units Sold
- Top-Selling Category
- Top Revenue-Generating Product
- Revenue by Category
- Delivery Status
- Orders by City
- Product Performance

### Step 5 — Save Outputs
Save charts/dashboard outputs in:

```text
outputs/charts/
outputs/dashboard/
```

Save the final report in:

```text
reports/final_report.pdf
```

Store dashboard screenshots in:

```text
screenshots/
```

## Author Details

**Author:** Shruti Saha  
**Project:** Data Science Internship — Week 1  
**Task:** E-Commerce Sales Data Analysis  
**Tools:** Microsoft Excel and Microsoft Power BI

## Project Outcome

This Week 1 project demonstrates the workflow:

**Raw Data → Data Cleaning → KPI Calculation → Power BI Visualization → Business Insights → Analytical Report**

The project focuses on producing measurable, data-driven findings from e-commerce sales data.
