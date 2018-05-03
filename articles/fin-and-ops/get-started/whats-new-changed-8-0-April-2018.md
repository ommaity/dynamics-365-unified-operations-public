---
# required metadata

title: What's new or changed in Dynamics 365 for Finance and Operations version 8.0 (April 2018)
description: This topic describes features that are either new or changed in Dynamics 365 for Finance and Operations version 8.0. This version was released in April 2018.
author: tonyafehr
manager: AnnBe
ms.date: 05/01/2018
ms.topic: article
ms.prod: 
ms.service: dynamics-ax-platform
ms.technology: 

# optional metadata

# ms.search.form: 
# ROBOTS: 
audience: Developer, IT Pro
# ms.devlang: 
ms.reviewer: tfehr
ms.search.scope:  Operations
# ms.tgt_pltfrm: 
ms.custom: 
ms.assetid: b265d51c-52d1-45c5-b578-64c5242c592a
ms.search.region: Global
# ms.search.industry: 
ms.author: tfehr
ms.search.validFrom: 2017-09-30 
ms.dyn365.ops.version: Release 8.0

---
# What's new or changed in Dynamics 365 for Finance and Operations version 8.0 (April 2018)

[!INCLUDE [banner](../includes/banner.md)]

This topic describes features that are either new or changed in Microsoft Dynamics 365 for Finance and Operations version 8.0 (April 2018). This version was released in April 2018 and has a build number of 8.0.30.

To discover the latest updates to our business applications, as well as a host of new capabilities for building your own applications and extensions on top of our platform, download the [Dynamics 365 Spring ’18 release notes](https://aka.ms/businessappsreleasenotes). The Release Notes provide details about the features that are either new or changed in Dynamics 365 for Finance and Operations.

### Introducing Dynamics 365 for Finance and Operations

Users and developers will see an updated product name, "Microsoft Dynamics 365 for Finance and Operations." With version 8.0, Microsoft is further simplifying our Dynamics 365 offerings and increasing ease of selection for our customers and ecosystem. Going forward, Microsoft is no longer offering separate editions (Business edition and Enterprise edition), so the product name for this Dynamics 365 application is Microsoft Dynamics 365 for Finance and Operations.

## Business productivity 

### Alerts

Client-based alert functionality enables a user to define alert rules based on
business events, such as when an invoice is paid or a customer changes an
address. For more information about alerts and how to create them, see [Alerts overview](alerts-overview.md).

### Optimization advisor

Uses telemetry to analyze customers’ business processes, finds optimization
opportunities, uses application data to quantify the opportunities, and then
recommends solutions.

### Project timesheet mobile

Employees can create and submit project timesheets. The use of saved favorites
and the ability to copy from a previous timesheet facilitates rapid, accurate
time entry.

### Edit default project fulfillment hours

Project resource managers can edit the default hours as part of the project
booking fulfillment process.

### Reserve project resources past the task end date

Project resource managers can fulfill resources on tasks past the current
planned end date for the task.

### Person search report

You can find a person and their personal data in Finance and Operations.

### Data sharing for customer and vendor tables

Data can be shared across customer and vendor tables and many related tables
across multiple legal entities.

### One voucher deprecation

One voucher is turned off by default, through a General ledger parameter.

## Extensibility and customization 

### Customizations through extensions only

Migrating customizations from one release to the next has been simplified by
moving away from over-layering to the use of extensions.

### Extensibility requests

Customers can submit a request to Microsoft for extension support to be added to
the product for a needed scenario. In this release, this feature is moved to
Lifecycle Services (LCS).

### Embedding PowerApps in workspaces and forms

Use PowerApps to embed data from external sources into Finance and Operations
data. For information about how to embed a PowerApp on a Finance and Operations page, see [Embed PowerApps](embed-power-apps.md).

### Custom fields

Organizations can add custom fields to tailor their application to their
business requirements, using a no-code extensibility experience. For information about how to add a custom field, see [Custom fields](user-defined-fields.md).

## Integration 

### Integration with Common Data Service (CDS) 

Dynamics 365 for Finance and Operations has enabled cross-application business
processes between Finance and Operations and Dynamics 365 for Field Service and
between Finance and Operations and Dynamics 365 for Project Service Automation.
These scenarios are configured using extensible Data integrator templates and
CDS to enable the cross-application scenarios.

### Integration with Dynamics 365 for Field Service

Provides data integration to support scenarios where Field Service activities
are done outside Finance and Operations, leveraging the data integrator.

### Integration with Dynamics 365 for Project Service Automation

Supports scenarios where project and resource management activities are done
outside Finance and Operations, and the project accounting activities are done
in Finance and Operations, leveraging the data integrator.

## Improved support experiences 

### Telemetry-based KB recommendation

Telemetry from a production environment can be used to identify the application
hotfixes that apply to a tenant.

### KB recommendations when entering a support case

LCS provides telemetry-driven KB recommendations.

### Report production outage

Provides a quick and effective channel to escalate issues to Microsoft Support
if the services in a production environment are degraded or become unavailable.

## Supply chain management 

### Vendor collaboration – RFQ process

Enhancements make it easy to tell who entered a bid (a vendor or a procurement
department). For more information, see [Requests for quotation (RFQs)](../../supply-chain/procurement/request-quotations.md).

### Partial shipment of a load (split load)

Allows single loads or multiple loads to be fully or partially loaded.

### Immediate replenishment of locations

Used during wave execution if allocation fails for a location directive line
that has a replenishment template. For more information about immediate replenishment, see [Immediate replenishment](../../supply-chain/warehousing/immediate-replenishment.md).

### Reason codes added to warehouse counting and adjustment

Users can add a reason code when performing counts and when making an
adjustment. For more information about reason codes, see [Reason codes for inventory counting](../../supply-chain/warehousing/reason-codes-for-counting-journals.md).

### Batch balancing enabled for advanced warehousing processes 

The batch balancing process is now available for products that are set up for
warehouse management processes (in earlier releases, the batch balancing process
was enabled only for products that were not set up for warehouse management
processes). This enhancement makes it possible for the user to release
ingredients to picking after the batch balancing process has been completed. For more information about batch balancing, see [Batch balancing](../../supply-chain/production-control/batch-balancing.md).

### Analytical workspaces with embedded Power BI for Cost management

New Analytical workspaces for Cost management are embedded in the Cost
administration and Cost Analysis workspaces. The content pack includes measures
such as beginning balance, ending balance, net sourcing and net usage. A set of
calculated measures, such as inventory turn ratio, days inventory on-hand, and
inventory accuracy are also included. The **Cost management** Power BI content is shown in the **Cost administration** and **Cost analysis** workspaces. For more information, see [Cost management Power BI content](../../dev-itpro/analytics/cost-management-content-pack.md).

## Globalization 

### India localization – project and upgrade

Users can manage India Goods and Services Tax (GST) for the Project management
and accounting module, and AX 2012 customers can upgrade to Dynamics 365 for
Finance and Operations.

### Enhanced configurability

New features include import and testing scenarios, and also broader support for
configurability without coding.

## Servicing, performance, and deployment 

### Improved delivery of platform and financial reporting updates

Platform and financial reporting updates will be continual updates managed by Microsoft rather than optional updates. This change is intended to improve service reliability and availability, and also to ensure that customers have the latest improvements and fixes. Platform and financial reporting updates are backward-compatible.  For more information, see [Finance and Operations cloud platform monthly updates FAQ](../../dev-itpro/sysadmin/faq-platform-monthly-updates.md).

### Upgrade automation

Upgrade automation makes major version upgrades a self-service operation for the
customer, using LCS for non-production environments.

### Service hardening

Added service monitoring and alerting for core business processes, and improved
form load performance of the most commonly used forms.

### Lifecycle Services sandbox self-service automation and RDP lockdown

Sandbox self-service automation supports data movement, debugging operations,
monitoring, and diagnostics without requiring access to the sandbox environments
through Remote Desktop. Remote Desktop capabilities for sandbox environments
will be deprecated. This means that customers won’t be required to use Remote
Desktop to access the VM, which improves reliability and security.

## Compliance 

### General Data Protection Regulation (GDPR)

Investments address the European privacy law’s requirements. Go to the [Trust
Center](https://www.microsoft.com/en-us/trustcenter/compliance/accessibility) to
learn more and find resources to help you comply.

### Accessibility enhancements

Go to the [Trust
Center](https://www.microsoft.com/en-us/trustcenter/compliance/accessibility) to
learn about our industry-leading accessibility standards.
