
meta-viewport: width=device-width, initial-scale=1.0 title: Durray Kausar — Privacy Architect
Durray Kausar

Overview
Havenwatch
Experience
Skills
Contact


Durray Kausar
Privacy Architect · Governance Framework Designer · AI & Compliance

MS Cybersecurity & Data Privacy Law | Albany Law, New York
HIPAA Certified | CIPP/US (In Progress) | AIGP (In Progress)

New York & North Carolina · Remote/Hybrid
durray25@gmail.com | (845) 665-8202


Overview
Privacy architect with 2+ years designing governance frameworks for high-risk data environments. Currently leading technical compliance architecture at Havenwatch Foundation (child safety operations). Expertise in DPIA/LIA frameworks, vendor risk assessment, access control design, incident response, and EU AI Act governance.

What I deliver: Audit-ready controls, vendor frameworks, policy automation, cross-functional program architecture.

Regulatory focus: GDPR, CPRA, LGPD, HIPAA, FERPA, ECPA/SCA, COPPA, EU AI Act

Tools: TrustArc, Microsoft 365, Azure Compliance, NIST Privacy Framework, ISO 27701/27001, AI-RMF


Havenwatch Foundation for Child Protection
Role: Privacy & Governance Architect | 2026 – Present

Technically leading end-to-end privacy framework architecture for child safety case management systems. Working across IT, Legal, and Operations to design controls protecting minor data (biometric records, investigative communications, health information) against unauthorized access, unlawful disclosure, and regulatory violations.


1. Access Control Architecture (4-Tier Model)
Designed and implemented tiered access controls governing who accesses what, when, and with what safeguards.

Tier 4 (Minor Records — Highest Risk)

Hardware token MFA required
Session recording + real-time access alerts
Active case access only
Immediate revocation on role change
Quarterly access reviews

Tier 1–3 (Case-Related Data)

Software MFA + device compliance checks
Least-privilege role assignment
90-day access reviews
Audit logging of all touches

Result: 100% access control coverage pre-launch; zero unauthorized access failures in testing.


2. Data Minimization & Retention
Classified data intake → pseudonymization → automated redaction → regulatory-aligned deletion.

At Intake

Only necessary fields collected
Classification by sensitivity level
Legal basis documented

In Transit/At Rest

Minor identifiers pseudonymized (e.g., "Minor_ID_00127" vs. full name)
Automated redaction of PII before display
AES-256 encryption at rest; TLS 1.3 in transit

At Expiration

Auto-expiry flags on schedule
Dual sign-off legal holds override deletion
Backup deletion validated

Coverage: SCA (no unauthorized access), COPPA (separate tier for <13), ECPA (messaging protection), GDPR (data minimization), HIPAA-equivalent controls.


3. Vendor Risk Assessment & DPA Framework
Built custom risk-scoring matrix for third-party tools before deployment on minor data.

15+ tools assessed in 2024

8 deployed (Green tier)
5 with remediation conditions (Yellow tier)
2 rejected — non-negotiable on SCA/ECPA compliance

Assessment Dimensions | Dimension | What We Check | |-----------|---------------| | SCA Compliance | Unauthorized access logging; law enforcement escalation protocol | | Data Residency | EU/US hosting; documented transfer agreements (SCCs) | | Encryption & Security | AES-256 at rest; TLS 1.3 in transit; SOC 2 Type II; pen testing cadence | | Audit Logging | Tamper-proof logs; session recording for Tier 4; 2-year retention | | Access & Auth | MFA mandatory; least-privilege; quarterly reviews; immediate revocation | | AI & Bias | No undisclosed AI; no behavioral prediction on minors; bias testing | | Breach Notification | 24-hour notification required; incident communication plan | | Sub-Processors | Complete list; no AI sub-processors on minor data; annual verification |

DPA Requirements Drafted

Algorithm transparency: training data disclosure, bias testing results (by race/age/gender)
Technical controls preventing re-indexing of deleted subjects
Sub-processor oversight: 5-10 day change notification, annual SOC 2 Type II audits
Vendor go/no-go criteria: vendors unable to commit to controls won't deploy


4. AI Governance & EU AI Act Framework
Built and delivered governance program applying EU AI Act risk tiers across all tools.

Program Components

Component
Output
AI Inventory
All tools mapped by risk tier; shadow AI identified
Risk Classification
Unacceptable (blocked) / High Risk (DPIA) / Limited Risk (transparency) / Minimal Risk (noted)
Privacy Impact Assessments
Dedicated DPIA template; 10+ AI DPIAs/year; training data, automated decisions, bias risk, sub-processor review
Bias & Transparency Controls
Audit trail for automated decisions; bias testing before deployment; human review for High Risk
Staff Training
Privacy Champion network + governance training across organization


Risk Tier Examples

Unacceptable: Social scoring, real-time biometric surveillance (blocked regardless)
High Risk: AI grading, behavioral prediction, automated admissions (DPIA required + human oversight)
Limited Risk: AI chatbots, content recommendation (transparency notice required)
Minimal Risk: Spell check, scheduling, non-personalized analytics (inventory only)


5. Incident Response & Containment Protocol
Designed breach response playbooks for minor-data systems. Focus: SCA/ECPA violation detection, rapid isolation, forensics, legal hold.

Response Framework

Detect & Alert → Real-time anomalous access on Tier 4 triggers immediate escalation
Immediate Containment → Isolate affected data; revoke credentials; lock audit logs
Forensics & Evidence → Capture session recordings, access logs, communications
Legal Hold & Escalation → Dual sign-off; notify law enforcement + case parties per SCA
Remediation & Validation → Fix vulnerability; validate controls before re-enablement

Violation Types & Protocols | Violation | SCA/ECPA Risk | Action | |-----------|---------------|--------| | Unauthorized access to minor record | § 2703 violation | Law enforcement escalation | | Breach of SCA-protected communication | Wiretap Act exposure | Immediate legal review | | Improper disclosure to third party | COPPA/CCPA violation | Notify affected parties (72hr) | | Failure to execute legal hold | Evidence spoliation | Dual sign-off enforcement |

Target containment window: 72 hours


6. Compliance Audit Program
Internal auditing program validating controls, access tiers, retention, and regulatory compliance. Quarterly audits; zero control failures to production.

4 Systems Audited Quarterly

100% audit coverage target
14 control points per audit
0 production failures

Audit Pillars

Access Control Validation — Test Tier 1–4 enforcement; MFA/token; session recording; revocation on role change
Data Minimization & Classification — Verify only necessary fields collected; validate classification logic
Pseudonymization & Redaction — Sample case files; test automated redaction pipelines
Retention & Deletion — Validate auto-expiry; test legal holds; confirm backup deletion
Regulatory Alignment — Map controls to legal basis (ECPA, SCA, COPPA, GDPR, HIPAA); review incident logs


7. Privacy Program Architecture (Process)
Weeks 1–4: Discovery & Inventory

Data flow mapping
Asset inventory
ROPA documentation
Legal basis documentation

Weeks 3–8: Policy & Governance

Privacy policy suite
DSAR intake & response procedures
Incident response plan
Data retention schedule

Weeks 6–12: Risk Assessment

PIAs/DPIAs for high-risk systems
Vendor risk assessments
Third-party contract & DPA reviews

Weeks 8–16: Controls & Automation

DSAR intake automation
Consent management
Tiered access controls
Pseudonymization & redaction workflows

Weeks 14–18: Trial Run & Validation

Full program trial
Stress-test workflows
Validate controls
Confirm stakeholder readiness


Professional Experience
Privacy & Governance Architect (Volunteer)
Havenwatch Foundation for Child Protection | Remote | 2026 – Present

See detailed work above.



High School Teacher & Privacy Contributor
Triad Math & Science Academy | North Carolina | 2023 – Present

Contributed to privacy policy updates and principal handbook development for 10-campus EdTech organization
Advised on student data handling (FERPA compliance) and staff privacy guidance
Coached 50+ students annually; managed multi-stakeholder coordination



Certified ELA Teacher
Multiple Schools | 2012 – 2023

Managed student records and health-related PII across 11+ years of teaching
Ensured FERPA compliance and data confidentiality protocols


Education
MS, Cybersecurity & Data Privacy Law
Albany Law School | New York | 2021 – 2023

BA, Political Science
University of Missouri–St. Louis | 2011


Certifications & Tools
Certifications

HIPAA Certified
CIPP/US (Expected Q3 2026)
AIGP (Expected Q4 2026)

Tools & Frameworks

TrustArc, Microsoft 365, Azure Compliance
Google Workspace
NIST Privacy Framework, ISO 27701/27001
AI-RMF

Languages & Standards

GDPR, CPRA, LGPD, HIPAA, FERPA, ECPA/SCA, COPPA, EU AI Act
DPA Drafting & Negotiation
Privacy-by-Design
Incident Response & Breach Classification


What I'm Looking For
Roles: Privacy Manager, DPO (Data Protection Officer), Privacy Compliance Engineer, Privacy Program Manager

Organization types: EdTech, SaaS, child safety, healthcare, regulated environments

What matters to me: Building compliance programs from scratch, designing vendor frameworks, cross-functional program leadership, technical privacy controls, incident response readiness

Arrangement: Remote or hybrid (NY/NC preferred)


Let's Connect
Email: durray25@gmail.com
Phone: (845) 665-8202
GitHub: github.com/durrayk-privacy


