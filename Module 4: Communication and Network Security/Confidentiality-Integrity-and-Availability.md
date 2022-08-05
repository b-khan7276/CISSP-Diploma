# Topic A 

# Confidentiality Integrity and Availability

# Confidentiality
Objective: Understand and apply concepts of confidentiality, integrity, and
availability

## Overview
- Secrecy of the data and not made available/disclosed
- Unauthorized individuals, entities, or processes
- Only the person with "authorized" access
## Confidentiality Maintained
- Encryption (Rest / Transmission)
  - Disk Encryption / Network Connections (SSL, IPSEC Tunnels, etc)
- Password Storage/Vaults
  - Locations to store passwords or key data
- Access Controls
  - Folders, Applications, any place data is stored and transmits

## Confidentiality Compromised
- Data shipped in plain text or stored unprotected
- Passwords being shared or stored in unprotected file structure
- "Everyone" has access to folder/file structure without Audit
- Employee Socially Engineered, clicking link allowing for unauthorized access
## Other Considerations around Confidentiality
- Data Sensitivity
  - How sensitive is the data to your organization / company
  - Intellectual Property / Critical Business Processes
- Operator Decision Rights (Data)
  - Who owns the data and has decision rights
  - Is it IT or is the data owner something separate

# Integriy
## Overview
- Integrity is dependent upon the Confidentiality of the data
- Maintaining assurances around the accuracy and completeness of the data
   - Lifecycle- Beginning to End
- Data cannot be modified in unauthorized or undetected manner
  - In transmission or in storage
- Assurance or process to ensure proper change of the data
  - Data may need to change, but is it proper


# Integrity Maintained
- Security mechanisms in place to ensure that data has not been compromised
  - Encryption (transit/rest)
- Proper Access provided to the data via authentication procedures
  - Keeping Unauthorized people and processes from data
- Audit/Oversight Trail
  - Proper logging/ monitoring ensuring only proper access to systems
# Integrity Compromised
- Data transmitted and/or stored in unprotected containers/media without encryption
- Inadequate authentication methods in place
- Systems are not logged/monitored to ensure data integrity


# Availability
## Overview
- Authorized items are granted timely and uninterrupted access - be available when it is needed
- High Availability - systems aim to remain available at all times
- Availlabilityincludes efficient, uninterrupted access, which would be the prevention of Denial of
Service Attacks
- Intentional / Unintentional (Accidents)


## Availability Maintained
- Power maintained and kept available
  - Uninterrupted Power Sources keeping data center active and operational
- High Availability Systems and Devices
  - Hardware in place to ensure that systems stay operational in the event of failure
- Polices and Procedures
  - Disaster Recover/ Business Continuity policies with a testing plan in place
## Availability Compromised
- Denial of Service causing an outage
- Critical System Unavailable
  - Example: Device or Network to Power production facility is down and unable to determine time to
recover
