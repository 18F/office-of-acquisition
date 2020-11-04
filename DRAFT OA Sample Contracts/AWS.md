## 1.0 General

This single award BPA is established under the contractor’s Federal Supply Schedule (‘FSS’ or just ‘Schedule) Contract (TBD at time of award), under Schedule 70 Special Item Number (SIN) 132-40, for Cloud Service Provider (CSP) Infrastructure-as-a-Service (IaaS) cloud services.

## 2.0 Background

GSA TTS requires an Infrastructure-as-a-Service (IaaS) solution to provide the government with on-demand Cloud IaaS access through available FedRAMP Authorized cloud service providers. TTS desires the ability for the reseller to provide a CSP(s) to not only be immediately and fully compatible with the applications that are currently operational for TTS (currently through Amazon Web Services), but TTS desires to experiment and sandbox with multiple FedRAMP Authorized CSPs over the life of the order in hopes of developing confidence in utilizing multiple CSPs.

These IaaS solutions will help TTS support internal and external clients by providing a dedicated master payer account(s) for the CSP(s) solutions. These dedicated master payer account(s) must contain only GSA TTS accounts and GSA TTS requires direct control over the root accounts. In addition, the reseller must allow for ad-hoc creation and disposal of accounts under the master payer account. To that end, TTS requires the reseller to provide the ability to support other governmental agencies who have signed memorandums of understanding (MOUs) and/or interagency agreements with TTS. TTS also requires consolidated monthly billing, detailed billing and usage data, and access to the raw IaaS billing source data via the CSP(s) console. 

Access to these services will be managed by TTS and used TTS-wide (and for TTS clients that TTS has an interagency agreement with at the time of award or executed during the life of the order) to ensure cloud services are consumed across TTS and clientbase with appropriate levels of governance, security, and technical integration with existing Information Technology (IT) services, and business integration with existing financial and contractual processes. This approach will greatly reduce the burden on the part of individual cloud users, organizations, programs, and projects, since a significant percentage of the requirements associated with federal agency use of commercial cloud services will be addressed and result in approved- for-use cloud services offered with facilitated access.

Objectives include:  
* Cost savings to the government for cloud services  
* Full transparency into billing and data usage information
* Establish a collaborative relationship with a reseller to improve customer service and general operational efficiencies   
* Increasingly use commercial cloud computing services to meet TTS’ own computational requirements and TTS’ clients’ computational requirements through industry leading and FedRAMP Authorized IaaS CSPs 
* Enable future technological, process, and acquisition efficiencies and adoption
* Reseller's ability to provide at least one CSP offering a managed Kubernetes service certified by FedRAMP

In order to meet these objectives, TTS intends to establish a single award BPA to provide a procurement solution for the acquisition of IaaS cloud services through a reseller in support of portability, service scalability, and flexibility with infrastructure needs. The cloud services and their FedRAMP certified cloud environments must support multiple cloud deployment models that TTS can instantiate directly in the cloud provider space without any proprietary components. 

## 3.0 BPA Overview

Under this Performance Work Statement (PWS), the reseller shall provide TTS with the following: 
* Minimal value added services other than maintaining a contractual relationship with the awarded CSP(s).
* Access to the entire catalog, marketplace, or otherwise commercially available Cloud Services existing now or in the future during the Period of Performance of this BPA for the awarded CSP(s).
* Consolidated billing services.
* Upon request, timely provisioning of Dedicated Master Payer Accounts to TTS with direct access to all usage and cost data associated with TTS’ use of CSP Member Accounts.

With the awarded CSP(s), TTS will utilize open-source, DevOps centric, on-demand access to a shared pool of configurable computing resources.  These resources include, but are not limited to, servers, storage, network infrastructure, identity management, managed databases, cryptographic key management service and various other web services to support GSA TTS hosting needs as well as non-production systems. The common use cases are for a wide range of web-based, cloud-native applications and may include legacy enterprise applications, in addition to developer sandboxes, experiments, prototypes, and pilots. This includes not only the hosting of single-application workloads, but also the replacement of traditional enterprise data centers with cloud environments that can support a highly diversified range of innovative computing technologies to support federal government IT modernization.  GSA TTS must be able to directly and immediately provision or release computing resources.

The reseller shall place no restrictions on TTS’s ability to acquire Reserved Instances or Spot Instances directly from the CSP as applicable. The reseller should have a direct relationship with the awarded CSP(s), but the reseller shall also place no restrictions on TTS’s ability to communicate directly with the CSP.

TTS will be solely responsible for controlling Service Control Policy and Identity and Access Management (IAM) access for all Member Accounts associated with this requirement.
 
TTS requires that CSP resources purchased at any point during the order be available for use during any point in the remaining term of the order. There shall be no reseller time-based restrictions on the use of ordered resources that would limit TTS’s ability to consume ordered, but unused, resources within any specific calendar year, fiscal year, or order timeframe, other than the end of the order.

## 3.1 Frequency of Ordering 

Orders against the BPA are estimated to occur at least once every 12 months from date of BPA award, however, additional ordering is expected as TTS team needs arise for the CSP(s). There is no maximum to the number of orders that may be placed.

It shall be noted that BPAs do not promise or guarantee actual orders.

## 3.2 Invoicing

See Section 5.6. Below. 

## 3.3 Discounts

When ordering against the BPA, GSA TTS will:
* Request spot discounts
* Seek additional price reductions and concessions
* Continue to monitor the commercial market and the contractor’s Schedule to ensure this BPA honors the best available price (i.e. similar or better discounts or prices that the contractor is otherwise providing to as its most favoring pricing)
* At the BPA annual review, request additional price reductions when estimated quantities/amounts under the BPA have been exceeded (8.405-3(e)(1)(iii) or as needed.

Discounting to the federal government does not invoke the Price Reduction Clause contained in the Schedule contract.

## 3.4 Requirements

### 3.4.1. - Supporting TTS’ Needs

* Environment with the ability to use open source software to support current and future requirements
* Reseller's ability to provide a managed Kubernetes service certified by FedRAMP
* Data management 
  * Ability to manage data/content in the cloud with the government’s own resources (e.g.: software/tools, contractors)
  * Key Management Service (KMS) to create and control the encryption keys used to encrypt data, and uses Hardware Security Modules (HSMs) to protect the security of the keys. Logs of all key usage to help meet regulatory and compliance needs.  
  * Record Management per [NARA Bulletin 2010-05](https://www.archives.gov/records-mgmt/bulletins/2010/2010-05.html) - Guidance on Managing Records in Cloud Computing Environments
  * TTS will retain all data when the order ends
* Ability for GSA TTS to use tooling that interacts directly with the CSP’s API (eg Terraform, CloudFormation) without any contractor-introduced incompatibility or metering.
* Accounts
  * Ability for GSA TTS to possess and manage a Dedicated Master Payer Account (primary/root account)
  * Ability for the Dedicated Master Payer Account to create and manage GSA TTS secondary/sub-accounts (i.e.: other governmental agencies who have signed memorandums of understanding and/or inter-agency agreements with GSA TTS.)
  * Ability for GSA TTS Dedicated Master Payer Account to create, modify and delete ad-hoc accounts. 
  


