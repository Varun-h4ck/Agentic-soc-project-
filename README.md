# Agentic-AI-SOC-Project
Multi-agent AI SOC system built with N8N and Groq 

## Overview
Multi-agent AI Security Operations 
Center built with N8N and Groq LLM.
Automates alert triage, investigation
and incident response with zero code.

## Architecture
Google Sheets → SOC Lead Agent
→ Triaging Agent (severity)
→ Investigation Agent (history)
→ Response Agent (action)
→ Discord + Google Sheets update

## Scenarios Tested
- Privilege Escalation (Critical)
- Malware Execution (High)
- Brute Force Attack (High)
- Impossible Travel (Critical)

## Tools Used
- N8N: Workflow automation
- Groq LLM: AI brain (llama-4-scout)
- Google Sheets: Alert database
- Discord: Real time notifications

## Results
All 4 security scenarios successfully:
- Triaged with correct severity
- Investigated with user history
- Responded with detailed findings
- Logged in Google Sheets
- Notified via Discord
