# Regulatory Tracker - Technical Architecture Documentation

**Source**: repository/technical-specifications/regulatory-tracker-technical-architecture.md
**Type**: Technical Specification
**Upload Date**: 2026-02-11
**Source SHA**: Not provided

## Key Points

- Three-tier cloud-ready architecture with asynchronous background processing: client layer (web browser), frontend layer (Next.js 14 with React 19), and backend layer (FastAPI with Python 3.11+)
- Multi-stage scan pipeline orchestrator coordinating 7 stages: initializing, retrieving sources, detecting changes, analyzing (Claude API), scoring, generating artifacts, and finalizing
- Claude Sonnet 4 AI integration for regulatory document analysis with structured JSON output including impact assessment, recommended actions, and confidence scoring
- SQLite database with three core tables (scans, results, sources) storing scan records, analysis results with workflow status tracking, and regulatory source metadata
- Docker Compose deployment with separate frontend (Node.js 20) and backend (Python 3.11) containers communicating over bridge network, supporting local development and production scaling
- Change detection service using SHA-256 hashing and keyword pattern matching to identify material regulatory changes across sources
- Document artifact generation producing both markdown (database-stored) and professional Word documents (.docx files) with cover pages, tables of contents, and formatted sections

## Entities and Topics

- **Next.js 14 & React 19**: Frontend framework with file-based App Router and component architecture for dashboard, scans, results, and workflow management
- **FastAPI & Python 3.11**: Backend web framework with Pydantic validation, Uvicorn ASGI server, and RESTful API endpoints for scan/results/workflow management
- **Claude Sonnet 4-20250514**: Anthropic's AI model for regulatory document analysis with configurable prompts and structured JSON output schema
- **SQLite Database**: File-based relational database (regulatory_tracker.db) with foreign key relationships between scans, results, and sources tables
- **ScanOrchestrator Service**: Core service managing 7-stage pipeline with error handling, status transitions, and inter-service coordination
- **ChangeDetectionService**: Identifies material changes via SHA-256 hashing, regex keyword detection, and optional demo mode
- **ArtifactGenerator**: Creates markdown artifacts and professional Word documents with metadata, summaries, and analysis sections
- **Mock Sources Directory**: JSON files simulating regulatory agency data (FinCEN, OCC, Federal Reserve) with document content and metadata
- **Docker Compose**: Multi-container orchestration with volumes for mock sources, artifacts, and database persistence
- **Anthropic API Integration**: External Claude API with rate limiting, error handling, token usage tracking, and cost estimation ($0.10-$0.50 per analysis)

## Relevance to Project

This technical architecture document provides comprehensive specifications for implementing an AI-powered regulatory compliance tracking system. It directly supports project development by defining the complete system design including API contracts, database schema, service responsibilities, data flows, and deployment procedures, enabling development teams to build and integrate components according to established architectural patterns and technology stack decisions.