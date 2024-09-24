# Security-Audit

As part of my Google Cybersecurity Professional Certificate, I conducted a security audit for a fictitious company based on the scenario provided. 
## Objective
Perform a comprehensive security audit based on a case study of a fictional company to identify vulnerabilities and provide remediation recommendations
## Case Study (provided in the course)
![img 0](./sampleCase.jpg)
### Steps of a Internal Security Audit
Typically, an internal security audit will comprise of the following steps - 
1. Audit Planning (Defining the scope, goal of the audit, as well as the security frameworks that will/might be considered)
2. Conducting a Risk Assessment
3. Conducting a Control Assessment
4. Compliance check
5. Final Review and Future Recommendations
## Step 1: Audit Planning
Scope refers to "The people, policies and procedures that may impact the security posture of the organisation" - this gives us an idea that people and procedures within the IT department are most likely to be vulnerable, hence will be focus of the audit. Assets related to the same will also be subject to scrutiny.
Goal - “Things to achieve in order to improve the security posture of the organisation”  
![img 1](./scopeGoals.jpg)
## Step 2: Risk Assessment
This assessment aims to identify vulnerabilities, threats, and risks to the company's assets. Based on it, a risk score can also be given. 
![img 2](./riskAssessment.jpg)
## Step 3: Control Assessment
Controls refer to the safeguards of different kinds that are implemented to tackle specific security threats. After this, a checklist of "Yes"/"No" against each security control is given to assess the current security posture.
![img 3](./controlAssessment.jpg)
## Step 4: Compliance Check
Policies - it depends on (A) the frameworks that the organisation voluntarily has chosen to work according to. (B) the frameworks that it must comply to because its operations are in a particular geographical location where certain laws have to be mandatorily complied with. Keeping point A in mind, NIST-CSF will be reviewed, and keeping B in mind, GDPR and PCI DSS will be considered because the organisation is expanding in the E.U. region.
![img 4](./compliance.jpg)
## Step 5: Final Review and Future Recommendations
Final ending note on the audit. Recommendations are optional. This part is generally for communicating the concerns/results to the stakeholders.
It may also mention technical recommendations for security professionals. A sample of it has been implemented by using Python to create a small script to automate the task of updating the list of IP Addresses that are allowed privileged access - please refer to the [Access Control Management based on IP Addresses](https://github.com/NityaAgarwal/Security-Audit/tree/main/Access%20Control%20Management%20based%20on%20IP%20addresses)
 folder in this repository for the same.
