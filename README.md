# Javier Romero Castro

Backend software engineer based in Geneva. I've spent the last 5+ years at CERN
building and maintaining scientific information platforms — primarily
[CDS](https://cds.cern.ch) and its migration to
[InvenioRDM](https://inveniosoftware.org/products/rdm/), an open-source research
data management platform used by institutions worldwide.

I work mostly in Python, with a focus on REST APIs, search infrastructure, and
data workflows.

---

## Stack

**Backend** — Python, Flask, PostgreSQL, OpenSearch/Elasticsearch, Celery, REST APIs  
**Frontend** — React, TypeScript  
**Infrastructure** — Docker, Kubernetes/OpenShift, CI/CD  
**Domain** — research data, open science, metadata standards, scientific repositories

---

## Projects

### [paper-assistant](https://github.com/jrcastro2/paper-assistant)
A metadata assistant for scientific papers built to learn LLM tool calling and
agentic workflows hands-on. Uses the Anthropic API and queries the
[INSPIRE HEP](https://inspirehep.net) database. The model decides which tools to
call and in what order — search, citation lookup, metadata fetch — without that
sequence being scripted.

### [invenio-mcp](https://github.com/jrcastro2/invenio-mcp)
An MCP (Model Context Protocol) server that exposes InvenioRDM record management
as tools an LLM can call. Lets an AI assistant create drafts, set metadata, upload
files, and publish records on a research repository through natural language.

### [rag-paper-assistant](https://github.com/jrcastro2/rag-paper-assistant)
A retrieval-augmented generation (RAG) system for question-answering over scientific
paper abstracts. Built in stages to understand each component: hybrid search
(dense vector + BM25 fused with RRF), cross-encoder reranking with a relevance
threshold, contextual RAG enrichment, and grounded generation with Claude. Indexes
real papers from the arXiv API.

### [paper-metadata](https://github.com/jrcastro2/paper-metadata)
Two LLM modules for processing scientific paper abstracts: a metadata extractor that
returns reliable structured JSON (title, authors, identifiers) from clean or messy
input, and a classifier that assigns arXiv-style categories using both zero-shot and
few-shot prompting — with a side-by-side comparison to show where each approach wins.

---

## Open source

Most of my open-source work is through contributions to the
[InvenioRDM](https://github.com/inveniosoftware) ecosystem — the framework
behind Zenodo, CDS, and a number of institutional repositories.

---

## Contact

[jrcastro9515@gmail.com](mailto:jrcastro9515@gmail.com)
