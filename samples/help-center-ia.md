# Help Center Audit & IA Redesign (AI Product)

## What it is
A reconstructed (non-proprietary) example of how I approach auditing and restructuring a Help Center for a fast-moving AI product to improve discoverability, reduce support friction, and make content scalable.

## Audience
- New users who need quick success and reassurance
- Intermediate users exploring workflows and troubleshooting
- Power users looking for integrations, advanced capabilities, and constraints
- CX/Support teams who need consistent reference material

## Problem
As AI-assisted products evolve quickly, Help Centers often become hard to navigate:
- articles pile up without a consistent structure
- content overlaps or contradicts itself
- users can’t find answers quickly, increasing support tickets
- the tone varies widely, reducing user confidence

## Approach
### 1) Audit and inventory
- Catalog existing articles by topic, user intent, and lifecycle (evergreen vs release-specific)
- Identify duplicates, gaps, and “where do I start?” dead ends
- Flag content that should be merged, split, or retired

### 2) Define an information architecture that scales
Organize content around user intent (not internal teams). Example top-level structure:

- **Start here**
  - What the product is (and isn’t)
  - First project walkthrough
  - Key concepts and limitations
- **Build workflows**
  - Create/edit projects
  - Prompting patterns and iteration
  - Working with assets and dependencies
- **Integrations & deployment**
  - Connecting services
  - Environment/configuration guidance
  - Publishing/deploying
- **Troubleshooting**
  - Common errors and recovery steps
  - Performance and limits
  - Known issues
- **Reference**
  - Glossary/terms
  - Feature catalog
  - Changelog / release notes

### 3) Modular page template
Use a consistent structure so pages are easy to scan and reusable for in-product help and AI/chat surfaces:
- Summary (1–2 sentences)
- When to use this
- Steps (numbered)
- Common pitfalls
- Related links

### 4) Tone and UX principles
For AI-driven products, clarity isn’t enough—users also need confidence:
- use an approachable, reassuring voice
- prefer “what to do next” over abstract explanations
- include recovery paths when things go wrong

## Example excerpt
### Troubleshooting: Generated output doesn’t match intent
**Summary:** If the generated output isn’t what you expected, tighten the prompt and constrain the change.

**Try this next:**
1. State the goal in one sentence.
2. Specify what should **not** change (UI, routes, data model, etc.).
3. Ask for a small change first, then iterate.

**Common pitfall:** Asking for multiple major changes at once can produce unexpected results. Break requests into smaller steps.

## Outcome
This approach improves:
- discoverability and time-to-answer
- consistency across contributors
- support readiness (fewer repeat questions)
- reuse for in-product help and chatbot responses

