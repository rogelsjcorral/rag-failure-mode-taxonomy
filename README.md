# RAG Is Not a Safety System

**RAG Is Not a Safety System: Why Retrieval Does Not Solve AI Reliability**  
Rogel S.J. Corral (Independent Researcher)  
Preprint, February 2026

## Abstract
This repository hosts the preprint **RAG Is Not a Safety System: Why Retrieval Does Not Solve AI Reliability**. The paper argues that Retrieval-Augmented Generation (RAG) improves access to relevant information but does not, by itself, constitute a safety mechanism. In particular, retrieval does not guarantee correct interpretation, constraint adherence, policy compliance, resistance to indirect prompt injection, or stable behavior under ambiguity and operational stress. The paper distinguishes evidence access from behavioral control and outlines the additional governance and enforcement components required for safety-critical or privileged workflows.

## Scope and non claims
This paper does not argue that Retrieval-Augmented Generation (RAG) is ineffective, nor that retrieval cannot improve factual grounding. It argues a narrower point: retrieval by itself is not an enforcement mechanism and therefore cannot guarantee correct interpretation, policy compliance, or safe behavior under ambiguity, adversarial pressure, or operational stress. The scope is enterprise usage, where RAG is applied to internal knowledge access and operational workflows that can influence privileged actions or high-impact decisions. This work is defensive in intent and does not provide offensive code.

## Topics covered
The paper discusses persistent failure modes that remain possible even with high-quality retrieval, including:
- incorrect synthesis or interpretation of retrieved material,
- elevated trust from citations without corresponding correctness,
- expanded attack surface via the retrieval corpus (including indirect prompt injection),
- policy text as context without enforceable constraints,
- ambiguity, conflicts, and staleness in source material,
- tail-risk behaviors under uncertainty.

## What is required beyond retrieval
The paper outlines a safety posture that requires governance at runtime, including mechanisms to:
- require minimum evidence before acting,
- refuse or escalate when evidence is missing, ambiguous, conflicting, or stale,
- enforce hard constraints and policy boundaries,
- gate privileged or irreversible actions,
- produce auditable traces describing evidence used, decisions taken, and refusal conditions.

## Persistent identifier
- Zenodo record: TBD  
- DOI: TBD  

## Citation
Until a DOI is available, cite this work as a preprint hosted in this repository.
