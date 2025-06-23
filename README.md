# BPMN Data Workflow Editor

A lightweight BPMN-based modeling environment for designing and validating data workflows across conceptual, logical, and physical layers. This tool is built upon the [bpmn.io](https://bpmn.io) ecosystem and extends it with domain-specific features for ETL and machine learning pipelines.

📘 _This repository accompanies the paper:_  
**"Developing Data Workflows: From Conceptual Blueprints to Physical Implementation"**  
Bruno Oliveira and Óscar Oliveira, *Data*, 2025.  
➡️ [Read the paper](https://www.mdpi.com/article/10.3390/data1010000)

---

## ✨ Features

- 🔹 **Conceptual Modeling Layer**  
  Custom BPMN palette limited to three specialized task types: `DataSource`, `DataTransformation`, and `DataSink`, with control flows and data object links for clarity and abstraction.

- 🔹 **Blueprint-Based Logical Modeling**  
  JSON-defined logical "blueprints" describe reusable ETL primitives with:
  - Explicit `inputs` and `outputs` with schema contracts
  - Cardinality constraints and logical invariants
  - Domain roles (`source`, `sink`, `transformation`)

- 🔹 **Validation and Consistency Checking**  
  Built-in model constraints and schema validation to ensure structural correctness and enable translation to execution.

- 🔹 **Extensibility**  
  Extend the blueprint library to support new domains (e.g., ML pipelines), and customize BPMN modeler behavior using BPMN-JS extensions.

- 🔹 **Future Physical Implementation Mapping**  
  A blueprint-to-BIML (or ADF) code generator is under development for generating SSIS or cloud-native ETL templates.

---

## 📦 Technologies Used

- [`bpmn-js`](https://github.com/bpmn-io/bpmn-js) – BPMN modeling engine
- `JSON Schema` – For defining blueprint contracts and constraints
- `TypeScript / JavaScript` – Core implementation
- `BIML` (planned) – Physical layer translation

---

## 📁 Repository Structure (to be available soon)
/editor/ → BPMN modeler with custom palette and validation
/blueprints/ → JSON schema definitions for reusable logical components
/schemas/ → Data contract specifications
/generator/ → Code generator for BIML (planned)
/docs/ → Documentation and GitHub Pages


---

## 🚧 Code Availability

The source code and examples will be made available in this repository **soon**.  
Stay tuned — or [watch this repo](https://github.com/YOUR_USERNAME/bpmn-dataworkflow-editor) for updates.

---

## 🌐 GitHub Pages

You can explore documentation and interactive examples once available at:  
**[https://your-username.github.io/bpmn-dataworkflow-editor](https://your-username.github.io/bpmn-dataworkflow-editor)**

---

## 📄 License

This project will be released under the **MIT License**.

---

## 👥 Authors

- **Bruno Oliveira** – [bmo@estg.ipp.pt](mailto:bmo@estg.ipp.pt)  
- **Óscar Oliveira** – [oao@estg.ipp.pt](mailto:oao@estg.ipp.pt)  
CIICESI, Porto Polytechnic

---


