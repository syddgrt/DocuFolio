# Cerebrum Commune 🧠

A personal documentation site and portfolio used to **learn, reason about, and document systems** — from DevOps and cloud infrastructure to Linux and machine automation.

This repository is both a **knowledge base** and a **professional portfolio**.  
It reflects my understanding at a given point in time and evolves as I learn.

---

## Purpose

This project exists to:

- Document what I learn while working with real systems
- Clarify my own mental models through writing
- Serve as a long-term technical portfolio
- Practice clean information architecture and DevOps workflows

This is **not** authoritative documentation.  
Content may be simplified, opinionated, or incomplete — always verify critical details independently.

---

## Structure Overview

The site is intentionally split into **clear domains** to avoid mixing concerns.

### 📚 Documentation

Organized by **areas of thinking**, not by individual tools:

- **Cloud**  
  Cloud fundamentals, architecture, and design principles

- **DevOps**  
  Delivery workflows and tooling, including:
  - Kubernetes  
  - Terraform  
  - CI/CD  

- **Linux**  
System fundamentals used across cloud, DevOps, and automation

- **Machine Automation**  
Software in manufacturing environments, soft PLC concepts, HMI systems, and real-world constraints

- **Site Reliability Engineering (SRE)**  
Reliability, observability, incident response, and operational trade-offs

---

### 🧑‍💻 Portfolio

Focused on **professional signal**, separate from learning notes:

- **About Me** — background and current direction  
- **Certifications** — verifiable credentials  
- **Experience** — real-world responsibilities and systems worked on  
- **Projects** — case studies with context, constraints, and lessons learned  

---

## Tech Stack

This site is built using:

- **Nuxt 4** — application framework  
- **Docus** — documentation framework built on Nuxt  
- **Nuxt Content** — Markdown-based content system  
- **Nuxt UI** — UI components and styling  

The stack is intentionally **boring and stable** to keep the focus on content, structure, and clarity.

---

## CI/CD Philosophy

This project practices DevOps by default:

- Every push triggers a build
- Broken content fails CI
- Deployment is automated
- No manual release steps

Current deployment uses **static hosting**.

Planned evolution:
- containerized builds
- Kubernetes-based hosting
- GitOps-style deployment

The goal is **incremental complexity**, not premature optimization.

---

## Why This Exists

I learn best by:

- building systems  
- observing failure modes  
- documenting what went wrong  
- refining my understanding  

This repository is the written trail of that process.

---

## Disclaimer

All content reflects personal understanding and experience.  
It should not be treated as official guidance or best-practice documentation.

---

If you find something useful here, that alone makes the project worthwhile.

