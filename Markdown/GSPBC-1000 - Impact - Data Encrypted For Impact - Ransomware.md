##### CIRT Playbook Battle Card: **GSPBC-1000 - Impact - Data Encrypted For Impact - Ransomware**

**(P) Preparation**

1.  Patch asset vulnerabilities
2.  Perform routine inspections of controls/weapons
3.  Confirm backups are free of malware
4.  Establish ability to pay ransoms w/cryptocurrency
5.  Obtain decryption keys for ransomware variants
6.  Confirm cybersecurity insurance coverages
7.  Conduct ransomware simulations
8.  Conduct phishing simulations
9.  Conduct user awareness training
10.  Conduct response training (this PBC)
11.  Examine file shares for loose/open privileges
12.  Maintain Antivirus/EDR application updates
13.  Create network segmentation
14.  Log traffic between network segments
15.  Incorporate threat intelligence
16.  Incorporate deception technology
17.  Perform routine inspections of asset backups
18.  Validate proper functionality

**(I) Identification**

1.  Monitor for:  
    a. Ransomware notes/messages  
    b. Unusual file extensions or maliciousextensions  
    c. User reports of files being corrupt or notreadable  
    d. Emails with suspicious attachments  
    e. Unusual DNS traffic  
    f. High velocity renaming of files  
    g. CPU spikes on file sharing systems  
    h. Unusual userland executable binaries  
    i. Anomalous network connections on hosts  
    j. Firewall denies to well known file sharingports  
    k. Network connections to known C2 andexploit kit locations  
    l. Use of TOR or I2P
2.  Investigate and clear ALL alerts of possible ransomware  
    a. IDS/IPS  
    b. Antivirus/EDR  
    c. Threat intelligence  
    d. Deception technology

**(C) Containment**

1.  Inventory (enumerate & assess)
2.  Detect | Deny | Disrupt | Degrade | Deceive | Destroy
3.  Observe -> Orient -> Decide -> Act
4.  Locate and isolate the assets responsible for encrypting files
5.  Isolate impacted file sharing systems
6.  Close the attack vector
7.  Fortify non-impacted file sharing systems
8.  Fortify non-impacted critical assets
9.  Issue perimeter enforcement for known threat actor locations
10.  Deploy EDR hunter/killer agents and terminate offending processes

**(E) Eradication**

1.  Close the attack vector
2.  Patch asset vulnerabilities
3.  Re-image impacted assets
4.  Inspect all assets for IOC consistent with the attack profile
5.  Inspect user activity for IOC consistent with the attack profile
6.  Inspect backups for IOC consistent with the attack profile PRIOR to systems recovery
7.  Implement newly obtained threat signatures

**(R) Recovery**

1.  Restore to the RPO within the RTO
2.  Restore from known clean backups
3.  Address collateral damage

**(L) Lessons/Opportunities**

1.  Perform routine cyber hygiene due diligence
2.  Engage external cybersecurity-as-a-service providers and response professionals
3.  Avoid opening email and attachments from unfamiliar senders
4.  Avoid opening email attachments from senders that do not normally include attachments

**References:**

1.  MITRE ATT&CK Technique T1486: https://attack.mitre.org/techniques/T1486/
2.  Paying ransoms is discouraged, but it should be a contingency available to executives (SEE Preparation #4 and #6).

**Resources:**

*    GuardSight GSVSOC Incident Response Plan: https://github.com/guardsight/gsvsoc\_cybersecurity-incident-response-plan
*    IT Disaster Recovery Planning: https://www.ready.gov/it-disaster-recovery-plan
*    Report Cybercrime: https://www.ic3.gov/Home/FAQ

![](data:image/png;base64,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)

  
© GuardSight, Inc.® | https://www.guardsight.com
