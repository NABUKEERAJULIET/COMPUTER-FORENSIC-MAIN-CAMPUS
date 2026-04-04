# FORENSIC INVESTIGATION REPORT
**Case Number:** 0028  
**Examiner:** Ayesiga Isaac  
**Date:** April 4, 2026  
**Status:** Under Investigation

---

## EXECUTIVE SUMMARY

This forensic investigation analyzed a disk image from Case 0028 using Autopsy digital forensics tools. The analysis focused on file system examination, deleted file recovery, web activity analysis, keyword searching, and timeline reconstruction.

---

## 1. INTRODUCTION

### 1.1 Purpose of Investigation
The objective of this investigation is to conduct a comprehensive digital forensic analysis of the provided disk image to:
- Identify suspicious or relevant files
- Recover deleted files
- Analyze user web activity
- Search for specific keywords
- Reconstruct timeline of events

### 1.2 Scope
- Data Source: nps-2009-canon2-gen2.E01
- Analysis Tools: Autopsy 4.22.1 and associated modules
- Timezone: Africa/Nairobi
- Investigation Date: April 4, 2026

### 1.3 Legal and Ethical Considerations
This investigation was conducted in accordance with:
- Digital Forensics Standards (NIST guidelines)
- Data Protection regulations
- Chain of custody procedures
- Professional ethics requirements

---

## 2. METHODOLOGY

### 2.1 Tools and Equipment Used
- **Primary Tool:** Autopsy 4.22.1
- **Operating System:** Windows/Linux
- **Analysis Modules:**
  - Recent Activity Module
  - Hash Lookup Module
  - File Type Identification
  - Extension Mismatch Detector
  - Embedded File Extractor
  - Picture Analyzer
  - Keyword Search
  - Email Parser
  - Encryption Detection
  - Interesting Files Identifier
  - Central Repository
  - PhotoRec Carver
  - Virtual Machine Extractor
  - Data Source Integrity
  - Android Analyzer (aLEAPP)
  - DJI Drone Analyzer
  - YARA Analyzer
  - iOS Analyzer (iLEAPP)
  - GPX Parser

### 2.2 Analysis Procedure
1. **Case Creation:** Set up forensic case in Autopsy
2. **Evidence Loading:** Import disk image and configure data sources
3. **Ingest Analysis:** Run selected modules for automated analysis
4. **Manual Investigation:** Detailed examination of findings
5. **Evidence Collection:** Document and export findings
6. **Timeline Reconstruction:** Organize events chronologically
7. **Report Generation:** Compile findings and conclusions

### 2.3 Chain of Custody
- All evidence examined in controlled forensic environment
- No modifications made to source data
- Hash verification completed: _______________
- Access logs maintained throughout analysis

---

## 3. EVIDENCE SUMMARY

### 3.1 Data Source Information
| Item | Details |
|------|---------|
| **Image File** | nps-2009-canon2-gen2.E01 |
| **Case Name** | Ayesiga Isaac 0028 |
| **Number of Data Sources** | 1 |
| **File System** | [To be determined] |
| **Size** | [To be determined] |
| **Timezone** | Africa/Nairobi |
| **Path** | D:\ck\nps-2009-canon2-gen2.E01 |

### 3.2 Image Hash Values
| Hash Type | Value |
|-----------|-------|
| **MD5** | _________________ |
| **SHA-1** | _________________ |
| **SHA-256** | _________________ |

### 3.3 Analysis Statistics
- **Total Files Found:** _________
- **Deleted Files Recovered:** _________
- **Keyword Hits:** _________
- **Web Activity Records:** _________

---

## 4. FINDINGS

### 4.1 TASK 1 - Installation and Setup (10 marks)
**Status:** ☐ Complete

#### Installation Evidence
[Insert screenshot of Autopsy installation]

#### Digital Forensics Explanation
Digital forensics is the practice of identifying, preserving, recovering, interpreting, and presenting evidence from digital devices. It involves:

**Key Principles:**
- Preservation of evidence integrity
- Maintaining chain of custody
- Following established procedures
- Objective analysis
- Proper documentation

**Autopsy Features:**
Autopsy is an open-source digital forensics framework that provides:
- [Document features based on your research]

---

### 4.2 TASK 2 - Case Creation and Evidence Loading (15 marks)
**Status:** ☐ Complete

#### Case Creation Screenshot
[Insert screenshot]

#### Data Source Configuration
[Insert screenshot of data source settings]

#### Forensic Imaging Explanation
A forensic image is a bit-by-bit duplicate of a storage device that preserves all data, including deleted files and slack space. 

**Why Forensic Imaging is Essential:**
- Preserves original evidence
- Allows multiple analyses
- Enables verification
- Creates audit trail

**Image Formats:**
- **.E01** - Encase format - widely used, compressible
- **.DD** - Raw format - simple, portable
- **.IMG** - Disk image format

---

### 4.3 TASK 3 - File System Analysis (15 marks)
**Status:** ☐ Complete

#### Directory Structure Overview
[Insert screenshot of file tree]

#### Key Directories Identified
| Directory | Purpose | Findings |
|-----------|---------|----------|
| [e.g., Windows/System32] | System files | [Your findings] |
| [e.g., Users/Documents] | User files | [Your findings] |
| [e.g., Temp] | Temporary files | [Your findings] |

#### Suspicious Files Identified
| Filename | Type | Size | Modified | Comments |
|----------|------|------|----------|----------|
| [Example] | .exe | [size] | [date] | [suspicious details] |
| | | | | |

#### File Access Timeline
[Timeline of recent file activity]

---

### 4.4 TASK 4 - Deleted File Recovery (15 marks)
**Status:** ☐ Complete

#### Recovered File #1
**Details:**
- Original Filename: ________________
- File Type: ________________
- File Size: ________________
- Recovery Date: ________________
- Estimated Deletion Date: ________________
- Recovery Method: [Carving/Unallocated Space]

**Content Summary:**
[Describe what the file contains]

**Forensic Significance:**
[Why is this file relevant to the investigation?]

**Evidence Screenshot:**
[Insert screenshot of recovered file]

---

#### Recovered File #2
**Details:**
- Original Filename: ________________
- File Type: ________________
- File Size: ________________
- Recovery Date: ________________
- Estimated Deletion Date: ________________

**Content Summary:**
[Describe what the file contains]

**Forensic Significance:**
[Why is this file relevant?]

**Evidence Screenshot:**
[Insert screenshot]

---

#### Recovered File #3
**Details:**
- Original Filename: ________________
- File Type: ________________
- File Size: ________________
- Recovery Date: ________________
- Estimated Deletion Date: ________________

**Content Summary:**
[Describe content]

**Forensic Significance:**
[Relevance analysis]

**Evidence Screenshot:**
[Insert screenshot]

---

### 4.5 TASK 5 - Web Activity Analysis (15 marks)
**Status:** ☐ Complete

#### Browser History Summary
| URL | Visited | Browser | Timestamp |
|-----|---------|---------|-----------|
| [Example] | 1 | Chrome | [date/time] |
| | | | |

#### Downloads Identified
| Filename | Type | Size | Date Downloaded |
|----------|------|------|-----------------|
| [Example] | .pdf | [size] | [date] |
| | | | |

#### Search Terms Extracted
[List of search queries found in browser history]

#### Cookies & Cache Analysis
[Significant cookies or cache entries]

#### Web Activity Pattern Analysis
[Description of user browsing patterns and behavior]

#### Suspicious Web Activity
[Any suspicious URLs, downloads, or activity]

**Evidence Screenshots:**
[Insert browser history screenshot]
[Insert downloads screenshot]

---

### 4.6 TASK 6 - Keyword Search and Filtering (10 marks)
**Status:** ☐ Complete

#### Keyword Search Configuration
**Keywords Searched:**
- password
- confidential
- secret
- admin
- [Additional keywords]

**Results Summary:**

| Keyword | Hits | Relevant | Not Relevant |
|---------|------|----------|--------------|
| password | ___ | ___ | ___ |
| confidential | ___ | ___ | ___ |
| secret | ___ | ___ | ___ |
| admin | ___ | ___ | ___ |

#### Significant Keyword Hits
##### Hit #1
- **Keyword:** ________________
- **File:** ________________
- **Location:** ________________
- **Context:** ________________
- **Significance:** ________________

##### Hit #2
- **Keyword:** ________________
- **File:** ________________
- **Context:** ________________
- **Significance:** ________________

##### Hit #3
- **Keyword:** ________________
- **File:** ________________
- **Context:** ________________
- **Significance:** ________________

#### Analysis of Results
[Detailed analysis of keyword search findings and their implications]

**Evidence Screenshots:**
[Insert keyword search results]

---

### 4.7 TASK 7 - Timeline Analysis (10 marks)
**Status:** ☐ Complete

#### Timeline Overview
[Description of key events in chronological order]

#### Key Events
| Time/Date | Event | Files Involved | Significance |
|-----------|-------|-----------------|--------------|
| [timestamp] | [event] | [files] | [details] |
| | | | |

#### Timeline Reconstruction
[Narrative description of user activity sequence based on timestamps]

#### Temporal Patterns Identified
- Peak activity times: ________________
- Suspicious timeframes: ________________
- Anomalies: ________________

**Timeline Visual:**
[Insert Autopsy timeline screenshot or visualization]

---

### 4.8 TASK 8 - Report Generation (10 marks)
**Status:** ☐ Complete

#### Report Components Generated
- ☐ Autopsy HTML Report
- ☐ Case Summary
- ☐ Data Source Information
- ☐ File Listing
- ☐ Timeline Report
- ☐ Artifact Report

---

## 5. ANALYSIS & INTERPRETATION

### 5.1 Key Findings Summary
Provide a comprehensive summary of all significant findings across all tasks.

[Your analysis here]

### 5.2 Significance Assessment
For each major finding, explain:
- What was found
- Where it was found
- When it was accessed/modified
- Why it's significant
- How it relates to investigation

### 5.3 Links Between Findings
[Describe relationships between different findings]

### 5.4 User Behavior Patterns
[Analysis of user behavior based on combined evidence]

### 5.5 Evidence Corroboration
[Cross-reference findings that support each other]

---

## 6. CONCLUSIONS

### 6.1 Summary of Investigation
This investigation successfully analyzed the provided disk image using Autopsy and identified:
- [Key finding 1]
- [Key finding 2]
- [Key finding 3]

### 6.2 Conclusions
Based on the evidence analyzed:

1. [Conclusion 1]
2. [Conclusion 2]
3. [Conclusion 3]

### 6.3 Recommendations for Further Investigation
- [Recommendation 1]
- [Recommendation 2]
- [Recommendation 3]

### 6.4 Limitations
[Any limitations in the analysis or investigation]

---

## 7. APPENDICES

### Appendix A: Screenshots
[All screenshots organized by task]

### Appendix B: Detailed File Listings
[Complete file inventory]

### Appendix C: Module Configuration
[Details of ingest modules used]

### Appendix D: Timeline Data
[Exported timeline information]

### Appendix E: Glossary
- **Forensic Image:** Bit-by-bit copy of storage media
- **Hash Value:** Unique identifier of data
- **Chain of Custody:** Documentation of evidence handling
- **Metadata:** Information about files
- **Allocated Space:** Actively used file storage
- **Unallocated Space:** Deleted or unused space
- **Carving:** Recovery of files from raw data
- **Timeline:** Chronological sequence of events

---

## 8. CERTIFICATION

I certify that this report is based on my analysis of the provided evidence using Autopsy digital forensics tools, conducted in accordance with professional standards and ethical guidelines.

**Examiner:** Ayesiga Isaac  
**Date:** April 4, 2026  
**Signature:** ________________

---

**END OF REPORT**

---

*This report is confidential and intended for authorized use only.*
