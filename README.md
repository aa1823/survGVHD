
# Chronic Graft-Versus-Host Disease Analysis


#Brief Project Description:
An advanced statistical analysis of factors influencing the time to Chronic Graft-Versus-Host Disease (CGVHD) in leukemia patients who underwent allogeneic bone marrow transplants.

Project Overview:
This project delves into the factors affecting the onset of CGVHD in leukemia patients following allogeneic bone marrow transplants. Using sophisticated statistical techniques, it examines various clinical characteristics across different treatment sites to provide valuable insights into the disease's timeline.

Table of Contents:

Project Details
Installation
Usage
Data Sources
Technologies Used
Contributors
License
Project Details
Description:
This project aims to understand the dynamics of CGVHD development in leukemia patients post-allogeneic bone marrow transplantation. By applying advanced statistical methods, it investigates the impact of clinical factors on the time to CGVHD onset, shedding light on potential risk factors and treatment site variations.

Key Features:

In-depth survival analysis
Examination of clinical characteristics
Identification of factors influencing CGVHD onset
Demo:
Link to Live Demo (if available)

Installation
Prerequisites:
To run this project locally, you need the following prerequisites:


SAS OnDemand for Academics: SAS Studio (or similar statistical software)
Installation Steps:

Clone this repository.

Set up SAS OnDemand for Academics: SAS Studio or SAS 9 following the official documentation.
Usage
Usage Guide:
To perform a similar analysis, follow these steps:

Load the dataset into your statistical software.
Apply Kaplan-Meier survival analysis.
Implement a Generalized Gamma Accelerated Time Failure (AFT) model.
Interpret the results, focusing on clinical factors' impact on CGVHD onset time.

Code Examples:


# Example SAS code for AFT model
proc lifereg data=dataset;
model time_to_cgvhd = age sex cmv_status clinical_site disease_group / dist=gamma;
run;

Data Sources
Data Description:
The project utilizes clinical data collected from multiple sites, comprising patient demographics and treatment details.

Data Processing:
Data already preproccesd for statistical analysis.

Technologies Used
Programming Languages:

SAS
Frameworks and Libraries:


SAS OnDemand for Academics: SAS Studio
Contributors
Team Members:

Azuka Atum - Project Lead
Contributing:
We welcome contributions. Please see our Contribution Guidelines for details.




