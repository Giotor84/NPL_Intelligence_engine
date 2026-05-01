# 🏛️ NPL Intelligence Engine (Acquisition Teaser)
**Proprietary Compound AI System for Non-Performing Loans (NPL) Due Diligence.**

*Notice: This repository serves as a public technical teaser for M&A / IP Sale purposes. The proprietary source code, LLM orchestration logic, and Kùzu Graph DB schemas are kept in a secure, private environment and will be shared via Data Room only after an NDA is signed.*

## 🚀 The Asset
A production-ready, highly scalable architecture built to completely automate the legal and financial due diligence of NPL portfolios. 
It replaces weeks of human manual review with deterministic, mathematical graph-based validation, processing complex legal PDFs in **~3 minutes per document**.

## 🧠 Core Technologies
- **Local-First LLMs:** Architecture designed to run on dedicated AWS instances (e.g., `ml.g6.12xlarge`) using 70B+ parameter models (Llama 3.3 / Qwen) via vLLM. 100% Data Privacy. Zero data sent to public cloud APIs.
- **Agentic Workflow:** A sophisticated 16-agent pipeline that handles OCR (Surya), layout parsing, data extraction, and legal qualification.
- **Constrained Decoding:** Forces the LLMs to output 100% structurally valid Pydantic/JSON schemas. Zero formatting hallucinations.
- **GraphRAG (Kùzu DB):** The extracted entities (Loans, Guarantors, Mortgages) are mathematically mapped into an embedded Property Graph. The system doesn't "guess" the chain of title; it computes the deterministic path.

## 📈 Value Proposition
- **80% Cost Reduction:** Slashes OPEX related to legal analysts and external consultants.
- **Loss Prevention:** Mathematically detects broken chains of title or expired guarantees that human eyes miss, saving millions in unrecoverable debts.
- **Scalability:** Fully parallelizable via batch processing on AWS.

## 🤝 Interested in Acquisition?
The full IP (Intellectual Property), architectural documentation, and source code are available for acquisition.
If you are viewing this via **Acquire.com**, please proceed with the NDA to request access to the Data Room and the video demonstration.
