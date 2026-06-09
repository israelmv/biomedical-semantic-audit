# Contributing to Biomedical Semantic Audit

Thank you for your interest in contributing to this audit framework.

## Getting Started
1. Clone the repository.
2. Set up a virtual environment: `python3 -m venv venv && source venv/bin/activate`
3. Install dependencies: `pip install requests python-dotenv`
4. Create a `.env` file with your `UMLS_API_KEY`.

## Audit Process
The audit relies on the 'Tracer Triad' methodology. To add a new tracer, update the `data/tracer_audit.csv` file with the following columns:
- `tracer_name`: Clinical identifier.
- `cui`: Unified Medical Language System Concept Unique Identifier.
- `domain`: Medical specialization.

## Reporting Issues
Please submit a GitHub issue for bugs or suggested methodology refinements. Ensure you include the environment details and, if applicable, the CUI involved.
