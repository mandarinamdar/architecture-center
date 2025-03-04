---
title: Team Data Science Process for DevOps
description: Developer Operations (DevOps) functions that are specific to an Advanced Analytics and Cognitive Services solution implementation.
author: marktab
manager: marktab
editor: marktab
services: architecture-center
ms.service: architecture-center
ms.subservice: azure-guide
ms.topic: conceptual
ms.date: 12/14/2021
ms.author: tdsp
ms.custom:
  - previous-author=deguhath
  - previous-ms.author=deguhath
products:
  - azure-machine-learning
categories:
  - ai-machine-learning
---

# Team Data Science Process for Developer Operations

This article explores the Developer Operations (DevOps) functions that are specific to an Advanced Analytics and Cognitive Services solution implementation. These training materials implement the Team Data Science Process (TDSP) and Microsoft and open-source software and toolkits, helpful for envisioning, executing and delivering data science solutions. It references topics that cover the DevOps Toolchain that is specific to Data Science and AI projects and solutions.

## Lesson Path
The following table provides level-based guidance to help complete the DevOps objectives for implementing data science solutions on Azure.

| Objective | Topic | **Resource** | **Technologies** | **Level** | **Prerequisites** |
|--|--|--|--|--|--|
| Understand Advanced Analytics | The Team Data Science Process Lifecycle | [This technical walkthrough describes the Team Data Science Process](overview.yml) | Data Science | Intermediate | General technology background, familiarity with data solutions, Familiarity with IT projects and solution implementation |
| Understand the Microsoft Azure Platform for Advanced Analytics | Information Management | [This reference gives and overview of Azure Data Factory to build pipelines for analytics data solutions](/azure/data-factory/v1/data-factory-introduction) | Microsoft Azure Data Factory | Experienced | General technology background, familiarity with data solutions, Familiarity with IT projects and solution implementation |
|  | | [This reference covers an overview of the Azure Data Catalog which you can use to document and manage metadata on your data sources](/azure/data-catalog/overview) | Microsoft Azure Data Catalog | Intermediate | General technology background, familiarity with data solutions, familiarity with Relational Database Management Systems (RDBMS) and NoSQL data sources |
|  | | [This reference covers an overview of the Azure Event Hubs system and how you and use it to ingest data into your solution](/azure/event-hubs/event-hubs-about) | Azure Event Hubs | Intermediate | General technology background, familiarity with data solutions, familiarity with Relational Database Management Systems (RDBMS) and NoSQL data sources, familiarity with the Internet of Things (IoT) terminology and use |
|  | Big Data Stores | [This reference covers an overview of using the Azure Synapse Analytics to store and process large amounts of data](/azure/synapse-analytics/sql-data-warehouse/sql-data-warehouse-overview-what-is) | Azure Synapse Analytics | Experienced | General technology background, familiarity with data solutions, familiarity with Relational Database Management Systems (RDBMS) and NoSQL data sources, familiarity with HDFS terminology and use |
|  |  | [This reference covers an overview of using Azure Data Lake to capture data of any size, type, and ingestion speed in one single place for operational and exploratory analytics](/azure/data-lake-store/data-lake-store-overview) | Azure Data Lake Store | Intermediate | General technology background, familiarity with data solutions, familiarity with NoSQL data sources, familiarity with HDFS |
|  | Machine learning and analytics | [This reference covers an introduction to machine learning, predictive analytics, and Artificial Intelligence systems](/azure/machine-learning) | Azure Machine Learning | Intermediate | General technology background, familiarity with data solutions, familiarity with Data Science terms, familiarity with Machine Learning and artificial intelligence terms |
|  |  | [This article provides an introduction to Azure HDInsight, a cloud distribution of the Hadoop technology stack. It also covers what a Hadoop cluster is and when you would use it](/azure/hdinsight/hadoop/apache-hadoop-introduction) | Azure HDInsight | Intermediate | General technology background, familiarity with data solutions, familiarity with NoSQL data sources |
|  |  | [This reference covers an overview of the Azure Data Lake Analytics job service](/azure/data-lake-analytics/data-lake-analytics-overview) | Azure Data Lake Analytics | Intermediate | General technology background, familiarity with data solutions, familiarity with NoSQL data sources |
|  |  | [This overview covers using Azure Stream Analytics as a fully-managed event-processing engine to up real-time analytic computations on streaming data](/azure/stream-analytics/stream-analytics-introduction) | Azure Stream Analytics | Intermediate | General technology background, familiarity with data solutions, familiarity with structured and unstructured data concepts |
|  | Intelligence | [This reference covers an overview of the available Cognitive Services (such as vision, text, and search) and how to get started using them](/azure/cognitive-services/what-are-cognitive-services) | Cognitive Services | Experienced | General technology background, familiarity with data solutions, software development |
|  |  | [This reference covers and introduction to the Microsoft Bot Framework and how to get started using it](/bot-framework/overview-introduction-bot-framework) | Bot Framework | Experienced | General technology background, familiarity with data solutions |
|  | Visualization | [This self-paced, online course covers the Power BI system, and how to create and publish reports](https://powerbi.microsoft.com/guided-learning/powerbi-learning-0-0-what-is-power-bi/) | Microsoft Power BI | Beginner | General technology background, familiarity with data solutions |
|  | Solutions | [This resource page covers multiple applications you can review, test and implement to see a complete solution from start to finish](https://gallery.cortanaintelligence.com/) | Microsoft Azure, Azure Machine Learning, Cognitive Services, Microsoft R, Azure Cognitive Search, Python, Azure Data Factory, Power BI, Azure Document DB, Application Insights, Azure SQL DB, Azure Synapse Analytics, Microsoft SQL Server, Azure Data Lake, Cognitive Services, Bot Framework, Azure Batch, | Intermediate | General technology background, familiarity with data solutions |
| Understand and Implement DevOps processes | What is DevOps? | [This article explains the fundamentals of DevOps and helps explain how they map to DevOps practices](/devops/what-is-devops) | DevOps, Microsoft Azure Platform, Azure DevOps | Intermediate | Familiarity with Agile and other Development Frameworks, IT Operations Familiarity |
| Use the DevOps Toolchain for Data Science | Configure | [This reference covers the basics of choosing the proper visualization in Visio to communicate your project design](https://support.office.com/article/Illustrate-business-processes-with-Visio-flowcharts-DAB16418-1FE6-4DE0-8F26-DBA44A26ED65) | Visio | Intermediate | General technology background, familiarity with data solutions |
|  |  | [This reference describes the Azure Resource Manager, terms, and serves as the primary root source for samples, getting started, and other references](/azure/azure-resource-manager/management/overview) | Azure Resource Manager, Azure PowerShell, Azure CLI | Intermediate | General technology background, familiarity with data solutions |
|  |  | [This reference explains the Azure Data Science Virtual Machines for Linux and Windows](/azure/machine-learning/data-science-virtual-machine/overview) | Data Science Virtual Machine | Experienced | Familiarity with Data Science Workloads, Linux |
|  |  | [This walkthrough explains configuring Azure cloud service roles with Visual Studio - pay close attention to the connection strings specifically for storage accounts](/visualstudio/azure/vs-azure-tools-configure-roles-for-cloud-service#configure-an-azure-cloud-service) | Visual Studio | Intermediate | Software Development |
|  |  | [This series teaches you how to use Microsoft Project to schedule time, resources and goals for an Advanced Analytics project](https://support.office.com/article/Project-2013-videos-and-tutorials-af7d1e17-5fa7-421f-a452-9bbe2cd7b082) | Microsoft Project | Intermediate | Understand Project Management Fundamentals |
|  |  | [This Microsoft Project template provides a time, resources and goals tracking for an Advanced Analytics project](/azure/architecture/data-science-process/team-data-science-process-project-templates#microsoft-project-template) | Microsoft Project | Intermediate | Understand Project Management Fundamentals |
|  |  | [This Azure Data Catalog tutorial describes a system of registration and discovery for enterprise data assets](/azure/data-catalog/data-catalog-get-started) | Azure Data Catalog | Beginner | Familiarity with Data Sources and Structures |
|  |  | [This Microsoft Virtual Academy course explains how to set up Dev-Test with Visual Studio Codespace and Microsoft Azure](https://mva.microsoft.com/training-courses/dev-test-with-visual-studio-online-and-microsoft-azure-8420?l=P7Ot1TKz_2104984382) | Visual Studio Codespace | Experienced | Software Development, familiarity with Dev/Test environments |
|  |  | This Management Pack download for Microsoft System Center contains a Guidelines Document to assist in working with Azure assets | System Center | Intermediate | Experience with System Center for IT Management |
|  |  | [This document is intended for developer and operations teams to understand the benefits of PowerShell Desired State Configuration](/powershell/scripting/dsc/overview/dscforengineers) | PowerShell DSC | Intermediate | Experience with PowerShell coding, enterprise architectures, scripting |
|  | Code | [This download also contains documentation on using Visual Studio Codespace Code for creating Data Science and AI applications](https://code.visualstudio.com/) | Visual Studio Codespace | Intermediate | Software Development |
|  |  | [This getting started site teaches you about DevOps and Visual Studio](https://www.visualstudio.com/devops/) | Visual Studio | Beginner | Software Development |
|  |  | [You can write code directly from the Azure portal using the App Service Editor. Learn more at this resource about Continuous Integration with this tool](https://github.com/projectkudu/kudu/wiki/App-Service-Editor) | Azure portal | Highly Experienced | Data Science background - but read this anyway |
|  |  | [This resource explains how to get started with Azure Machine Learning](/azure/machine-learning/overview-what-is-azure-machine-learning) | Azure Machine Learning  | Intermediate | Software Development |
|  |  | [This reference contains a list and a study link to all of the development tools on the Data Science Virtual Machine in Azure](/azure/machine-learning/data-science-virtual-machine/overview) | Data Science Virtual Machine | Experienced | Software Development, Data Science |
|  |  | [Read and understand each of the references in this Azure Security Trust Center for Security, Privacy, and Compliance - VERY important](https://azure.microsoft.com/support/trust-center/) | Azure Security | Intermediate | System Architecture Experience, Security Development experience |
|  | Build | [This course teaches you about enabling DevOps Practices with Visual Studio Codespace Build](https://mva.microsoft.com/training-courses/enabling-devops-practices-with-visual-studio-online-build-12478?l=ipCj6MuNB_6305094681) | Visual Studio Codespace | Experienced | Software Development, Familiarity with an SDLC |
|  |  | [This reference explains compiling and building using Visual Studio](/previous-versions/visualstudio/visual-studio-2015/ide/compiling-and-building-in-visual-studio) | Visual Studio | Intermediate | Software Development, Familiarity with an SDLC |
|  |  | [This reference explains how to orchestrate processes such as software builds with Runbooks](/system-center/orchestrator/automate-runbooks) | System Center | Experienced | Experience with System Center Orchestrator |
|  | Test | [Use this reference to understand how to use Visual Studio Codespace for Test Case Management](http://www.almguide.com/2014/07/visual-studio-online-test-case-management/) | Visual Studio Codespace | Experienced | Software Development, Familiarity with an SDLC |
|  |  | [Use this previous reference for Runbooks to automate tests using System Center](/system-center/orchestrator/automate-runbooks) | System Center | Experienced | Experience with System Center Orchestrator |
|  |  | [As part of not only testing but development, you should build in Security. The Microsoft SDL Threat Modeling Tool can help in all phases. Learn more and download it here](https://www.microsoft.com/SDL/adopt/threatmodeling.aspx) | Threat Monitoring Tool | Experienced | Familiarity with security concepts, software development |
|  |  | [This article explains how to use the Microsoft Attack Surface Analyzer to test your Advanced Analytics solution](https://technet.microsoft.com/security/gg749821.aspx) | Attack Surface Analyzer | Experienced | Familiarity with security concepts, software development |
|  | Package | [This reference explains the concepts of working with Packages in TFS and Visual Studio Codespace](/cli/vsts/package) | Visual Studio Codespace | Experienced | Software development, familiarity with an SDLC |
|  |  | [Use this previous reference for Runbooks to automate packaging using System Center](/system-center/orchestrator/automate-runbooks) | System Center | Experienced | Experience with System Center Orchestrator |
|  |  | [This reference explains how to create a data pipeline for your solution, which you can save as a JSON template as a "package"](/azure/data-factory/v1/data-factory-introduction) | Azure Data Factory | Intermediate | General computing background, data project experience |
|  |  | [This topic describes the structure of an Azure Resource Manager template](/azure/azure-resource-manager/templates/template-syntax) | Azure Resource Manager | Intermediate | Familiarity with the Microsoft Azure Platform |
|  |  | [DSC is a management platform in PowerShell that enables you to manage your IT and development infrastructure with configuration as code, saved as a package. This reference is an overview for that topic](/powershell/scripting/dsc/overview) | PowerShell Desired State Configuration | Intermediate | PowerShell coding, familiarity with enterprise architectures, scripting |
|  | Release | [This head-reference article contains concepts for build, test, and release for CI/CD environments](/azure/devops/pipelines/) | Visual Studio Codespace | Experienced | Software development, familiarity with CI/CD environments, familiarity with an SDLC |
|  |  | [Use this previous reference for Runbooks to automate release management using System Center](/system-center/orchestrator/automate-runbooks) | System Center | Experienced | Experience with System Center Orchestrator |
|  |  | [This article helps you determine the best option to deploy the files for your web app, mobile app backend, or API app to Azure App Service, and then guides you to appropriate resources with instructions specific to your preferred option](/azure/app-service/deploy-local-git) | Microsoft Azure Deployment | Intermediate | Software development, experience with the Microsoft Azure platform |
|  | Monitor | [This reference explains Application Insights and how you can add it to your Advanced Analytics Solutions](/azure/azure-monitor/app/app-insights-overview) | Application Insights | Intermediate | Software Development, familiarity with the Microsoft Azure platform |
|  |  | [This topic explains basic concepts about Operations Manager for the administrator who manages the Operations Manager infrastructure and the operator who monitors and supports the Advanced Analytics Solution](/previous-versions/system-center/system-center-2012-R2/hh230741(v=sc.12)) | System Center | Experienced | Familiarity with enterprise monitoring, System Center Operations Manager |
|  |  | [This blog entry explains how to use the Azure Data Factory to monitor and manage the Advanced Analytics pipeline](https://azure.microsoft.com/blog/azure-data-factory-updates-monitoring-and-management-enhancements/) | Azure Data Factory | Intermediate | Familiarity with Azure Data Factory |
| Understand how to use Open Source Tools with DevOps on Azure | Open Source DevOps Tools and Azure | [This reference page contains two videos and a whitepaper on using Chef with Azure deployments](https://www.chef.io/) | Chef | Experienced | Familiarity  with the Azure Platform, Familiarity with DevOps |
|  |  | [This site has a toolchain selection path](https://azure.microsoft.com/try/devops/) | DevOps, Microsoft Azure Platform, Azure DevOps, Open Source Software | Experienced | Used an SDLC, familiarity with Agile and other Development Frameworks, IT Operations Familiarity |
|  |  | [This tutorial automates the build and test phase of application development using a continuous integration and deployment CI/CD pipeline](/azure/developer/jenkins/pipeline-with-github-and-docker) | Jenkins | Experienced | Familiarity  with the Azure Platform, Familiarity with DevOps, Familiarity with Jenkins |
|  |  | [This contains an overview of working with Docker and Azure as well as additional references for implementation for Data Science applications](https://docs.docker.com/cloud/aci-integration) | Docker | Intermediate | Familiarity  with the Azure Platform, Familiarity with Server Operating Systems |
|  |  | [This installation and explanation explains how to use Visual Studio Code with Azure assets](https://marketplace.visualstudio.com/items?itemName=MadsKristensen.OpeninVisualStudioCode) | VSCODE | Intermediate | Software Development, familiarity with the Microsoft Azure Platform |
|  |  | [This blog entry explains how to use R Studio with Microsoft R](https://www.r-bloggers.com/using-microsoft-r-open-with-rstudio/) | R Studio | Intermediate | R Language experience |
|  |  | [This blog entry shows how to use continuous integration with Azure and GitHub](https://blogs.msdn.microsoft.com/microsoftimagine/2015/09/01/using-continuous-integration-with-azure-github/) | Git, GitHub | Intermediate | Software Development |

## Contributors

*This article is maintained by Microsoft. It was originally written by the following contributors.* 

Principal author:

 - [Mark Tabladillo](https://www.linkedin.com/in/marktab/) | Senior Cloud Solution Architect

*To see non-public LinkedIn profiles, sign in to LinkedIn.*

## Next steps

See [Team Data Science Process for data scientists](team-data-science-process-for-data-scientists.md). This article provides guidance for implementing data science solutions with Azure.
