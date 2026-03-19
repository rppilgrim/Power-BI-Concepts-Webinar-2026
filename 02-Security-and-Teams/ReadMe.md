# Session-02 Power BI Security and Teams

Link to interactive slide deck 

https://rppilgrim.github.io/website-REACH-2026-Power-BI-Webinar-Session-02/
---
# Who am I

 Robert Pilgrim, Ph.D. | rpilgrim@uark.edu
- Associate Director of Data Strategy & Insights
- Office of Sponsored Programs, UARK
- B.Sc Astrophysics | Ph.D. Space Science
- My Website [rpilgrim.com](rpilgrim.com) | [LinkedIn](https://www.linkedin.com/in/robert-pilgrim-2181a213/) | [Substack](https://researchanalytics.substack.com/)
# Purpose of these Webinars

- Met many people:
  - Conferences / Summits
  - Workshops / presentations
  - REACH mentoring
- Most people just need help starting
![](https://pub-5f7080454d3c4473a1cc20896fa1b068.r2.dev/illustrations/illustration_pacman-eating-data_v01.png)

# Session Framework
- All data / dashboards are dummy

![](https://pub-5f7080454d3c4473a1cc20896fa1b068.r2.dev/illustrations/illustration_workshop-REACH-2026-power-bi-session-overview.png)

# Question from the Chat Accessibility
- Accessibility Features
- [Design Power BI Reports for Accessibility - Power BI | Microsoft Learn](https://learn.microsoft.com/en-us/power-bi/create-reports/desktop-accessibility-creating-reports)
- No configuration needed. 
- Keyboard navigation. - Screen-reader compatibility
- High contrast colors view,  Focus mode
- Show visuals as data table![](https://pub-5f7080454d3c4473a1cc20896fa1b068.r2.dev/screenshots/screenshot_microsoft-power-bi-example-accessibility_v01.png)
# Accessibility

![](https://pub-5f7080454d3c4473a1cc20896fa1b068.r2.dev/screenshots/screenshot_microsoft-power-bi-Accessibility_v01.png)
# Where We Left Off

- Power BI Desktop, Service, Data Models
- Data Model | DAX
![](https://pub-5f7080454d3c4473a1cc20896fa1b068.r2.dev/diagrams/diagram_workflow-analytics_01.png)

# Recap Power BI Service

- Cloud based
- Share /  Collaborate
- Microsoft campus?
- app.powerbi.com

  ![](https://pub-5f7080454d3c4473a1cc20896fa1b068.r2.dev/diagrams/diagram_power-bi-desktop-vs-service_portrait_v01.png)

# Recap The Data Model

- Relationships NOT merging
- Powered by Data Analysis Expressions (DAX)
- DAX wraps around your data model
- Cross-data analytics

![](https://pub-5f7080454d3c4473a1cc20896fa1b068.r2.dev/diagrams/diagram_example-data-model_01.png)

# Recap Data Analysis Expressions (DAX)

- Data Models = BRAINS | DAX = LOGIC
- DAX wraps around the data model
  ![](https://pub-5f7080454d3c4473a1cc20896fa1b068.r2.dev/illustrations/illustration_microsoft-power-bi-dax_01.png)

# Data Models and Reporting
![](https://pub-5f7080454d3c4473a1cc20896fa1b068.r2.dev/illustrations/Illustration_data-models-reporting-split_v01.png)

# Single Source of Truth
![](https://pub-5f7080454d3c4473a1cc20896fa1b068.r2.dev/illustrations/illustration_ai-octopus-reaching-into-laptops_v1.png)

# Workspaces

- What is a workspace?
- Creating and organizing workspaces
- Dev  / Prod separation

# Publishing a Report
- Live demo next
- Power BI Desktop click "Publish
- Select your Workspace"
![](https://pub-5f7080454d3c4473a1cc20896fa1b068.r2.dev/screenshots/screenshot_microsoft-power-bi-example-publish_v01.png)

# Direct Sharing  via Workspace
- Individual user and report sharing
- Not scalable
- Hard to manage for large groups
- Let's look at an example
![](https://pub-5f7080454d3c4473a1cc20896fa1b068.r2.dev/screenshots/screenshot_microsoft-power-bi-example-workspace-sharing-direct_01.png)

# Example Problem
- **Executive Reports:** 3 reports,10 users
- **HERD Reports:** 3 reports, 20 users
- **Operations Reports:** 3 reports, 10 users
- **Quality Control Reports:** 3 reports, 10 users
- 150 individual shares to manage!!

![](https://pub-5f7080454d3c4473a1cc20896fa1b068.r2.dev/screenshots/screenshot_microsoft-power-bi-example-reporting-groups_v01.png)

# From Workspace to APP

- Defining who sees what within an App
- Audience groups
- Different pages to different users
- Managing access without duplicating reports
![](https://pub-5f7080454d3c4473a1cc20896fa1b068.r2.dev/screenshots/screenshot_microsoft-power-bi-example-reporting-groups_v01.png)

# Report Groups

- **Executive** 
- **HERD** 
- **Operations** 
- **Quality Control** 
![](https://pub-5f7080454d3c4473a1cc20896fa1b068.r2.dev/screenshots/screenshot_microsoft-power-bi-example-reporting-groups_v01.png)

# Deploying to an APP
- A. Click Create/Update APP
- B. Click "Content"
- C. Click "Add Content"
- D. Select reports
![](https://pub-5f7080454d3c4473a1cc20896fa1b068.r2.dev/screenshots/screenshot_microsoft-power-bi-example-publish-app_v01.png)

# Split App into  Reporting Groups
- App shows all reports
- This is not what we want

![](https://pub-5f7080454d3c4473a1cc20896fa1b068.r2.dev/screenshots/screenshot_microsoft-power-bi-example-publish-app_v02.png)

# Reporting Groups
![](https://pub-5f7080454d3c4473a1cc20896fa1b068.r2.dev/screenshots/screenshot_microsoft-power-bi-example-reporting-groups_v01.png)

# App Groups
- Go back to workspace
- Click "Update App"
- A. Click "Audience"
- B. Create your groups
- C. Select reports for that group
- D. Add group members
- Individual users or Azure security groups
![](https://pub-5f7080454d3c4473a1cc20896fa1b068.r2.dev/screenshots/screenshot_microsoft-power-bi-example-reporting-groups_v03.png)


# App Audience
- Live demo next
![](https://pub-5f7080454d3c4473a1cc20896fa1b068.r2.dev/screenshots/screenshot_microsoft-power-bi-example-reporting-groups_v04.png)

# Live Demo
![](https://pub-5f7080454d3c4473a1cc20896fa1b068.r2.dev/screenshots/screenshot_microsoft-power-bi-example-reporting-groups_v03.png)

# Renaming Report in the App
![](https://pub-5f7080454d3c4473a1cc20896fa1b068.r2.dev/screenshots/screenshot_microsoft-power-bi-example-app-report-rename_v01.png)

# Embedding Reports in SharePoint
![](https://pub-5f7080454d3c4473a1cc20896fa1b068.r2.dev/screenshots/screenshot_microsoft-power-bi-example-app-report-embed_v01.png)

# Power BI Mobile
- Customize views in the Power BI Desktop
![](https://pub-5f7080454d3c4473a1cc20896fa1b068.r2.dev/screenshots/screenshot_microsoft-power-bi-example-mobile-view_01.png)

# Version Control (Simple)
- By default all your work is already version control
![](https://pub-5f7080454d3c4473a1cc20896fa1b068.r2.dev/screenshots/screenshot__onedrive-version-control_v02.png)

# Version Control Power BI (Advanced)
- Power BI PBIX vs PBIP format
![](https://pub-5f7080454d3c4473a1cc20896fa1b068.r2.dev/illustrations/illustration_microsoft-power-bi-old-new-format.png)

# Version Control Power BI (Advanced)
- PBIP file format
- Data is not stored

![](https://pub-5f7080454d3c4473a1cc20896fa1b068.r2.dev/illustrations/illustration_microsoft-power-bi-pbip-folder-structure_01.png)

# Learn more from my Articles
[Power BI and GitHub: Better Together for Higher Ed Analytics](https://researchanalytics.substack.com/p/power-bi-and-github-better-together)

[Managing Complex Analytics Workflows in GitHub Using a Live Microsoft Repository](https://researchanalytics.substack.com/p/managing-complex-analytics-workflows)


![](https://pub-5f7080454d3c4473a1cc20896fa1b068.r2.dev/screenshots/screenshot_my-blog-post_v01.png)

