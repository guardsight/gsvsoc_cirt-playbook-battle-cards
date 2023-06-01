##### CIRT Playbook Battle Card: **GSPBC-1068 - Credential Access - Network Sniffing**

**(P) Preparation**

1.  Patch asset vulnerabilities
2.  Perform routine inspections of controls/weapons
3.  Maintain Antivirus/EDR application updates
4.  Create network segmentation
5.  Log traffic between network segments
6.  Incorporate threat intelligence
7.  Perform routine inspections of asset backups
8.  Conduct phishing simulations
9.  Conduct user security awareness training
10.  Conduct response training (this PBC)
11.  Ensure that all wired and/or wireless traffic is encrypted appropriately. Use best practices for authentication protocols, such as Kerberos, and ensure web traffic that may contain credentials is protected by SSL/TLS. \[1\]
12.  Use multi-factor authentication wherever possible. \[2\]
13.  In cloud environments, ensure that users are not granted permissions to create or modify traffic mirrors unless this is explicitly required. \[3\]

**(I) Identification**

1.  Monitor for:  
    a. executed commands and arguments for actions that aid in sniffing network traffic to capture information about an environment, including authentication material passed over the network \[4\]  
    b. newly executed processes that can aid in sniffing network traffic to capture information about an environment, including authentication material passed over the network \[5\]
2.  Investigate and clear ALL alerts associated with the impacted assets or accounts
3.  Routinely check firewall, IDS, IPS, and SIEM logs for any unusual activity
4.  Utilize Sysinterals Autoruns to view programs configured to run in response to startup or application execution \[2\]

**(C) Containment**

1.  Inventory (enumerate & assess)
2.  Detect | Deny | Disrupt | Degrade | Deceive | Destroy
3.  Observe -> Orient -> Decide -> Act
4.  Issue perimeter enforcement for known threat actor locations
5.  Archive scanning related artifacts such as IP addresses, user agents, and requests
6.  Determine the source and pathway of the attack
7.  Fortify non-impacted critical assets

**(E) Eradication**

1.  Close the attack vector by applying the Preparation steps listed above
2.  Perform endpoint/AV scans on targeted systems
3.  Reset any compromised passwords
4.  Inspect ALL assets and user activity for IOC consistent with the attack profile
5.  Inspect backups for IOC consistent with the attack profile PRIOR to system recovery
6.  Patch asset vulnerabilities

**(R) Recovery**

1.  Restore to the RPO (Recovery Point Objective) within the RTO (Recovery Time Objective)
2.  Address any collateral damage by assessing exposed technologies
3.  Resolve any related security incidents
4.  Restore affected systems to their last clean backup

**(L) Lessons/Opportunities**

1.  Perform routine cyber hygiene due diligence
2.  Engage external cybersecurity-as-a-service providers and response professionals
3.  Implement policy changes to reduce future risk
4.  Utilize newly obtained threat signatures
5.  Avoid opening email and attachments from unfamiliar senders
6.  Avoid opening email attachments from senders that do not normally include attachments
7.  Pay attention to unusual behavior exhibited by trusted parties
8.  Remember that data and events should not be viewed in isolation but as part of a chain of behavior that could lead to other activities

**References:**

1.  https://attack.mitre.org/mitigations/M1041/
2.  https://attack.mitre.org/mitigations/M1032/
3.  https://attack.mitre.org/mitigations/M1018/
4.  https://attack.mitre.org/datasources/DS0017/
5.  https://attack.mitre.org/datasources/DS0009/

**Resources:**

*    GuardSight GSVSOC Incident Response Plan: https://github.com/guardsight/gsvsoc\_cybersecurity-incident-response-plan
*    IT Disaster Recovery Planning: https://www.ready.gov/it-disaster-recovery-plan
*    Report Cybercrime: https://www.ic3.gov/Home/FAQ
