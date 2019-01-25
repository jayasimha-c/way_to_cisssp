# Intro
> "inch deep mile wide"
> [from CISSP ALL-IN-ONE EXAM GUIDE]
CISSP professional ensurance the availability, integrity and confidentiality of information systems.
The best security people are the ones who are driven towards an ethical outcome.

8 CBK(Common Body of Knowledge) security domains:
- Security & Risk Management
- Asset Security
- Security Architecture and Engineering
- Communication and Network Security
- Identity and Access Management (IAM)
- Security Asessment & Testing
- Security operations
- Software development security

Security laws, regulations & standards: 
- SOX (Sarbanes-Oxley), 
- GLBA (Gramm-leach-Bliley Act), 
- PCI-DSS (Payment Card Industry Data Security Standard), 
- HIPAA (Health Insurance Portability & Accountability Act) and 
- FISMA (Federal Information Security Management Act)

Core goals of security is to provide:
- availability
- integrity
- confidentiality 
also known as (AIC triad, also known as CIA).

# Terms and definitions
Terms:
- Vulnerability
Weakness in the system, that allows a threat cause to compromise its security

- Threat 
Is any potential danger that is associated with the exploitation of a vulnerability. Entity that takes advantage of a vulnerability. Entity that takes advantage of a vulnerability is referred to as a threat agent.

- Risk
Likelihood of a threat source exploiting a vulnerability and the corresponing business impact.

- Exposure
Is an instance of being exposed to losses. A vulnerability exposes an organization to possible damages.

- Control or contermeasure
Put into place to mitigate (reduce) the potential risk.

Flow:
[1] Threat agent -> (raises to) -> Threat -> (exploits) -> Vulnerability -> (leads to) -> Risk -> (can damage) -> Asset -> (and cause) -> Exposure -> (can be countermeasured) -> Safeguard.


## Control or contermeasure
Types:
- Administrative ("soft control"): docs, training...
- Technical controls ("logical controls"): firewalls; IPS; encrytpion...
- Physical controls security guards, locks, fencing...

Defemnce-in-depth is a coordinated use of multiple security controls in a layered approach.

Physical controls:
- fence
- locked external doors
- closed circuit TV (CCTV)
- security guards
- locked internal doors
- locked server room
- physically secured computers (cable locks)

Technical controls:
- firewalls
- intrusion detections system
- intrusion preventive system
- antimalware
- acccess controls
- encryption

Control functionalities:
- Preventive 
Avoid incident from occuring
- Detective
Odentify incidents activities & intruder
- Corrective 
Fix components / systems after incident occured
- Deterrant
Discourage a potential attacker
- Recovery
Bring back to regular operations
- Compensating
Controle that provide an alternative measure of control. Compensating control is an alternative control that provides similar protection as the original control but has to be used because it is more affordable or allows specifically required business functions.

Security through obscurity is assuming that your enemies are not as smart as you are and that they can not figure out something that you feel is very tricky (e.g. changing the SSH port numbers assuming nobody would guess it).


### Preventive + Administrative:
- policy and procedure
- effective hiring practises
- pre-employment background check
- controlled termination process
- data classification
- security awareness

### Preventive + Physical
- badges: swipe cards
- guards, dogs
- fences, locks, mantraps

### Preventive + Technical
- passwords, biometrics, smart cars
- encryption, secure protocols, call-back systems, db views, constrained user interfaces
- antimalware software, access control list, firewall, intrusion prevension system

> more, page 12

### Standards
Security Program Development:
- ISO / IEC 27000 series: international standard on how to develop and maintain an ISMS developed by ISO & IEC

Enterprise Architecture Development:
- Zachman Framework: model for development of enterprise architecture by John Zachman
- TOGAF model & methodology for the development of enterprise architecture developed by The Open Group
- DoDAF US Department of Defence architecture framework that ensures interoperability of systems to meet military mission goals
- MODAF framework used in military support missinos developed by the British Ministry of Defence
- SABSA model - model & technology for the development of information security enterprise architecture

Security Controls Development:
- COBiT5 in Information System Audit & Control Association (ISACA)
- NIST SP 800-53 Set of controls to protect US federal systems developed by the National Institute of standard and technology
- COSO Internal Control Integrated Framework - reduce risk of financial fraud developed by the Commetee of Sponsoring Org (COSO) of the Treadway Commission

Process Management Development
- ITIL IT Service management developed by the UKs Office of Goverment Commeetee
- Six Sigma - business management strategy to carry out process improvement
- Capability Maturity Model Integration (CMMI) organization development process improvement developed by Carnegie Mellon University

#### ISO / IEC 2700 Series
British Standard 7799 (BS7799) - standard outlines how information security management system should be built and maintained.
Part1 - outlined control objectoved and range of controls cna be used to meet those objectives.
Part2 - outlines how security program can be set up and maintained. Also Part2 is baseline organization can be certified against.

Aliases: BS7799, BS7799v1, BS7799v2, ISO17799, BS77990-3i25 etc.

Published Standards in Series:
- ISO/IEC 27000 - overview and vocabulary
- ISO/IEC 27001 - ISMS requirements
- ISO/IEC 27002 - code of practise for information security controls
- ISO/IEC 27003 - ISMS implementation
- ISO/IEC 27004 - ISMS measurement
- ISO/IEC 27005 - Risk management
- ISO/IEC 27006 - Certification body requirements
- ISO/IEC 27007 - ISMS auditing
- ISO/IEC 27008 - Guidance for auditors
- ISO/IEC 27011 - Telecoms organizations
- ISO/IEC 27014 - Infosec Governance
- ISO/IEC 27015 - Financial sector
- ISO/IEC 27031 - Business continuity
- ISO/IEC 27032 - Cybersecurity
- ISO/IEC 27033 - Network Security
- ISO/IEC 27034 - Application Security
- ISO/IEC 27035 - Incident management
- ISO/IEC 27037 - Digital evidence collection & preservation
- ISO/IEC 27799 - Health organization

