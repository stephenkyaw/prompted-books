You are an expert AI engineer, LLM application architect, RAG engineer, agentic systems designer, prompt engineer, LangChain/LangGraph developer, production backend engineer, AI safety reviewer, technical book author, curriculum designer, and professional book typesetter.

Create a professional project-based technical ebook called:

# Production LLM and Agentic App Development 2026

Subtitle:

**Prompting, RAG, BM25, Contextual Retrieval, GraphRAG, LangChain, LangGraph, Agent Skills, Tools, Agents, Safety, Evaluation, and Real-World AI Apps**

## Audience

The reader is a developer who wants to learn practical LLM application development, RAG, AI agents, tool calling, LangChain, LangGraph, agent skills, evaluation, safety, and production deployment.

The book should teach beginners clearly but also be useful for engineers building real production AI applications.

Assume the reader understands basic Python and web/backend concepts, but do not assume they already know LLM engineering, RAG, vector search, agent workflows, or AI safety.

Use simple, clear English. Avoid hype. Be honest about what works, what fails, and what is risky.

## Important Source Rule

This field changes quickly.

Before writing final technical code or setup instructions, verify the current official documentation for:

* OpenAI APIs
* LangChain
* LangGraph
* vector databases
* BM25/search tooling
* GraphRAG approaches
* structured outputs
* tool/function calling
* MCP-style integration
* model providers
* evaluation tools
* deployment recommendations

Use official documentation as the source of truth. Do not invent APIs. If an API is uncertain, clearly say it must be checked before implementation.

## Goal

Teach practical production LLM and agentic app development from fundamentals to advanced real-world systems.

The book should help the reader understand:

* LLM fundamentals
* prompt engineering
* context engineering
* provider abstraction
* streaming
* structured outputs
* tool calling
* MCP-style tool integration
* embeddings
* vector search
* sparse retrieval
* BM25 indexing
* hybrid retrieval
* reranking
* semantic caching
* RAG fundamentals
* advanced RAG
* contextual retrieval
* contextual BM25
* parent-child chunking
* hierarchical RAG
* corrective RAG
* adaptive RAG
* agentic RAG
* GraphRAG
* multimodal/document intelligence
* LangChain
* LangGraph
* agent architecture
* agent design patterns
* agent skills and SKILL.md-style packages
* multi-agent systems
* memory and state management
* AI evaluation
* AI safety and guardrails
* observability
* cost control
* LLMOps
* model strategy
* deployment
* real-world AI solution design

This should not be a hype-heavy AI book. It should feel like a real production engineering roadmap.

## Main Project

Build a production-style:

# AI Research and Support Assistant

Features:

* prompt playground
* model provider abstraction
* streaming chat
* prompt registry
* prompt versioning
* structured outputs
* tool calling
* safe tool registry
* MCP-style external tool integration overview
* document upload
* text extraction
* BM25 index
* vector index
* hybrid retrieval
* reranking
* contextual retrieval
* contextual BM25
* advanced RAG
* GraphRAG search
* citations
* support ticket workflow
* LangGraph agent
* human approval gates
* agent skills system
* SKILL.md templates
* memory and context builder
* evaluation tests
* safety tests
* prompt injection tests
* observability
* cost tracking
* deployment checklist
* rollback checklist
* portfolio README

## Main Teaching Style

For each important topic, explain:

* What is it?
* Why use it?
* When should you use it?
* When should you not use it?
* How do you use it?
* Small focused example
* Explanation of the example
* Real-world AI app example
* Apply it to the running project
* Project files and folders
* Important code
* What changed in the project
* Do / Don’t
* Tips and tricks
* Production habit
* Common mistakes
* Debug checklist
* Evaluation checklist
* Safety note
* Code review questions
* Small task
* Production bridge

Do not repeat generic template text in every chapter. Make each chapter specific and useful.

Do not use placeholder code. Every code example should be meaningful, runnable, and connected to the project.

## Chapter Writing Style

Each chapter should feel like a real technical book chapter.

Use this flow when useful:

1. Chapter goal
2. Plain-English explanation
3. Small focused example
4. Explanation of the example
5. Real-world use case
6. Apply it to the running project
7. Show files created or edited
8. Show important code
9. Explain what changed
10. Add Do / Don’t
11. Add production habits
12. Add common mistakes
13. Add debug checklist
14. Add evaluation checklist
15. Add safety note
16. Add small task
17. Add production bridge

Avoid vague advice. Avoid pretending agents are magic. Always explain trade-offs: cost, latency, safety, complexity, and maintainability.

## Book Structure

Use this exact TOC unless I ask you to revise it.

# Table of Contents

## Front Matter

* Title Page
* Copyright / Usage Notes
* How to Use This Book
* Who This Book Is For
* What You Should Already Know
* What You Will Build
* Required Tools
* LLM App Development Roadmap
* Source Code and Project Structure Guide
* Safety and Responsible AI Notes
* How to Use the Chapter-by-Chapter Source Code

---

# Part 1 — LLM Fundamentals for Developers

**Mini Project: Prompt Playground**

## Chapter 1 — What LLMs Are

Cover:

* what an LLM does
* prediction vs understanding
* strengths and limitations
* why LLM apps are different from normal apps

## Chapter 2 — Tokens, Context Windows, and Cost

Cover:

* input tokens
* output tokens
* context limits
* token cost
* cost estimation mindset

## Chapter 3 — Chat Messages and Roles

Cover:

* system messages
* developer instructions
* user messages
* assistant messages
* tool messages
* message ordering

## Chapter 4 — Model Parameters

Cover:

* temperature
* top-p
* max tokens
* stop sequences
* determinism vs creativity

## Chapter 5 — Model Selection

Cover:

* small vs large models
* fast vs accurate models
* cost vs quality
* fallback models
* model switching strategy

## Chapter 6 — Latency and Reliability

Cover:

* network latency
* model latency
* streaming responses
* retries
* timeouts
* graceful degradation

## Chapter 7 — Hallucination and Limitations

Cover:

* what hallucination means
* why hallucinations happen
* grounding
* unsupported claims
* why evaluation is required

## Chapter 8 — Responsible AI Basics

Cover:

* unsafe outputs
* sensitive data
* user trust
* human review
* responsible deployment mindset

## Part 1 Project — Prompt Playground

Build:

* basic chat request
* prompt input area
* model parameter controls
* token/cost display
* response logging
* simple prompt comparison

---

# Part 2 — Prompt Engineering and Context Design

**Mini Project: Reusable Prompt Library**

## Chapter 9 — Prompt Engineering Mental Model

## Chapter 10 — System and Developer Instructions

## Chapter 11 — User Prompt Design

## Chapter 12 — Few-Shot Prompting

## Chapter 13 — Output Format Control

## Chapter 14 — Prompt Templates

## Chapter 15 — Prompt Debugging

## Chapter 16 — Prompt Versioning

## Chapter 17 — Context Engineering Basics

Cover:

* what goes into context
* what stays out
* relevance
* recency
* priority
* context window pressure

## Chapter 18 — Prompt Anti-Patterns

Cover:

* overloaded prompts
* role-play-only prompts
* hidden assumptions
* no evaluation
* no fallback plan

## Part 2 Project — Reusable Prompt Library

Build:

* prompt template folder
* prompt version file
* reusable prompt loader
* prompt changelog
* prompt test cases
* prompt review checklist

---

# Part 3 — LLM App Architecture and Provider Abstraction

**Mini Project: LLM Service Layer**

## Chapter 19 — LLM App Architecture Overview

Cover:

* API layer
* model provider layer
* prompt layer
* tool layer
* retrieval layer
* evaluation layer
* observability layer

## Chapter 20 — Model Provider Abstraction

## Chapter 21 — Request and Response Models

## Chapter 22 — Streaming Responses

## Chapter 23 — Retries, Timeouts, and Fallbacks

## Chapter 24 — Rate Limits and Quotas

## Chapter 25 — Caching LLM Responses

## Chapter 26 — Model Routing

## Chapter 27 — LLM Service Error Design

## Chapter 28 — LLM Service Logging

## Part 3 Project — LLM Service Layer

Build:

```txt
app/
  llm/
    provider.py
    openai_provider.py
    schemas.py
    errors.py
    retry.py
    cache.py
    router.py
```

Include:

* provider interface
* chat wrapper
* streaming wrapper
* retry policy
* fallback model example
* response metadata logging

---

# Part 4 — Structured Outputs, Tool Calling, and Tool Integration

**Mini Project: AI Task Extractor**

## Chapter 29 — Why Structured Outputs Matter

## Chapter 30 — JSON and Schema-Based Outputs

## Chapter 31 — Pydantic for LLM Outputs

## Chapter 32 — Tool Calling Mental Model

## Chapter 33 — Tool Registry Design

## Chapter 34 — Designing Tools Safely

## Chapter 35 — Tool Error Handling

## Chapter 36 — Human Approval for Dangerous Tools

## Chapter 37 — MCP-Style Tool Integration

Cover:

* tool interoperability
* external tool servers
* tool discovery
* tool permissions
* tool integration risks

## Chapter 38 — Tool Calling Anti-Patterns

Cover:

* too many tools
* unclear tool descriptions
* dangerous side effects
* no approval gate
* no audit log

## Part 4 Project — AI Task Extractor

Build:

* extract tasks from text
* validate structured output
* create task tool
* simulate tool approval
* tool error handling
* audit log

---

# Part 5 — Embeddings, Sparse Retrieval, BM25, and Vector Search

**Mini Project: Document Search Engine**

## Chapter 39 — What Embeddings Are

## Chapter 40 — Vector Search Mental Model

## Chapter 41 — Sparse Retrieval Mental Model

Cover:

* keyword retrieval
* exact term matching
* inverted index
* when sparse retrieval helps
* why vector search is not enough

## Chapter 42 — BM25 Indexing

Cover:

* what BM25 is
* term frequency
* inverse document frequency
* document length normalization
* exact keyword search
* technical terms, IDs, names, and codes
* BM25 failure cases

## Chapter 43 — Document Ingestion

## Chapter 44 — Chunking Strategy

## Chapter 45 — Metadata Design

## Chapter 46 — Vector Store Options

## Chapter 47 — BM25 + Vector Hybrid Search

Cover:

* sparse retrieval
* dense retrieval
* combining results
* score fusion
* reciprocal rank fusion
* deduplication
* hybrid retrieval debugging

## Chapter 48 — Reranking

Cover:

* cross-encoder reranking idea
* LLM-based reranking overview
* cost and latency trade-offs

## Chapter 49 — Semantic Caching

## Chapter 50 — Search Index Maintenance

Cover:

* updating vector indexes
* updating BM25 indexes
* re-indexing documents
* versioning indexes
* stale index risks

## Chapter 51 — Retrieval Debugging

Cover:

* bad chunks
* missing metadata
* wrong top-k
* similar but irrelevant results
* keyword mismatch
* debugging search quality

## Part 5 Project — Document Search Engine

Build:

* document loader
* chunker
* BM25 index
* vector index
* metadata filter
* hybrid retriever
* reciprocal rank fusion
* reranking example
* retrieval comparison report

---

# Part 6 — RAG Fundamentals

**Mini Project: PDF Knowledge Assistant**

## Chapter 52 — What RAG Is

## Chapter 53 — When RAG Helps and When It Does Not

## Chapter 54 — RAG Pipeline Design

Cover:

* ingestion
* chunking
* embedding
* indexing
* retrieval
* reranking
* prompt construction
* answer generation

## Chapter 55 — Context Construction

## Chapter 56 — Citation Design

## Chapter 57 — Answer Grounding

## Chapter 58 — RAG Evaluation Basics

## Chapter 59 — Common RAG Mistakes

## Part 6 Project — PDF Knowledge Assistant

Build:

* upload PDF
* extract text
* chunk document
* embed chunks
* retrieve relevant chunks
* generate cited answer
* insufficient-context response
* RAG evaluation examples

---

# Part 7 — Advanced RAG and Retrieval Architecture

**Mini Project: Advanced Knowledge Assistant**

## Chapter 60 — Naive RAG vs Production RAG

## Chapter 61 — Query Transformation

Cover:

* query rewriting
* query expansion
* multi-query retrieval
* step-back prompting
* HyDE-style retrieval overview

## Chapter 62 — Multi-Stage Retrieval

Cover:

* first-stage retrieval
* metadata filtering
* reranking
* context selection
* final answer generation

## Chapter 63 — Contextual Retrieval

Cover:

* why normal chunks lose context
* chunk-specific context generation
* contextualized chunks
* contextual embeddings
* contextual BM25
* when contextual retrieval helps
* when it is too expensive

## Chapter 64 — Contextual BM25

Cover:

* adding document-level context before BM25 indexing
* adding section-level context
* adding page-level context
* exact search with contextualized chunks
* contextual BM25 vs normal BM25
* contextual BM25 vs contextual embeddings

## Chapter 65 — Contextual Retrieval Failure Modes

Cover:

* wrong context added to chunk
* context too long
* context too generic
* context changes meaning
* stale contextualized chunks
* higher indexing cost

## Chapter 66 — Parent-Child Chunking

## Chapter 67 — Hierarchical RAG

## Chapter 68 — Multi-Hop RAG

## Chapter 69 — Corrective RAG

## Chapter 70 — Adaptive RAG

## Chapter 71 — Agentic RAG

Cover:

* RAG as a tool
* agent decides when to retrieve
* agent checks evidence
* agent retries retrieval
* risks of agentic retrieval

## Chapter 72 — RAG for Tables and Semi-Structured Data

## Chapter 73 — RAG for Codebases

## Chapter 74 — RAG for Long Documents

## Chapter 75 — Advanced RAG Failure Modes

Cover:

* wrong chunk retrieved
* right chunk ignored
* citation mismatch
* overstuffed context
* conflicting sources
* stale documents
* permission leakage

## Part 7 Project — Advanced Knowledge Assistant

Build:

* query rewriter
* BM25 retriever
* vector retriever
* hybrid retriever
* reranker
* contextual chunk generator
* contextual embedding index
* contextual BM25 index
* parent-child retrieval
* multi-hop retrieval flow
* corrective RAG fallback
* RAG evaluation report

---

# Part 8 — GraphRAG and Knowledge Graph Retrieval

**Mini Project: Graph-Based Research Assistant**

## Chapter 76 — What GraphRAG Is

Cover:

* baseline RAG
* graph-based RAG
* entities
* relationships
* communities
* claims
* why graphs help with connected information

## Chapter 77 — When GraphRAG Helps

## Chapter 78 — When GraphRAG Is Too Much

## Chapter 79 — Knowledge Graph Construction

Cover:

* entity extraction
* relationship extraction
* claim extraction
* entity resolution
* deduplication
* graph storage

## Chapter 80 — Graph Indexing Pipeline

Cover:

* text units
* entity extraction
* relationship extraction
* community detection
* community summaries
* graph metadata

## Chapter 81 — Local Graph Search

## Chapter 82 — Global Graph Search

## Chapter 83 — DRIFT / Mixed Graph Search

## Chapter 84 — GraphRAG vs Vector RAG

Cover:

* accuracy trade-offs
* cost trade-offs
* latency trade-offs
* complexity trade-offs
* maintenance trade-offs

## Chapter 85 — GraphRAG Evaluation

Cover:

* entity extraction quality
* relationship accuracy
* community summary quality
* answer faithfulness
* citation quality
* cost and latency

## Part 8 Project — Graph-Based Research Assistant

Build:

* entity extractor
* relationship extractor
* simple graph store
* local graph search
* global summary search
* DRIFT-style mixed search overview
* graph citation format
* GraphRAG evaluation checklist

---

# Part 9 — Multimodal and Document Intelligence

**Mini Project: Multimodal Knowledge Assistant**

## Chapter 86 — Multimodal LLM App Mental Model

## Chapter 87 — PDF and Document Understanding

## Chapter 88 — Image and Screenshot Understanding

## Chapter 89 — Table and Spreadsheet Understanding

## Chapter 90 — Chart and Diagram Understanding

## Chapter 91 — Multimodal RAG

## Chapter 92 — Document Intelligence Evaluation

## Part 9 Project — Multimodal Knowledge Assistant

Build:

* PDF parser
* table extractor example
* screenshot question example
* multimodal answer format
* document evaluation checklist

---

# Part 10 — LangChain Fundamentals

**Mini Project: LangChain RAG Assistant**

## Chapter 93 — Why LangChain Exists

## Chapter 94 — When to Use Plain SDK vs LangChain

## Chapter 95 — Models and Prompts

## Chapter 96 — Output Parsers

## Chapter 97 — Runnables and Chains

## Chapter 98 — Retrievers

## Chapter 99 — Tools

## Chapter 100 — Callbacks and Tracing

## Chapter 101 — LangChain Design Patterns

Cover:

* chain pattern
* retriever pattern
* tool pattern
* parser pattern
* callback/tracing pattern
* runnable composition pattern

## Chapter 102 — LangChain Anti-Patterns

## Part 10 Project — LangChain RAG Assistant

Build:

* LangChain prompt
* retriever
* RAG chain
* structured output parser
* tracing callback
* evaluation examples

---

# Part 11 — LangGraph and Agent Workflow Architecture

**Mini Project: Research Agent Graph**

## Chapter 103 — Why LangGraph Exists

## Chapter 104 — Agent Workflow Architecture

Cover:

* state
* nodes
* edges
* tools
* memory
* guards
* human approval
* observability

## Chapter 105 — Graph State Design

## Chapter 106 — Node Design Patterns

Cover:

* planner node
* retriever node
* tool node
* evaluator node
* summarizer node
* approval node
* fallback node

## Chapter 107 — Edge and Routing Patterns

## Chapter 108 — Tool Nodes

## Chapter 109 — Human-in-the-Loop Architecture

## Chapter 110 — Durable Agent Execution

## Chapter 111 — Debugging Agent Graphs

## Chapter 112 — LangGraph Anti-Patterns

## Part 11 Project — Research Agent Graph

Build:

* graph state
* planner node
* retrieval node
* summarization node
* tool node
* evaluator node
* human approval node
* fallback route
* graph debug logs

---

# Part 12 — Agent Design, Architecture, and Design Patterns

**Mini Project: Support Ticket Agent**

## Chapter 113 — What an Agent Really Is

## Chapter 114 — Agent vs Workflow vs Chain

## Chapter 115 — Agent Architecture Layers

Cover:

* user interface
* API layer
* agent orchestration layer
* tool layer
* skill layer
* memory layer
* retrieval layer
* safety layer
* evaluation layer
* observability layer

## Chapter 116 — Router Pattern

## Chapter 117 — Planner-Executor Pattern

## Chapter 118 — ReAct Pattern

## Chapter 119 — Evaluator-Optimizer Pattern

## Chapter 120 — Orchestrator-Worker Pattern

## Chapter 121 — Supervisor Pattern

## Chapter 122 — Tool-Use Agent Pattern

## Chapter 123 — RAG Agent Pattern

## Chapter 124 — Reflection Pattern

## Chapter 125 — Human Approval Gate Pattern

## Chapter 126 — Agent Pattern Selection Guide

Cover:

* which pattern fits which problem
* cost comparison
* latency comparison
* risk comparison
* simplicity comparison

## Part 12 Project — Support Ticket Agent

Build:

* router
* planner-executor workflow
* RAG agent path
* safe tool path
* human approval gate
* evaluator step
* fallback response

---

# Part 13 — Agent Skills and SKILL.md-Style Capability Packages

**Mini Project: Skill-Based Support Assistant**

## Chapter 127 — What Agent Skills Are

Cover:

* skill vs prompt
* skill vs tool
* skill vs workflow
* skill vs MCP server
* reusable capability packages

## Chapter 128 — SKILL.md File Structure

Cover:

* skill name
* description
* when to use
* how to use
* inputs
* outputs
* safety rules
* examples
* reference files
* optional scripts

## Chapter 129 — Designing Useful Skills

## Chapter 130 — Skill Registry Design

## Chapter 131 — Skill Selection

## Chapter 132 — Skill Execution Architecture

## Chapter 133 — Skill Safety and Governance

Cover:

* treat third-party skills as untrusted
* review instructions
* review scripts
* sandbox execution
* permission boundaries
* allowed tools
* blocked tools
* audit logs
* approval workflow

## Chapter 134 — Skills, Tools, MCP, and Plugins

## Chapter 135 — Skill Evaluation

## Part 13 Project — Skill-Based Support Assistant

Build:

* support-response skill
* policy-search skill
* escalation skill
* SKILL.md templates
* skill registry
* skill selection logic
* skill audit log
* skill safety checklist

---

# Part 14 — Multi-Agent Systems

**Mini Project: Multi-Agent Research Team**

## Chapter 136 — When Multi-Agent Systems Help

## Chapter 137 — When Multi-Agent Systems Are Overkill

## Chapter 138 — Multi-Agent Architecture

## Chapter 139 — Agent Communication Patterns

## Chapter 140 — Specialist Agents

Cover:

* research agent
* retrieval agent
* writer agent
* reviewer agent
* safety agent
* tool agent

## Chapter 141 — Conflict Resolution

## Chapter 142 — Multi-Agent Evaluation

## Part 14 Project — Multi-Agent Research Team

Build:

* supervisor agent
* research agent
* retrieval agent
* writer agent
* reviewer agent
* safety agent
* final report aggregator

---

# Part 15 — Memory, Context, and State Management

**Mini Project: Context-Aware Assistant**

## Chapter 143 — Context Engineering Mental Model

## Chapter 144 — Conversation Memory

## Chapter 145 — Retrieval Memory

## Chapter 146 — User Memory

## Chapter 147 — Agent State

## Chapter 148 — Context Compression

## Chapter 149 — Context Poisoning

## Chapter 150 — Memory Evaluation

## Part 15 Project — Context-Aware Assistant

Build:

* conversation summary memory
* retrieval memory
* user preference store
* agent state object
* context builder
* memory evaluation checklist

---

# Part 16 — Evaluation, Testing, and Quality

**Mini Project: AI Evaluation Suite**

## Chapter 151 — Why AI Apps Need Evaluation

## Chapter 152 — Golden Datasets

## Chapter 153 — Unit Tests for Prompts

## Chapter 154 — Structured Output Tests

## Chapter 155 — Retrieval Evaluation

## Chapter 156 — RAG Answer Evaluation

## Chapter 157 — GraphRAG Evaluation

## Chapter 158 — Tool Call Evaluation

## Chapter 159 — Skill Evaluation

## Chapter 160 — Agent Evaluation

## Chapter 161 — Multi-Agent Evaluation

## Chapter 162 — Safety Evaluation

## Chapter 163 — Regression Testing

## Chapter 164 — Human Review Workflow

## Part 16 Project — AI Evaluation Suite

Build:

* eval dataset
* prompt tests
* structured output tests
* retrieval tests
* RAG tests
* GraphRAG tests
* skill tests
* tool call tests
* agent task tests
* safety tests
* evaluation report

---

# Part 17 — Security, Safety, and Guardrails

**Mini Project: Guardrailed AI Assistant**

## Chapter 165 — AI Security Mindset

## Chapter 166 — Prompt Injection

## Chapter 167 — Indirect Prompt Injection

## Chapter 168 — Data Leakage

## Chapter 169 — Retrieval Permissions

## Chapter 170 — Tool Abuse

## Chapter 171 — Skill Supply-Chain Risk

Cover:

* malicious skills
* unsafe scripts
* dependency risks
* external network calls
* permission escalation
* data exfiltration

## Chapter 172 — Output Validation and Moderation

## Chapter 173 — Human Approval Design

## Chapter 174 — Least-Privilege Tool and Skill Design

## Chapter 175 — Audit Logs

## Chapter 176 — Safety Testing

## Part 17 Project — Guardrailed AI Assistant

Build:

* prompt injection test cases
* document safety filter
* permission-aware retrieval
* least-privilege tool registry
* least-privilege skill registry
* tool approval gate
* skill approval gate
* output validation
* safety evaluation checklist

---

# Part 18 — Observability, Cost Control, and LLMOps

**Mini Project: AI Ops Dashboard**

## Chapter 177 — Observability for LLM Apps

## Chapter 178 — Token and Cost Tracking

## Chapter 179 — Latency Tracking

## Chapter 180 — Error Tracking

## Chapter 181 — Retrieval Observability

## Chapter 182 — BM25 and Hybrid Search Observability

## Chapter 183 — Agent Trace Observability

## Chapter 184 — Skill Usage Observability

## Chapter 185 — Feedback Collection

## Chapter 186 — Prompt and Model Operations

## Chapter 187 — Budget Controls

## Chapter 188 — LLMOps Runbooks

## Part 18 Project — AI Ops Dashboard

Build:

* usage logger
* cost tracker
* latency tracker
* retrieval trace
* BM25/vector comparison log
* agent trace
* skill usage trace
* error log
* feedback table
* basic ops report

---

# Part 19 — Model Customization and Optimization

**Mini Project: Model Strategy Report**

## Chapter 189 — Prompting vs RAG vs Fine-Tuning

## Chapter 190 — Fine-Tuning Overview

## Chapter 191 — Synthetic Data

## Chapter 192 — Distillation Overview

## Chapter 193 — Model Routing and Cascades

## Chapter 194 — Small Models and Local Models

## Chapter 195 — Model Strategy Decision Guide

Cover:

* prompt-only
* RAG
* hybrid RAG
* contextual retrieval
* GraphRAG
* fine-tuning
* tool use
* agent workflow
* skills
* human review

## Part 19 Project — Model Strategy Report

Create:

* model selection matrix
* RAG vs fine-tuning decision
* cost estimate
* evaluation plan
* rollout plan

---

# Part 20 — Deployment and Production Runtime

**Mini Project: Deployable AI Assistant**

## Chapter 196 — Deployment Options

## Chapter 197 — Environment Variables and Secrets

## Chapter 198 — Docker for AI Apps

## Chapter 199 — Background Workers

## Chapter 200 — Queue-Based Ingestion

## Chapter 201 — Production Runtime Reliability

## Chapter 202 — Index Migration and Re-Indexing

## Chapter 203 — BM25 Index Deployment

## Chapter 204 — Vector Index Deployment

## Chapter 205 — Skill Deployment and Approval

## Chapter 206 — Deployment Checklist

## Chapter 207 — Rollback Strategy

## Part 20 Project — Deployable AI Assistant

Build:

* Docker Compose setup
* worker process
* environment config
* BM25 index build script
* vector index build script
* skill approval workflow
* re-indexing script
* deployment checklist
* rollback checklist
* production README

---

# Part 21 — Advanced Real-World Use Cases

**Mini Project: AI Solution Design Portfolio**

## Chapter 208 — Enterprise Knowledge Assistant

## Chapter 209 — Customer Support Agent

## Chapter 210 — Legal / Compliance Research Assistant

## Chapter 211 — Financial Research Assistant

## Chapter 212 — Software Engineering Assistant

## Chapter 213 — Data Analysis Assistant

## Chapter 214 — Meeting and Operations Assistant

## Chapter 215 — Agentic Workflow Automation

## Chapter 216 — Skill-Based Internal Assistant

## Chapter 217 — GraphRAG Research Assistant

## Chapter 218 — AI Use Case Design Template

For each use case, include:

* user problem
* business value
* data sources
* model choice
* retrieval strategy
* RAG strategy
* GraphRAG need
* agent pattern
* tool strategy
* skill strategy
* safety risks
* evaluation plan
* deployment plan
* cost estimate
* rollback plan

## Part 21 Project — AI Solution Design Portfolio

Create:

* 5 real-world solution designs
* architecture diagrams
* retrieval strategy per use case
* RAG strategy per use case
* agent pattern per use case
* skill strategy per use case
* safety checklist
* evaluation checklist
* cost checklist

---

# Part 22 — AI Tools and Ecosystem

**Mini Project: Tool Comparison Notes**

## Chapter 219 — OpenAI API

## Chapter 220 — Other Model Providers Overview

## Chapter 221 — LangChain

## Chapter 222 — LangGraph

## Chapter 223 — LlamaIndex Overview

## Chapter 224 — Vector Database Options

## Chapter 225 — BM25 and Search Engine Options

Cover:

* local BM25
* Elasticsearch / OpenSearch overview
* PostgreSQL full-text search overview
* hybrid retrieval options

## Chapter 226 — MCP and Tool Integration Ecosystem

## Chapter 227 — Agent Skills Ecosystem

## Chapter 228 — Evaluation and Observability Tools

## Chapter 229 — Tool Selection Guide

---

# Part 23 — Legacy and Misleading AI Patterns

## Chapter 230 — Prompt-Only Apps

## Chapter 231 — Unsafe Autonomous Agents

## Chapter 232 — Overusing Agents

## Chapter 233 — Poor RAG Systems

## Chapter 234 — Vector-Only Search Mistakes

## Chapter 235 — Overcomplicated GraphRAG

## Chapter 236 — Contextual Retrieval Overuse

## Chapter 237 — Skill Abuse and Unsafe Skill Loading

## Chapter 238 — Memory Abuse

## Chapter 239 — No Evaluation Culture

## Chapter 240 — Trusting Model Output Without Validation

---

# Part 24 — Final Capstone Project

**Capstone: AI Research and Support Assistant**

## Chapter 241 — Capstone Requirements

## Chapter 242 — Capstone Solution Design

## Chapter 243 — Capstone Architecture

## Chapter 244 — Building the Prompt Playground

## Chapter 245 — Building the LLM Service Layer

## Chapter 246 — Building Document Upload and Ingestion

## Chapter 247 — Building the BM25 Index

## Chapter 248 — Building the Vector Index

## Chapter 249 — Building Hybrid Search and Reranking

## Chapter 250 — Building Contextual Retrieval

## Chapter 251 — Building Contextual BM25

## Chapter 252 — Building Advanced RAG

## Chapter 253 — Building GraphRAG Search

## Chapter 254 — Building Retrieval and Citations

## Chapter 255 — Building the Support Ticket Workflow

## Chapter 256 — Building Tool Calling

## Chapter 257 — Building the Agent Skills System

## Chapter 258 — Building the LangGraph Agent

## Chapter 259 — Building Human Approval Gates

## Chapter 260 — Building Memory and Context

## Chapter 261 — Building Evaluation Tests

## Chapter 262 — Building Safety and Guardrails

## Chapter 263 — Building Observability and Cost Tracking

## Chapter 264 — Final Deployment Pass

## Chapter 265 — Final Code Quality Review

## Chapter 266 — Portfolio README

---

# Appendices

## Appendix A — LLM Concepts Cheatsheet

## Appendix B — Prompt Engineering Cheatsheet

## Appendix C — Prompt Template Examples

## Appendix D — Structured Output Examples

## Appendix E — Tool Calling Checklist

## Appendix F — MCP-Style Tool Integration Checklist

## Appendix G — Agent Skills and SKILL.md Template

## Appendix H — Agent Skill Safety Checklist

## Appendix I — Embedding and Vector Search Cheatsheet

## Appendix J — BM25 and Sparse Retrieval Cheatsheet

## Appendix K — Hybrid Retrieval Checklist

## Appendix L — Contextual Retrieval Prompt Template

## Appendix M — Contextual Retrieval Evaluation Checklist

## Appendix N — Advanced RAG Pattern Matrix

Include:

* naive RAG
* BM25 retrieval
* vector RAG
* hybrid RAG
* contextual RAG
* contextual BM25
* parent-child RAG
* hierarchical RAG
* corrective RAG
* adaptive RAG
* agentic RAG
* multi-hop RAG
* GraphRAG

## Appendix O — GraphRAG Checklist

## Appendix P — RAG Evaluation Checklist

## Appendix Q — LangChain Cheatsheet

## Appendix R — LangGraph Cheatsheet

## Appendix S — Agent Design Pattern Matrix

Include:

* router
* planner-executor
* ReAct
* evaluator-optimizer
* orchestrator-worker
* supervisor
* tool-use agent
* RAG agent
* reflection
* human approval gate

## Appendix T — Agent Architecture Checklist

## Appendix U — Multi-Agent System Checklist

## Appendix V — Memory and Context Checklist

## Appendix W — AI Evaluation Dataset Template

## Appendix X — Prompt Versioning Template

## Appendix Y — Safety and Guardrails Checklist

## Appendix Z — Prompt Injection Test Set

## Appendix AA — AI Observability Checklist

## Appendix AB — Cost Tracking Template

## Appendix AC — Model Strategy Decision Matrix

## Appendix AD — Real-World AI Use Case Template

## Appendix AE — Deployment Checklist

## Appendix AF — Rollback Checklist

## Appendix AG — Architecture Decision Record Template

## Appendix AH — Source Bundle Structure

Use this structure:

```txt
source-bundle/
  starter-project/
  completed-project/
  chapter-snapshots/
    part-01-prompt-playground/
    part-03-llm-service-layer/
    part-05-bm25-vector-search/
    part-07-advanced-rag/
    part-08-graph-rag/
    part-11-langgraph/
    part-12-agent-patterns/
    part-13-agent-skills/
    part-16-evaluation/
    part-17-guardrails/
    part-24-capstone/
  prompt-templates/
  skill-templates/
  eval-datasets/
  safety-tests/
  bm25-examples/
  rag-examples/
  graph-rag-examples/
  langchain-examples/
  langgraph-examples/
  agent-pattern-examples/
  real-world-use-cases/
  docs/
  checklists/
  README.md
```

## Appendix AI — Source Bundle Guide

---

# Design Requirements

Make the final PDF look like a clean professional technical book, not a chat export.

Use this style:

* simple title page
* clean table of contents with page numbers
* clickable TOC
* PDF bookmarks / outline
* running page header
* thin blue accent line
* white page background
* black or near-black text
* clean chapter headings
* readable paragraphs
* light bordered code blocks
* monospace code font
* RAG pipeline diagrams
* BM25/vector hybrid search diagrams
* GraphRAG diagrams
* agent workflow diagrams
* LangGraph diagrams
* skill registry diagrams
* evaluation tables
* cost tables
* safety checklists
* callout boxes for Tip, Do, Don’t, Warning, Production habit, Safety note, Evaluation note, Task
* comfortable margins
* good spacing between sections
* no cramped pages
* no huge blank bottom spaces
* no hype-heavy design
* no chat-style formatting

## Output Files

Create:

1. `Production_LLM_and_Agentic_App_Development_2026_Final.pdf`
2. `Production_LLM_and_Agentic_App_Development_2026_Google_Docs_Editable.docx`
3. `Production_LLM_and_Agentic_App_Development_2026_Source_Bundle.zip`

The source ZIP should include:

* starter project
* completed project
* chapter snapshots
* prompt playground
* LLM service layer
* prompt templates
* skill templates
* BM25 examples
* vector search examples
* hybrid retrieval examples
* contextual retrieval examples
* GraphRAG examples
* LangChain examples
* LangGraph examples
* agent pattern examples
* agent skills examples
* eval datasets
* safety tests
* real-world solution designs
* docs
* checklists
* README templates
* deployment checklist
* rollback checklist

## Important Workflow

Do not build the whole book immediately.

First, show the final TOC only for review.

After TOC approval, show **Part 7 — Advanced RAG and Retrieval Architecture** as a PDF design sample for review.

Wait for approval.

After approval, build the full PDF, DOCX, and ZIP.
