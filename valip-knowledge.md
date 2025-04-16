# Abstract

The VA Logistics and Integration (VALIP) Platform design offers a comprehensive set of agile
integration and messaging capabilities that provide service composition and orchestration, real -time
messaging, data streaming, and API management. Combined with a sophisticated container platform
and cloud native tool chain, it lets developers connect applications and data with a variety of internal
and external systems across hybrid architectures. The VALIP Platform offers a variety of integration
patterns natively to allow for flexible microservice composition, one of the core characteristics of the
platform is the eventing backbone that is a fundamental component of the platform. Enabled by the
policies, the inherent load latency problems common with most middleware solutions is eliminated.
The Supply Chain Management (SCM) VALIP Platform is designed to aid in the transformation of
the SCM legacy portfolio into composable microservices that are highly configura ble, interoperable,
and flexible, resulting in platform extensibility that enables adaptation to future business demands
and adoption of future technologies. VALIP pulls in Veteran, VA employees, and VA contractors
PII/PHI as part of the data standardization initiative to include employee and contractor First Name,
Last Name, Facility Address, Phone Number and Email Address. This information is stored within
VALIP and incorporates role-based access controls (RBAC) and other data security policies. Other
PHI/PII (i.e., Date of Birth, SSN, Veteran Full Name, Veteran Home Address, Veteran Email
address, Prescription Information, and Site-Specific Order Number) are supported in applications
hosted in VALIP. Access to this information is solely controlled by the application owner.

# Overview

The overview is the most important section of the PIA. A thorough and clear overview gives the reader
the appropriate context to understand the responses in the PIA. The overview should contain the
following elements:

## General Description
1. What is the IT system name and the name of the program office that owns the IT system?
VA Logistics Integration Platform (VALIP), VHA Health Enterprise & Logistics
Management (HELM).
1. What is the business purpose of the program, IT system, or technology and how it relates to
the program office and agency mission?
VA established the Healthcare Environment and Logistics Management (HELM) program
to lead the modernization of the VA supply chain product line. Recognizing the need for a
DevSecOps platform to support modernization efforts, the VA Logistics Integration
Platform (VALIP) was built as a single, data-driven, interoperable environm
DevSecOps pipeline, composable microservice architecture, integrated data fabric, and
Version date: October 1, 2023 security modernization serve as the foundation for modernizing
the VA supply chain. This digital transformation is essential in enabling a modern, connected
healthcare experience for veterans through faster, more secure, and costarchitecture
is helping to streamline the distribution of medical supplies and equipment
and yield significant cost savings. Its highly adaptable design not only facilitates
modernization within the VA supply chain but also enhances compatibility with other
advanced systems such as the VA Integrated Financial Management System (iFAMS) and
Enterprise Health Records Modernization (EHRM). By shortening delivery times,
minimizing expenses, and improving the utilization of IT initiatives, VALIP is paving the
way for a more efficient and integrated VA enterprise.
1. Who is the owner or control of the IT system or project?
VA Owned and VA Operated

## Information Collection and Sharing
1. What is the expected number of individuals whose information is stored in the system and a
brief description of the typical client or affected individual?
Currently there are 9,820,134 distinct individuals in the SSTAFF Table for VA Staff
All Veterans in VistA system.
1. What is a general description of the information in the IT system and the purpose for
collecting this information?
VALIP hosted applications connect to this data for analytics and reporting purposes.
The Data is for all current VA Staff and Patients.
1. What information sharing is conducted by the IT system? A general description of the
modules and subsystems, where relevant, and their functions.
4 SIGHT II Eyeglass Prescription Orders
VistA All Patient Data
SCDIO/SCMD Staff Data
1. Is the system is operated in more than one site, and if so, a description of how use of the
system and PII is maintained consistently in all sites and if the same controls are used across
sites?
Yes, For 4sight-II, depending on the site they will be supporting, the PII/PHI will be retrieved
on the identified sites using 4-sight-II application.

## Legal Authority and SORN
1. What is the citation of the legal authority to operate the IT system?
The information in VALIP so it is not a Privacy Act System of Record. The information
is obtained from the VHA Corporate Data Warehouse, which is maintained under Title 38,
United States Code, Section 501.
1. If the system is in the process of being modified and a SORN exists, will the SORN require
amendment or revision and approval? If the system is using cloud technology, does the SORN
for the system cover cloud usage or storage?
Version date: October 1, 2023
The information in VALIP is not searcha r and does not fall
under a Privacy Act SORN.

## System Changes
1. Will the completion of this PIA will result in circumstances that require changes to business
processes?
No

1. Will the completion of this PIA could potentially result in technology changes?
No

# Characterization of the Information

The following questions are intended to define the scope of the information requested and collected as
well as the reasons for its collection as part of the program, IT system, or technology being developed.

1. What information is collected, used, disseminated, created, or maintained in the system?
Identify and list all Sensitive Personal Information (SPI) that is collected and stored in the system,
including Individually Identifiable Information (III), Individually Identifiable Health Information (IIHI),
Protected Health Information (PHI), and Privacy- Protected Information. For additional information on
these information types and definitions, please see VA Directives and Handbooks in the 6500 series
(https://vaww.va.gov/vapubs/). If the system creates information (for example, a score, analysis, or
report), list the information the system is responsible for creating.
If a requesting system receives information from another system, such as a response to a background
check, describe what information is returned to the requesting system.
This question is related to privacy control AP-1, Authority To Collect, and AP-2, Purpose Specification.
The information selected below must match the information provided in question 2.1 as well as the data
elements columns in 4.1 and 5.1. It must also match the information provided in question 3.4 of the PTA.
Please check any information listed below that your system collects, uses, disseminates, creates, or
maintains. If additional SPI is collected, used, disseminated, created, or maintained, please list those in
the text box below:
Name
Social Security
Number
Date of Birth
Personal Mailing
Address
1 *Specify type of Certifica te or
License Number (e.g.,
Occupational, Education, Medical)
Personal Phone
Number(s)
Personal Fax Number
Personal Email
Address
Emergency Contact
Information (Name, Phone
Number, etc. of a different
individual)
Financial Information
Health Insurance
Beneficiary Numbers
Account numbers
Certificate/License
numbers1
Version date: October 1, 2023
Vehicle License Plate
Number
Internet Protocol (IP)
Address Numbers
Medications
Medical Records
Race/Ethnicity
Tax Identification
Number
Medical Record
Number
Gender
Integrated Control
Number (ICN)
Military
History/Service
Connection
Next of Kin
Other Data Elements
(list below)
Other PII/PHI data elements: Eye Prescription; Site Specific Order Number
PII Mapping of Components (Servers/Database)
VALIP consists of 3 key components (servers/databases/instances/applications/software/application
programming interfaces (API). Each component has been analyzed to determine if any elements of that
component collect PII. The type of PII collected by VALIP and the reasons for the collection of the PII
are in the table below.
Note: Due to the PIA being a public facing document, please do not include server names in the table.
The first table of 3.9 in the PTA should be used to answer this question.
Internal Components Table
Component
Name (Database,
Instances,
Application,
Software,
Application
Program
Interface (API)
etc.) that
contains PII/PHI
Does this
system collect
PII? (Yes/No)
Does
this
system
store
PII?
(Yes/No)
Type of PII (SSN,
DOB, etc.)
Reason for
Collection/
Storage of
PII
Safeguards
All access is
based on
Role-Based
Access
Controls
RBAC
InterSystems IRIS Yes Yes Phone Number
Contractor) Email
Address
Eye Care
Related
User/Role-
Based Access
Controls
Pass through
only VALIP
the data.
AWS Redshift Yes Yes Employee/Contractor
Full Name
Employee/Contractor
Email Address
Analytics on
purchases
User/Role-
Based Access
Controls
AWS S3 Yes Yes Employee/Contractor
Full Name
Employee/Contractor
Email Address
Analytics on
purchases
User/Role-
Based Access
Controls
Version date: October 1, 2023
1. What are the sources of the information in the system?
These questions are related to privacy controls DI-1, Data Quality, and IP-1, Consent.
1. List the individual, entity, or entities providing the specific information identified above. For
example, is the information collected directly from the individual as part of an application for a
benefit, or is it collected from other sources such as commercial data aggregators?
VHA Corporate Data Warehouse (CDW).
1. Describe why information from sources other than the individual is required? For example, if a
gregator of information or data taken from
public Web sites, state the fact that this is where the information is coming from and then in question
indicate why the system is using this source of data.
The information is obtained from CDW as it is the source that is connected to VistA
1. Does the system create information (for example, a score, analysis, or report), list the system as
a source of information?
There are analysis reports in the SCDIO Toolbox.
There are new reports being created to replicate existing fusion charts for SEPG.
1. How is the information collected?
These questions are related to privacy controls DI-1, Data Quality, and IP-1, Consent.
1. This question is directed at the means of collection from the sources listed in question 1.2.
Information may be collected directly from an individual, received via electronic transmission from
another system, or created by the system itself. Specifically, is information collected through
technologies or other technologies used in the storage or transmission of information in identifiable
form?
The data is extracted from the VHA Corporate Data Warehouse (CDW) using Talend in a
Extract Transform & Load (ETL) process.
1. If the information is collected on a form and is subject to the Paperwork Reduction Act, what is?
VALIP does not collect any PII/PHI on a form, therefore it is not subject to the
Paperwork Reduction Act.
1. How will the information be checked for accuracy? How often will it be checked?
These questions are related to privacy controls DI-1, Data Quality, and DI-2, Data Integrity and
Integrity Board.
1. Discuss whether and how often information stored in the system is checked for accuracy. Is
information in the system checked against any other source of information (within or outside your
organization) before the information is used to make decisions about an individual? For example, is
there a computer matching agreement in place with another government agency? For systems that
receive data from internal data sources or VA IT systems, describe the system checks to ensure that
data corruption has not occurred during transmission.
Version date: October 1, 2023
This information is provided from the source and is updated as changes are made to the
source system, changes are not made outside of the source-initiated changes, therefore all
responsibility for the validation of the accuracy of the data is on the source system data
Subject Matter Experts (SMEs).
1. Does the system check for accuracy by accessing a commercial aggregator of information,
describe this process and the levels of accuracy required by the contract?
VALIP uses information collected from other data systems. Accuracy is checked by those
systems before it is included in CDW.
1. What specific legal authorities, arrangements, and agreements defined the collection of
information?
List the full legal authority for operating the system, specifically the authority to collect the
information listed in question 1.1. Provide the authorities in a manner understandable to any
potential reader, i.e., do not simply provide a legal citation; use statute names or regulations in
addition to citations. Legal authorities include Federal laws, regulations, statutes, and Executive
Orders. This question is related to privacy control AP-1, Authority to Collect
Privacy Act System of Record. The information is obtained from the VHA Corporate
Data Warehouse, which is maintained under Title 38, United States Code, Section 501.
1. PRIVACY IMPACT ASSESSMENT: Characterization of the information
Consider the specific data elements collected and discuss the potential privacy risks and what steps,
if any are currently being taken to mitigate those identified risks. (Work with your System ISSO to
complete this section)
Consider the following Fair Information Practice Principles (FIPPs) when assessing the risk to
individual privacy:
Principle of Purpose Specification: Explain how the collection ties with the purpose of the
underlying mission of the organization and its enabling authority.
Principle of Minimization: Is the information directly relevant and necessary to accomplish the
specific purposes of the program?
Principle of Individual Participation: Does the program, to the extent possible and practical, collect
information directly from the individual?
Principle of Data Quality and Integrity: Are there policies and procedures for VA to ensure that
personally identifiable information is accurate, complete, and current?
This question is related to privacy control AR-1, Governance and Privacy Program, and AR-2,
Privacy Impact and Risk Assessment.
Version date: October 1, 2023
Follow the format below when entering your risk assessment:
Privacy Risk: The system collects, processes, and retains PII and PHI on Veterans and on
Members of the Public. If this information were to be breached or accidentally disclosed to
inappropriate parties or the public, it could result in personal and financial harm to the
individuals impacted and adverse negative effect to the VA.
Mitigation: Data collected, processed, and retained will be protected in accordance with VA
Handbook 6500 and FIPS 140-2 encryption and data in-transit protection standards. All systems
and individuals with access to the system will be approved, authorized, and authenticated before
access is granted. VA annual privacy and security training compliance will be enforced for all
VA employees, contractors, and vendors.

# Uses of the Information

The following questions are intended to clearly delineate the use of information and the accuracy of
the data being used.
2.1 Describe how the information in the system that
business purpose.
Identify and list each use (both internal and external to VA) of the information collected or
maintained. This question is related to privacy control AP-2, Purpose Specification.
PII/PHI Data Element Internal Use External Use
Name File Identification purposes Not used
employee/Contractor Full
Name
File Identification purposes Not used
Personal Mailing Address File Identification purposes Not used
Personal Phone Number(s) File Identification purposes Not used
Personal Email Address File Identification purposes Not used
Eye Prescription File Identification purposes Not used
Address File Identification purposes Not used
2.2 What types of tools are used to analyze data and what type of data may be produced?
These questions are related to privacy controls DI-1, Data Quality, DI-2, Data Integrity and
Integrity Board, and SE-1, Inventory of Personally Identifiable Information.
2.2a Many systems sift through large amounts of information in response to a user inquiry or
programmed functions. Systems may help identify areas that were previously not obvious and need
additional research by agents, analysts, or other employees. Some systems perform complex
Version date: October 1, 2023
analytical tasks resulting in, among other types of data, matching, relational analysis, scoring,
reporting, or pattern analysis. Describe any type of analysis the system conducts and the data that is
created from the analysis?
Talend Studio, Talend Data Preparation, Talend Data Stewardship does not conduct any
analysis.
2.2b If the system creates or makes available new or previously unutilized information about an
individual, explain what will be done with the newly derived information. Will it be placed in the
individual's existing record? Will a new record be created? Will any action be taken against or for
the individual identified because of the newly derived data? If a new record is created, will the newly
created information be accessible to Government employees who make determinations about the
individual? If so, explain fully under which circumstances and by whom that information will be
used.
For 4sight-II, the data is used for prescribing new eyeglasses.
provide access for the user
interface access management and verification.
2.3 How is the information in the system secured?
These questions are related to security and privacy controls SC-9, Transmission Confidentiality, and
SC-28, Protection of Information at Rest.
2.3a What measures are in place to protect data in transit and at rest?
In transit, we use SSL/TLS to encrypt data. Also, all request/query are tied to a valid VA
user.
2.3b If the system is collecting, processing, or retaining Social Security Numbers, are there
additional protections in place to protect SSNs?
In transit, we use SSL/TLS to encrypt data. Also, all request/query are tied to a valid VA
user.
2.3c How is PII/PHI safeguarded in accordance with OMB Memorandum M-06-15?
The controls are listed in the VALIP SOPs, in addition to the mandatory privacy training
from the training management system (TMS) These adhere to the standards set for the
OMB Memo M-06-15.
2.4 PRIVACY IMPACT ASSESSMENT: Use of the information.
Describe any types of controls that may be in place to ensure that information is handled in
accordance with the uses described above. Example: Describe if training for users of the project
covers how to appropriately use information. Describe the disciplinary programs or system controls
(i.e. denial of access) that are in place if an individual is inappropriately using the information.
Consider the following FIPPs below to assist in providing a response:
Principle of Transparency: Is the PIA and SORN, if applicable, clear about the uses of the
information?
Version date: October 1, 2023
Principle of Use Limitation: Is the use of information contained in the system relevant to the mission
of the project?
This question is related to privacy control AR-4, Privacy Monitoring and Auditing, AR-5, Privacy
Awareness and Training, and SE-2, Privacy Incident response.
2.4a How is access to the PII determined?
Access is tied to a VA user via Identity and Access Management with the use of validating
the Designated User.
2.4b Are criteria, procedures, controls, and responsibilities regarding access documented?
Yes, those are documented in the VALIP Access Control Standard Operating Procedure (AC
SOP).
2.4c Does access require manager approval?
Yes, managers are required to approve access requests, and only granted in conjunction with the
principle of least privilege and a need to know.
2.4d Is access to the PII being monitored, tracked, or recorded?
Yes. per the VALIP SOP paragraph 4 user privileges are reviewed and audited annually.
2.4e Who is responsible for assuring safeguards for the PII?
The Information System Owner, Information System Security Owner, and System Steward
are all responsible for assuring safeguards are in place.
