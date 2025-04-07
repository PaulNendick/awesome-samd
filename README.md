
# Awesome Software as a Medical Device (SaMD) [![Awesome](https://awesome.re/badge.svg)](https://awesome.re)

> 🩻 A curated list of awesome resources for creating Software as a Medical Device (SaMD)

## Contents

- [Standards and Guidelines](#standards-and-guidelines)
- [Quality Management](#quality-management)
- [SaMD Software Development Life Cycle](#samd-software-developement-life-cycle)
	- [Application Lifecycle Management](#application-lifecycle-management)
	- [Software Requirements Management](#software-requirements-management)
	- [Software Architectural Design](#software-architectural-design)
	- [Security Analysis](#security-analysis)
	- [Software Unit Implementation](#software-unit-implemenation)
	- [Verification and Validation](#verification-and-validatiom)
	- [Cybersecurity](#cybersecurity)
		- [Software Bill of Materials](#software-bill-of-materials)
- [Contribute](#contribute)
- [License](#license)

## Standards and Guidelines
Internationally recognised standards and guidelines relevant to the development of SaMD.
- [IBR Standards Portal](https://ibr.ansi.org/Standards/iso3.aspx) - read-only copy of ISO 13485 standard.
- [Premarket Cybersecurity Guidance](https://www.fda.gov/regulatory-information/search-fda-guidance-documents/content-premarket-submissions-management-cybersecurity-medical-devices) - US FDA cybersecurity guidance.
- [AI/ML-Based SaMD Action Plan](https://www.fda.gov/medical-devices/software-medical-device-samd/artificial-intelligence-and-machine-learning-software-medical-device) - US FDA's approach to AI/ML.

## Quality Management
Resources relevant to the processes, procedures, and responsibilities required to achieve and maintain consistent quality in SaMD products or services.

- [OpenRegulatory Templates](https://github.com/openregulatory/templates) - Templates for ISO 13485, IEC 62304, ISO 14971 and ISO 62366 compliance.

## SaMD Software Development Life Cycle
### Application Lifecycle Management
ALM manages the complete application lifecycle, covering governance, development, and maintenance across disciplines from requirements to release. ALM tools standardize team communication and automate development processes to achieve efficient, predictable software delivery.
- [Tuleap](https://www.tuleap.org/) - open source/freemium integrated Application Lifecycle Management (ALM) solution that combines portfolio, project management, and development tools with ISO 13485 and IEC 62304-specific capabilities.
- [Cairis](https://github.com/cairis-platform/cairis) - An open source platform for usability, requirements, and risk analysis.

### Software Requirements Management
Requirements engineering in SaMD is the systematic process of defining, documenting, and maintaining safety and functional requirements that ensure software meets intended use while complying with regulatory standards. It involves rigorous risk management, traceability, and verification to establish that the software functions safely within its medical context.
- [Doorstop](https://github.com/doorstop-dev/doorstop) - Requirements management using version control.
- [rtm_doorstop](https://github.com/asimon-1/rtm_doorstop) - A tool to generate Requirement Traceability Matrices (RTMs) from Doorstop documents.
- [rmToo](https://github.com/florath/rmtoo) - Free and Open Source Requirements Management Tool, optimised for command-line handling of requirements.
- [RDM](https://github.com/innolitics/rdm) - Regulatory Documentation Manager provides Markdown templates and Python scripts to manage IEC 62304, ISO 14971, and FDA 510(k) documentation.

### Software Architectural Design
Software architectural design focuses on creating a robust and safe structure for the software, ensuring it meets medical device standards and user needs, while also enabling lifecycle processes like agile development, verification, validation, and maintenance. 
- [C4 Model](https://c4model.com/) - The C4 model is a lean graphical notation technique for modelling the architecture of software systems.
- [Gaphor](https://github.com/gaphor/gaphor) - Gaphor is a UML, SysML, RAAML, and C4 modelling application written in Python.
- [Archi](https://www.archimatetool.com/) - The Open Source modelling toolkit for creating ArchiMate models and sketches.
- [Modelio](https://www.modelio.org/index.htm) - The Open Source Modelling Environment.

### Security Analysis
Threat modelling is a structured process that helps identify potential threats and vulnerabilities in medical devices early in the development lifecycle, allowing for the implementation of appropriate security measures. 

- [Threagile](https://threagile.io/) - Threagile is the open-source threat modelling toolkit which allows users to model an architecture with its assets in an agile declarative fashion as a YAML file directly inside the IDE or any YAML editor.
- [IriusRisk](https://www.iriusrisk.com/community) - An automated threat modelling tool built atop draw.io.
- [Aristiun](https://threat-modeling.com/) - Aristiun gives some helpful example use cases, for example using STRIDE in a healthcare organisation, this tool is a good place to start to increase threat modelling knowledge
- [PLOT4ai](https://plot4.ai/) - A threat modelling library to help you build responsible AI.
- [LINDDUN](https://linddun.org/) - Privacy threat modelling methods.
- [OWASP Threat Dragon](https://owasp.org/www-project-threat-dragon/) - creates threat model diagrams supporting STRIDE,  LINDDUN, CIA, DIE, and PLOT4ai methodologies. Generates modelling diagrams and implements a rule engine to auto-generate threats and their mitigations.
- [Microsoft Threat Modelling Tool](https://learn.microsoft.com/en-us/azure/security/develop/threat-modeling-tool) - Free threat modelling tool (Windows only).
- [Microsoft Threat Modelling Templates](https://github.com/microsoft/threat-modeling-templates) - templates for above including for a medical device.
- [AWS Threat Composer](https://github.com/awslabs/threat-composer) - Open source threat modelling tool.
### Software Unit Implementation
Software unit implementation is a critical phase in the software development lifecycle where developers translate designs and specifications into actual, working code. 
- [Ferrocene](https://ferrocene.dev/en/) - Ferrocene, a Rust compiler toolchain, is the first open-source toolchain to achieve IEC 62304 Class C qualification for medical device software, enabling developers to use Rust for safety-critical applications in the medical industry.

### Verification and Validation
Verification and validation are the two essential processes used to ensure the quality of a SaMD product or system. Verification checks if the product is built correctly according to specifications, while validation checks if the product meets the user's needs and requirements. 
- [QaraTMS](https://github.com/a13xh7/QaraTMS) - open source test management software for managing test suites, test cases, test plans, test runs and documentation.
- [Kiwi TCMS](https://kiwitcms.org/) - open source test management system for both manual and automated testing. It features bug tracker integration (JIRA, ADO, more), search, access control, test automation framework plugins, visual reports and an API layer.

### Cybersecurity
Cybersecurity focuses on protecting patient data and ensuring the safe and reliable operation of the SaMD, encompassing data privacy, authentication, vulnerability management, secure software development, and incident response planning. 
- [SonarQube](https://github.com/SonarSource/sonarqube) - SonarQube  is a powerful open-source platform that can perform static code analysis (SAST) for a wide range of programming languages, helping to identify potential bugs, security vulnerabilities, and code quality issues without executing the code. 
- [Betterscan](https://github.com/tcosolutions/betterscan) - Code Scanning/SAST/Static Analysis/Linting using many tools/Scanners with One Report (Code, IaC)
- [OWASP ZAP](https://www.zaproxy.org/) - OWASP ZAP (Zed Attack Proxy) is a free, open-source web application security scanner and penetration testing tool developed by the Open Web Application Security Project (OWASP) that helps identify vulnerabilities in web applications. 
### Software Bill of Materials 
A Software Bill of Materials (SBOM) is a comprehensive list of all the software components used in a product, including open-source libraries, third-party components, and proprietary software. The SBOM helps identify what software is running within the device, providing transparency and allowing for effective management of vulnerabilities.
- [Trivy](https://github.com/aquasecurity/trivy) - Find vulnerabilities, misconfigurations, secrets, SBOM in containers, Kubernetes, code repositories, clouds and more.
- [OWASP Dependency-Track](https://dependencytrack.org/) - OWASP Dependency-Track is an intelligent Component Analysis platform that allows organisations to identify and reduce risk in the software supply chain. Consumes SBOM to identify associated CVEs.
- [OWASP Dependency-Check](https://owasp.org/www-project-dependency-check/) - OWASP Dependency-Check is a Software Composition Analysis (SCA) tool that attempts to detect publicly disclosed vulnerabilities contained within a project’s dependencies.
- [Interlynk](https://github.com/interlynk-io) - Interlynk open source toolset collection for making Software Bill of Materials (SBOM) operational in DevSecOps.
- [app.interlynk.io](https://app.interlynk.io/) - freemium online collaboration platform that automates CVE checks for  SBOMs across NTIA and FDA fields.
- [CycloneDX](https://cyclonedx.org/) - OWASP CycloneDX is a full-stack Software Bill of Materials (SBOM) standard that provides advanced supply chain capabilities for cyber risk reduction.
- [CycloneDX Tools](https://cyclonedx.org/tool-center/) - Open source and proprietary tools that support the CycloneDX standard.
- [CycloneDX Examples](https://github.com/CycloneDX/bom-examples) - A repository with examples of CycloneDX BOMs (SBOM, SaaSBOM, OBOM, VEX, etc)
- [SPDX](https://spdx.dev/) - An open standard capable of representing systems with software components in as  Software Bill of Materials (SBOMs) and other AI, data and security references supporting a range of risk management use cases.
- [SPDX Tools](https://spdx.dev/use/spdx-tools/) - Open source ([spdx/spdx-online-tools](https://github.com/spdx/spdx-online-tools)) and proprietary tools that support the SPDX SBOM standard.
- [Syft](https://github.com/anchore/syft) - A command line tool and Go library for generating SBOMs from container images and filesystems. Works seamlessly with [Grype](#grype).
- [Grype](https://github.com/anchore/grype) - A vulnerability scanner for container images and filesystems. Works seamlessly with [Syft](#syft), SPDX, and CycloneDX SBOM formats.


## Contribute

Contributions welcome! Read the [contribution guidelines](contributing.md) first.

## License

[![CC0](https://mirrors.creativecommons.org/presskit/buttons/88x31/svg/cc-zero.svg)](https://creativecommons.org/publicdomain/zero/1.0/)
