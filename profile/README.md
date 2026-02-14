# OpenCAPai: Enterprise AI via SAP CAP & SAP AI Core

Welcome to the **OpenCAPai** organization. Our mission is to provide a standardized, modular, and production-ready ecosystem for bridging **SAP AI Core** capabilities with the **SAP Cloud Application Programming Model (CAP)**.

## 🎯 Our Mission

As Generative AI moves from experimental prototypes to enterprise-grade business processes, the need for structured, scalable, and cost-efficient frameworks becomes paramount. **OpenCAPai** focuses on delivering:

* **Standardized Integration:** Enabling seamless connectivity between SAP BTP AI services and the CAP lifecycle.
* **Architectural Excellence:** Implementing "Clean Core" compliant patterns for AI-driven applications.
* **Performance Engineering:** Offering a polyglot approach to handle enterprise data at scale, from native Node.js/Java logic to high-performance specialized engines.

---

## 🛠 Architectural Approach

We advocate for a dual-tier strategy to address varying enterprise requirements on **SAP Business Technology Platform (BTP)**:

### 1. The Standard Tier (Maintainability)

Focuses on 100% SAP-native implementations using **Node.js**. This tier prioritizes developer accessibility, standard Fiori guidelines, and rapid delivery using the official SAP SDKs.

### 2. The Performance Tier (Scalability)

Focuses on cost-optimized, high-throughput architectures. We leverage **Rust** and specialized engines to offload heavy vector processing and complex LLM orchestration. These components are designed as **Sidecars** to the main CAP application, ensuring the business core remains lean while AI operations scale efficiently.

---

## 🏗️ Technical Stack

Our projects leverage the full breadth of the SAP BTP ecosystem:

* **Orchestration:** [SAP AI Core](https://help.sap.com/docs/sap-ai-core) & Generative AI Hub.
* **Business Framework:** [SAP Cloud Application Programming Model (CAP)](https://cap.cloud.sap/).
* **Data Foundation:** SAP HANA Cloud (Vector Engine).
* **Runtimes:** SAP BTP Kyma (Kubernetes) & Cloud Foundry.
* **High-Performance Layer:** Rust-based engines for advanced RAG and data processing.

---

## 🚀 Getting Started

To utilize the resources and patterns provided by this organization, ensure you have:

1. An active **SAP BTP** subaccount.
2. **SAP AI Core** service instance (Extended service plan recommended).
3. **SAP HANA Cloud** instance with **Vector Engine** enabled.
4. Professional proficiency in **CAP** and/or **Cloud Native** development.

---

## 🤝 Contributing

We welcome contributions from the SAP community. Whether you are improving a standard CAP pattern or optimizing a high-performance sidecar, your expertise helps bridge the gap between business processes and AI innovation.
