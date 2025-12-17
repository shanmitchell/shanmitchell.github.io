# Prompting & Iteration Guide for an AI App Builder

## What it is
A reconstructed (non-proprietary) example of user-facing documentation designed to help non-technical and mixed-skill users get better results from an AI-powered application builder through clear prompting and safe iteration.

## Audience
- First-time builders unfamiliar with traditional coding
- Designers, PMs, and founders prototyping ideas
- Developers using AI tools for rapid scaffolding
- Support teams assisting users when AI output isn’t what they expect

## Problem
Users often struggle with AI-powered builders not because the tool fails, but because:
- prompts are too broad or vague
- multiple changes are requested at once
- users aren’t sure how to recover from unexpected results
- uncertainty leads to trial-and-error frustration or abandonment

Clear prompting guidance dramatically improves user confidence and outcomes.

## Core principles
### 1) Start with intent, not features
Begin by stating the goal in plain language before listing requirements.

**Instead of:**  
“Build a React app with auth, a dashboard, and charts.”

**Try:**  
“Create a simple internal dashboard for tracking customer requests. Users should log in and see a list of open items.”

---

### 2) Constrain what should *not* change
Tell the system what to preserve to avoid unintended side effects.

**Example:**  
“Update the form validation, but don’t change the existing layout or routing.”

This helps users iterate safely.

---

### 3) Make one change at a time
Smaller prompts produce more predictable results.

**Recommended workflow:**
1. Generate a baseline version
2. Adjust one behavior or feature
3. Review the result
4. Repeat

Avoid stacking multiple major changes into a single prompt.

---

### 4) Use examples when possible
Concrete examples reduce ambiguity.

**Example:**  
“When a user submits the form, show a success message like ‘Request saved’ instead of redirecting.”

---

## Troubleshooting common issues
### The output doesn’t match what I expected
**Try this:**
1. Restate the goal in one sentence
2. Clarify what should stay the same
3. Ask for a single, specific adjustment

**Common pitfall:**  
Rewriting the entire prompt from scratch instead of refining it.

---

### The app became more complex than intended
AI tools tend to over-optimize.

**Recovery strategy:**
- Ask to simplify the solution
- Remove optional features
- Request the “simplest version that still meets the goal”

---

## Outcome
Providing structured prompting guidance like this:
- reduces user frustration
- increases successful first builds
- improves iteration speed
- lowers support volume
- builds trust in AI-assisted workflows
