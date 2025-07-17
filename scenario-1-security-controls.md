# Scenario 1: Security Controls Audit

In this scenario, I evaluated the security posture of a fictional company (Botium Toys) by identifying and assessing the presence of various administrative and technical controls. My objective was to determine which common security controls are currently in place, identify any gaps, and recommend improvements to reduce the organization's overall risk exposure.

### Given Scenario: 
Botium Toys: Scope, goals, and risk assessment report

## Scope and goals of the audit<br>
**Scope:** The scope of this audit is defined as the entire security program at Botium Toys. This includes their assets like employee equipment and devices, their internal network, and their systems. You will need to review the assets Botium Toys has and the controls and compliance practices they have in place.<br>

**Goals:** Assess existing assets and complete the controls and compliance checklist to determine which controls and compliance best practices that need to be implemented to  improve Botium Toys’ security posture.<br>

**Current assets**
Assets managed by the IT Department include: <br>
* On-premises equipment for in-office business needs  
* Employee equipment: end-user devices (desktops/laptops, smartphones), remote workstations, headsets, cables, keyboards, mice, docking stations, surveillance cameras, etc.
* Storefront products available for retail sale on site and online; stored in the company’s adjoining warehouse
* Management of systems, software, and services: accounting, telecommunication, database, security, ecommerce, and inventory management
* Internet access
* Internal network
* Data retention and storage
* Legacy system maintenance: end-of-life systems that require human monitoring<br>

### Risk assessment<br>

#### Risk description<br>
Currently, there is inadequate management of assets. Additionally, Botium Toys does not have all of the proper controls in place and may not be fully compliant with U.S. and international regulations and standards.<br>

#### Control best practices<br>
The first of the five functions of the NIST CSF is Identify. Botium Toys will need to dedicate resources to identify assets so they can appropriately manage them. Additionally, they will need to classify existing assets and determine the impact of the loss of existing assets, including systems, on business continuity.<br>

#### Risk score<br>
On a scale of 1 to 10, the risk score is 8, which is fairly high. This is due to a lack of controls and adherence to compliance best practices.<br>

#### Additional comments<br>
The potential impact from the loss of an asset is rated as medium, because the IT department does not know which assets would be at risk. The risk to assets or fines from governing bodies is high because Botium Toys does not have all of the necessary controls in place and is not fully adhering to best practices related to compliance regulations that keep critical data private/secure. Review the following bullet points for specific details:<br>

* Currently, all Botium Toys employees have access to internally stored data and may be able to access cardholder data and customers’ PII/SPII.
* Encryption is not currently used to ensure confidentiality of customers’ credit card information that is accepted, processed, transmitted, and stored locally in the company’s internal database. 
* Access controls pertaining to least privilege and separation of duties have not been implemented.
* The IT department has ensured availability and integrated controls to ensure data integrity.
* The IT department has a firewall that blocks traffic based on an appropriately defined set of security rules.
* Antivirus software is installed and monitored regularly by the IT department. 
* The IT department has not installed an intrusion detection system (IDS).
* There are no disaster recovery plans currently in place, and the company does not have backups of critical data. 
* The IT department has established a plan to notify E.U. customers within 72 hours if there is a security breach. Additionally, privacy policies, procedures, and processes have been developed and are enforced among IT department members/other employees, to properly document and maintain data.
* Although a password policy exists, its requirements are nominal and not in line with current minimum password complexity requirements (e.g., at least eight characters, a combination of letters and at least one number; special characters). 
* There is no centralized password management system that enforces the password policy’s minimum requirements, which sometimes affects productivity when employees/vendors submit a ticket to the IT department to recover or reset a password.
* While legacy systems are monitored and maintained, there is no regular schedule in place for these tasks and intervention methods are unclear.
* The store’s physical location, which includes Botium Toys’ main offices, store front, and warehouse of products, has sufficient locks, up-to-date closed-circuit television (CCTV) surveillance, as well as functioning fire detection and prevention systems.<br>


## Controls and compliance checklist

To complete the controls assessment checklist, refer to the information provided in the scope, goals, and risk assessment report. For more details about each control, including the type and purpose, refer to the control categories document.

Then, select “yes” or “no” to answer the question: Does Botium Toys currently have this control in place? 

#### <u>Controls assessment checklist</u> <br>
<img src="https://github.com/user-attachments/assets/7fef6848-d8c1-4063-a795-a7257bd00931" alt="Screenshot" width="400"/>

To complete the compliance checklist, refer to the information provided in the scope, goals, and risk assessment report. For more details about each compliance regulation, review the controls, frameworks, and compliance reading.

Then, select **“yes”** or **“no”** to answer the question: Does Botium Toys currently adhere to this compliance best practice?

### Compliance checklist

**Payment Card Industry Data Security Standard (PCI DSS)** <br><br>
<img src="https://github.com/user-attachments/assets/be3eb249-d705-4e54-befe-e90db7cf2954" alt="Screenshot" width="400"/>

**General Data Protection Regulation (GDPR)** <br><br>
<img src="https://github.com/user-attachments/assets/137c21ab-898b-432d-afc5-4f65701a0ac1" alt="Screenshot"
width="400"/>

**System and Organizations Controls (SOC type 1, SOC type 2)** <br><br> 
<img src="https://github.com/user-attachments/assets/7846932c-0973-4a9c-a417-a9fa2bb4cd9d" alt="Screenshot" width="400"/>




User access policies are established.




Sensitive data (PII/SPII) is confidential/private.




Data integrity ensures the data is consistent, complete, accurate, and has been validated.




Data is available to individuals authorized to access it.



This section is optional and can be used to provide a summary of recommendations to the IT manager regarding which controls and/or compliance best practices Botium Toys needs to implement, based on the risk posed if not implemented in a timely manner.
Recommendations (optional): In this section, provide recommendations, related to controls and/or compliance needs, that your IT manager could communicate to stakeholders to reduce risks to assets and improve Botium Toys’ security posture.
Botium Toy’s current security posture has resulted in a wide attack surface that would allow for hackers to utilize a plethora of different attack vectors. This is the reason for its high risk score. To improve Botium Toy’s security posture it is recommended to implement the following changes: 

Implement Access Controls: Access to sensitive data and systems should only be provided to those necessary, follow the principle of least privilege. 
Utilize Encryption: Sensitive data such as PII and SPII should always be encrypted to mitigate risk in the case of a data breach.
Update Password Security: Enforce higher standards of complexity and a centralized password management system to reduce the chances of unauthorized access.
Install IDS: An IDS system will detect suspicious activity and allow the organization to  take immediate action. 
Create a Disaster Recovery Plan: Establish a disaster recovery plan, with data backups, to ensure a continuity of operations in the event of a security incident or disaster. 
Improve PCI DSS Compliance: Move towards PCI DSS compliance by encrypting customer card data, and enforcing stricter access to credit card transactions. 
Improve GDPR and SOC Framework Compliance: To comply with GDPR, classify personal data and enforce stricter access policies. For SOC 1 and SOC 2 compliance, ensure data integrity, access policies, and regularly monitor data availability


