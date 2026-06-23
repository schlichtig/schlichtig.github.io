---
layout: single
title: "Research"
permalink: /research/
author_profile: true
---

My research lies at the intersection of **program analysis**, **human-centered software engineering**, and **AI-assisted secure software** — increasingly, *software engineering with and for AI*. The long-term goal is to build security-relevant analysis tools that developers actually use, and to combine them with AI so that tools not only detect problems but help developers fix them, while keeping AI-based systems themselves analyzable, testable, and trustworthy.

## Research Lines

**AI-Assisted Repair of Cryptographic API Misuses**
Studying how static analysis (SAST) tools can guide large language models toward *correct* repairs of cryptographic API misuses — supplying the violated constraint, the relevant code path, and the specification as structured context to reduce hallucination and improve fix correctness, evaluated on the CamBench benchmark. This line moves software analysis from *detecting* defects to *fixing* them with AI.

**SecAI — AI-supported Security Testing**
A SonarQube plugin that integrates LLM-assisted repair, false-positive prediction, and usability principles, surfacing prioritized, explainable, and fixable warnings inside a development environment practitioners already use. Built in a one-year master's project group I independently conceived and led (Winter 2024 – Summer 2025). [Project page](https://www.hni.uni-paderborn.de/en/sse/lehre/projektgruppen-vergangener-semester/ss-ws-ai-supported-security-testing) · [Plugin docs](https://secure-software-engineering.github.io/CogniCryptSQPlugin/latest/)

## Completed Projects

**API\_ASSIST** *(BMBF Software Campus, 2023–2024)*
BMBF-funded research project (100,000 EUR) on specifiable API misuse detection and developer-facing tool integration in CI pipelines, conducted in cooperation with Trumpf SE + Co. KG. PI: Schlichtig. Results published at SANER 2022 and ICSE 2024.

**DFG CRC CROSSING** *(Subproject E1, 2019–2026)*
Maintainer of CogniCrypt within the DFG Collaborative Research Center 1119 on cryptography engineering. Static analysis using the CrySL specification language, with CI/CD integration.

## Grants & Funding

| Project | Funder | Amount | Role | Period |
|---|---|---|---|---|
| API\_ASSIST | BMBF Software Campus | 100,000 EUR | **Principal Investigator** | 2023–2024 |

## Awards

- **[CROSSING Collaboration Award](https://www.crossing.tu-darmstadt.de/crc_1119/awards_crossing/collaboration_award/collaboration_award.en.jsp)** — CRC 1119 CROSSING, TU Darmstadt, 2021. For work on QKD post-processing software (with Wickert, Schickel, Weber, Fitzke, Nikiforov, Sauer, Tippmann).

## Artifacts and Repositories

- **CamBench** — Benchmark suite for cryptographic API misuse detection tools. [github.com/CROSSINGTUD/CamBench](https://github.com/CROSSINGTUD/CamBench)
- **CogniCrypt** — Plugin for cryptographic API misuse detection. [github.com/CROSSINGTUD/CryptoAnalysis](https://github.com/CROSSINGTUD/CryptoAnalysis)
- **FUM** — Framework for API Usage Constraint and Misuse Classification. Published at SANER 2022.
