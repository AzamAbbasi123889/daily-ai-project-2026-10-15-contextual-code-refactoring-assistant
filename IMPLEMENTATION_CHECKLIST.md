# Implementation Checklist

Build the application yourself using `PROJECT_BRIEF.md`.

## Initial setup

- [ ] Read the project specification.
- [ ] Review the architecture and data model.
- [ ] Create a Python virtual environment.
- [ ] Install and pin the required dependencies.
- [ ] Configure credentials through environment variables.
- [ ] Review the data privacy and security requirements.

## Project acceptance criteria

- [ ] API returns 202 with job_id
- [ ] Graph contains at least 90% of functions detected
- [ ] Embeddings stored in Neo4j property 'embedding'
- [ ] Returns ≥3 suggestions
- [ ] Each suggestion includes a valid unified diff
- [ ] Confidence score >0.6 for at least one suggestion
- [ ] Patch applies cleanly with no syntax errors
- [ ] Git‑style response includes changed lines
- [ ] Set up FastAPI skeleton
- [ ] Implement zip upload & async extraction
- [ ] Parse AST to generate Neo4j nodes
- [ ] Compute embeddings with Sentence‑Transformers
- [ ] Write CI pipeline with unit tests
- [ ] Unit tests for AST parser and Neo4j insertion
- [ ] Integration tests for each endpoint using pytest‑asyncio
- [ ] Mock LLM responses to verify prompt composition
- [ ] Security test: ensure uploaded zip cannot escape sandbox
- [ ] Dockerfile builds multi‑stage image (Python runtime + Neo4j community edition)
- [ ] docker‑compose.yml defines api and neo4j services with persisted volume
- [ ] GitHub Actions workflow builds image, runs tests, pushes to GitHub Packages
- [ ] Optional: Deploy to Render or Railway for public demo

## Before completion

- [ ] Implement the planned MVP features.
- [ ] Add unit and integration tests.
- [ ] Run the test suite.
- [ ] Measure the evaluation metrics in the brief.
- [ ] Record actual results and known limitations.
- [ ] Document setup and deployment.
- [ ] Update the README to reflect the implemented features.
- [ ] Add only verified outcomes to your resume.
