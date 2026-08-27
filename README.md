# SAP-CO-Cost-Management-Simulation
## Project Overview

This project presents a simulated cost management and controlling process using SAP Controlling (CO) concepts.

The project is based on a hypothetical software and IT services company named **TechNova Solutions (Pvt) Ltd.**

The purpose of this project is to demonstrate how organisations can use cost centers, cost elements, internal orders, planned versus actual cost analysis, and variance analysis to improve cost control and management decision-making.

---

## Project Objectives

The objectives of this project are to:

- Simulate SAP CO cost management processes.
- Create and analyse organisational cost centers.
- Classify costs using cost elements.
- Compare planned costs with actual costs.
- Perform variance analysis.
- Track project costs using internal orders.
- Analyse the impact of costs on profitability.
- Provide recommendations for improving cost management.

---

## Company Scenario

### Company Name

TechNova Solutions (Pvt) Ltd.

### Industry

Software Development and Information Technology Services

### Business Activities

- Software development
- IT consulting
- Cloud services
- Business information systems

---

## Cost Centers

The simulation uses four main cost centers:

| Cost Center | Department | Main Responsibility |
|---|---|---|
| CC100 | Software Development | Software development and testing |
| CC200 | IT Infrastructure | Cloud services and technical support |
| CC300 | Sales and Marketing | Customer acquisition and promotion |
| CC400 | Administration | General administrative activities |

---

## Project Structure

```text
SAP-CO-Cost-Management-Simulation
│
├── data
│   ├── cost_center_data.csv
│   ├── planned_costs.csv
│   └── actual_costs.csv
│
├── analysis
│   └── variance_analysis.xlsx
│
├── documentation
│   └── Week3_CO_Report.docx
│
└── diagrams
    └── CO_Process_Flow.png
````

---

## Cost Analysis

The project compares planned costs with actual costs.

### Variance Formula

Variance = Actual Cost - Planned Cost

A positive variance represents an unfavorable cost variance because actual costs exceeded the planned budget.

A negative variance represents a favorable variance.

---

## Key Findings

The simulation identified unfavorable cost variances in:

* Software Development
* IT Infrastructure
* Administration

The major reasons include:

* Increased employee costs
* Employee overtime
* Higher cloud infrastructure usage
* Additional software requirements
* Unexpected project changes

Sales and Marketing recorded a favorable cost variance.

---

## Tools and Technologies

* SAP FICO Concepts
* SAP Controlling (CO)
* Microsoft Excel
* Cost Center Accounting
* Variance Analysis
* GitHub

---

## Author

Yasuri Tashmika

AIS Undergraduate

````

Then scroll down and click:

**Commit changes**

Use this commit message:

```text
Update project documentation and project overview
````

---

# Step 3: Create the Data Folder

Go to the main page of your repository.

Click:

**Add file → Create new file**

In the filename box, type:

```text
data/cost_center_data.csv
```

This will automatically create the `data` folder.

Add the following content:

```csv
Cost Center ID,Cost Center Name,Department,Manager
CC100,Software Development,Software Development,Development Manager
CC200,IT Infrastructure,IT Infrastructure,IT Manager
CC300,Sales and Marketing,Sales and Marketing,Marketing Manager
CC400,Administration,Administration,Administration Manager
```

Click:

**Commit changes**

Use the commit message:

```text
Add cost center master data
```

---

# Step 4: Create the Planned Costs File

Again click:

**Add file → Create new file**

Enter this filename:

```text
data/planned_costs.csv
```

Add:

```csv
Cost Center,Planned Cost (LKR)
Software Development,1500000
IT Infrastructure,800000
Sales and Marketing,600000
Administration,400000
Total,3300000
```

Commit message:

```text
Add planned cost data
```

---

# Step 5: Create the Actual Costs File

Click:

**Add file → Create new file**

Filename:

```text
data/actual_costs.csv
```

Add:

```csv
Cost Center,Actual Cost (LKR)
Software Development,1720000
IT Infrastructure,930000
Sales and Marketing,540000
Administration,430000
Total,3620000
```

Commit message:

```text
Add actual cost data
```

---

# Step 6: Create the Variance Analysis

Open Microsoft Excel.

Create the following table:

| Cost Center          | Planned Cost | Actual Cost | Variance |
| -------------------- | -----------: | ----------: | -------: |
| Software Development |    1,500,000 |   1,720,000 |  220,000 |
| IT Infrastructure    |      800,000 |     930,000 |  130,000 |
| Sales and Marketing  |      600,000 |     540,000 |  -60,000 |
| Administration       |      400,000 |     430,000 |   30,000 |
| Total                |    3,300,000 |   3,620,000 |  320,000 |

Use this formula for the Variance column:

```text
=Actual Cost - Planned Cost
```

For example, if:

* Planned Cost is in column B
* Actual Cost is in column C

Use:

```excel
=C2-B2
```

Save the file as:

```text
variance_analysis.xlsx
```

---

# Step 7: Upload the Excel File

Return to your repository.

Click:

**Add file → Upload files**

Upload:

```text
variance_analysis.xlsx
```

GitHub allows files to be uploaded and committed through the repository's web interface.

Before uploading, create the folder name by placing the file inside an `analysis` folder on your computer.

Your structure should be:

```text
analysis
   └── variance_analysis.xlsx
```

Upload the folder contents.

Use this commit message:

```text
Add planned versus actual cost variance analysis
```

---

# Step 8: Add Your Word Report

Use the completed Week 3 report and save it with this exact filename:

```text
Week3_CO_Report.docx
```

Place it inside a folder called:

```text
documentation
```

The structure should be:

```text
documentation
   └── Week3_CO_Report.docx
```

Upload it to your GitHub repository.

Use the commit message:

```text
Add Week 3 SAP CO controlling process report
```

---

# Step 9: Create the SAP CO Process Diagram

Create the following diagram using Microsoft PowerPoint, Word, Canva, or another diagram tool:

```text
Cost Planning
      ↓
Cost Center Definition
      ↓
Cost Element Classification
      ↓
Budget Allocation
      ↓
Actual Cost Recording
      ↓
Internal Order Tracking
      ↓
Planned vs Actual Comparison
      ↓
Variance Analysis
      ↓
Management Review
      ↓
Corrective Action
```

Save the diagram as:

```text
CO_Process_Flow.png
```

Create a folder named:

```text
diagrams
```

Place the image inside it:

```text
diagrams
   └── CO_Process_Flow.png
```

Upload it to GitHub.

Commit message:

```text
Add SAP CO controlling process flow diagram
```

---

# Step 10: Check Your Final Repository

Your repository should now look like this:

```text
SAP-CO-Cost-Management-Simulation
│
├── README.md
│
├── data
│   ├── cost_center_data.csv
│   ├── planned_costs.csv
│   └── actual_costs.csv
│
├── analysis
│   └── variance_analysis.xlsx
│
├── documentation
│   └── Week3_CO_Report.docx
│
└── diagrams
    └── CO_Process_Flow.png
```

---

# Step 11: Make the Repository Professional

Check the following:

* README has a clear project description.
* All files have meaningful names.
* The cost data matches the report.
* The Excel calculations are correct.
* The Word report contains the required analysis.
* The process flow diagram is clear.
* The repository is accessible.

---

# Step 12: Copy the Correct Repository URL

For the internship submission portal, use the main repository URL.

Do NOT use the README editing URL or the individual file URL.

Use the main repository page URL.

Paste that repository URL into the:

**GitHub Project URL**

field.

---

# Final Submission Checklist

* [ ] README.md completed
* [ ] Cost center data added
* [ ] Planned cost data added
* [ ] Actual cost data added
* [ ] Variance analysis Excel file uploaded
* [ ] Week 3 Word report uploaded
* [ ] SAP CO process flow diagram uploaded
* [ ] Repository checked for errors
* [ ] Correct GitHub repository URL copied
* [ ] Report uploaded to the internship portal
* [ ] GitHub project URL added to the internship portal
* [ ] Minimum 200-word report description completed
* [ ] Submit button clicked

