---
title: Integrate PowerApps, Microsoft Flow, and Power BI with SharePoint Online (Introduction) | Microsoft Docs
description: 'This series of tutorials explores how to build out a basic project-management app based on SharePoint lists and three key technologies that integrate with SharePoint Online: PowerApps, Microsoft Flow, and Power BI.'
services: ''
suite: powerapps
documentationcenter: na
author: mgblythe
manager: anneta
editor: ''
tags: ''

ms.service: powerapps
ms.devlang: na
ms.topic: article
ms.tgt_pltfrm: na
ms.workload: na
ms.date: 06/12/2017
ms.author: mblythe

---
# Integrate PowerApps, Microsoft Flow, and Power BI with SharePoint Online
Do you have SharePoint Online and want to better automate and streamline your business processes? Have you worked with PowerApps, Microsoft Flow, or Power BI, but you're not sure how to use them with SharePoint Online? You've come to the right place! This series of tutorials explores how to build out a basic project-management app based on SharePoint lists and three key technologies that integrate with SharePoint Online: PowerApps, Microsoft Flow, and Power BI. These technologies work together, making it easy to *measure* your business, *act* on the results, and *automate* your workflows. When you're done with this series, you will have a cool scenario like the following:

![Diagram of completed scenario](./media/sharepoint-scenario-intro/composite-with-background.png)

## Business scenario
In this series of tutorials, the company Contoso has a SharePoint Online site where they manage the lifecycle of projects, from request, to approval, to development, to final review. A *project requestor*, such as a department head, requests an IT project by adding an item to a SharePoint list. A *project approver*, such as an IT manager, reviews the project, and then approves it or rejects it. If approved, the project is assigned to a *project manager*, and additional detail is added to a second list through the same app. A *business analyst* reviews current and completed projects using a Power BI report embedded in SharePoint.  Microsoft Flow is used to send approval email and respond to Power BI alerts.

## Getting started quickly
The scenario we present in this series of tutorials is simple compared to a full-blown project management and analysis app, but it still takes some time to complete all the tasks. If you just want a quick introduction to using PowerApps, Microsoft Flow, and Power BI with SharePoint, check out the following articles:

* **PowerApps**: [Generate an app from within SharePoint using PowerApps](generate-app-from-sharepoint-list-interface.md) and [Generate an app to manage data in a SharePoint list](app-from-sharepoint.md)
* **Microsoft Flow**: [Wait for approval in Microsoft Flow](https://flow.microsoft.com/documentation/wait-for-approvals)
* **Power BI**: [Embed with report web part in SharePoint Online](https://powerbi.microsoft.com/documentation/powerbi-service-embed-report-spo)

When you're done, we hope you'll be back to check out this full scenario.

Even within the scenario, you can focus on the tasks that interest you, and complete the tasks as you have time. After you set up SharePoint lists in task 1, you can work through tasks 2-5 in any order; then tasks 6-8 are sequential. Lastly, we have included two finished apps and a Power BI Desktop report as part of the [download package](https://aka.ms/o4ia0f) for this scenario. You can look at these and learn by example even if you don't go through all the steps in each task.

## Prerequisites
To complete the scenario, you need the following subscriptions and desktop tools. The Office 365 Business Premium subscription includes PowerApps and Microsoft Flow.

| **Subscription or tool** | **Link** |
| --- | --- |
| Office 365 Business Premium subscription |[Trial subscription](https://signup.microsoft.com/Signup?OfferId=467eab54-127b-42d3-b046-3844b860bebf&dl=O365_BUSINESS_PREMIUM&ali=1) |
| PowerApps Studio |Use PowerApps Studio for web (no download required) or [PowerApps Studio for Windows](https://aka.ms/powerappswin) |
| Power BI Pro subscription |[Trial subscription](https://powerbi.microsoft.com/get-started/) (click **TRY FREE**) |
| Power BI Desktop |[Free download](https://powerbi.microsoft.com/get-started/) (click **DOWNLOAD FREE**) |

Ideally, you have basic familiarity with each technology, but you can still complete the scenario if you're new to some of these technologies. Use the following content to get up to speed:

* [Get started with SharePoint](https://support.office.com/article/Get-started-with-SharePoint-909ec2f0-05c8-4e92-8ad3-3f8b0b6cf261)
* [PowerApps Guided Learning](https://powerapps.microsoft.com/guided-learning/)
* [Microsoft Flow Guided Learning](https://flow.microsoft.com/guided-learning/)
* [Power BI Guided Learning](https://powerbi.microsoft.com/guided-learning/)

## Next steps
The next step in this tutorial series is to [set up the SharePoint Online lists](sharepoint-scenario-setup.md) that we use throughout the series.

