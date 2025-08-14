# CIS Benchmarks (Center for Internet Security)
CIS Benchmarks are consensus-based, best practice security configuration guides developed and maintained by cybersecurity experts, government, and industry professionals. These benchmarks provide step-by-step guidance to securely configure IT systems, applications, and network devices.
### Key Features
- Platform-specific: Available for operating systems (e.g., Windows, Linux), cloud environments (e.g., AWS, Azure), applications (e.g., Apache, MySQL), and network devices.
- Different levels of security based on the business requirements.
- Used for:
  -  Hardening servers and systems
  -  Establishing secure baselines
  -  Compliance with standards like NIST, ISO 27001, HIPAA, PCI-DSS
## CIS Microsoft Windows Server 2022 Benchmark
The Microsoft Windows Benchmarks are written for Active Directory domain-joined systems using Active Directory’s Group Policy Manager only. This benchmark is not intended for use on standalone or workgroup systems,systems joined to a cloud offering, such as Entra ID, or systems created, maintained, or used in the Cloud
This benchmark covers supported endpoint states for Active Directory and Entra Hybrid joined systems that receive policies from Active Directory Group Policy Manager only.

### Profile Definitions
The following configuration profiles are defined in this Benchmark:

| **Profile Name**                                         | **Target Role**        | **Security Level**        | **Description**                                                                                                                                                             |
| -------------------------------------------------------- | ---------------------- | ------------------------- | --------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| **Level 1 – Domain Controller**                          | Domain Controller      | Basic Security            | Designed to be practical and minimally intrusive, while providing essential security settings. Suitable for most domain controllers without impacting functionality.        |
| **Level 1 – Member Server**                              | Member Server (non-DC) | Basic Security            | Applies core security configurations with minimal impact to operations. Suitable for general-purpose servers joined to a domain.                                            |
| **Level 2 – Domain Controller**                          | Domain Controller      | Enhanced/Strict Security  | Applies stricter policies for environments requiring higher security. May affect functionality or compatibility with certain applications.                                  |
| **Level 2 – Member Server**                              | Member Server (non-DC) | Enhanced/Strict Security  | Provides stronger hardening for member servers, ideal for high-security environments or systems with sensitive data.                                                        |
| **Next Generation Windows Security – Domain Controller** | Domain Controller      | Advanced, Modern Security | Leverages modern Windows security features (e.g., Credential Guard, Device Guard, virtualization-based security). Recommended for modern, enterprise-grade infrastructures. |
| **Next Generation Windows Security – Member Server**     | Member Server (non-DC) | Advanced, Modern Security | Applies next-gen security technologies for member servers, requiring Windows Server 2019+ and hardware that supports advanced features.                                     |
