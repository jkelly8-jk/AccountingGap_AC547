# **AC-547 Project 2 — Group 11**

**Group Members:** Julia Kelly, Stephanie Smith, Olivia Curl, Karlie Auer, Emma Korby  
**Professor:** Dr. Swanquist  
**Course:** AC 547  
**Date:** 12 November 2025  

---

## **Data Analytics Final Project**

### **What is the problem/topic?**

Our project will analyze the gap between the number of individuals who earn accounting degrees each year and the number who enter and remain in public accounting. Recent discussions in the profession highlight declining CPA pipelines, high turnover, demographic shifts, and changing preferences among new graduates. We want to quantify who is entering public accounting, who is not, and how characteristics such as age, gender, and demographic location relate to this trend.

---

### **Why is this topic important?**

Understanding this gap is critical for firms, universities, and the profession. Public accounting firms are struggling to hire and retain qualified staff, while universities continue to produce accounting graduates who may be choosing different career paths.

By identifying demographic patterns in entry and retention, we can provide insight into:

- Whether certain regions face more or severe talent shortages  
- Whether specific demographic groups are migrating away from public accounting  
- How the labor pipeline has shifted in response to work–life balance concerns, burnout, compensation issues, and alternative career paths (such as data analytics and industry roles)

---

### **How will we address it?**

We will merge publicly available workforce and education datasets to measure the relationship between accounting degree completion and employment outcomes in public accounting. We will clean and join datasets across years, calculate descriptive statistics, and create visualizations to highlight patterns such as regional disparities or age/gender differences.

---

### **Datasets we plan to use**

#### **1. IPUMS CPS**
https://cps.ipums.org/cps-action/variables/group  
From this dataset, we will pull occupation and industry data, focusing on public accountants and grouping them by age and sex as needed.

#### **2. U.S. Census Bureau — ACS PUMS**
https://data.census.gov/app/mdat/ACSPUMS1Y2023?cv=SEX&rv=OCCP(0800),ucgid,SCHL(21,22,23)&vv=AGEP,*PERNP&wt=PWGTP&g=AwJm-BVBlEBoCMcDMcAsQ  
We will use this dataset to gather information about people with accounting degrees, then join it with occupation datasets to compare the two values. We will also be able to sort people with accounting degrees by region, sex, and gender to reveal trends.

#### **3. NSF NCSES — National Workforce Data**
https://ncsesdata.nsf.gov/builder/ntews  
This dataset provides individuals whose highest degree is in accounting. We will also join this with data about where people work and expand the analysis by adding information for people who hold professional licenses. Like the previous datasets, we can subset by age, gender, and other demographic factors.

---

