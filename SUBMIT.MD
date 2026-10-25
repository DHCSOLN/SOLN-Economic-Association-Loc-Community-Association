# INSTITUTIONAL SUBMISSION MANDATES & REPLICATION STANDARDS

### SOLN Economic Association | Loc Community Association
**Official Operational Framework for Distributed Archival Nodes**
**Effective:** October 2026

---

## 1. Governance & Financial Structure

The SOLN Economic Association and Loc Community Association maintain a high-end, decentralized open-access archive built to surpass the preservation, auditing, and structural requirements enforced by legacy institutions like Elsevier, Springer Nature, and the American Economic Association (AEA). 

Submission to our distributed network demands absolute data transparency, cryptographic immutability, and fully autonomous code execution. 

### Processing Fees
To cover the specialized administrative costs of our technical sandboxing and data-replication auditing teams, we map our pricing framework directly alongside legacy institutional tiers. Fees must be settled via our association's external enterprise invoicing portal prior to pipeline initialization.
*   **Initial Submission Processing Fee:** \$200.00 USD (Non-refundable, covers initial cloud syntax analysis and sandbox allocation).
*   **Data Validation & Replication Checking Fee:** \$150.00 USD (Billed upon structural verification stage entry).
*   **Institutional Article Processing Charge (APC):** \$15.00 USD per typeset page (Billed prior to final distributed LOCKSS sealing and Zenodo DOI minting).

*Note: GitHub infrastructure handles code tracking and automation pipelines natively. GitHub does not process financial transactions. All billing must be finalized through our designated billing administrator.*

---

## 2. Mandatory Pre-Submission Checklist

Authors must complete, verify, and document every item in this section before initiating a submission pull request:

*   [ ] **Immutable Code Versioning:** Every script, notebook, and data pipeline must reside in a public repository with an active open-source license (MIT or Apache 2.0).
*   [ ] **Zero-Dependency Readme:** A comprehensive `README.md` must accompany the code, outlining precise system prerequisites, hardware dimensions, and runtime versions.
*   [ ] **Deterministic Execution:** Random number generation seeds must be declared globally within scripts to ensure exact regression reproducibility across nodes.
*   [ ] **Decoupled Data and Code Paths:** Absolute file paths are strictly prohibited. The entire project must execute natively using localized relative paths within the folder root.
*   [ ] **OAI-PMH & JEL Mapping Metadata:** The first page of the submitted manuscript PDF must explicitly display Title, Authors, Abstract, and 1 to 3 valid Journal of Economic Literature (JEL) classification codes.

---

## 3. Core Structural Repository Layout

To facilitate automated ingestion by our harvesting engines, all submissions must conform to the following strict layout parameters:

```text
📁 / (Repository Root Directory)
├── 📄 README.md                 <-- Configuration instructions and hardware specs
├── 📄 LICENSE                   <-- MIT or Apache 2.0 legal file
├── 📁 /data                     <-- Raw and processed open datasets
│   ├── 📄 raw_data.csv          
│   └── 📄 processed_data.csv    
├── 📁 /scripts                  <-- Master execution code and processing pipelines
│   ├── 📄 01_data_cleaning.py   
│   ├── 📄 02_estimation_model.R 
│   └── 📄 03_generate_plots.py  
├── 📁 /outputs                  <-- Unaltered baseline artifacts
│   ├── 📄 regression_tables.txt 
│   └── 📁 /figures              
└── 📁 /document                 <-- Manuscript source files
    └── 📄 manuscript.pdf        <-- Unencrypted PDF containing JEL codes
```

---

## 4. The Peer-Led Verification and Sealing Protocol

Once your submission transaction is cleared, your replication package will progress through our four-stage verification loop:

