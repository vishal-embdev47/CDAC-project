# 📰 Fake News & Misinformation Detection Toolkit

This project presents a practical methodology and open-source toolkit for verifying **fake news**, **phishing emails**, **WhatsApp hoaxes**, and **social media posts**. Built during the Cyber Gyan Virtual Internship, it explores widely-used OSINT tools and platforms that help detect misinformation, manipulated media, and suspicious digital content.

---

## 📘 Project Overview

The increasing spread of misinformation through digital platforms has made media verification a critical need in cybersecurity, journalism, and public awareness. This project focuses on identifying fake information using a wide range of freely available verification tools and documenting the process through real-world examples.

The project includes:

- Verifying fake headlines and viral news
- Analyzing phishing emails and suspicious domains
- Investigating WhatsApp message credibility
- Detecting reused or AI-generated media content
- Documenting common Indicators of Compromise (IOCs)

> 🎓 This project is educational and promotes digital media literacy and misinformation awareness.


---

## 🧰 Tools & Platforms Used

### 🔍 News and Claim Verification
- [Snopes](https://www.snopes.com)
- [PolitiFact](https://www.politifact.com)
- [FactCheck.org](https://www.factcheck.org)
- [CheckYourFact](https://checkyourfact.com)
- [Google Fact Check Explorer](https://toolbox.google.com/factcheck/explorer)

### 📧 Email & URL Scanning
- [urlscan.io](https://urlscan.io)

### 💬 WhatsApp Message Indicators
- WhatsApp Forwarded Tag Analysis
- External validation via fact-checking sources

### 🖼️ Image and Video Verification
- [TinEye](https://www.tineye.com)
- [Google Reverse Image Search](https://images.google.com)
- [InVID Verification Plugin](https://www.invid-project.eu/tools-and-services/invid-verification-plugin)

---

## 🚦 Implementation Highlights

- **Fake News Verification**: Compared news claims with Snopes and Google Fact Check Explorer.
- **Email Phishing Analysis**: Examined suspicious sender domains and links using urlscan.io.
- **WhatsApp Message Verification**: Checked mass-forwarded health misinformation using PolitiFact and metadata clues.
- **Image/Video Forensics**: Detected reused or AI-generated media through reverse image searches and InVID keyframe analysis.
- **IOCs Identified**:
  - Typosquatted sender domains (e.g., `support@paypal-security.org`)
  - Shortened/tracked links (e.g., `bit.ly`, `tinyurl`)
  - Recycled visual content with mismatched metadata
  - “Forwarded many times” WhatsApp messages with no credible source

---

## 🏁 Project Outcome

- Improved understanding of OSINT tools for misinformation detection
- Documented red flags and common digital deception patterns
- Promoted awareness around responsible content sharing
- Proposed fact-checking strategies for users and organizations

---

## 📢 Recommendations

- Always cross-check news from trusted fact-checking platforms
- Validate email links and sender information before clicking
- Educate users on how to recognize signs of misinformation
- Encourage API integration of fact-checking services into social apps
- Conduct digital literacy programs for students and employees

---

## ✍️ Author

**Vishal Kumar**  
Cybersecurity SOC Analyst | Embedded Developer  | Roboticist

---

## 📚 References

- [Snopes](https://www.snopes.com)  
- [PolitiFact](https://www.politifact.com)  
- [urlscan.io](https://urlscan.io)  
- [Google Fact Check Explorer](https://toolbox.google.com/factcheck/explorer)  
- [InVID Plugin](https://www.invid-project.eu/tools-and-services/invid-verification-plugin)  
- *The Misinformation Age* – Cailin O’Connor & James Weatherall  
- *Verification Handbook* – Craig Silverman  
- *The Anatomy of Fake News* – Nolan Higdon

---

## 🔐 License

This repository is for **educational use only**. Unauthorized use of these techniques for disinformation or surveillance is strictly discouraged.

---
