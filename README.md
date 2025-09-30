# AI-based UFDR Analysis Tool

## Overview
AI-powered forensic tool that ingests Universal Forensic Extraction Device Reports (UFDRs),
supports natural language queries for Investigating Officers (IOs), highlights key findings, 
and generates officer-friendly reports.

## Features
- UFDR ingestion (XML, JSON, CSV).
- Natural language query (NLP + semantic search).
- Evidence highlighting (crypto addresses, suspicious contacts).
- Graph-based interconnection visualization.
- Automated report generation (PDF, HTML).
- Secure role-based access.

## Tech Stack
- Backend: Python (FastAPI, transformers, spaCy)
- Database: MongoDB + Elasticsearch / FAISS
- Frontend: React (optional for UI)
- Deployment: Docker, Kubernetes (Helm)

## Getting Started
```bash
git clone https://github.com/<org>/ufdr-ai-tool.git
cd ufdr-ai-tool
docker-compose up --build
