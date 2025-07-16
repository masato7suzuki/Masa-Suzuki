# Legal Prompter Design across Singapore, Malaysia, and Japan  
_ChatGPT-based Research Archive_

This repository contains an experimental **Legal Prompter Generator**, designed for multilingual legal query transformation.  
It was developed by Masato Suzuki (ORCID: 0009-0006-2197-9344) and released in conjunction with the Zenodo DOI publication:  
[![DOI](https://zenodo.org/badge/DOI/10.5281/zenodo.15950003.svg)](https://doi.org/10.5281/zenodo.15950003)

---

## 📌 Description

This project serves as a cross-jurisdictional **prompt generator** for ChatGPT, focused on legal queries related to employment law, contract clauses, and case settlements in:

- 🇸🇬 Singapore  
- 🇲🇾 Malaysia  
- 🇯🇵 Japan  

The prompter is intended to assist **legal process outsourcing**, **AI-based moderation**, and **paralegal operations** using ChatGPT-4 and similar models.  

The HTML output (`200.html`) demonstrates prompt assembly logic, metadata handling, and localization strategy.  

---

## 🧠 Prompt Generator Structure

The system is built as a modular prompt maker, with:

- **Template fragments** for common legal patterns  
- **Jurisdiction toggles** for regulatory adaptation  
- **Natural language fillers** to adjust tone and register  
- **Input/Output control zones** for clean separation of context and question

It is intended to be integrated with LLMs via API or plugin layer, though this repo provides a static implementation.

---

## 🔄 Versioning

- v1.0.0 (2025-07-16): Initial release
- Github Release: [v1.1.0](https://github.com/masato7suzuki/Masa-Suzuki/releases/tag/v1.1.0)

---

## 📄 License & Citation

MIT License  
DOI: https://doi.org/10.5281/zenodo.15950003  

If you use or reference this tool, please cite as:  
_Suzuki, Masato. Legal Prompter Design across Singapore, Malaysia, and Japan (ChatGPT-based Research Archive), Zenodo, 2025. DOI: 10.5281/zenodo.15950003_


