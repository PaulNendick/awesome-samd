
# Awesome Software as a Medical Device (SaMD) [![Awesome](https://awesome.re/badge.svg)](https://awesome.re)

> 🩻 A curated list of awesome resources for creating Software as a Medical Device (SaMD)

## Contents

- [Quality Management](#quality-management)
- [SaMD Software Development Life Cycle](#samd-sdlc)
	- [Software Architectural Design](#software-architectural-design)
	- [Software Detailed Design](#software-detailed-design)
	- [Software Unit Implementation and Verification](#software-unit-implemenation-and-verification)
	- [Software Integration and Integration Testing](#software-integration-and-integration-testing)
	- [Software System Testing](#software-system-testing)
	- [Software Release](#software-release)
- [Security](#security)
- [AI and ML](#ai-and-ml)


## Quality Management
- [OpenRegulatory Templates](https://github.com/openregulatory/templates) - Templates for ISO 13485, IEC 62304, ISO 14971 and ISO 62366 compliance.

## SaMD Software Development Life Cycle

### Software Requirements Management
Requirements engineering in medical device software (IEC 62304) is the systematic process of defining, documenting, and maintaining safety and functional requirements that ensure software meets intended use while complying with regulatory standards. It involves rigorous risk management, traceability, and verification to establish that the software functions safely within its medical context.
- [Doorstop](https://github.com/doorstop-dev/doorstop) - Requirements management using version control.
- [rtm_doorstop](https://github.com/asimon-1/rtm_doorstop) - A tool to generate Requirement Traceability Matrices (RTMs) from Doorstop documents.
- [Reqflow](https://goeb.github.io/reqflow/) - Reqflow is a free and open-source tool for traceability of requirements across documents, designed to analyse documents with speed and efficiency.
- [rmToo](https://github.com/florath/rmtoo) - Free and Open Source Requirements Management Tool. 
- [OSRMT](https://github.com/osrmt/osrmt) - Open Source Requirements Management Tool for defining and managing software requirements.
- [RDM](https://github.com/innolitics/rdm) - Regulatory Documentation Manager. Streamlines 62304, 14971, and 510(k) documentation for software projects.
- [Tuleap](https://www.tuleap.org/) - ALM
### Software Architectural Design
- [C4 Model](https://c4model.com/) - The C4 model is a lean graphical notation technique for modelling the architecture of software systems.
- [Gaphor](https://gaphor.org/) - Gaphor is a UML, SysML, RAAML, and C4 modelling application written in Python.
- [Cairis](https://cairis.org/) - An open source platform for building security and usability into your software
- [Archi](https://www.archimatetool.com/) - The Open Source modelling toolkit for creating ArchiMate models and sketches.
- [Modelio](https://www.modelio.org/index.htm) - The Open Source Modelling Environment.

### Software Unit Implementation and Verification
- [Ferrocene](https://ferrocene.dev/en/) - Ferrocene, a Rust compiler toolchain, is the first open-source toolchain to achieve IEC 62304 Class C qualification for medical device software, enabling developers to use Rust for safety-critical applications in the medical industry.
### Software Integration and Integration Testing
### Software System Testing
- [SonarQube](https://github.com/SonarSource/sonarqube) - : SonarQube  is a powerful open-source platform that can perform static code analysis for a wide range of programming languages, helping to identify potential bugs, security vulnerabilities, and code quality issues without executing the code. 
#### Cybersecurity Risk Management
- [Dependency-Track](https://dependencytrack.org/) - OWASP Dependency-Track is an intelligent Component Analysis platform that allows organisations to identify and reduce risk in the software supply chain. Consumes SBOM to identify associated CVEs.
- [OWASP Threat Dragon](https://owasp.org/www-project-threat-dragon/)
- [Microsoft Threat Modelling Tool](https://learn.microsoft.com/en-us/azure/security/develop/threat-modeling-tool)
- [Microsoft Threat Modelling Templates](https://github.com/microsoft/threat-modeling-templates)
- [AWS Threat Composer](https://awslabs.github.io/threat-composer/workspaces/default/dashboard)
- [Threagile](https://threagile.io/) - Threagile is the open-source toolkit which allows users to model an architecture with its assets in an agile declarative fashion as a YAML file directly inside the IDE or any YAML editor.
- [IriusRisk](https://www.iriusrisk.com/community) - An automated threat modelling tool built atop draw.io.
- [Aristiun](https://threat-modeling.com/) - Aristiun gives some helpful example use cases, for example using STRIDE in a healthcare organisation, this tool is a good place to start to increase threat modelling knowledge
- [Interlynk](https://github.com/interlynk-io) - Interlynk open source toolset for making Software Bill of Materials (SBOM) operational in DevSecOps.
- [](https://app.interlynk.io/) - hosted app that checks SBOMs for NTIA and FDA fields
- [Snyk SBOM Checker](https://snyk.io/code-checker/sbom-security/)
- [CycloneDX](https://cyclonedx.org/) - OWASP CycloneDX is a full-stack Software Bill of Materials (SBOM) standard that provides advanced supply chain capabilities for cyber risk reduction.
- [CycloneDX Tools](https://cyclonedx.org/tool-center/) - Open source and proprietary tools that support the CycloneDX standard.
- [SPDX](https://spdx.dev/) - An open standard capable of representing systems with software components in as  Software Bill of Materials (SBOMs) and other AI, data and security references supporting a range of risk management use cases.
- [SPDX Tools](https://spdx.dev/use/spdx-tools/) - Open source and proprietary tools that support the SPDX SBOM standard.
- [Syft](https://github.com/anchore/syft) - A command line tool and Go library for generating SBOMs from container images and filesystems. Works seamlessly with [Grype](#grype).
- [DecoderRing](https://github.com/DanBeard/DecoderRIng)
- [](https://github.com/spdx/spdx-online-tools)
- [](https://github.com/lfscanning)
- [](https://github.com/CycloneDX/bom-examples)
- [](https://github.com/CERTCC/SBOM/)
- [](https://github.com/a13xh7/QaraTMS)
- [Kiwi TCMS](https://kiwitcms.org/)


### Software Release
- [Grype](https://github.com/anchore/grype) - A vulnerability scanner for container images and filesystems. Works seamlessly with [Syft](#syft), SPDX, and CycloneDX SBOM formats.
- [Betterscan](https://github.com/tcosolutions/betterscan) - Code Scanning/SAST/Static Analysis/Linting using many tools/Scanners with One Report (Code, IaC)
- [Trivy](https://github.com/aquasecurity/trivy) - Find vulnerabilities, misconfigurations, secrets, SBOM in containers, Kubernetes, code repositories, clouds and more.


## Security

- [Premarket Cybersecurity Guidance](https://www.fda.gov/regulatory-information/search-fda-guidance-documents/content-premarket-submissions-management-cybersecurity-medical-devices) - US FDA cybersecurity guidance

## AI and ML

- [AI/ML-Based SaMD Action Plan](https://www.fda.gov/medical-devices/software-medical-device-samd/artificial-intelligence-and-machine-learning-software-medical-device) - US FDA's approach to AI/ML
- [PLOT4ai](https://plot4.ai/) - A threat modelling library to help you build responsible AI.
- [LINDDUN](https://linddun.org/) - Privacy threat modelling methods.


## Contribute

Contributions welcome! Read the [contribution guidelines](contributing.md) first.

## License

[![CC0](https://mirrors.creativecommons.org/presskit/buttons/88x31/svg/cc-zero.svg)](https://creativecommons.org/publicdomain/zero/1.0/)
