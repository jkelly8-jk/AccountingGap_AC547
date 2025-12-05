# AC-547.project2-group11
Group 11- Julia Kelly, Stephanie Smith, Olivia Curl, Karlie Auer, Emma Korby
Dr. Swanquist
AC 547
12 November 2025
Data Analytics Final Project
What is the problem/ topic?
- Our project will analyze the gap between the number of individuals who earn accounting
degrees each year and the number who enter and remain in public accounting. Recent
discussions in the profession highlight declining CPA pipelines, high turnover,
demographic shifts, and changing preferences among new graduates. We want to quantify
who is entering public accounting, who is not, and how characteristics such as age,
gender, and demographic location relate to this trend.
Why is this topic important?
- Understanding this gap is critical for firms, universities, and the profession. Public
accounting firms are struggling to hire and retain qualified staff, while universities
continue to produce accounting graduates who may be choosing different career paths.
By identifying demographics patterns in entry and retention, we can provide insight into:
o Whether certain regions face more or serve talent shortages
o Whether specific demographic groups are migrating away from public accounting
o How the labor pipeline has shifted in response to work-life balance concerns,
burnout, compensation issues, and alternative career paths, such as data analytics
and industry roles.
How will we address it?
- We will merge publicly available workforce and education datasets to measure the
relationship between accounting degree completion and employment outcomes in public
accounting. We will clean and join datasets across years, calculate descriptive statistics
and create visualization to highlight patterns such as regional disparities or age/gender
differences.
Datasets we plan to use:
https://cps.ipums.org/cps-action/variables/group
From this, we are able to pull occupation and industry data. We will focus on accountants in
public accounting and group them by age and sex when necessary, as well. 
https://data.census.gov/app/mdat/ACSPUMS1Y2023?cv=SEX&rv=OCCP(0800),ucgid,SCHL(2
1,22,23)&vv=AGEP,*PERNP&wt=PWGTP&g=AwJm-BVBlEBoCMcDMcAsQ
We will use the census bureau to pull relevant information about people with accounting degrees
and eventually hopefully join this with occupation datasets to compare the two values. We will
also be able to sort people with accounting degrees by region, sex, and gender allowing us to see
more information about potential trends in the data.
https://ncsesdata.nsf.gov/builder/ntews
With this dataset, we will pull people who have their highest degree in accounting. We will also
be able to join this with a set about where people work and can further expands by adding data
for people who hold professional licenses. Like the previous datasets, we can subset this for age,
gender, and other important factors. 
