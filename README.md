# COBOL to Java Migration Tool

## Overview
This application automates the conversion of legacy COBOL code to modern Java implementations through a multi-step process using AI agents. The tool helps organizations modernize their legacy systems while preserving business logic and functionality.

## Features
- Generates Business Requirements Documents (BRD) from COBOL source code
- Creates Java code implementations based on the extracted requirements
- Evaluates and optimizes the generated Java code
- Applies enterprise-grade refinements for production readiness
- Supports COBOL-specific features like COMP-3 fields and fixed-length records

## How to Use
1. Paste your COBOL code into the text area
2. Add business glossary terms if available
3. Generate a BRD to document the requirements
4. Convert the COBOL to Java code
5. Apply optimization and refinement steps as needed
6. Download the final Java implementation

## Requirements
- Python 3.8+
- Streamlit
- CrewAI
- LangChain
- python-docx

## Installation
```bash
pip install -r requirements.txt
streamlit run app1.py