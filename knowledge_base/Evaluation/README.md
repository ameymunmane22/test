# Nexora Enterprise Knowledge Base
This dataset contains a synthetic enterprise knowledge base for a fictional company named Nexora Technologies, designed to test Retrieval-Augmented Generation (RAG) and Q&A assistants.

## Company Profile
**Nexora Technologies** provides cloud-based enterprise software, API integration services, workflow automation, and business analytics solutions.

## Dataset Contents
- **20 Documents**: Divided into 5 PDFs, 5 HTML files, 5 TXT files, and 5 Markdown files.
- **Total Word Count**: Approximately 35,000 words.
- **Conflicts**: 5 intentional, traceable contradictions across versions and dates to test RAG conflict resolution capabilities.
- **Evaluation Set**: 50 questions (JSON/CSV) covering factual, multi-doc, ambiguous, unanswerable, and conflicting queries.

## Intentional Conflicts
1. **API Rate Limit**: `DOC-005` (v1.0) states 5,000 req/hr. `DOC-017` (v2.0) states 10,000 req/hr.
2. **Data Retention**: `DOC-014` (older) states 30 days. `DOC-003` (newer) states 90 days.
3. **Password Policy**: `DOC-010` (Admin Guide) requires 8 characters. `DOC-003` (Security Guide) requires 12.
4. **Storage Limits**: `DOC-004` (Subscription Plans) states 500GB for Pro. `DOC-016` (Usage Limits) states 1TB for Pro.
5. **Refund Window**: `DOC-011` (FAQ) states 14 days. `DOC-012` (Billing Policy) states 30 days.

## Hackathon Reference
Use Case 2: EnterpriseDocQ&Aassist_AIEngineer_Usecase2.docx
