# Deliverable 2: Exploratory Data Analysis of Ottawa Housing Development Pipeline

**Date:** November 18, 2024  
**Course:** MPAD 2003: Introductory Data Storytelling  
**Student Name:** Ria Gandhi  
**Instructor:** Jean-Sébastien Marier  


## 1. Getting Data

This exploratory data analysis investigates administrative records from the City of Ottawa Housing Data Hub (2024) dataset, supplemented by Canada Mortgage and Housing Corporation (CMHC) housing construction benchmarks. The dataset tracks residential development proposals across Ottawa through four consecutive lifecycle stages: planning application approval, building permit issuance, construction commencement (housing starts), and final construction completion.

The raw data was accessed via the Open Ottawa Housing Data Hub portal. To analyze the records, I imported the dataset into Google Sheets using File > Import > Upload, setting character encoding to UTF-8 and delimiter settings to comma-separated values.

* Public Spreadsheet Link: https://docs.google.com/spreadsheets/d/1t_ed0XrftnDFWNFgSexk8WGgaqlS_EKZpuiYndzRnlg/edit?usp=sharing

![Raw Dataset in Google Sheets](raw_data.png)

The imported dataset contains 250 project rows and 7 core variables.
* Column A (PROJECT_ID): Represents nominal qualitative variables containing unique alphanumeric codes assigned to each housing proposal. No duplicate project identifiers were identified during initial validation.
* Column C (DWELLING_TYPE): Represents nominal categorical variables classifying building density (e.g., "Apartment / High-Rise", "Townhouse / Row", "Single Detached").
* Column D (PIPELINE_STAGE): Represents ordinal categorical variables tracking project progression ("1. Planning Approved", "2. Building Permit Issued", "3. Construction Commenced", "4. Construction Completed").
* Column E (APPROVED_UNITS): Represents quantitative discrete variables measuring the number of approved housing units associated with each permit application.

### Research Hypothesis

Investigative Question: At which stage of Ottawa's residential development pipeline does the largest drop-pff in ousing unit production occur, and do high-density multi-residential apartment developments face greater conversion delays between planning approval and active construction than low-density single-family housing?


## 2. Understanding Data





### 2.1. VIMO Analysis

Use three hashtag symbols (`###`) to create a level 3 heading like this one. Please follow this template when it comes to level 1 and level 2 headings. However, you can use level 3 headings as you see fit.

Insert text here.

Support your claims by citing relevant sources. Please follow [APA guidelines for in-text citations](https://apastyle.apa.org/style-grammar-guidelines/citations).

**For example:**

As seen in Bounegru & Gray (2011), a data visualization should be clear...

### 2.2. Cleaning Data

Insert text here.

### 2.3. Analyzing Data

Insert text here.

**This section should include a screen capture of your pivot table, like so:**

![](pivot-table-screen-capture.png)<br>
*Figure 2: This pivot table shows...*

**This section should also include a screen capture of your exploratory chart, like so:**

![](chart-screen-capture.png)<br>
*Figure 3: This exploratory chart shows...*

## 3. Delivering Data

Insert text here.

## 4. References

Include a list of your references here. Please follow [APA](https://apastyle.apa.org/style-grammar-guidelines/references) or [MLA](https://www.mla.org/MLA-Style) guidelines for references. Hanging paragraphs aren't required though.

**Here's an example:**

Bounegru, L., & Gray, J. (Eds.). (2021). *The Data Journalism Handbook 2: Towards A Critical Data Practice*. Amsterdam University Press. [https://ocul-crl.primo.exlibrisgroup.com/permalink/01OCUL_CRL/hgdufh/alma991022890087305153](https://ocul-crl.primo.exlibrisgroup.com/permalink/01OCUL_CRL/hgdufh/alma991022890087305153)
