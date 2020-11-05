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

### 3.1 Frequency of Ordering 

Orders against the BPA are estimated to occur at least once every 12 months from date of BPA award, however, additional ordering is expected as TTS team needs arise for the CSP(s). There is no maximum to the number of orders that may be placed.

It shall be noted that BPAs do not promise or guarantee actual orders.

### 3.2 Invoicing

See Section 5.6. Below. 

### 3.3 Discounts

When ordering against the BPA, GSA TTS will:
* Request spot discounts
* Seek additional price reductions and concessions
* Continue to monitor the commercial market and the contractor’s Schedule to ensure this BPA honors the best available price (i.e. similar or better discounts or prices that the contractor is otherwise providing to as its most favoring pricing)
* At the BPA annual review, request additional price reductions when estimated quantities/amounts under the BPA have been exceeded (8.405-3(e)(1)(iii) or as needed.

Discounting to the federal government does not invoke the Price Reduction Clause contained in the Schedule contract.

### 3.4 Requirements

#### 3.4.1. - Supporting TTS’ Needs

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
  
#### 3.4.2. - Transparency Requirements

* Reseller’s ability to provide a dedicated master payer account for each CSP
* Ability to allow TTS to self-service all capacity activity for each CSP (for example AWS Reserved Instances purchasing, and similar functions for other CSPs)
* Provide ability to use all the CSP Marketplaces (as applicable) directly
* Reseller's ability to allow for TTS to submit support requests directly to all the CSP(s)
* Reseller’s ability to allow for TTS to select the type of support (as applicable) with no change in reseller discounting for each CSP
* Reseller’s ability to provide TTS with direct access to unaltered CSP billing and usage data for each CSP (not through third party tools such as CloudCheckr)
* Reseller’s ability to provide TTS access to native CSP dashboards, cost tools, and systems (for example, AWS Management Console, AWS Cost Explorer, and AWS Organizations, and similar tools for other CSPs), as well as provide visibility into spending rates using these components 

#### 3.4.3. - TTS & Reseller Collaboration Requirements

* During the base period of performance, the reseller shall meet with TTS at least once monthly for the first quarter of the requirement, and then once per quarter for the remaining period of performance to highlight new offerings, suggestions on better ordering/buying procedures, and answer questions. This shall be done virtually either by video or telephone. No travel is authorized.
* During any option period (as exercised), meet with TTS at least twice per period of performance to highlight new offerings, suggestions on better ordering/buying procedures, and answer questions. This shall be done virtually either by video or telephone. No travel is authorized.
* Vendor shall work with TTS to create custom account specific reports throughout the life of the order to assist in making it easier for TTS to map billing charges to monthly usage.

#### 3.4.4. - Services TTS Does Not Require

GSA TTS *does not* require assistance managing the information systems within the accounts. 

### 3.5 Estimated Quantities - Funded Call Orders

The government’s Good Faith Estimate for funded call orders over the life the BPA (if all options are exercised) is below $10,000,000 (**Note - for any non-AWS CSP BPA awarded, this amount will be updated at time of award to reflect $500,000**). However, please note, this is not a ceiling and may be raised without any justification at the discretion of the contracting officer. It shall also be noted that the government is not obligated to fund any orders if, for whatever reason, a need does not ultimately arise.

### 3.6 Delivery and Delivery Locations

Because delivery occurs electronically, the actual location of delivery is relatively moot.

FOB destination.

### 3.7 Time and Period of Performance

The BPA will consist of a base year period and four one (1) - year option periods. The BPA includes 52.217-9 (Option to Extend the Term of the Contract). FAR clause 52.217-8, Option to Extend Services, is also incorporated to potentially add up to six months to the BPA.

Call orders themselves may have options as well. 

NOTE - Orders shall not be awarded, nor shall Options of the BPA be exercised, if and when the Schedule contract has expired or has been terminated or cancelled by the government.

Any order issued against the BPA before the BPA expires will have its own PoP and shall be completed in accordance with Schedule clause 52.216-22(d) which states, “any order issued during the effective period of this contract and not completed within that period shall be completed by the contractor within the time frame specified in the order. The contract shall govern the contractor’s and government’s rights and obligations with respect to that order to the same extent as if the order were completed during the contract’s effective period, provided that the contractor shall not be required to make any deliveries under this contract after the completion of customer order, including options, 60 months following the expiration of the basic contract ordering period.” 

However, it is noted that a BPA does not survive the expiration of the Schedule contract from which it was issued. Once the Schedule contract expires (regardless of the BPA ordering period), the BPA automatically expires and no new orders can be issued against it from that point forward. A Schedule contractor may be awarded a BPA that extends beyond the current term of its GSA Schedule contract as long as there are option periods in the GSA Schedule contract that, if exercised, will cover the BPA’s Period of Performance

An annual review, in writing, will be completed reasonably near the government’s intention to exercise the next BPA option in accordance with 8.405-3(e). Note - this requirement does not apply to orders placed against the BPA.

### 3.8 Order Placing Procedures

A TTS Contracting Officer shall place a written order through ITSS. Contracting Officer’s outside of TTS’ Office of Acquisition shall not place orders.

Only a TTS warranted Contracting Officer (or Purchasing Agent) may place an order or otherwise obligate the government. Any order accepted by the contractor that was not placed by a warranted contracting officer (or Purchasing Agent) puts the contractor at risk of not being allowed payment for that order.

The government may issue call orders directly through ITSS to the contractor without any additional information needed up to $X00,000 (the maximum order limitation of the contractors Schedule - to be updated at time of award).

For orders above this amount, or for any other nuanced orders, the TTS Contracting Officer shall contact the contractor point of contact.

### 3.9 Deliverables

Other than access to the CSP(s), the contractor will:
* Provide consolidated monthly billing and detailed billing and usage data for each CSP no later than five business days after the preceding month for which the billing and usage data apply.
* Provide trend analysis for billing and usage to support planning and funding efforts at least twice per period of performance.
* TTS will invite the contractor to participate in the CPARs process by having the contractor submit their self-identified ratings for the relevant period of performance. TTS will review the information and either accept it as is or add information (whether positive or negative), remove information TTS does not agree with (to which TTS would provide reasoning), or TTS may not utilize any of the information. In all cases, TTS desires the process to be as collaborative as possible in hopes of it leading to better and more transparent outcomes.

Term | Definition
------------ | -------------
BPA Contracting Officer	| The contracting officer is the final authority in all contractual matters relating to the BPAs.  The BPA CO has overall responsibility for administration of the BPAs and is authorized to take action on behalf of the Government relating to the BPAs. The BPA CO and TO CO may be the same person or different person(s).

Task Order (TO) Contracting Officer	| Has final authority for individual awarded Task Orders. The TO CO may delegate certain responsibilities to Task Order contracting officer representative (TO COR) associated with the performance of individual Task Orders.  The TO CORs name and contact information as well as delegated responsibilities will be provided to the contractor by the TO CO. The BPA CO and TO CO may be the same person or different person(s).

CSP Marketplace	| Curated digital catalog that customers can use to find, buy, deploy, and manage third-party software and services that customers need to build solutions and run their businesses within the CSP. 

Dedicated Master Payer Account	| Or, simply, ‘Payer Account’. Pays the charges of all member accounts.

Root User	| Single sign-in identity that has complete access to all cloud services and resources in the account.

National Institute of Standards and Technology (NIST) Cloud Computing Reference Architecture is hereby referenced for definition purposes (NIST SP 500-292)

## 4.0 Call Order/BPA Details

### 4.1 Type of Line Items
The BPA will be issued on a Time and Material (T&M) basis.

Contract Line Item Number (CLIN)s will be funded as not-to-exceed (NTE) line items.  TTS shall only be charged (or invoiced) based on actual usage of the services at the then-current CSP unit pricing reflected in the CSPs commercial services catalog, but no more than the unit pricing found in the contractors Schedule Contract price list minus the percentage discount at the order level. 
  
The contractor shall invoice monthly in arrears, based on actual consumption, less any discount applied.
 
In all instances, the reseller shall collaborate with the Government to help the Government purchase services most effectively. This means, once awarded, the reseller shall assist the Government in using the most appropriate pricing model for Reserved Instances, Spot pricing, on demand pricing, or other effective models based on the Government’s trends and the reseller experience helping other federal agencies.

**The Contractor shall not make expenditures, nor incur obligations, in the performance of this contract, which exceeds the current available funding amount specified herein, except at the Contractor’s own risk.**

Order Level Materials (OLM) under SIN 70 500 are included as part of this BPA and may be applicable at the call order level for cloud services acquired in direct support of call order(s) placed against the BPA when the services are not known at the time of award of the BPA.

**Limitation of Funds**

The Contractor shall not provide services resulting in charges to the government that exceed obligated funds.  The contractor shall notify the Contracting Officer, and the COR, in writing, whenever it has reason to believe that in the next 90 days, the charges to the government will exceed 75% of the obligated funds for any current call orders issued. The government is not obligated to reimburse the Contractor for charges in excess of the obligated funds and the Contractor is not obligated to continue performance or otherwise incur costs that would result in charges to the government in excess of the amount obligated under this order. Alerting the government in this timeframe will allow the government to have additional funding approved internally so another order can be placed (as needed).

### 4.2 Pricing Transparency

Due to the constant downward pricing trend in commercial cloud services driven by new technology and competition, coupled with the absolute minimum level of value-add services requested of the reseller in this PWS, the metered CSP service unit cost paid by TTS under this requirement shall never exceed the commercial CSP unit pricing published on the CSP commercial website that is effective at the time the unit of service is consumed by TTS. The same requirement exists for non-metered awarded CSP services consumed by TTS as applicable.
 
While the awarded CSPs published unit pricing shall never be exceeded under this requirement, and TTS understands the reseller must maintain an adequate margin as a business necessity, TTS encourages the reseller to offer subsequently increasing discounts for TTS as the reseller market for the awarded CSPs becomes more competitive, TTS resource consumption increases under this requirement, and the resellers processes for meeting the requirements of the delivery become more refined and efficient.
 
Since TTS users of information technology are both extremely aware of published pricing and very sensitive about ensuring TTS receives the best possible pricing, in addition to meeting all other PWS requirements, the reseller’s minimum discount percentage of the awarded CSPs and subsequent additional discounts throughout the life of the order (as applicable) presents a prime opportunity for the reseller to be viewed as responsive to the TTS requirement on an on-going basis. Furthermore, TTS will constantly be assessing the dynamic cloud services marketplace on behalf of TTS’ user base to ensure this requirement remains the best possible vehicle for, cost-wise and other, acquiring CSP services to meet the Agency’s very diverse needs.

### 4.3 Consolidating Billing

The reseller shall provide TTS with consolidated billing services for all awarded CSP Master and Member Accounts under this requirement and new awarded CSP Accounts provisioned during this requirement period of performance. Consolidated billing services and all related capabilities shall be ready for TTS access within five (5) business days of requirement award.
 
Upon request by TTS, and at no additional cost, the reseller shall also provide consolidated billing services, after transfer of the account, for existing CSP Accounts used by TTS directly or used indirectly by TTS through other arrangements with other resellers, integrators, or federal contractors as applicable. Requests to transfer existing applicable CSP Master and Member Accounts will include coordination by TTS with the existing CSP owner, including ensuring their approval, cooperation, and involvement in CSP Account transfer steps. 
 
Upon provisioning of a new awarded CSP Master or Member Account for TTS or completing the transfer of an existing CSP Account (associated with TTS use through another arrangement as indicated above) for the purposes of the reseller providing consolidated billing services, TTS will be responsible for all subsequent costs incurred within the Account(s). Additionally, all pricing, terms and conditions associated with award of this requirement will apply to all CSP Accounts for which consolidated services are provided. The reseller shall not discontinue consolidated billing services for a TTS CSP Account within the terms of the requirement without TTS approval.
 
The reseller shall support multiple awarded CSP Master Accounts for TTS exclusive to managing the payment of TTS CSP Member Accounts. The reseller shall not associate any non-TTS CSP Member Accounts within TTS Master Accounts and shall not associate any TTS member accounts with any master account not dedicated exclusively to TTS.
 
TTS will be solely responsible for configuring all Service Control Policy (SCP) and Identity and Access Management (IAM) access to CSP Billing and Cost Management Resources involving TTS. This includes access by member accounts and tools used by member accounts, some of which may be third party cloud management tools.
 
The reseller shall never provide a non-TTS entity, individual, or commercial Software-as-a-Service (SaaS) tool with access to TTS CSP account cost information without written approval by TTS’ Contracting Officer or delegated COR.
 
TTS envisions an increasing number of TTS CSP Master Accounts will be required throughout the term of the requirement to separate and organize accounts associated with a diverse number of missions, projects, and programs. The reseller shall provide additional TTS CSP Master Accounts upon request at no additional charge. TTS requests for new CSP Master Accounts shall be provisioned by the reseller within three business days. The number of Member Accounts that may be managed by the reseller for purposes of consolidated billing is estimated at 300-5,000, although the actual count may be higher or lower.

## 4.4 CSP Account Holder Information

For all intents and purposes, TTS shall be considered the “Account Holder” of CSP Linked/Member Accounts, under TTS’s Dedicated Master Payer Account(s), supported under this requirement, with all associated rights and responsibilities, excluding the direct payment to the awarded CSP, which will be the responsibility of the reseller as described in the requirement for Consolidated Billing. TTS’s role as the “Account Holder” explicitly includes TTS’s unrestricted and exclusive rights and ownership of all data placed into the Accounts by TTS, all TTS-developed and TTS-licensed software operating within the Account, and all mechanisms configured, constructed, or developed by TTS for purposes of operating TTS workloads, applications, and services within the Account.
 
No system integration services are being acquired via this award such that the reseller would be required, or be allowed, to develop, apply, or create reseller intellectual property to configure, operate, or support TTS data, TTS workloads, TTS applications, and TTS services within TTS CSP Accounts. As a condition of award acceptance, the reseller agrees it will not subsequently claim ownership of, nor intellectual and other types of property rights to, any of the above assets operating within a TTS CSP Account for which the reseller is providing consolidated billing services and will help TTS transfer all data when the order ends.

## 4.5 Administrative Account Transfer

TTS intends to acquire cloud services under this requirement up to the value and duration stated, subject to demand. However, TTS retains the right, no sooner than one year after requirement award, to administratively transfer, with at least 60-days notice, its CSP Accounts to another reseller, integrator, federal contractor, or federal agency should TTS determine this is in the Government’s best interest.
 
In order to accomplish the seamless transfer of a TTS CSP Linked Account to another reseller (in the event this should ever be required by TTS before the end of the BPA), the reseller agrees to support TTS’s execution of the account transfer at no additional cost.
 
Similarly, the reseller shall facilitate the transfer of all TTS CSP accounts in the manner indicated above when either the term or the estimated dollar value of the BPA is reached. Reseller shall deliver the data, at no extra cost and in a format of TTS’ choosing, no more than 30 days after the Contracting Officer’s written notification. 

## 4.6 United States Based Ownership, Location, and Staffing

TTS requires a reseller entity that is U.S. owned, will administer the requirement only from a United States based location, and only assign U.S citizens to administer the requirement (i.e., provide consolidated billing services and provision Master Accounts). 

## 4.7 Percentage Discounts

The percent (%) discount applies to the CSP’s entire catalog of commercial services and ancillary services provided. 

The percent discount shall be fixed as a minimum discount percentage at the time of award for each period of performance, but TTS encourages the reseller to offer subsequently increasing discounts that apply to the awarded CSPs throughout the life of the order as the reseller market for the awarded CSPs becomes more competitive, TTS resource consumption increases under this requirement, and/or the reseller’s processes for meeting the requirements of the delivery become more refined and efficient. A resellers ability to increase the discount throughout the life of the order would result in favorable comments within a CPARs, among other items.

Cloud services consumed by TTS may be significantly less than the estimated ceiling quantities and/or the amount actually funded. As such, any percentage discount should address the strong possibility that the actual invoice to TTS may fluctuate from month to month based on actual consumption and usage.  TTS will not accept discounts tied to minimum monthly invoiced amounts.

Since TTS users of information technology are both extremely aware of published pricing and very sensitive about ensuring TTS receives the best possible pricing, in addition to meeting all other PWS requirements, the reseller’s minimum discount percentage of the awarded CSP and subsequent additional discounts throughout the life of the order (as applicable) presents a prime opportunity for the reseller to be viewed as responsive to the Agency requirement on an on-going basis. Furthermore, TTS will constantly be assessing the dynamic cloud services marketplace on behalf of the TTS user base to ensure this requirement remains the best possible vehicle for, cost-wise and other, acquiring CSP services to meet the Agency’s very diverse needs.

TTS requires a minimum discount percentage across all CSPs that would be credited by the reseller on each monthly invoice based on the total amount of resources consumed and invoiced to TTS for the month per CSP. This will enable any discount to be immediately realized by individual TTS customers instead of waiting for particular cost thresholds to be met in future months, since it is possible the customer may have completed their use of any of the CSPs by the time the credits are applied by the reseller. 

## 4.8 CSP Commercial Rates

Any price drop of commercial pricing during any period of performance becomes effective at the same time the drop becomes effective with the CSP. During any period of performance, the contractor shall supply their Schedule Contract (or other catalog pricing tool/dashboard if TTS doesn’t already have native access) prices for each CSP upon request within three business days.

By submission of the quote, contractors understand that rates may not exceed commercial public cloud rates for the quoted and awarded CSPs available at any time in the period of performance, or the rates stated within their Schedule Contract approved pricing sheets. 

Vendors should assume the monthly invoice costs are all encompassing, including any awarded CSP, Reserved Instance purchases (as applicable), and potentially any cloud service available from the awarded CSP. 

### 4.9 Unused Funds

Unused or excess funds not invoiced may be deobligated from one call order and obligated to another call order if the funds are still valid for obligation and a bona fide need exists.

                                                                       Example

If during Call Order 1, the government funds $2,000,000, but, after all invoices have been submitted for the order, the actual invoiced amount is $1,700,000, that leaves $300,000 in unused funding.

If those funds are still eligible to be obligated in the relevant fiscal year, and a bona fide need still exists, TTS may, via modification, deobligate those funds to another Call Order (as applicable) so the funding does not go unused.

### 4.10 Government Furnished Information

None, unless otherwise requested.

### 4.11 Contractor Furnished Property/Equipment/Information

None, other than access to the CSPs.

