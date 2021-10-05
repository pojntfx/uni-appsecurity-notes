% Uni App Security Notes
% Felicitas Pojtinger
% \today
\tableofcontents
\newpage

# Uni App Security Notes

## Introduction

### Contributing

These study materials are heavily based on [professor Heuzeroth's "Anwendungssicherheit" lecture at HdM Stuttgart](https://www.hdm-stuttgart.de/studierende/abteilungen/sprachenzentrum/kursangebot/kursangebot/block?sgname=Medieninformatik+%28Bachelor%2C+7+Semester%29&blockname=Anwendungssicherheit&sgblockID=2573375&sgang=550033).

**Found an error or have a suggestion?** Please open an issue on GitHub ([github.com/pojntfx/uni-appsecurity-notes](https://github.com/pojntfx/uni-appsecurity-notes)):

![QR code to source repository](./static/qr.png){ width=150px }

If you like the study materials, a GitHub star is always appreciated :)

### License

![AGPL-3.0 license badge](https://www.gnu.org/graphics/agplv3-155x51.png){ width=128px }

Uni App Security Notes (c) 2021 Felicitas Pojtinger and contributors

SPDX-License-Identifier: AGPL-3.0
\newpage

## Organization

- 60 Minutes of test at the end
- Will have practical examples
- Threat detection plays a fundamental role in tests

## Overview

### Elements of a Secure Development Process

**Primary purpose**: Analysis of the data flow; data is both protected by the GDPR and represents value of the coporation

- **Requirements**
  - Security-Requirements
  - Anti-Requirements
  - Abuse cases
  - Protection poker
  - → **Security analysis/architecture analysis**
- **Draft**
  - AuthN/AuthZ
  - Drafting concepts
  - **Risk modelling**
- **Implementation**
  - Secure implementation guidelines
  - **Code review, dynamic analysis**
- **Tests**
  - Security testing plans
  - Security testing cases
  - **Ethical hacking, pentesting, dynamic analysis**
- **Operations/Maintenance**
  - Secure initial settings
  - Assumptions of runtimes
  - Observation of logs
  - **Processes for management and reaction to breaches**
- **Documentation**
  - Installation
  - Configuration
  - Customization
  - Operations
  - → **Impact area of security incidents must be visible\***

### Support Hierarchy

- **Level 1**: Direct support with customers; call center, non-technical
- **Level 2**: People who know about typical problems with the software
- **Level 3**: Developers of the software
