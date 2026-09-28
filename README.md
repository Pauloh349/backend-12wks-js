# Backend 12-Week Engineering Journey

A 12-week practical journey to become a stronger **backend engineer**.

This journey focuses on:

- Node.js
- TypeScript
- Fastify
- PostgreSQL
- REST APIs
- Authentication & security
- Testing
- Performance
- Docker
- Linux
- Nginx
- Deployment

This is **not a beginner JavaScript course**. I already have a foundation in JavaScript, so the goal is to use that knowledge to build real backend systems.

---

## Why Am I Doing This?

AI can now generate a lot of code very quickly.

But being able to generate code is not the same as understanding software.

I want to be able to:

- Understand how backend systems work
- Build APIs myself
- Design databases
- Read documentation
- Debug problems
- Make technical decisions
- Write secure code
- Understand performance
- Deploy applications
- Use AI without depending on it

The goal is simple:

> **I want to understand the code I write, not just have code that works.**

---

# My Main Rule

## I Type the Code Myself

I will **not copy and paste complete solutions from AI**.

When learning something new, I will write it myself.

That means I will:

1. Read about the problem
2. Read the documentation
3. Think about the solution
4. Write the code
5. Run it
6. Make mistakes
7. Debug the mistakes
8. Test the result
9. Improve the code

The struggle is part of the learning.

> **If I cannot write it, explain it, and debug it myself, I have not learned it yet.**

---

# Documentation First

Before asking AI how something works, I will first check the official documentation.

For example:

- Node.js → official Node.js docs
- TypeScript → official TypeScript docs
- Fastify → official Fastify docs
- PostgreSQL → official PostgreSQL docs
- Docker → official Docker docs
- Nginx → official Nginx docs

I want to become comfortable finding answers myself.

Documentation is not something I should avoid just because AI can explain things faster.

---

# Debugging First

When something breaks, I will try to fix it myself before asking AI.

My process:

```text
Something breaks
      ↓
Read the error
      ↓
Check my code
      ↓
Check the documentation
      ↓
Test possible causes
      ↓
Fix the problem
      ↓
Test again
```

If I am still stuck after a genuine attempt, then I can ask AI for help.

But I should ask for an **explanation or hint first**, not a complete solution.

### Good

> "Why is my Fastify route returning 400? Help me understand the problem without writing the solution."

### Avoid

> "Build this Fastify API for me."

---

# How I Will Use AI

AI is allowed, but **AI comes later**.

### I can use AI to:

- Explain a concept
- Explain an error
- Give me a hint
- Explain documentation
- Help me understand something difficult
- Review code I already wrote
- Suggest things I should test
- Discuss architecture

### I will not use AI to:

- Build my projects for me
- Generate complete exercises
- Generate complete API implementations
- Generate entire files for me to copy
- Generate database schemas that I blindly use
- Generate authentication systems that I simply paste
- Replace documentation reading
- Replace debugging

The purpose is to make AI a **teacher and reviewer**, not my programmer.

---

# The 12-Week Roadmap

| Week | Focus                  | Goal                           |
| ---- | ---------------------- | ------------------------------ |
| 01   | JavaScript for Backend | Strengthen backend JS          |
| 02   | Async JavaScript       | Understand asynchronous code   |
| 03   | Node.js                | Understand the Node.js runtime |
| 04   | TypeScript             | Build typed applications       |
| 05   | HTTP & REST            | Understand APIs                |
| 06   | Fastify                | Build backend APIs             |
| 07   | PostgreSQL             | Learn SQL and databases        |
| 08   | Fastify + PostgreSQL   | Connect API to database        |
| 09   | Architecture           | Structure backend applications |
| 10   | Auth & Security        | Secure the API                 |
| 11   | Performance            | Measure and optimize           |
| 12   | Production             | Deploy the application         |

---

# Week 01 — JavaScript for Backend

Focus on JavaScript concepts that are important for backend development.

### Learn

- Functions
- Objects
- Arrays
- Array methods
- Destructuring
- Modules
- Scope
- Closures
- Error handling
- Data transformation

### Build

Small programs such as:

- Student manager
- Grade calculator
- Data filtering system
- CLI application

---

# Week 02 — Async JavaScript

### Learn

- Callbacks
- Promises
- `async/await`
- Promise chaining
- Error handling
- `Promise.all`
- Concurrent vs sequential operations
- Fetch
- JSON
- Event loop

### Build

A small API client.

---

# Week 03 — Node.js

### Learn

- Node.js runtime
- npm
- `package.json`
- Modules
- Environment variables
- File system
- Paths
- Events
- Buffers
- Streams
- HTTP

### Build

A basic HTTP server using Node.js without a framework.

The goal is to understand what frameworks such as Fastify are doing for me.

---

# Week 04 — TypeScript

### Learn

- Types
- Interfaces
- Type aliases
- Unions
- Type narrowing
- Generics
- Functions
- Modules
- `tsconfig.json`

### Build

Convert a Node.js project to TypeScript.

---

# Week 05 — HTTP & REST

### Learn

- HTTP methods
- Status codes
- Headers
- Request bodies
- Query parameters
- Route parameters
- REST
- Pagination
- Filtering
- Error responses
- CORS
- Rate limiting

### Build

Design the API for the Student Learning API.

Before writing code, decide:

- What resources exist?
- What endpoints are needed?
- What should requests look like?
- What should responses look like?
- What errors can occur?

---

# Week 06 — Fastify

### Learn

- Routes
- Parameters
- Query strings
- Request bodies
- Responses
- Schemas
- Validation
- Serialization
- Plugins
- Hooks
- Error handling
- Logging

### Build

A CRUD API using Fastify.

---

# Week 07 — PostgreSQL

### Learn

- Tables
- Rows
- Columns
- Primary keys
- Foreign keys
- Constraints
- CRUD
- Filtering
- Sorting
- Joins
- Relationships
- Indexes
- Transactions

### Build

A database for:

- Students
- Courses
- Units
- Learning materials
- Past papers

I will write the SQL myself.

---

# Week 08 — Fastify + PostgreSQL

Connect the Fastify API to PostgreSQL.

### Build

- Student creation
- Student retrieval
- Student updates
- Student deletion
- Courses
- Units
- Learning materials

Learn:

- Connection pools
- Queries
- Parameterized queries
- Transactions
- Database errors

---

# Week 09 — Backend Architecture

Move from "it works" to "it is well organized."

### Learn

- Project structure
- Routes
- Controllers
- Services
- Database layer
- Configuration
- Validation
- Error handling
- Separation of responsibilities

### Build

Refactor the Student Learning API into a clean structure.

---

# Week 10 — Authentication & Security

### Learn

- Password hashing
- Argon2id
- Registration
- Login
- JWT
- Access tokens
- Refresh tokens
- Authorization
- Roles
- Protected routes
- Rate limiting
- Secrets
- CORS
- SQL injection prevention

### Build

Authentication for the Student Learning API.

I will implement it myself and use documentation to understand every part.

---

# Week 11 — Performance

### Learn

- Database indexes
- Query performance
- `EXPLAIN`
- Connection pooling
- Pagination
- Payload size
- Caching
- Load testing
- Bottlenecks

### Practice

Find something that is actually slow.

Then:

```text
Measure
   ↓
Identify the problem
   ↓
Make one change
   ↓
Measure again
   ↓
Compare the results
```

---

# Week 12 — Production

### Learn

- Linux
- Environment variables
- Docker
- Nginx
- HTTPS
- Domains
- Process management
- Logging
- Monitoring
- Backups
- Deployment

### Goal

Take the Student Learning API from a development project toward a production-ready application.

---

# Main Project

## Student Learning API

Throughout the 12 weeks, I will gradually build one backend project.

Eventually it will include:

- Users
- Authentication
- Authorization
- Students
- Courses
- Units
- Learning materials
- Past papers
- Notes
- Search
- Filtering
- Pagination
- PostgreSQL
- Validation
- Rate limiting
- Error handling
- Tests
- Performance improvements
- Production deployment

I will **not build everything at once**.

Each feature will be added as I learn the technology needed for it.

---

# My Learning Process

For every new topic:

```text
1. Understand
2. Read the documentation
3. Take notes
4. Think about the solution
5. Write the code myself
6. Run it
7. Debug it
8. Test it
9. Improve it
10. Explain what I built
11. Use AI only if I am still stuck
```

This is the process I want to build into a habit.

---

# Keep Notes

Each week will have a `notes.md` file.

Example:

```text
week-06-fastify/
├── exercises/
├── fastify-crud/
└── notes.md
```

My notes should record:

- What I learned
- What confused me
- What went wrong
- What I tried
- How I fixed it
- What documentation I read
- What I still don't understand

---

# Keep a Debugging Journal

When I solve an important problem, I will document it.

Example:

```markdown
## Problem

POST /students returned 500.

## Cause

The foreign key referenced a course that did not exist.

## Fix

I corrected the relationship.

## Lesson

Foreign keys help protect data integrity.
```

The goal is to turn mistakes into knowledge.

---

# Repository Structure

```text
backend-12-week-journey/
│
├── README.md
├── .gitignore
│
├── week-01-javascript/
├── week-02-javascript-async/
├── week-03-nodejs/
├── week-04-typescript/
├── week-05-rest-api/
├── week-06-fastify/
├── week-07-postgresql/
├── week-08-fastify-postgresql/
├── week-09-architecture/
├── week-10-auth-security/
├── week-11-performance/
├── week-12-production/
│
└── student-learning-api/
    ├── src/
    ├── tests/
    ├── migrations/
    ├── package.json
    ├── tsconfig.json
    ├── .env.example
    └── README.md
```

One repository contains the entire 12-week journey.

---

# Progress

- [ ] Week 01 — JavaScript for Backend
- [ ] Week 02 — Async JavaScript
- [ ] Week 03 — Node.js
- [ ] Week 04 — TypeScript
- [ ] Week 05 — HTTP & REST
- [ ] Week 06 — Fastify
- [ ] Week 07 — PostgreSQL
- [ ] Week 08 — Fastify + PostgreSQL
- [ ] Week 09 — Architecture
- [ ] Week 10 — Authentication & Security
- [ ] Week 11 — Performance
- [ ] Week 12 — Production

---

# My Rules

### 1. Type it myself

I don't copy complete solutions.

### 2. Read the docs

I check the official documentation first.

### 3. Try before asking

I attempt the problem myself before asking for help.

### 4. Debug myself

I investigate errors before asking AI to fix them.

### 5. Understand what I use

I should know why I am using a dependency or technology.

### 6. Write SQL myself

I want to understand what PostgreSQL is actually doing.

### 7. Test my work

I don't assume something works because it ran once.

### 8. Measure performance

I measure before optimizing.

### 9. AI comes later

AI helps me learn; it does not do the learning for me.

### 10. Explain what I build

If I cannot explain it, I need to learn it again.

---

# What I Want at the End

By the end of these 12 weeks, I want to be able to:

- Build backend APIs
- Use Node.js and Fastify
- Write TypeScript
- Design PostgreSQL databases
- Write SQL
- Build authentication
- Secure APIs
- Debug backend problems
- Test applications
- Understand performance
- Deploy backend applications
- Read technical documentation confidently
- Make backend architecture decisions
- Understand code written by others
- Use AI without depending on it

Most importantly:

> **I want to be able to build and understand software even when AI is not doing the work for me.**

---

# Final Principle

**Learn manually.**

**Read the documentation.**

**Try before asking.**

**Debug your own mistakes.**

**Understand what you build.**

**Use AI later.**
