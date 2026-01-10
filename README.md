# FedEx DCA AI Management Platform

## Problem
Debt Collection Agency (DCA) management is currently manual, fragmented, and lacks visibility, leading to delayed recoveries and weak governance.

## Solution
A centralized, AI-enabled platform that automates case allocation, enforces SOP and SLA workflows, and provides real-time performance insights.

## Key Capabilities
- Centralized case tracking and closure
- AI-based case prioritization
- Automated workflows (SOP & SLA)
- Secure DCA collaboration portal
- Real-time dashboards

## Technology Stack
- Workflow Automation: n8n
- AI/ML: Python
- UI: HTML/CSS/JS
- Data: CSV / Database
- ## Project Structure

fedex-dca-ai-platformmm/
│
├── model/
│   └── recovery_model.py        # AI logic for priority & recovery prediction
│
├── pipeline/
│   └── case_allocator.py        # Case allocation & SLA logic
│
├── ui/
│   └── app.py                   # Streamlit-based user interface
│
├── data/
│   └── sample_data.csv          # Sample overdue case data

## Status
Phase 1 – Concept design & initial prototype (Hackathon Round 1)

