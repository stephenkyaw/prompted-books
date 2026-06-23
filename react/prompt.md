You are an expert React educator, senior frontend architect, book typesetter, and technical-content designer.

Create a professional technical ebook called:

# Production React App 2026

Subtitle:

**A Project-Based Guide to Building Production-Grade React Applications**

Audience:

The reader is a senior backend engineer familiar with Python/FastAPI and C#, comfortable with programming fundamentals, but weak on frontend and React.

Goal:

Write and design a practical, project-based React ebook that teaches how to build real production-grade React apps. Do not write a shallow React tutorial. Teach the tools, patterns, architecture, coding standards, and project workflow used by real teams.

Use current official documentation as the source of truth for React, Next.js, TanStack Query, Zustand, Tailwind CSS, shadcn/ui, React Hook Form, Zod, Vitest, Testing Library, MSW, Playwright, and Storybook.

Main project:

Build one running capstone project throughout the book:

**Production React App 2026 — Issue Tracker Dashboard**

Final app features:

* authentication
* dashboard layout
* projects
* issues/tasks
* issue status workflow
* search and filters
* create/edit/delete forms
* validation
* loading/error/empty states
* optimistic updates
* role-based UI
* typed API layer
* reusable components
* production folder structure
* testing
* CI/CD checklist
* deployment checklist
* portfolio README

Required stack:

* React with TypeScript
* Next.js App Router
* Tailwind CSS
* shadcn/ui
* React Hook Form
* Zod
* Zustand
* TanStack Query
* TanStack Table
* Vitest
* React Testing Library
* MSW
* Playwright
* Storybook
* ESLint
* Prettier
* TypeScript strict mode
* npm or pnpm
* optional backend integration examples with FastAPI, C#/.NET, and Next.js Route Handlers

Book structure:

Part 1 — JavaScript and TypeScript You Need for React

Cover:

* modern JavaScript mental model for React
* destructuring
* spread/rest syntax
* array methods: map, filter, find, some, every, reduce, safe sorting
* optional chaining
* nullish coalescing
* async/await
* fetch
* modules
* TypeScript object types
* unions and literal types
* generics
* narrowing
* React TypeScript basics: props, callback props, children, useState, events

Mini project:

**Issue Data Playground**

Part 2 — Thinking in React and Designing Components from UI/UX

Cover:

* how to think in React
* reading UI/Figma/wireframes
* turning UI into component hierarchy
* designing component APIs
* component types in production apps
* UI states: loading, empty, error, disabled, submitting, success, permission denied
* mapping UI/UX to state model
* feature folders from UI screens
* component review checklist

Part 3 — React Core You Must Know

Create a Vite React TypeScript mini project named:

**Vite Issue Board**

Include setup commands:

```bash
npm create vite@latest issue-board-vite -- --template react-ts
cd issue-board-vite
npm install
npm run dev
```

Cover:

* JSX, components, and composition
* props and component boundaries
* state and rendering behavior
* events and controlled inputs
* lists, keys, and conditional rendering
* derived state
* useEffect: when to use it and when not to
* refs and escape hatches
* custom hooks

Part 4 — React Best Practices and Techniques

Cover:

* data down, events up
* single source of truth
* colocating state
* lifting state only when needed
* common React mistakes
* component design techniques
* controlled vs uncontrolled components
* compound components
* slot-style composition
* headless component thinking
* loading/error/empty state patterns
* reusable UI API design

Part 5 — Architecture, Folder Structure, and Coding Standards

Cover:

* frontend architecture overview
* recommended production folder structure
* folder rules
* naming standards
* component coding standard
* TypeScript coding standard
* import/export standard
* API layer coding standard
* state coding standard
* styling coding standard
* form coding standard
* testing coding standard
* code quality tools
* PR coding standard
* common architecture mistakes

Use this structure:

```txt
src/
  app/
  components/
    ui/
    layout/
    feedback/
  features/
    auth/
    projects/
    issues/
  hooks/
  lib/
  stores/
  types/
  tests/
```

Part 6 — Build Real UI

Cover:

* Tailwind CSS
* shadcn/ui
* dashboard layout
* app shell
* sidebar
* top navigation
* responsive layout
* accessibility basics
* production UI polish
* skeletons
* empty states
* confirmation dialogs
* toast feedback
* Storybook/component playground

Part 7 — Forms and Validation

Cover:

* manual forms first
* React Hook Form
* Zod
* React Hook Form + Zod + shadcn/ui
* create issue form
* edit issue form
* field errors
* server errors
* dirty state
* submit loading
* reset after success
* form UX best practices

Part 8 — Client State and Server State

Cover:

* local state
* client UI state
* server state
* form state
* URL state
* Zustand
* TanStack Query
* queries
* mutations
* invalidation
* optimistic updates
* pagination
* search
* filters
* URL search params
* state best practices

Part 9 — Data Tables and Dashboard Patterns

Cover:

* table UX basics
* TanStack Table
* columns
* sorting
* filtering
* pagination
* row actions
* selected rows
* bulk actions
* dashboard cards
* metrics
* search and filters

Part 10 — Next.js App Router

Cover:

* why Next.js for production React
* App Router structure
* Server Components vs Client Components
* routing and layouts
* route groups
* loading.tsx
* error.tsx
* not-found.tsx
* server-side fetching
* client-side fetching
* Server Actions
* Route Handlers
* authentication
* authorization
* environment variables

Part 11 — Common Tools Used in Production React Teams

Cover:

* npm, pnpm, Bun overview
* lockfiles
* ESLint
* Prettier
* TypeScript strict mode
* React DevTools
* TanStack Query Devtools
* browser DevTools
* clsx
* tailwind-merge
* class-variance-authority
* date-fns
* lucide-react
* sonner
* monorepo basics
* Turborepo overview

Part 12 — Backend Integration for a Frontend Engineer

Cover:

* mock API first
* Next.js Route Handlers
* FastAPI backend option
* C#/.NET backend option
* PostgreSQL option
* Prisma
* Drizzle
* DTOs
* request/response types
* error response shape
* validation boundary
* CORS
* auth tokens
* OpenAPI/generated types

Part 13 — Testing and Quality

Cover:

* testing strategy
* Vitest
* React Testing Library
* MSW
* Playwright
* test data factories
* component tests
* API mocks
* E2E flows
* testing loading/error/empty states
* testing forms
* testing protected routes

Part 14 — Production Hardening

Cover:

* error handling
* error boundaries
* observability basics
* error monitoring
* performance techniques
* unnecessary re-renders
* useMemo/useCallback/memo
* dynamic imports
* virtualization
* Suspense and loading UX
* security basics
* deployment readiness
* CI/CD checklist
* dependency maintenance

Part 15 — Legacy React You Will See

Cover:

* class components
* lifecycle methods
* old Redux boilerplate
* HOCs
* render props
* old Next.js Pages Router
* how to recognize and modernize them

Part 16 — Capstone Project

Build the final:

**Production React App 2026 — Issue Tracker Dashboard**

Include:

* capstone architecture
* final folder structure
* routes
* entities
* data flow
* auth flow
* state model
* issue table
* project pages
* create/edit issue forms
* optimistic status update
* role-based UI
* tests
* code review
* deployment checklist
* portfolio README template

Writing style:

Use simple, clear English. Write like a professional technical book author, not like a chat assistant.

For each major topic, explain:

* What is it?
* Why use it?
* When should you use it?
* When should you not use it?
* How do you use it?
* Real-world example
* Apply it to the project
* Common mistakes
* Do / Don’t
* Tips and tricks
* Production habit
* Debug checklist or code review questions
* Checkpoint
* Small task
* Production bridge

Do not repeat the same generic template text in every chapter. Make each chapter specific and useful.

Every chapter should include enough complete code that the reader can follow without guessing.

Use this chapter rhythm:

1. Explain the idea in simple English.
2. Show a small focused example.
3. Explain the example.
4. Show where it belongs in the running project.
5. Show real project files and code.
6. Explain what changed in the app.
7. Add practical tips, Do/Don’t, and common mistakes.
8. Add a checkpoint and a small task.
9. Explain how this simple version becomes production-grade later.

Design style:

Make the PDF look like a clean, simple technical book, not a chat export.

Use this visual style:

* simple title page
* simple table of contents with page numbers
* clickable TOC
* PDF bookmarks / outline
* running page header
* thin blue line under page header
* clean chapter titles
* white page background
* black or near-black body text
* one light blue accent color
* readable serif or clean sans-serif body font
* simple bordered code blocks, not heavy dark boxes
* monospace code font
* no low-contrast code
* no unnecessary decorative boxes
* no large blank bottom spaces
* comfortable spacing between paragraphs and sections
* diagrams where they improve understanding
* simple centered screenshots or mock UI diagrams when useful
* print-friendly layout

Use light, simple callout boxes:

* Tip
* Do
* Don’t
* Warning
* Production habit
* Debug checklist
* Task

Keep boxes clean with thin borders or a subtle left accent bar.

Output required:

1. Final polished PDF ebook:
   **Production_React_App_2026_Final_Polished_Book.pdf**

2. Editable DOCX version for Google Docs:
   **Production_React_App_2026_Google_Docs_Editable.docx**

3. Source bundle ZIP:
   **Production_React_App_2026_Final_Source_Bundle.zip**

The ZIP should include:

* part-1-data-playground
* issue-board-vite
* production-react-app-2026
* tests/examples
* docs/checklists
* README.md
* portfolio README template
* deployment checklist
* PR checklist

Important:

Before building the full book, show Part 3 as a PDF sample for review. Use the simple clean book design, with title page, TOC, running header, light code blocks, and readable spacing. Wait for approval. After approval, build the full PDF, DOCX, and source ZIP.
