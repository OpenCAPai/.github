# OpenCAPai: Enterprise AI via SAP CAP & SAP AI Core

Welcome to the **OpenCAPai** organization. Our mission is to provide a standardized, modular, and production-ready ecosystem for integrating **SAP AI Core** capabilities into the **SAP Cloud Application Programming Model (CAP)**.

## 🎯 Objective

As Generative AI moves from experimentation to enterprise integration, the need for a structured framework becomes paramount. This organization focuses on:
* **Reference Architectures:** Implementing Clean Core compliant AI patterns.
* **Seamless Integration:** Leveraging the `sap-ai-sdk` within the CAP lifecycle.
* **Scalability:** Best practices for handling Vector Engines (SAP HANA Cloud) and LLM orchestration.

---

## 🛠 Tech Stack

We leverage the full power of the SAP Business Technology Platform (BTP):
* **Core Framework:** [SAP CAP](https://cap.cloud.sap/) (Node.js & Java)
* **AI Orchestration:** [SAP AI Core](https://help.sap.com/docs/sap-ai-core) & AI Launchpad
* **Data Foundation:** SAP HANA Cloud (Vector Engine)
* **SDKs:** SAP Cloud SDK & SAP AI SDK for SAP Cloud Application Programming Model

---

## 📂 Repository Structure

All projects within this organization follow a strict architectural pattern:

| Repository | Description |
| :--- | :--- |
| `cap-ai-boilerplate` | A foundational template for CAP + AI Core integration. |
| `cap-ai-rag-pattern` | Reference implementation of Retrieval-Augmented Generation using HANA Vector Engine. |
| `cap-ai-middleware` | Utilities for managing AI Core deployment cycles and grounding. |

---

## 🚀 Getting Started

To utilize the resources in this organization, ensure you have:
1. An active **SAP BTP** subaccount.
2. **SAP AI Core** service instance (Extended service plan recommended).
3. **SAP HANA Cloud** instance with Vector Engine enabled.
4. `@sap/cds-dk` installed locally.

---

## 🤝 Contributing

We welcome contributions from the SAP community. Please ensure that all pull requests adhere to the **SAP Cloud Programming Model** best practices and include unit tests for all AI service integrations.

---

© 2024 OpenCAPai – Empowering Enterprise Intelligence.
