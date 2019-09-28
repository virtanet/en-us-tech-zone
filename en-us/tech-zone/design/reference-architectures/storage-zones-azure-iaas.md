---
layout: doc
---
# Title

## Contributors

**Author:** [name](https://twitter.com/handle)

## Audience

This document is intended for Citrix technical professionals, IT decision makers, partners, and security consultants who want to explore and adopt the Citrix Cloud service of Access Control. The reader must have a basic understanding of Citrix products, security, and Citrix Cloud frameworks. For more information on Citrix Cloud and its services, see the official product documentation for [Citrix Cloud](/en-us/citrix-cloud.html).

## Objective of this document

This document provides a technical overview of Citrix Access Control and architecture that provides conditional access to cloud apps and internet browsing-enhancing the organization’s overall security and compliance posture. Citrix Access Control combines elements of several Citrix Cloud services to deliver an integrated experience for end users and administrators.

The document guides admins on an approach to deliver a secure digital workspace with a consolidated solution using Citrix Access Control integrated with multiple Citrix Cloud services including Citrix Gateway Service and Secure Browser. To monitor user behavior and activities Citrix Access Control integrates with Citrix Analytics.

## Use Cases
Customers deploy their own customer-managed storage zones for different reasons. Typical use cases for utilizing storage zones on Azure includes:
*  **Performance:**  While Citrix hosts storage zones in multiple geographic regions; customers in certain regions may not have access to a zone that provides the user experience employees expect. A customer could decide to deploy the storage zone directly in their Data center closer to the users, however this will impose the tax of CAPEX cost as well as ongoing operations/management costs. With 54 Azure regions across the globe, customer will have more choice deploying the storage zone in a regions closer to their users. That reduces the latency when transferring files providing a better user experience to employees and external collaborators.
In the scenario when a customer deploys a Citrix Virtual App and Desktop resource location in Azure, customer should always deploy a Content collaboration storage zone in Azure in the same region closer proximity to their App/Desktops in Azure.
*  **Governance and Data Residency:**  Similar to the prior statement, a customer might be required to host the data in a specific geography where Citrix might not have that footprint. The alternative would be customer hosting in their own datacenter and potentially being covered by one of the Azure Regions. 
*  **Modernize existing repositories:** Migration of files is not always possible or can be time consuming. With Citrix Content Collaboration this doesn’t mean that employees cannot have or have to wait for modern ways of accessing and working with files. By deploying a customer-managed storage zone, customers can directly unlock a modern workstyle on any device without having to migrate existing data. 

## TODO SectionX

TODO

## Summary

Summarize the goal and lessons learned from this document

## Sources

Goal of this reference architecture is to assist you with planning your own implementation. To make this job easier, we would like to provide you with source diagrams that you can adapt in your own detailed designs and implementation guides: [source diagrams](https://citrix.sharefile.com/todo).

## References

Links to all useful references
