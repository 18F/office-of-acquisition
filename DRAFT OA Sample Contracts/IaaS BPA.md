[Related RFQ](https://github.com/18F/office-of-acquisition/blob/master/DRAFT%20OA%20Sample%20RFQs/IaaS%20RFQ.md)

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

### 4.4 CSP Account Holder Information

For all intents and purposes, TTS shall be considered the “Account Holder” of CSP Linked/Member Accounts, under TTS’s Dedicated Master Payer Account(s), supported under this requirement, with all associated rights and responsibilities, excluding the direct payment to the awarded CSP, which will be the responsibility of the reseller as described in the requirement for Consolidated Billing. TTS’s role as the “Account Holder” explicitly includes TTS’s unrestricted and exclusive rights and ownership of all data placed into the Accounts by TTS, all TTS-developed and TTS-licensed software operating within the Account, and all mechanisms configured, constructed, or developed by TTS for purposes of operating TTS workloads, applications, and services within the Account.
 
No system integration services are being acquired via this award such that the reseller would be required, or be allowed, to develop, apply, or create reseller intellectual property to configure, operate, or support TTS data, TTS workloads, TTS applications, and TTS services within TTS CSP Accounts. As a condition of award acceptance, the reseller agrees it will not subsequently claim ownership of, nor intellectual and other types of property rights to, any of the above assets operating within a TTS CSP Account for which the reseller is providing consolidated billing services and will help TTS transfer all data when the order ends.

### 4.5 Administrative Account Transfer

TTS intends to acquire cloud services under this requirement up to the value and duration stated, subject to demand. However, TTS retains the right, no sooner than one year after requirement award, to administratively transfer, with at least 60-days notice, its CSP Accounts to another reseller, integrator, federal contractor, or federal agency should TTS determine this is in the Government’s best interest.
 
In order to accomplish the seamless transfer of a TTS CSP Linked Account to another reseller (in the event this should ever be required by TTS before the end of the BPA), the reseller agrees to support TTS’s execution of the account transfer at no additional cost.
 
Similarly, the reseller shall facilitate the transfer of all TTS CSP accounts in the manner indicated above when either the term or the estimated dollar value of the BPA is reached. Reseller shall deliver the data, at no extra cost and in a format of TTS’ choosing, no more than 30 days after the Contracting Officer’s written notification. 

### 4.6 United States Based Ownership, Location, and Staffing

TTS requires a reseller entity that is U.S. owned, will administer the requirement only from a United States based location, and only assign U.S citizens to administer the requirement (i.e., provide consolidated billing services and provision Master Accounts). 

### 4.7 Percentage Discounts

The percent (%) discount applies to the CSP’s entire catalog of commercial services and ancillary services provided. 

The percent discount shall be fixed as a minimum discount percentage at the time of award for each period of performance, but TTS encourages the reseller to offer subsequently increasing discounts that apply to the awarded CSPs throughout the life of the order as the reseller market for the awarded CSPs becomes more competitive, TTS resource consumption increases under this requirement, and/or the reseller’s processes for meeting the requirements of the delivery become more refined and efficient. A resellers ability to increase the discount throughout the life of the order would result in favorable comments within a CPARs, among other items.

Cloud services consumed by TTS may be significantly less than the estimated ceiling quantities and/or the amount actually funded. As such, any percentage discount should address the strong possibility that the actual invoice to TTS may fluctuate from month to month based on actual consumption and usage.  TTS will not accept discounts tied to minimum monthly invoiced amounts.

Since TTS users of information technology are both extremely aware of published pricing and very sensitive about ensuring TTS receives the best possible pricing, in addition to meeting all other PWS requirements, the reseller’s minimum discount percentage of the awarded CSP and subsequent additional discounts throughout the life of the order (as applicable) presents a prime opportunity for the reseller to be viewed as responsive to the Agency requirement on an on-going basis. Furthermore, TTS will constantly be assessing the dynamic cloud services marketplace on behalf of the TTS user base to ensure this requirement remains the best possible vehicle for, cost-wise and other, acquiring CSP services to meet the Agency’s very diverse needs.

TTS requires a minimum discount percentage across all CSPs that would be credited by the reseller on each monthly invoice based on the total amount of resources consumed and invoiced to TTS for the month per CSP. This will enable any discount to be immediately realized by individual TTS customers instead of waiting for particular cost thresholds to be met in future months, since it is possible the customer may have completed their use of any of the CSPs by the time the credits are applied by the reseller. 

### 4.8 CSP Commercial Rates

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

## 5.0 Call Order/Contract Administration

### 5.1 Government Points of Contact

After initial BPA award, the government will share information related to the Contracting Officer and Contracting Officer Representative and their respective contact information.

This acquisition will be administered by the following points of contact (POCs), who will also monitor the contractor’s performance:

  1.	Contracting Officer (CO): Stephen Carroll
  2.	Contracting Officer Representative (COR): TBD at time of award

If a change occurs to either the CO or COR, the government will notify the contractor. Specifically for the COR, the contractor will receive a copy of ‘COR Delegation of Authority” assignment letter when a COR is assigned, and the contractor will also receive a letter rescinding the COR delegation when appropriate.

It is expected that the CO and COR for the BPA will also be the same CO and COR for each order, however, others may assume those roles.

### 5.2 Contractor Point(s) of Contact

At a minimum, the Contractor shall identify at least one person that:
* Has a full understanding of the technical solution presented through the Contractor’s quotation and delivered after award;
* Will be a direct liaison to the GSA POCs whom the Government can reach out to with any questions or concerns about the administration of the contract.

The Vendor must provide a single point of contact, whether an email address or individual, that can be contacted by GSA with any questions or concerns about the contract throughout the POP. This single point of contact is not to be considered Key Personnel. The information shall be uploaded through the ITSS Collaboration tool.

### 5.3 Post Award Orientation Conference

The government's team, CO/COR, and the TTS Product Owner will hold a kickoff meeting/post-award conference with the selected contractor within 10 calendar days of the BPA award for the AWS BPA. This kickoff will include the selected contractor’s team and other relevant government staff to review and clarify the project’s objectives, expectations from the government, and address any questions the selected contractor may have.

For a BPA awarded for any FedRAMP Authorized CSP other than AWS, a kickoff will be held prior to when TTS has funding available for that CSP (if and when applicable).

### 5.4 Inspection and Acceptance

At time of award, the inspection and acceptance terms and conditions of the awardees Schedule Contract will apply.

### 5.5 Contractor Performance

In accordance with FAR 8.406-7 and FAR 42.1502(c), Past performance evaluations shall be prepared at least annually and at the time the work under the BPA or order is completed (to include options of the BPA) when an order, individually, exceeds the simplified acquisition threshold. These evaluations are generally for the entity, division, or unit that performed the contract or order. Past performance information shall be entered into CPARS, the Governmentwide evaluation reporting tool for all past performance reports on contracts and orders.

### 5.6 Invoicing

Note - As the BPA vehicle does not have attached funding, the information contained within this invoicing section shall apply and flow-down to Call Orders issued against the BPA. 

Note 2 - Please note the LiSaaS requirements in Section 5.7. LiSaaS ATO shall be approved prior to acceptance of any invoicing.

The contractor shall submit a proper invoice on a monthly basis in arrears (no later than five business days of the end of the month) based on actual usage minus applicable discounts. 

#### 5.6.2 Content of Invoice

The contractor will be provided with the following information when the Call Order has been awarded:

* GSA Call Order Number
* QP Number (funding document number)
* Prompt Payment Discount
* Remittance Address
* POP for Billing Period
* POC and Phone Number
* Invoice Amount
* Invoice Marked as ‘Final’
* Name of CSPs matching award documents.
* Via the CLIN structure outlined in the Call Order
* Complete invoice breakout and consolidated billing information
* Clear reflection of percent discount application to invoice

All of this information, along with the Period of Performance covered by the invoice, must be included on each invoice in addition to the requirements for a proper invoice.

All of this information must be included on each invoice in addition to the requirements for a proper invoice specified in FAR 52.212-4 (g) and the Prompt Payment clause, FAR 52.212-4(i)(2).

The contractor will be expected to provide GSA TTS with a detailed consolidated monthly billing statement. The detailed billing statement will be provided for individual accounts and summarized at the master account level.
  
The consolidated detailed monthly billing will include usage data and billing discounts (for each account), as well as direct access to the awarded CSP consoles for the raw billing data. TTS does not prefer or desire 3rd party billing or dashboard tools.

TTS makes no guarantee or commitment to quantity. 

All invoices for each period of performance shall be submitted no later than 30 days after the end of the period of performance so that the performance period can be closed and unused ceiling and/or unused funding can be rolled forward as applicable in either case. After 30 days, the Government will consider all invoicing to be completed and the CLINs related to the period of performance shall be closed.

The contractor must submit a final invoice within 30 calendar days after contract completion. No further charges are to be billed following the final invoice submission. 

#### 5.6.3 Invoice Submission

The Contractor shall submit invoices for this contract/order through the GSA Office of the Chief Financial Officer, Vendor and Customer Self Service (VCSS) web portal [https://vcss.ocfo.gsa.gov](https://vcss.ocfo.gsa.gov/).

The funding reference to use when submitting invoices is the QP number referenced in the Call Order. Invoices submitted by the contractor in VCSS shall not contain any characters other than simply numbers and letters.

Billing and payment shall be accomplished in accordance with contract terms and GSA payment procedures. 

If you have problems submitting your invoice, please contact one of the following, as applicable.

**VCSS General System, Login ID, Password Issues**
	GSA Financial Systems Service Desk:
	Ph: 866-450-6588
	Email: OCFOServiceDesk@gsa.gov

**Invoice & Payment Related Questions**
	BCEB Help Desk:
	Ph: 800-676-3690, Opt 3

Fax: (816)926-7800
	Email: kc-accts-payable.finance@gsa.gov

**VCSS Inquiries with Invoicing Issues**
	Email: kc-acctspayable.vcss@gsa.gov
 
 ### 5.7 Termination for Cause

If a CSP is delivered, but it does not conform to the order requirements, GSA shall take appropriate action in accordance with the inspection and acceptance clause of the contract, as supplemented by the order. If the contractor fails to perform an order or take appropriate corrective action, GSA may terminate the order for cause or modify the order to establish a new delivery date (after obtaining consideration, as appropriate). GSA shall follow the procedures in FAR 8.406-4 when terminating an order for cause. The Contracting Officer must send a cure notice prior to terminating an order for a reason other than late delivery. A cure notice is not needed when the reason for termination is late delivery. If the time remaining in the order delivery schedule is not sufficient to permit a realistic cure period of 10 days or more, the cure notice should not be issued and the performance period should be allowed to expire. 

Note: The successful contractor must agree to comply with Low Impact Software-as-a-Service (LiSaaS) requirements and once the BPA is awarded achieve LiSaaS ATO prior to invoicing the government for services received under this BPA. And then no later of 1 year from date of award, they must achieve at least FedRamp Low (Tailored)  ATO. If not, the BPA will be terminated. A link to CIO-IT-09-48 (“IT Security Procedural Guide: Security and Privacy IT Acquisition Requirements”) is contained in Section 6.5. of this document.

Once the contractor receives the cure notice, the contractor has the opportunity to remedy the problem.

The Contracting Officer may terminate individual orders for cause. The GSA shall notify the Schedule Contracting Officer of all instances of termination for cause of individual orders or if fraud is suspected. If the contractor asserts that the failure was excusable, the Contracting Officer shall follow the procedures in FAR 8.406-6, as appropriate. 

The ordering activity's Contracting Officer must report any terminations for cause to FAPIIS. See FAR 8.406-4(e) and 42.1503(f). 

### 5.8 Termination for Convenience

FAR 8.406-5 permits the Contracting Officer to terminate individual orders for the convenience of the government when it is in the government’s best interest. Terminations for convenience must comply with FAR 12.403. 

### 5.9 Transition Activities

For the AWS BPA, the contractor will be provided a two-week transition period (after the kick-off meeting). During the transition, the Vendor will be required to perform all necessary transition activities. Expected transition activities will include, but not be limited to:

* Continuation of full services to TTS and customers.
* Assistance with planning projections and purchasing units in the most advantageous manner

Also see Section 4.5 of this BPA.

### 5.10 Travel

No travel is anticipated or will be required as part of this order.

### 5.11 Quality Assurance

#### 5.11.1 Place of Inspection and Acceptance

Inspection and acceptance of all deliverables under this BPA/associated orders will be performed by the COR. The Vendor must deliver all items to the satisfaction of GSA TTS.  The COR will review the Monthly Cost Reports and all reports submitted by the Vendor to GSA to ensure compliance with this requirement and provide written feedback, if any, concerning the services during the performance of the BPA/associated orders. 

#### 5.11.2 Nonconforming Product and Services

Non-conforming services will be rejected. If the deficiencies cannot be corrected within ten (10) business days, the Vendor will immediately notify the COR of the reason for the delay and provide a proposed corrective action plan within five (5) work days.

#### 5.11.3 Contractor Performance

In accordance with FAR 42.1502(c), past performance evaluations shall be prepared at least annually and at the time the work under the BPA/associated orders are completed when an order, individually, exceeds the simplified acquisition threshold. These evaluations are generally for the entity, division, or unit that performed the contract or order. Past performance information shall be entered into CPARS, the Governmentwide evaluation reporting tool for all past performance.

##### Quality Assurance Surveillance Plan

1. PURPOSE

This Quality Assurance Surveillance Plan (QASP) provides a systematic method for evaluating the performance of the reseller.  This QASP explains the following:
 
* What will be monitored.
* How monitoring will take place.
* Who will conduct the monitoring.
* How monitoring efforts and results will be documented.

2.  This QASP does not detail how the Vendor accomplishes the work.  Rather, the QASP is created with the premise that the Vendor is responsible for management and quality control actions to meet the terms of the order.  It is the Government’s responsibility to be objective, fair, and consistent in evaluating performance.  In addition, the QASP should recognize that unforeseen and uncontrollable situations may occur.

3.  This QASP is a “living document”. Either prior to award with the apparently successful Vendor and/or at the kickoff, the Government intends to work collaboratively with the Vendor on better defining (as applicable) the performance areas listed below. The Government may review and revise it on a regular basis.  However, the Government will coordinate changes with the contractor.  Updates shall ensure that the QASP remains a valid, useful, and enforceable document.  Revisions shall be provided to the contractor and Government officials implementing surveillance activities and will be modified into the order.

**Performance Objectives** | **Performance Standards** | **Method of Surveillance** | **Acceptable Quality Levels** | **Incentive/
Disincentive**
------------ | -------------  | -------------  | ------------- | -------------
Monthly Invoices	| Invoices shall be submitted within five business days of the end of the month. | Reviewing the date of the Invoice submission in the GSA invoicing portal of record. Monitored by both the CO and COR | At least 11 of 12 months of submitted invoices per period of performance are submitted within the performance standard	| CPARs Ratings and Narrative

End of the Period of Performance Invoices |	All invoices for the period of performance just ending shall be submitted within 30 days after the end of the period of performance | Reviewing the GSA invoicing portal of record. Monitored by both the CO and COR | 100% within the performance standard |	CPARs Ratings and Narrative and the related CLIN for the period of performance will be closed

Final Invoice	| The contractor must submit a final invoice within 30 calendar days after contract completion. |	Reviewing the GSA invoicing portal of record.
Monitored by both the CO and COR	| 100% within the performance standard |	CPARs Ratings and Narrative and the related CLIN for the period of performance will be closed

Provisioning	| TTS requests for new awarded CSP Master accounts shall be provisioned by the reseller within three business days |	Confirming the date of request email to the Vendor’s confirmation of provisioning and the Government acceptance of the account. | No less than 96% provisioned within three business days	| CPARs Ratings and Narrative

Supplying Rates	| During any period of performance, the Vendor shall supply their Schedule Contract (or other catalog pricing tool/dashboard if TTS doesn’t already have native access) prices for each CSP upon request within three business days. | Confirming the date of request email to the Vendor’s submission. Monitored by the COR | No less than 96% within the performance standard	CPARs Ratings and Narrative

Trend analysis for billing and usage to support planning and funding efforts |	At least twice per period of performance |	Confirming the Vendor’s submission. Monitored by both the CO and COR	| 100% within the performance standard |	CPARs Ratings and Narrative

Consolidated Billing Services |	Consolidated billing services and all related capabilities shall be ready for TTS access within five (5) business days of requirement award.	| Government shall confirm with the Vendor via email that consolidated billing services and all related capabilities are ready with performance standard. Monitored by the COR and underlying root account users	| No errors. Capabilities are ready within the performance standard	| CPARs Ratings and Narrative

4.  QUALITY SURVEILLANCE METHOD

The government has defined the performance measures (see above) which will be monitored through surveillance of contractor activity, review of system reports, and resultant services.

##### 5.11.4 Service Level Agreements

The commercial Service Level Agreement (SLA) with each CSP shall be incorporated into the BPA (once reviewed and accepted by TTS) and serve as part of the quality assurance control plan (QASP). The TTS team, including mainly the COR, will monitor CSP performance against the SLA.

Where a Commercial SLA with each CSP is not available, or silent in any of the areas below, the SLAs shall reflect at a minimum:

* Response time (for tier 1 - tier 3 support, request/completion fulfillment, etc)
  * Where the current commercial SLA does not specify, response time shall be no longer than 24 hours from time of request.

* Response time related to billing/payment inquiries 
  * Where the current commercial SLA does not specify, response time shall be no longer than 24 hours from time of request.

* Reports (filtered by accounts)
   * Where the current commercial SLA does not specify, response time shall be no longer than 24 hours from time of request.

* Ability to measure the uptime percentage performance and define how uptime is calculated
   * Where the current commercial SLA does not specify, monthly uptime percentage is calculated by subtracting from 100% the average of the Error Rates from each 5-minute interval in the monthly billing cycle.

* Detail remedies that CSPs would pay to the agency if the CSP did not meet uptime requirements in accordance with NIST SP 800-146.
* Where the current commercial SLA does not specify -
  * anything less than 95.0% uptime shall receive a 100% service credit, 
  * less than 99.0%, but greater than or equal to 95.5% shall receive a 50% service credit, and 
  * less than 99.9%, but greater than or equal to 99.0% shall receive a 25% credit.

* Automated tool to monitor and measure actual uptime and compare it to the uptime percentage specified in the order, and pursue credits when applicable in accordance with NIST SP 800-146.

## 6.0 Terms and Conditions 

**Terms and conditions previously negotiated and awarded on the contractor’s Schedule shall apply in addition to the below.**

### 6.1 TTS Transparency Policy

Vendors are advised that TTS reserves the right to publish documents associated with this acquisition on a publicly-available website, including any Requests for Quotation or their amendments, as well as question and answer exchanges with contractors without source-identifying information removed. TTS reserves the right to publish any other relevant information that is not confidential or proprietary in nature, but will not publish any source selection sensitive information that would otherwise implicate procurement integrity concerns.

Upon award of the acquisition, TTS may publish the total price of the selected proposal and certain non-source-identifying data (e.g. the number of bids, the mean price, the median, and the standard deviation of price). During the performance of the BPA, TTS may similarly publish data related to project management (e.g. user stories, milestones, and performance metrics) and top-line spending data.

### 6.2 Section 508 Compliance

The Contractor shall support the government in its compliance with Section 508 throughout the development and implementation of the work to be performed.

Section 508 of the Rehabilitation Act of 1973, as amended (29 U.S.C. 794d) requires that when Federal agencies develop, procure, maintain, or use electronic information technology, Federal employees with disabilities have access to and use of information and data that is comparable to the access and use by Federal employees who do not have disabilities, unless an undue burden would be imposed on the agency. Section 508 also requires that individuals with disabilities, who are members of the public seeking information or services from a Federal agency, have access to and use of information and data that is comparable to that provided to the public who are not individuals with disabilities, unless an undue burden would be imposed on the agency.

Schedule products and services were already verified at the Schedule level.

### 6.3 Data Rights and Ownership of Deliverables

Terms and conditions previously negotiated and awarded on the contractor’s Schedule shall apply.

The government intends that any software source code created as a result of the work performed under the BPA be publicly posted. Accordingly, FAR 52.227-17 (Rights in Data -- Special Works) will be included in the solicitation

The government shall have unlimited rights in any data or deliverable created as a result of the work performed under the purchase order, including the output of SaaS analytics reports and dashboards.

The contractor shall use open source technologies wherever possible, in support of the [18F source code policy](https://18f.gsa.gov/open-source-policy/). All licenses must be expressly listed in the deliverable. Regardless of license(s) used (i.e., MIT, GPL, Creative Commons CC0), the license(s) shall be clearly listed in the documentation.

If an open source license provides implementation guidance, the contractor shall ensure compliance with that guidance. If implementation guidance is not available, the contractor shall attach or include the license within the work itself. Examples of this include code comments at the beginning of a file or contained in a license file within a software repository.

### 6.4 Requirements for GSA Information Systems

* ●	If the reselling contractor provides their own applications, tools, or dashboards other than the native applications, tools, or dashboards by the awarded CSPs, the contractor shall first notify the TTS Contracting Officer and Contracting Officer’s Representative. If approved by the CO and COR, the applications, tools, or dashboards (system) are subject to the requirements of Section 2 of GSA’s guide Security and Privacy Requirements for IT Acquisition Efforts [CIO-IT Security 09-48, Rev. 4] 01/25/2018 (and any future update of the guide) on a conditional basis.

* Security
  * Option to select CSP data hosting regions to restrict geographic boundaries, such as CONUS only regions for data availability
  * Ability to verify where data is located at any point in time
  * Meet regulatory compliance requirements throughout the life of the contract

* FedRAMP

If there is any conflict between the information below and the information from the CSPs FedRAMP Authorization, the FedRAMP Authorization information shall lead.

  * The CSP sought under this requirement is required to be in conformance with the FedRAMP Program for services designated as being authorized by the FedRAMP Program.  Continued use of the CSP services is contingent upon the CSP’s on-going adherence to the FedRAMP Program and its Continuous Monitoring requirements for all services authorized under the FedRAMP Program.  Due to the rapid and continuous release of new services, there is often a significant period of time between when a CSP service is available and when it is authorized under the FedRAMP Program. 
  
  The FedRAMP Standard Requirements specifies the types of notifications required from a CSP to the Government.  Below are additional TTS requirements related to planned and scheduled maintenance, emergency maintenance and incident communications and responses.

  * Planned and Scheduled Maintenance/Update of Hardware and Software
  
  The reseller shall make arrangements with TTS to ensure that any planned maintenance that will affect TTS’s ability to use the CSP’s services is communicated with TTS in advance, with as much lead time as possible.  TTS will also monitor the appropriate CSP web pages to maintain an awareness of scheduled maintenance affecting CSP resources and will take the appropriate operational steps to minimize impact and accommodate the scheduled maintenance.

  * Emergency Maintenance/Update of Hardware and Software
  
  The reseller shall communicate with TTS in advance, with as much lead time as possible to ensure they are aware of any emergency or unscheduled maintenance that will affect TTS’s ability to use the CSP services.  The reseller’s communications to TTS should be emailed to the COR and should provide:
    * Primary and alternate reseller points of contract for TTS to communicate with
    * Emergency maintenance progress
    * Notification when the activity is complete 

  * Incident Communications and Responses
  
  As TTS increasingly relies on the use of CSP services, TTS must be absolutely certain that it will be promptly and adequately notified in the event of an incident that potentially will or is known to affect TTS cloud resources. TTS will continuously assess CSP posture via existing mechanisms under the FedRAMP Program which are designed to ensure CSPs are operating in a manner consistent with Federal security requirements, including Incident Communications and Response.  Notwithstanding the FedRAMP JAB’s documented Incident Communications Procedure for their current FedRAMP JAB PATOs, in the event of an incident, TTS prefers the most direct communication path between the CSP (or reseller) to eliminate delays in notification and response. TTS will continually assess the effectiveness of the CSP’s role in the FedRAMP Incident Communications and Response approach.  Due to the importance of IT security and maintenance of active PATOs, TTS reserves the right, at any time, to inform the CSP that TTS is discontinuing its use of the CSP services within a period of not less than 45 days.

  * For Incidents Involving a Suspected or Confirmed Security Threat or 	Compromise 
  
  The reseller shall communicate and coordinate with TTS using specified secured communications approach and protocol agreed upon in advance by TTS and the reseller. Information shall be provided that enables TTS to effectively assess the incident for purposes of understanding which resources may be affected and determining appropriate contingency mechanisms.

  * For Incidents Not Involving a Suspected or Confirmed Security Threat or Compromise
  
  The reseller shall communicate and coordinate with TTS in a way that is consistent with notifications provided to other federal government customers.  Information shall be provided that enables TTS to effectively assess the incident for purposes of understanding which resources may be affected and determining appropriate contingency mechanisms.

### 6.5 Assessment and Authorization (A&A) Activities

Governed by the terms of access allowed by the underlying infrastructure provider as defined in the IaaS’s FedRAMP A&A authorization package.
If the reselling contractor provides their own applications, tools, or dashboards other than the native applications, tools, or dashboards by the awarded CSPs, the contractor shall first notify the TTS Contracting Officer and Contracting Officer’s Representative. If approved by the CO and COR, the applications, tools, or dashboards (system) are subject to the requirements of Section 2 of GSA’s guide Security and Privacy Requirements for IT Acquisition Efforts [CIO-IT Security 09-48, Rev. 4] 01/25/2018 (and any future update of the guide) on a conditional basis.

### 6.6 Reporting and Continuous Monitoring
GSA’s Continuous Monitoring Strategy (CIO IT Security 12-66 Rev 2 - dated 10/10/2017) can be [found at this link](https://www.gsa.gov/policy-regulations/policy/information-integrity-and-access/it-security-procedural-guides).

### 6.7 Data Rights

The commercial Terms and Conditions (T&C) for CSP data rights will be accepted to the extent not inconsistent with Federal law or Government needs. The contractor shall submit any T&Cs intended to bind the Government if and when requested by the Contracting Officer for Government review and approval prior to award. See also Section 6.10 below. If any conflicts, Section 6.10 below shall prevail.

### 6.8 Data Privacy Requirements

**Best Practice:** Data Privacy Requirements
**Definition of Best Practice:** Ensure control of Account Root Credentials and Identity and Access Management

**Responsibility of TTS** | **Responsibility of Vendor** 
-------------  | -------------
Request new TTS CSP Master Accounts from Vendor.	| Provide TTS with temporary root credentials for their Accounts when new Master Accounts are requested by TTS
Accept temporary root credentials from Vendor for new TTS CSP Master Accounts and then immediately change the root credentials to eliminate Vendor root access to Master Accounts	| Operate without requiring Vendor reseller ability to access TTS CSP Master and Member Account capabilities and other Account information consolidated billing
Maintain all root credentials for TTS CSP Member Accounts	| Execute addendum to CSP reseller agreement for each TTS CSP account that requires TTS ownership of root credentials
Manage all Identity and Use multifactor authentication for TTS CSP Accounts where determined appropriate	| Establish additional TTS Master CSP accounts as requested by the TTS CO and/or COR
  | Use multifactor authentication for TTS provisioned IAM access to Billing and Cost Management Master Accounts
  | Do not provide any form of access or disclosure in response to an external or third party request for TTS information or resources used or operated within CSP without first receiving TTS approval
  
### 6.9 Data Privacy Requirements

The contractor shall implement the controls contained within the FedRAMP Cloud Computing Security Requirements Baseline and FedRAMP Continuous Monitoring Requirements for the full spectrum (Low, Moderate, High) impact systems (as defined in FIPS PUB 199). These documents define requirements for compliance to meet minimum Federal information security and privacy requirements for Low, Moderate, or High impact systems. The FedRAMP baseline controls are based on NIST Special Publication 800-53, Revision 4, “Security and Privacy Controls for Federal Information Systems and Organizations” (as amended), and also includes a set of additional controls for use within systems providing cloud services to the federal government.
The contractor shall generally, substantially, and in good faith follow FedRAMP guidelines and Security guidance. In situations where there are no procedural guides, the contractor shall use generally accepted industry best practices for IT security.
GSA may choose to cancel the contract and terminate any outstanding orders if the contractor, or the Cloud Services Provider it is reselling, has its FedRAMP authorization (Joint Authorization Board [JAB] Provisional or Agency) revoked and the deficiencies are greater than agency risk tolerance thresholds.
For more information, see GSA’s guide Security and Privacy Requirements for IT Acquisition Efforts [CIO-IT Security 09-48, Rev. 4] 01/25/2018. The guide, and any future updates, is hereby incorporated.

## 7.0 Clauses

All clauses included and accepted as part of the quoter’s Schedule Contract shall flowdown to this RFQ. In the event of any conflict between the Schedule contract and the BPA, the terms and conditions of the Contractor’s Schedules shall prevail over the BPA and Task Orders, except to the extent that any discounts established in the BPA or its orders take precedence over any Schedule contract higher prices.

**FAR 52.252-2 CLAUSES INCORPORATED BY REFERENCE (FEB 1998)**
This contract incorporates one or more clauses by reference, with the same force and effect as if they were given in full text. Upon request, the Contracting Officer will make their full text available. Also, the full text of a clause may be accessed electronically at this/these address(es): [https://www.acquisition.gov/browsefar](https://www.acquisition.gov/browse/index/far)

**52.204-25 Prohibition on Contracting for Certain Telecommunications and Video Surveillance Services or Equipment (AUG 2019)**

(a) Definitions. As used in this clause—
    
    “Covered foreign country” means The People’s Republic of China.
     
     “Covered telecommunications equipment or services” means–
           
           (1) Telecommunications equipment produced by Huawei Technologies Company or ZTE Corporation (or any subsidiary or affiliate of such entities);
          
          (2) For the purpose of public safety, security of Government facilities, physical security surveillance of critical infrastructure, and other national security purposes, video surveillance and telecommunications equipment produced by Hytera Communications Corporation, Hangzhou Hikvision Digital Technology Company, or Dahua Technology Company (or any subsidiary or affiliate of such entities);
           
           (3) Telecommunications or video surveillance services provided by such entities or using such equipment; or
           
           (4) Telecommunications or video surveillance equipment or services produced or provided by an entity that the Secretary of Defense, in consultation with the Director of National Intelligence or the Director of the Federal Bureau of Investigation, reasonably believes to be an entity owned or controlled by, or otherwise connected to, the government of a covered foreign country.
   
   “Critical technology” means–
          
          (1) Defense articles or defense services included on the United States Munitions List set forth in the International Traffic in Arms Regulations under subchapter M of chapter I of title 22, Code of Federal Regulations;
          
          (2) Items included on the Commerce Control List set forth in Supplement No. 1 to part 774 of the Export Administration Regulations under subchapter C of chapter VII of title 15, Code of Federal Regulations, and controlled-
                
                (i) Pursuant to multilateral regimes, including for reasons relating to national security, chemical and biological weapons proliferation, nuclear nonproliferation, or missile technology; or
               
               (ii) For reasons relating to regional stability or surreptitious listening;
          
          (3) Specially designed and prepared nuclear equipment, parts and components, materials, software, and technology covered by part 810 of title 10, Code of Federal Regulations (relating to assistance to foreign atomic energy activities);
           
           (4) Nuclear facilities, equipment, and material covered by part 110 of title 10, Code of Federal Regulations (relating to export and import of nuclear equipment and material);
           
           (5) Select agents and toxins covered by part 331 of title 7, Code of Federal Regulations, part 121 of title 9 of such Code, or part 73 of title 42 of such Code; or
          
          (6) Emerging and foundational technologies controlled pursuant to section 1758 of the Export Control Reform Act of 2018 (50 U.S.C. 4817).
     “Substantial or essential component” means any component necessary for the proper function or performance of a piece of equipment, system, or service.
      
      (b) Prohibition. Section 889(a)(1)(A) of the John S. McCain National Defense Authorization Act for Fiscal Year 2019 (Pub. L. 115-232) prohibits the head of an executive agency on or after August 13, 2019, from procuring or obtaining, or extending or renewing a contract to procure or obtain, any equipment, system, or service that uses covered telecommunications equipment or services as a substantial or essential component of any system, or as critical technology as part of any system. The Contractor is prohibited from providing to the Government any equipment, system, or service that uses covered telecommunications equipment or services as a substantial or essential component of any system, or as critical technology as part of any system, unless an exception at paragraph (c) of this clause applies or the covered telecommunication equipment or services are covered by a waiver described in Federal Acquisition Regulation [4.2104](https://www.acquisition.gov/far/part-4).
      
      (c) Exceptions. This clause does not prohibit contractors from providing—
          
          (1) A service that connects to the facilities of a third-party, such as backhaul, roaming, or interconnection arrangements; or
           
           (2) Telecommunications equipment that cannot route or redirect user data traffic or permit visibility into any user data or packets that such equipment transmits or otherwise handles.
      
      (d) Reporting requirement. (1) In the event the Contractor identifies covered telecommunications equipment or services used as a substantial or essential component of any system, or as critical technology as part of any system, during contract performance, or the Contractor is notified of such by a subcontractor at any tier or by any other source, the Contractor shall report the information in paragraph (d)(2) of this clause to the Contracting Officer, unless elsewhere in this contract are established procedures for reporting the information; in the case of the Department of Defense, the Contractor shall report to the website at [https://dibnet.dod.mil](https://dibnet.dod.mil/portal/intranet/). For indefinite delivery contracts, the Contractor shall report to the Contracting Officer for the indefinite delivery contract and the Contracting Officer(s) for any affected order or, in the case of the Department of Defense, identify both the indefinite delivery contract and any affected orders in the report provided at [https://dibnet.dod.mil](https://dibnet.dod.mil/portal/intranet/).
           
           (2) The Contractor shall report the following information pursuant to paragraph (d)(1) of this clause
                
                (i) Within one business day from the date of such identification or notification: the contract number; the order number(s), if applicable; supplier name; supplier unique entity identifier (if known); supplier Commercial and Government Entity (CAGE) code (if known); brand; model number (original equipment manufacturer number, manufacturer part number, or wholesaler number); item description; and any readily available information about mitigation actions undertaken or recommended.
                (ii) Within 10 business days of submitting the information in paragraph (d)(2)(i) of this clause: any further available information about mitigation actions undertaken or recommended. In addition, the Contractor shall describe the efforts it undertook to prevent use or submission of covered telecommunications equipment or services, and any additional efforts that will be incorporated to prevent future use or submission of covered telecommunications equipment or services.
      
      (e) Subcontracts. The Contractor shall insert the substance of this clause, including this paragraph (e), in all subcontracts and other contractual instruments, including subcontracts for the acquisition of commercial items.
**(End of clause)**

**GSAR clause 552.204-70 Representation Regarding Certain Telecommunications and Video Surveillance Services or Equipment (AUG 2019)**

(a) Definitions. As used in this clause “covered telecommunications equipment or services", "Critical technology", and “substantial or essential component" have the meanings provided in FAR 52.204-25, Prohibition on Contracting for Certain Telecommunications and Video Surveillance Services or Equipment. 

(b) Prohibition. Section 889(a)(1)(A) of the John S. McCain National Defense Authorization Act for Fiscal Year 2019 (Pub. L. 115-232) prohibits the head of an executive agency on or after August 13, 2019, from procuring or obtaining, or extending or renewing a contract to procure or obtain, any equipment, system, or service that uses covered telecommunications equipment or services as a substantial or essential component of any system, or as critical technology as part of any system. Contractors are not prohibited from providing- 

 (1) A service that connects to the facilities of a third-party, such as backhaul, roaming, or interconnection arrangements; or 

 (2) Telecommunications equipment that cannot route or redirect user data traffic or permit visibility into any user data or packets that such equipment transmits or otherwise handles.

 (c) Representation. [Contractor to complete and submit to the Contracting Officer] The Offeror or Contractor represents that it [ ] will or [ ] will not provide covered telecommunications equipment or services to the Government in the performance of any contract, subcontract, order, or other contractual instrument resulting from this contract. This representation shall be provided as part of the proposal and resubmitted on an annual basis from the date of award. 

(d) Disclosures. If the Offerer or Contractor has responded affirmatively to the representation In paragraph (c) of this clause, the Offeror or Contractor shall provide the following additional information to the Contracting Officer-- 

 (1) All covered telecommunications equipment and services offered or provided (include brand; model number, such as original equipment manufacturer (OEM) number, manufacturer part number, or wholesaler number; and item description, as applicable); 

 (2) Explanation of the proposed use of covered telecommunications equipment and services and any factors relevant to determining if such use would be permissible under the prohibition in paragraph (b) of this provision; 10 

 (3) For services, the entity providing the covered telecommunications services (include entity name, unique entity identifier, and Commercial and Government Entity (CAGE) code, if known); and 
 
 (4) For equipment, the entity that produced the covered telecommunications equipment (include entity name, unique entity identifier, CAGE code, and whether the entity was the OEM or a distributor, if known). 

**(End of clause)**

**FAR 52.217-8 Option to Extend Services (Nov 1999)**

The Government may require continued performance of any services within the limits and at the rates specified in the contract. These rates may be adjusted only as a result of revisions to prevailing labor rates provided by the Secretary of Labor. The option provision may be exercised more than once, but the total extension of performance hereunder shall not exceed 6 months. The Contracting Officer may exercise the option by written notice to the Contractor within one day of the option start.

**FAR 52.217-9 Option to Extend the Term of the Contract (Mar 2000)**

(a) The Government may extend the term of this contract by written notice to the Contractor within one calendar day before the contract expires; provided that the Government gives the Contractor a pre­liminary written notice of its intent to extend at least five calendar days before the contract expires. The preliminary notice does not commit the Government to an extension.

(b) If the Government exercises this option, the extended contract shall be considered to include this option clause.

(c) The total duration of this contract, including the exercise of any options under this clause, shall not exceed five years and six months (66 months).






