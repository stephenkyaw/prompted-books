Here is the clean `README.md` text without your name.

# Prompted Books

> Original, AI-assisted technical books for working engineers — practical, project-based, and designed like real books.

**Prompted Books** is a growing library of original technical books created through a prompt-driven workflow, reviewed by a human, and typeset into clean, readable formats.

Repository: [github.com/stephenkyaw/prompted-books](https://github.com/stephenkyaw/prompted-books)

Each book focuses on one technical area and teaches it through real projects, not only definitions or API references. The goal is to learn the way engineers actually build software — with architecture, trade-offs, code, testing, deployment, mistakes, and production habits included.

---

## What This Repository Is

This repository contains original technical books and the prompts used to create them.

Each book is designed to be:

* **Project-based** — concepts are applied to one running project.
* **Production-minded** — architecture, testing, deployment, and trade-offs are included.
* **Readable** — clean PDF layout, table of contents, code blocks, and structured chapters.
* **Reusable** — prompts are saved so the process can be improved and repeated.
* **Practical** — written for learners who want to build, not just read.

---

## What This Repository Is Not

This is **not** a curated list of other people’s books.

This is also **not** official documentation for any framework, library, platform, or tool.

The books are AI-assisted and human-reviewed, but technical details can still become outdated or contain mistakes. Always cross-check important implementation details with official documentation.

---

## Current Book Catalog

| Book                                                | Topic                                                                                                          | Status          | Output       |
| --------------------------------------------------- | -------------------------------------------------------------------------------------------------------------- | --------------- | ------------ |
| **Production React App 2026**                       | React, TypeScript, Next.js, TanStack Query, Zustand, Tailwind, shadcn/ui, React Hook Form, Zod, testing        | ✅ Available     | PDF / Source |
| **Programming Fundamentals with Python 2026**       | Python basics, CLI apps, files, JSON, debugging, beginner projects                                             | 📝 Prompt Ready | Planned      |
| **Data Structures and Algorithms with Python 2026** | DSA, LeetCode patterns, problem solving, 100-problem bank                                                      | 📝 Prompt Ready | Planned      |
| **Production Python Backend Development 2026**      | FastAPI, Docker, ORM, PostgreSQL, REST APIs, auth, testing, deployment                                         | 📝 Prompt Ready | Planned      |
| **Advanced Python Engineering 2026**                | Advanced functions, OOP, typing, design patterns, architecture, TDD, async, packaging                          | 📝 Prompt Ready | Planned      |
| **Production LLM and Agentic App Development 2026** | Prompting, RAG, BM25, Contextual Retrieval, GraphRAG, LangChain, LangGraph, agents, skills, safety, evaluation | 📝 Prompt Ready | Planned      |

---

## Book Series Overview

### Production React App 2026

A project-based React book for developers who want to build production-grade frontend applications.

Covers:

* React fundamentals
* TypeScript for React
* component design
* hooks
* state management
* TanStack Query
* Zustand
* Tailwind CSS
* shadcn/ui
* React Hook Form
* Zod
* testing
* Next.js App Router
* production architecture
* capstone project

---

### Programming Fundamentals with Python 2026

A beginner-friendly programming book using Python.

Covers:

* Python setup
* variables and data types
* strings, numbers, booleans
* conditionals
* loops
* lists, tuples, dictionaries, sets
* functions
* files and JSON
* debugging
* basic OOP
* modules and packages
* final CLI task manager project

---

### Data Structures and Algorithms with Python 2026

A practical DSA and LeetCode-style problem-solving book.

Covers:

* Big-O
* problem-solving strategy
* Python for DSA
* arrays and strings
* hash maps
* stacks and queues
* linked lists
* recursion and backtracking
* trees
* graphs
* heaps
* binary search
* greedy and intervals
* tries
* dynamic programming
* interview strategy
* 100-problem practice bank
* answer guide and solution explanations

---

### Production Python Backend Development 2026

A backend engineering book focused on building production REST APIs with Python.

Covers:

* HTTP and REST
* FastAPI
* Pydantic
* SQLAlchemy or SQLModel
* PostgreSQL
* Alembic migrations
* Docker and Docker Compose
* Redis
* background jobs
* authentication and authorization
* API architecture
* coding standards
* testing
* logging
* observability
* security
* CI/CD
* deployment
* production task management API capstone

---

### Advanced Python Engineering 2026

A senior-level Python engineering book.

Covers:

* Python runtime behavior
* object identity and references
* mutability
* equality and hashing
* modern Python features
* advanced functions
* decorators
* generators
* context managers
* OOP
* dataclasses
* protocols
* type-driven design
* data validation
* SOLID principles
* design patterns
* architecture design
* TDD
* testing strategy
* performance
* GIL
* concurrency and async
* metaprogramming
* packaging
* public API design
* legacy code refactoring
* plugin-based workflow automation capstone

---

### Production LLM and Agentic App Development 2026

A production-focused LLM engineering book.

Covers:

* LLM fundamentals
* prompt engineering
* context engineering
* model provider abstraction
* streaming
* structured outputs
* tool calling
* MCP-style tool integration
* embeddings
* vector search
* sparse retrieval
* BM25
* hybrid search
* reranking
* RAG
* advanced RAG
* contextual retrieval
* contextual BM25
* GraphRAG
* LangChain
* LangGraph
* agent design patterns
* agent skills and `SKILL.md`
* multi-agent systems
* memory and state
* evaluation
* safety and guardrails
* observability
* cost tracking
* deployment
* AI Research and Support Assistant capstone

---

## How the Books Are Made

Each book follows the same repeatable workflow.

### 1. Topic Planning

Each book starts with a clear technical area, target audience, and final project.

Example:

```text
Advanced Python Engineering for developers who already know Python basics.
```

### 2. TOC First

Before generating the full book, the table of contents is created and reviewed.

The TOC includes:

* parts
* chapters
* mini-projects
* capstone project
* appendices
* source bundle structure

### 3. Prompt Creation

A detailed prompt is written for the book.

Each prompt includes:

* audience
* goals
* teaching style
* chapter structure
* exact TOC
* design requirements
* output files
* workflow rules

### 4. Sample PDF Review

Before building the full book, one selected part is generated as a PDF sample.

This helps check:

* writing style
* code style
* page layout
* code block readability
* spacing
* table of contents design
* overall book quality

### 5. Full Book Generation

After sample approval, the full book is generated.

Typical outputs:

```text
Book_Title_Final.pdf
Book_Title_Google_Docs_Editable.docx
Book_Title_Source_Bundle.zip
```

### 6. Human Review

Each book is reviewed for:

* clarity
* outdated APIs
* incorrect code
* weak explanations
* repeated filler
* missing production details
* bad formatting

### 7. Typesetting

The final version is formatted like a real book:

* clean cover
* readable typography
* clickable table of contents
* running headers
* page numbers
* syntax-highlighted code blocks
* diagrams and tables where useful
* appendices and checklists

---

## Accuracy Notice

These books are **AI-assisted and human-reviewed**, but they are not guaranteed to be perfect.

Large language models can produce:

* outdated API usage
* incorrect function signatures
* incomplete examples
* inaccurate library behavior
* overconfident explanations
* missing edge cases

Always check critical details against official documentation.

When reporting an issue, include:

```text
Book:
Chapter or page:
Problem:
Suggested fix:
Reference link:
```

---

## Repository Structure

```text
prompted-books/
├── README.md
├── react/
│   ├── README.md
│   ├── production-react-app-2026.pdf
│   ├── production-react-app-2026.html
│   └── source-bundle/
├── python-fundamentals/
│   ├── README.md
│   ├── prompts/
│   └── source-bundle/
├── dsa-python/
│   ├── README.md
│   ├── prompts/
│   └── source-bundle/
├── python-backend/
│   ├── README.md
│   ├── prompts/
│   └── source-bundle/
├── advanced-python/
│   ├── README.md
│   ├── prompts/
│   └── source-bundle/
├── llm-agentic-apps/
│   ├── README.md
│   ├── prompts/
│   └── source-bundle/
├── prompts/
│   ├── 01-programming-fundamentals-python.md
│   ├── 02-dsa-python.md
│   ├── 03-python-backend.md
│   ├── 04-advanced-python-engineering.md
│   ├── 05-llm-agentic-app-development.md
│   └── style-guide.md
├── assets/
│   ├── covers/
│   ├── diagrams/
│   └── templates/
└── docs/
    ├── workflow.md
    ├── accuracy-policy.md
    └── contribution-guide.md
```

---

## Prompt Library

The prompts used to generate the books are stored in [`/prompts`](./prompts).

These prompts are part of the project because the process matters as much as the final PDF.

Prompt files may include:

* book-generation prompts
* TOC prompts
* style prompts
* PDF design prompts
* source bundle prompts

This makes the workflow transparent, repeatable, and easier to improve.

---

## Book Format

Each completed book may include:

```text
Book_Title_Final.pdf
Book_Title_Google_Docs_Editable.docx
Book_Title_Source_Bundle.zip
Book_Title.html
README.md
CHANGELOG.md
```

Not every book will have every format immediately.

The main reading format is PDF.

---

## Source Bundles

Source bundles may include:

* starter project
* completed project
* chapter snapshots
* exercises
* solution examples
* checklists
* diagrams
* README templates
* test files
* configuration files
* deployment notes

The goal is to make every book buildable, not only readable.

---

## Reading and Downloading

Open a book folder and download the PDF directly.

No build step is required to read the books.

Example:

```text
react/production-react-app-2026.pdf
```

---

## Roadmap

* [x] Create first React book
* [x] Create prompt system for Python fundamentals
* [x] Create prompt system for DSA with Python
* [x] Create prompt system for Python backend development
* [x] Create prompt system for Advanced Python Engineering
* [x] Create prompt system for LLM and agentic app development
* [ ] Publish all book prompts
* [ ] Create consistent cover system
* [ ] Generate Python Fundamentals book
* [ ] Generate DSA with Python book
* [ ] Generate Production Python Backend book
* [ ] Generate Advanced Python Engineering book
* [ ] Generate Production LLM and Agentic App book
* [ ] Add EPUB versions
* [ ] Add website or GitHub Pages preview

---

## Contributing

Feedback is welcome.

Useful contributions include:

* reporting technical errors
* improving prompts
* suggesting missing topics
* fixing code examples
* improving diagrams
* improving formatting
* adding official documentation references
* improving source bundles

When opening an issue, include:

```text
Book:
Chapter or page:
Problem:
Suggested fix:
Reference link:
```

---

## Suggested Issue Labels

```text
bug
technical-error
outdated-api
formatting
prompt-improvement
new-book-request
source-bundle
documentation
good-first-issue
```

---

## License

Suggested license setup:

* **Book prose and diagrams:** Creative Commons Attribution 4.0 International — CC BY 4.0
* **Code samples and source bundles:** MIT License

Before making the repository public, add:

```text
LICENSE
LICENSE-CODE
```

Adjust the license choice before publishing if needed.

---

## Repository

GitHub Repository: [stephenkyaw/prompted-books](https://github.com/stephenkyaw/prompted-books)

Clone the repository:

```bash
git clone https://github.com/stephenkyaw/prompted-books.git
cd prompted-books
```

A star on the repository is appreciated and helps others discover the books.
