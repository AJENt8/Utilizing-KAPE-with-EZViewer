# 🧰 KAPE & EZ Tools Forensic Triage (TryHackMe)

> **Summary:** Used both the **KAPE GUI and CLI** to collect and parse forensic artifacts from a Windows system, then analyzed results with **EZ Viewer / EZ Tools** to identify Acceptable Use Policy violations involving removable media, network drives, software installation sources, program execution, and network connections.

---

## 🎯 Objectives
- Learn how to use **KAPE** for Windows forensic triage  
- Practice collecting artifacts with both the **GUI** and **command line**  
- Analyze output with **EZ Viewer / EZ Tools**  
- Investigate whether a user violated an organization's **Acceptable Use Policy**  

---

## 🛠️ Environment
- Platform: TryHackMe — *KAPE* room  
- Tools Used:
  - **KAPE GUI**
  - **KAPE CLI**
  - **EZ Viewer / EZ Tools**

---

## 🚀 Workflow

### 1) KAPE Collection & Parsing
- Navigated to the **KAPE** directory on the Desktop in the provided VM  
- Ran KAPE using selected **Targets** and **Modules** to collect Windows artifacts relevant to:
  - USB device usage
  - Installed applications
  - execution evidence
  - network history
  - user activity
- Used **EZ Viewer** in the EZtools folder to review the resulting CSV artifacts

### 2) GUI + CLI Usage
- Practiced using the **KAPE GUI** for target/module selection and collection setup  
- Practiced using the **KAPE CLI** for faster artifact collection and parsing workflows  
- Used command-line execution with `!EZParser` to process and review forensic artifacts through EZ Tools

### 3) Investigative Focus
- The scenario involved determining whether a user violated organization policy by:
  - Connecting removable media
  - Using network drives
  - Installing software from unknown locations
  - Connecting to unknown networks

### Additional Evidence Reviewed
- Beyond the room questions, I also reviewed additional forensic data points in EZ Viewer, including:
  - Password change artifacts
  - Execution history
  - Volume Serial Number (VSN) references
  - Removable drive traces
  - Related Windows forensic evidence produced through KAPE and EZ Tools

---

## ✅ Outcome
- Successfully used KAPE to triage a Windows system for forensic evidence
- Identified evidence of removable media use, software installation from a network drive, program execution, and network connection history
- Demonstrated the ability to pair artifact collection with artifact analysis using KAPE + EZ Viewer
- Applied forensic evidence to assess a user's compliance with organizational policy

---

## 🧩 Skills Demonstrated
- Windows forensic triage
- Artifact collection with KAPE GUI and KAPE CLI
- Parsing and reviewing results with EZ Tools / EZ Viewer
- USB and removable media analysis
- Network connection artifact analysis
- Software installation source tracing
- Execution history review
- Evidence-driven Acceptable Use Policy investigation


  
