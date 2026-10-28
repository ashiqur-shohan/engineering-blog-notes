# Engineering Blog Notes & System Design Digest

A structured knowledge base for deconstructing engineering blogs from top tech companies (Netflix, Google, Anthropic, IBM, Uber, etc.) into architectural concepts.

---

## 🤖 AI Agent Instructions & Guardrails
*If you are an AI agent (Cursor, Claude Code, Copilot, etc.) assisting in this repository, strictly follow these rules:*
1. **Directory Routing:**
   - Company-specific case studies go in `articles/<company-name>/<article-slug>.md` using `templates/article-template.md`.
   - Reusable fundamental ideas go in `concepts/<concept-slug>.md` using `templates/concept-template.md`.
2. **No Verbatim Copying:** Never copy-paste paragraphs from articles. Synthesize ideas into concise bullet points and plain English.
3. **Bidirectional Linking:** Whenever an article mentions a Core or Supporting concept, link it to `[[../../concepts/concept-name.md]]` and update the concept file's "Seen In The Wild" section.
4. **Knowledge Triage:** Always categorize unfamiliar terms into **Core Concepts**, **Supporting Concepts**, or **Implementation Details**. Do not waste deep explanations on mere implementation tools unless requested.


engineering-blog-notes/
├── README.md                        # Rules for me and your AI agent
├── READING_QUEUE.md                 # Backlog of links you plan to read next
│
├── concepts/                        # explanations of technical concepts (synthesized across multiple blogs)
│   ├── caching-strategies.md
│   ├── database-indexing.md
│   ├── rate-limiting.md
│   └── api-backward-compatibility.md
│
├── articles/                        # Grouped by company for easy browsing
│   ├── anthropic/
│   │   └── 2026-prompt-caching-architecture.md
│   ├── google/
│   │   └── spanner-true-time.md
│   ├── ibm/
│   │   └── enterprise-rag-pipelines.md
│   └── netflix/
│       └── quasar-data-pipeline.md
│
└── templates/                       # Reusable structures and instructions
    ├── article-template.md
    └── concept-template.md