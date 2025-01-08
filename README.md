# Internal IT Audit for Botium Toys

## Scope and Goals
**Scope:**  
The audit encompasses the entire security program of Botium Toys, focusing on:  
- Employee equipment and devices.  
- Internal network and systems.  
- On-premises equipment and retail products.  
- Management of systems, software, and services, including accounting, e-commerce, and inventory.  

**Goals:**  
- Assess existing assets and identify gaps in security controls and compliance.  
- Complete a controls and compliance checklist to improve Botium Toys' security posture.  

## Risk Assessment
**Key Risks Identified:**  
1. Inadequate asset management and lack of critical controls.  
2. Non-compliance with U.S. and international regulations, including PCI DSS and GDPR.  

**Risk Score:**  
8/10 – High risk due to insufficient controls and adherence to compliance standards.  

**Potential Impacts:**  
- Medium impact on business continuity due to asset loss.  
- High risk of fines and data breaches due to non-compliance and insufficient security measures.  

## Controls Assessment Checklist
| Control                        | Status  |
|--------------------------------|---------|
| Least Privilege                | ❌      |
| Disaster Recovery Plans        | ❌      |
| Password Policies              | ❌      |
| Separation of Duties           | ❌      |
| Firewall                       | ✅      |
| Intrusion Detection System     | ❌      |
| Backups                        | ❌      |
| Antivirus Software             | ✅      |
| Legacy System Maintenance      | ❌      |
| Encryption                     | ❌      |
| Password Management System     | ❌      |
| Physical Locks                 | ✅      |
| CCTV Surveillance              | ✅      |
| Fire Detection/Prevention      | ✅      |

## Compliance Checklist
**PCI DSS:**  
- Only authorized users have access to credit card information: ❌  
- Secure environment for storing, processing, and transmitting credit card data: ❌  
- Data encryption procedures in place: ❌  
- Secure password management policies: ❌  

**GDPR:**  
- E.U. customers' data privacy ensured: ✅  
- Breach notification plan (within 72 hours): ✅  
- Data classification and inventory: ❌  
- Privacy policies and documentation enforced: ✅  

**SOC Type 1 & 2:**  
- User access policies established: ❌  
- Sensitive data (PII/SPII) confidentiality ensured: ❌  
- Data integrity validated: ✅  
- Data availability for authorized individuals: ✅  

## Recommendations
1. **Implement Missing Controls:**  
   - Enforce Least Privilege and Separation of Duties policies.  
   - Develop Disaster Recovery Plans and regular backups.  
   - Introduce an Intrusion Detection System (IDS) and encryption protocols.  
   - Establish a centralized Password Management System with robust policies.  

2. **Enhance Compliance:**  
   - Secure customer credit card data by implementing PCI DSS best practices.  
   - Classify and inventory data to ensure GDPR compliance.  
   - Regularly audit and validate sensitive data to maintain SOC standards.  

3. **Legacy System Management:**  
   - Schedule regular maintenance and define clear intervention protocols.  

## Conclusion
By addressing the identified gaps and implementing recommended controls, Botium Toys can significantly improve its security posture, ensure compliance with regulations, and protect critical assets against potential risks and threats.
