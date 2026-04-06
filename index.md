---
title: Introduction
layout: home
nav_order: 1
---

#  TechWorkshop L300: Fabric with Databricks for Data Analytics

#  TechWorkshop L300: Fabric with Databricks for Data Analytics

This lab teaches you how to integrate Azure Databricks with Microsoft Fabric to build end-to-end analytics and AI workflows. You'll work across data engineering, governance, analytics, and AI experiences to understand how Fabric and Databricks complement each other in an enterprise data platform.

## Architecture
This lab uses Microsoft Fabric as the unified analytics platform, with Azure Databricks integrated for advanced data engineering, transformation, and governance. Data is ingested from Azure Data Lake Storage Gen2, processed using Spark and Delta Live Tables in Databricks, governed with Unity Catalog, and surfaced in Fabric through lakehouses, semantic models, AI agents, and real-time analytics.

## Exercises
This lab has the following exercises:
- Exercise 00: Provision and configure resources
- Exercise 01: Explore the Fabric data engineering experience
- Exercise 02: Integrate Azure Databricks with Fabric
- Exercise 03: Build AI Agents by using Fabric Data Agents
- Exercise 04: Explore the Fabric Power BI experience
- Exercise 05: Explore the Microsoft Fabric data science experience
- Exercise 06: Explore real-time intelligence in Fabric
- Exercise 07: Create AI-driven insights by using Microsoft Foundry and Genie

## Prerequisites
Before starting this lab, you should be familiar with basic concepts in Azure, Microsoft Fabric, and data analytics. Experience with data engineering workflows, SQL, and notebooks is helpful but not required. No prior Databricks or Fabric configuration is necessary, as all required resources are provisioned for you.


## Customer scenario

Zava Retail Group is a global retail company operating in brick-and-mortar stores and a rapidly expanding e-commerce platform. To accelerate digital transformation, Zava established an AI Center of Excellence (COE) tasked with identifying high-impact, agentic AI opportunities that improve operational efficiency, employee productivity, and strategic decision-making. 

Zava operates in a hybrid cloud environment-Azure for productivity and analytics, AWS for certain legacy workloads, and SAP for supply chain and inventory. They rely on Microsoft 365, Teams, SharePoint, Azure DevOps (ADO), and a mix of third-party and custom systems. 

However, the COE faces pressure: 
Google and AWS teams are actively proposing AI solutions, and Zava's leadership wants to quickly identify a strategic partner with security, governance, extensibility, and enterprise-grade readiness 

---

## Important notes

- The workshop instructions include text fields where you'll be asked to enter information. We use the information that you enter in the text fields later in the instructions to provide you with important values.
- We appended an 8-digit unique identifier (the lab instance ID from the live labs) to the names of the resources created during this workshop that is represented by a tag: **@lab.LabInstance.Id**. You should replace these tags with your actual information if you bring your own license.
- The lab instance IDs used in screenshots will differ from your actual information. They represent the ID in use when we captured screenshots.


## Disclaimer

This presentation, demonstration, and demonstration model are for informational purposes only and (1) are not subject to SOC 1 and SOC 2 compliance audits, and (2) are not designed, intended, or made available as a medical device(s) or as a substitute for professional medical advice, diagnosis, treatment, or judgment. Microsoft makes no warranties, express or implied, in this presentation, demonstration, and demonstration model. Nothing in this presentation, demonstration, or demonstration model modifies any of the terms and conditions of Microsoft’s written and signed agreements. This is not an offer, and applicable terms and the information provided are subject to revision and may be changed at any time by Microsoft.

This presentation, demonstration, and demonstration model do not give you or your organization any license to any patents, trademarks, copyrights, or other intellectual property covering the subject matter in this presentation, demonstration, and demonstration model.

The information contained in this presentation, demonstration, and demonstration model represents the current view of Microsoft on the issues discussed as of the date of presentation and/or demonstration, for the duration of your access to the demonstration model. Because Microsoft must respond to changing market conditions, it should not be interpreted to be a commitment on the part of Microsoft, and Microsoft cannot guarantee the accuracy of any information presented after the date of presentation and/or demonstration and for the duration of your access to the demonstration model.

No Microsoft technology, nor any of its component technologies, including the demonstration model, is intended or made available as a substitute for the professional advice, opinion, or judgment of (1) a certified financial services professional, or (2) a certified medical professional. Partners or customers are responsible for ensuring the regulatory compliance of any solution they build using Microsoft technologies.

## Copyright

© 2026 Microsoft Corporation. All rights reserved. 

By using this demo/lab, you agree to the following terms:

The technology/functionality described in this demo/lab is provided by Microsoft Corporation for purposes of obtaining your feedback and to provide you with a learning experience. You may only use the demo/lab to evaluate such technology features and functionality and provide feedback to Microsoft. You may not use it for any other purpose. You may not modify, copy, distribute, transmit, display, perform, reproduce, publish, license, create derivative works from, transfer, or sell this demo/lab or any portion thereof.

COPYING OR REPRODUCTION OF THE DEMO/LAB (OR ANY PORTION OF IT) TO ANY OTHER SERVER OR LOCATION FOR FURTHER REPRODUCTION OR REDISTRIBUTION IS EXPRESSLY PROHIBITED.

THIS DEMO/LAB PROVIDES CERTAIN SOFTWARE TECHNOLOGY/PRODUCT FEATURES AND FUNCTIONALITY, INCLUDING POTENTIAL NEW FEATURES AND CONCEPTS, IN A SIMULATED ENVIRONMENT WITHOUT COMPLEX SET-UP OR INSTALLATION FOR THE PURPOSE DESCRIBED ABOVE. THE TECHNOLOGY/CONCEPTS REPRESENTED IN THIS DEMO/LAB MAY NOT REPRESENT FULL FEATURE FUNCTIONALITY AND MAY NOT WORK THE WAY A FINAL VERSION MAY WORK. WE ALSO MAY NOT RELEASE A FINAL VERSION OF SUCH FEATURES OR CONCEPTS. YOUR EXPERIENCE WITH USING SUCH FEATURES AND FUNCITONALITY IN A PHYSICAL ENVIRONMENT MAY ALSO BE DIFFERENT.

