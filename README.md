# chopR
This repo contains various materials developed by analysts in the Office of Quality Improvement (OCQI) at the Children's Hospital of Philadelphia that are used to train new and existing analysts on how to use R. Although these materials have been tailored to the needs of this specific analyst group, they could be useful training materials for other analysts wanting to adopt R, particularly those in a healthcare setting. 

# What's in this repository?

## Data Viz Guides-Templates
 
This folder contains ggplot and highcharter guides along with a flexdashboard template that is used by OCQI to create R dashboards. You can use these files to begin learning how to visualize your data in R and also how to organize these visualizations into a dashboard.
There are a few things to note about these guide/templates: 

1. The ggplot tutorial is included both as a .md and .Rmd file for users' convenience. 

2. The highcharter tutorial is only included as a .Rmd file because the html output of this .Rmd is not supported by github. Users can view the output of this tutorial here: https://chop-analytics.github.io/chopR/docs/highcharter_tutorial.html

3. The flexdashboard template was built specifically for CHOP analysts and, therefore, cannot be used as-is by users outside of CHOP. Below are the following reasons for this: 

   * The guide contains information on how to connect to the CHOP Data Warehouse, which is essential for pulling data into the dashboard. This step could be replaced by non-CHOP users if they have a different mechanism for pulling data into R Studio. 
   
   * The guide is also dependent on an internal R package developed by OCQI called `rocqi`, which currently is only available to CHOP employees. If you are a CHOP employee that wishes to download this package, please see this repo for documentation: https://github.research.chop.edu/CQI/rocqi. 
   
   Regardless of these limitations, the guide can be used as a conceptual framework for CHOP and non-CHOP users to build an interactive flexdashboard. 

## Instructional Sessions

This folder contains PDF files of the in-person sessions that all new OCQI analysts completed during their R portion of onboarding and all current OCQI analysts completed during the two-day training. The files cover the following topics: CHOP Analytics R Standards, dplyr, lubridate, tidyr, and ggplot. These sessions contain lecture-formatted instructions, examples, and also practice exercises using a dummy dataset. Additionally, there is also a Welcome Packet within this folder that outlines the training schedule, practice exercises, and R package cheat sheets relevant to the sessions. Although the internal `rocqi` package was taught to OCQI analysts during this training, these materials are not included in this public repo because the package is not publicly available. 

## Standards

This folder contains documentation related to CHOP Analytics R Standards that all analysts are recommended to adhere to in order to allow for effective and efficient code review, project handoff, and project sustainment. The standards cover the following topics: querying philosophy, organization, code structure, and code style for projects using R scripts and R markdowns.

# Who created this repository?

The materials contained in this repository were developed and are maintained by members of the R Adoption team within the OCQI at the Children's Hospital of Philadelphia. Below is the problem statement, mission statement, and goal that this team had in mind when developing these materials as well as a list of people who directly contributed to this work. 

## Problem Statment

Despite its many advantages, R is not a widely used tool within OCQI due to lack of analysts' understanding of practical value of R, OCQI R standards, R templates, and comprehensive training to adopt the tool. 

## Mission

Identify the gaps in R adoption, generate excitement around this tool, and create the necessary materials and trainings so that analysts can use this tool in their relevant day to day work

## Goals

This group aimed to address four primary goals with these materials: 
1. Establish OCQI R Standards
2. Develop data visualization guides and templates
3. Create training materials to teach the OCQI "standard packages"
4. Generate excitement around R

## Team Members

### Co-leads

Emily Schriver ; schrivere@email.chop.edu
Matt Dye ; dyem1@email.chop.edu

### Team Members

Ashley Oliver
Brendan Graham
Emily Foster
Jake Riley
Joe Mirizio
Paul Wildenhaim
Siying Wang



