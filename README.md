# Awesome-Know-Your-Customer-KYC-Identity-Orchestrator

## Top Know Your Customer (KYC) Identity Orchestrator Ecosystem



**Curated List of SaaS Products & Open-Source GitHub Projects**  

*Focused on Document Verification, Facial Liveness & Multi-Modal Identity Pipelines*  

**Last updated: October 2026**



This repository tracks notable **SaaS platforms** and **open-source projects** for **Know Your Customer (KYC) Identity Orchestration**. These tools enable organizations to verify user identities through multi-modal pipelines—document capture, OCR, facial biometrics, liveness detection, and AML screening—while maintaining compliance and audit trails.



**Examples** include Persona, Trulioo, Veriff, Sumsub, Onfido, Jumio, IDnow, Alloy, Middesk, and Passbase (the category leaders).



**Open-source emphasis**: This section is heavily expanded with every major active project for self-hosting, document processing, and open facial analysis—ideal for fintech developers, compliance engineers, and organizations seeking transparent, vendor-independent identity verification.



Contributions welcome! Open a PR to add/update entries. Keep descriptions factual and link to official sites.



## Table of Contents

- [SaaS/Hosted Platforms](#saas-hosted-platforms)

- [Open-Source GitHub Projects](#open-source-github-projects)

- [How to Contribute](#how-to-contribute)

- [Disclaimer](#disclaimer)



## SaaS/Hosted Platforms



- **[Persona](https://withpersona.com/)**  

  Identity platform with **document verification in 200+ countries**, business verification (KYB) in 100+ countries, and global PEP/sanctions screening across 100+ watchlists . Features **no-code workflow builder**, passive signals, liveness detection, real-time link analysis, and case management. **Trusted by Twilio, Square Capital, and Lime** .



- **[Trulioo](https://www.trulioo.com/)**  

  Global identity verification platform with document verification, database checks, and business verification across 195+ countries.



- **[Veriff](https://www.veriff.com/)**  

  AI-powered identity verification platform. Features document verification, facial biometrics, liveness detection, and AML screening.



- **[Sumsub](https://sumsub.com/)**  

  All-in-one identity verification and compliance platform. Features KYC, KYB, AML screening, and transaction monitoring.



- **[Onfido](https://onfido.com/)**  

  Identity verification platform with document capture, facial biometrics, and liveness detection. Widely used in fintech and financial services.



- **[Jumio](https://www.jumio.com/)**  

  AI-powered identity verification and AML screening platform. Features document verification, facial recognition, and liveness detection.



- **[IDnow](https://www.idnow.io/)**  

  European identity verification platform with video-based verification and automated document checks.



- **[Alloy](https://www.alloy.com/)**  

  Identity risk platform with KYC/KYB orchestration, fraud detection, and AML screening.



- **[Middesk](https://www.middesk.com/)**  

  Business identity verification (KYB) platform. Features business registry checks, beneficial ownership, and compliance.



- **[Passbase](https://passbase.com/)**  

  Identity verification platform with document checks, facial biometrics, and liveness detection.



## Open-Source GitHub Projects



- **[Ballerine](https://github.com/ballerine-io/ballerine)**  

  **The most comprehensive open-source infrastructure for identity and risk management** (Y Combinator-backed) . Features **KYC/KYB UI flows**, **case management dashboard**, **integrations with identity verification providers**, and a **rule engine** to automate decisioning . **The leading open-source alternative to Persona or Onfido.** Self-hosted with full customization. MIT licensed.



- **[Clarium](https://github.com/QuantSingularity/Clarium)**  

  **RegTech compliance module with FastAPI KYC/AML engine** (open-source) . Features **KYC pipeline** (submit, upload document, status, review queue), **AML transaction monitoring** with four rules (amount threshold, velocity, geographic risk, PEP matching), **hash-chained audit trail** (SHA-256, tamper-detectable), **jurisdiction rules** (US, GB, EU, SG, AE), and **HMAC-signed webhooks** . **The most complete open-source KYC/AML orchestration backend available.**



- **[UniFace](https://pypi.org/project/uniface/)**  

  **All-in-one face analysis library** (MIT, PyPI) . **The most comprehensive open-source facial processing pipeline for KYC.** Features **face detection** (RetinaFace, SCRFD, YOLOv5-Face, YOLOv8-Face), **face recognition** (AdaFace, ArcFace, EdgeFace, MobileFace), **anti-spoofing** (MiniFASNet), **gaze estimation**, **head pose estimation**, **age/gender/race analysis** (FairFace), and **vector store** (FAISS) for fast multi-identity search . **Note**: YOLOv5-Face/YOLOv8-Face weights are GPL-3.0; FairFace is CC BY 4.0—verify licensing for commercial use .



- **[liveness-detector](https://pypi.org/project/liveness-detector/)**  

  **Gesture-based facial liveness detector** (AGPL-3.0, PyPI) by 2060.io . Uses **randomized facial gesture challenges** (blink, smile, head turn) to defeat replay and spoof attacks. Features **C++/MediaPipe core**, customizable gestures and locales via JSON, and **all processing local by default** . **The most focused open-source liveness detection library.**



- **[django-camera-kit](https://pypi.org/project/django-camera-kit/)**  

  **Document scanning and KYC face verification widgets for Django** (open-source) . Features **live document edge detection** with manual corner adjustment, **multi-page PDF assembly**, and **KYC module with selfie/ID capture, embedding comparison, and head-movement liveness challenge** . Requires PostgreSQL with pgvector. **The most complete open-source Django-native KYC toolkit.**



- **[personal_validation_system](https://pub.dev/packages/personal_validation_system)**  

  **Flutter plugin for identity verification** (open-source) . Provides document validation, face matching, and personal information verification. **The most accessible open-source KYC plugin for Flutter mobile apps.**



- **[FaceVault](https://docs.hollaex.com/plugins/use-plugins/facevault-automatic-kyc)**  

  **Fully open-source KYC plugin for HollaEx exchanges** . Features **hosted verification flow** (government ID capture, OCR, selfie liveness, face matching, anti-spoofing), **trust score (0-100)** with accept/review/reject decision, and **webview-only integration** . **The most complete open-source KYC plugin for crypto exchanges.**



- **[open-kyc](https://github.com/College-Canine/open-kyc)**  

  **Open-source KYC solution for free compliance** (TypeScript, open-source) . Community project enabling free KYC compliance. Early-stage but demonstrates the open-source approach.



- **[org.id](https://github.com/windingtree/org.id)**  

  **Self-Sovereign Identity (SSI) solution for organizations** (open-source) . W3C-DID compliant decentralized business registry. **The most standards-compliant open-source KYB solution** for organizations seeking decentralized identity.



- **[pykolofinance](https://pypi.org/project/pykolofinance/)**  

  **Python utility package for banking microservices with KYC verification** (open-source) . Features KYC integration with **Dojah** (Nigerian identity provider) for **BVN, NIN, and BVN_SELFIE** verification types, JWT authentication, and audit logging . **The most focused open-source KYC integration for African banking.**



- **[crypto-aml](https://pypi.org/project/crypto-aml/)**  

  **Crypto AML/KYT Python SDK** (open-source) . Features **address risk screening** with AnChain.AI integration, **graph visualization**, and **exchange whitelist policy** patterns. Risk score bands: 0-29 LOW, 30-50 GUARDED, 51-79 ELEVATED, 80-100 SEVERE . **The most exchange-integration-ready open-source crypto AML SDK.**



- **[tf-kyc-verifier](https://pkg.go.dev/github.com/threefoldtech/tf-kyc-verifier)**  

  **KYC verification service for ThreeFold** (Go, open-source) . Features **iDenfy webhook integration**, verification tokens, sponsorship APIs, and **Swagger documentation** . **The most focused open-source KYC verification service for decentralized infrastructure.**



- **[idverification (authsome)](https://pkg.go.dev/github.com/xraph/authsome/plugins/enterprise/idverification)**  

  **Go plugin for identity verification with multi-provider support** (open-source) . Features **verification sessions**, **middleware for access control** (RequireDocumentVerified, RequireAMLClear, RequireAge), **webhook handling**, and **verification status checks** . **The most complete open-source KYC middleware for Go applications.**



### Additional Strong Open-Source Options



- **[MiniAiLive ID Document Recognition](https://github.com/MiniAiLive/ID-DocumentRecognition-Linux)** — Intelligent ID OCR for identity verification (open-source). Linux, Windows, and server SDKs .

- **[kby-ai IDCardRecognition](https://github.com/kby-ai/IDCardRecognition-Docker)** — ID document recognition for ID card, passport, and driver license (open-source). Windows, Docker, iOS, Android, and Flutter SDKs .

- **[FaceOnLive Face-Liveness-Detection-SDK](https://github.com/FaceOnLive/Face-Liveness-Detection-SDK-Linux)** — Face anti-spoofing server SDK (open-source) .

- **[recognito-vision iOS SDK](https://github.com/recognito-vision/iOS-FaceRecognition-FaceLivenessDetection)** — NIST FRVT Top 1 Face Recognition and Liveness Detection iOS SDK (open-source) .

- **[passive_liveness](https://pub.dev/packages/passive_liveness)** — Flutter passive liveness detection with MiniFAS model (open-source) .

- Community **n8n** workflows for KYC verification routing and alert automation.



**Frameworks for building custom systems**: Combine **Ballerine** for KYC/KYB orchestration with **Clarium** for KYC/AML backend, **UniFace** for facial recognition and anti-spoofing, **django-camera-kit** for document capture and liveness, and **PostgreSQL** for persistence—creating a fully self-hosted, enterprise-grade identity verification platform.



## How to Contribute



1. Fork the repo.

2. Add/edit entries in `README.md` (follow existing format).

3. Include: name, link, 1–2 sentence description, and whether it's SaaS or open-source.

4. Submit PR with a short explanation.



Star the repo if you find it useful!



## Disclaimer



- This is a **community-curated** list — not exhaustive and not an endorsement.

- KYC identity verification systems handling biometric and document data must comply with **GDPR, CCPA, BIPA, AML directives, and local identity regulations**. **Legal review and qualified compliance expertise remain essential**—tools support automation, not legal advice.

- **Open-source KYC orchestration is maturing but incomplete.** Ballerine provides the most comprehensive open-source identity infrastructure with UI flows, case management, and rule engine . Clarium provides the most complete KYC/AML backend with hash-chained audit trails . UniFace provides production-grade facial analysis . **No single open-source tool provides the end-to-end global coverage of Persona or Trulioo.** Integration work is required.

- **Liveness detection is critical for fraud prevention.** liveness-detector uses randomized gesture challenges to defeat replay and spoof attacks . UniFace includes MiniFASNet anti-spoofing . **Passive liveness (miniFAS) is more user-friendly but less robust than active challenge-based detection.**

- **Model licensing matters for commercial use.** UniFace is MIT-licensed, but YOLOv5-Face/YOLOv8-Face weights are GPL-3.0, and FairFace is CC BY 4.0 . **Verify licensing for every model before commercial deployment.**

- **Audit trails are mandatory for compliance.** Clarium's hash-chained audit trail (SHA-256, tamper-detectable) provides the evidence integrity that regulators require . **Without tamper-evident logging, compliance evidence is worthless.**

- **On-premise processing matters for data sovereignty.** liveness-detector processes all data locally by default . **This is critical for jurisdictions with strict data localization requirements.**

- Self-hosted open-source solutions require proper security hardening, biometric data protection, and ongoing maintenance. **Biometric data is irreversible—if compromised, it cannot be reset like a password.** Access controls and encryption are non-negotiable.



---



**Made for fintech developers, compliance engineers, and developers building transparent KYC identity solutions.**  

Let's make Know Your Customer Identity Orchestration more open, data-driven, and privacy-preserving.
