##### CIRT Playbook Battle Card: **GSPBC-1063 - Execution - Scheduled Task or Job**

**(P) Preparation**

1.  Patch asset vulnerabilities
2.  Perform routine inspections of controls/weapons
3.  Ensure antivirus/endpoint protection software is installed on workstations and laptops
4.  Regularly update virus definitions and signatures
5.  Conduct employee security awareness training
6.  Ensure all software is kept up to date
7.  Audit for permission weaknesses that could be used to escalate privileges \[4\]
8.  Leverage GPO to force tasks to run under an authenticated account \[2\]
9.  Restrict scheduled tasks to a defined group of administrators \[3\]

**(I) Identification**

1.  Monitor for:  
    a. Existing commands that may abuse task scheduling functionality to execute malicious code \[1\]  
    b. Newly constructed containers or files that may abuse task scheduling to execute malicious code \[1\]  
    c. Newly created scheduled jobs for initial indicators of malicious activity \[1\]
2.  Investigate and clear ALL alerts

**(C) Containment**

1.  Inventory (enumerate & assess)
2.  Detect | Deny | Disrupt | Degrade | Deceive | Destroy
3.  Observe -> Orient -> Decide -> Act
4.  Utilize EDR hunter/killer agents to terminate offending processes
5.  Remove the affected system from the network
6.  Determine the source and pathway of the attack
7.  Issue a perimeter enforcement for known threat actor locations

**(E) Eradication**

1.  Close the attack vector
2.  Create forensic backups of affected systems
3.  Perform endpoint/AV scans on targeted systems
4.  Reset any compromised passwords
5.  Inspect ALL assets and user activity for IOC consistent with the attack profile
6.  Inspect backups for IOC consistent with the attack profile PRIOR to system recovery
7.  Patch asset vulnerabilities
8.  Reset the passwords of any compromised accounts

**(R) Recovery**

1.  Restore to the RPO (Recovery Point Objective) within the RTO (Recovery Time Objective)
2.  Assess and address collateral damage
3.  Resolve any related security incidents
4.  Restore affected systems to their last clean backup

**(L) Lessons/Opportunities**

1.  Perform routine cyber hygiene due diligence
2.  Engage external cybersecurity-as-a-service providers and response professionals
3.  Implement policy changes to reduce future risk
4.  Utilize newly obtained threat signatures

**References:**

1.  https://attack.mitre.org/techniques/T1053/
2.  https://attack.mitre.org/mitigations/M1028/
3.  https://attack.mitre.org/mitigations/M1026/
4.  https://attack.mitre.org/mitigations/M1047/

**Resources:**

*    GuardSight GSVSOC Incident Response Plan: https://github.com/guardsight/gsvsoc\_cybersecurity-incident-response-plan
*    IT Disaster Recovery Planning: https://www.ready.gov/it-disaster-recovery-plan
*    Report Cybercrime: https://www.ic3.gov/Home/FAQ