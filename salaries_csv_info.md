# Introduction

This repo contains salary information from `ai-jobs.net`. A `salaries.csv` file, downloaded on 4 July 2021, contains self-reported job titles, salary, location, etc. A data dictionary, taken from [ai-jobs.net](https://www.ai-jobs.net) is replicated below for your convenience when working with the data.


# Data dictionary:

> What's inside?
> The download basically contains a single table with all salary information structured roughly as follows:

The variable_name coding is not very descriptive, so we've added clarifing information below for variables; this information is contained in the right-most column:

| variable_name      | variable_description                                                     | variable_definitions                                                                                |
|--------------------|------------------------------------|---------------------------------------------------------|
| work_year          | The year during which the salary was paid                                | 2020, 2021e (2021 estimated)                                                                        |
| experience_level   | The experience level in the job during the year                          | "entry-level/junior","mid-level/intermediate", "senior-level/expert","executive-level/director"     |
| employment_type    | The type of employment for the role                                      | "part-time","full-time","contract","freelance"                                                      |
| job_title          | The role worked in during the year                                       |                                                                                                     |
| salary             | The total gross salary amount paid                                       |                                                                                                     |
| salary_currency    | The currency of the salary paid                                          |                                                                                                     |
| salary_in_usd      | The salary in USD (FX rate divided by avg. USD rate for respective year) |                                                                                                     |
| employee_residence | Employee's primary country of residence in during the work year          |                                                                                                     |
| remote_ratio       | The overall amount of work done remotely                                 | "no remote work (less than 20% remote)","partially remote", "fully remote (more than 80%)"          |
| company_location   | The country of the employer's main office or contracting branch          |                                                                                                     |
| company_size       | The average number of people that worked for the company during the year | "small (less than 50 employees)", "medium (50 to 250 employees)", "large (more than 250 employees)" |
