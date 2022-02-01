---
author: [Felicitas Pojtinger]
date: "2022-02-01"
subject: "Uni App Security Themes"
keywords: [secops, pentesting, appsec, it-security, hdm-stuttgart]
subtitle: "Themes for the Anwendungssicherheit (app security) course at HdM Stuttgart"
lang: "en"
---

# Uni App Security Themes

## Introduction

### Contributing

These study materials are heavily based on [professor Heuzeroth's "Anwendungssicherheit" lecture at HdM Stuttgart](https://www.hdm-stuttgart.de/studierende/abteilungen/sprachenzentrum/kursangebot/kursangebot/block?sgname=Medieninformatik+%28Bachelor%2C+7+Semester%29&blockname=Anwendungssicherheit&sgblockID=2573375&sgang=550033).

**Found an error or have a suggestion?** Please open an issue on GitHub ([github.com/pojntfx/uni-appsecurity-notes](https://github.com/pojntfx/uni-appsecurity-notes)):

![QR code to source repository](./static/qr.png){ width=150px }

If you like the study materials, a GitHub star is always appreciated :)

### License

<!-- ![AGPL-3.0 license badge](https://www.gnu.org/graphics/agplv3-155x51.png){ width=128px } -->

Uni App Security Themes (c) 2022 Felicitas Pojtinger and contributors

SPDX-License-Identifier: AGPL-3.0
\newpage

### Themes

- Basics and Security Objectives (8 points)
  - CIA triad
  - Definition of security & safety
  - Definition of software security & safety
  - How do software security issues occur, and what are their causes?
  - What are risks, threats and vulnerabilities? (from the basics slides)
  - Ranking risks
  - Contradictions in software security (security vs vulernability)
- Secure Development Process (4 points): Data flow diagram (see STRIDE) and modelled system are given, analyze the secure development principles
- Buffer Overflow (10 points):
  - Screenshots from SL-Mail exploit are given, explain step by step (with parameters and tool names)
  - Include buffer overflow cheat sheet
  - Unique string search vs binary search
- Security of Web Applications (13 points):
  - OWASP Top 10 (names, explanation and example)
  - 2x: Bad example code is given, find, describe and execute possible attacks, show countermeasures
  - Attack vector is given, execute attack
  - Explain countermeasure to one of the OWASP 2021 attacks
- Secure Coding (10 points):
  - Explanation of program is given, find and fix the vulnerability
- Authentication and Authorization (5 points):
  - Authentication vs Authorization
  - Methods of authentication (knowledge, ownership or attributes)
  - What are OAuth2 refresh & access tokens?
