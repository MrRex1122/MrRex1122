# CTAIO AI Governance Triage

Built specifically for the CTAIO screening task.

A tiny static decision aid for CTOs / CAIOs. It asks six questions about data sensitivity, autonomous actions, high-impact decisions, human review, audit logging, and ownership. It returns a lightweight governance priority and a short list of next controls.

## Why this shape

- Small enough to ship in one sitting.
- Directly aligned with CTAIO's audience and AI-governance content.
- Deterministic by design: AI helped create the artifact, but the runtime does **not** pretend an LLM can make a compliance determination.
- Single-file HTML/CSS/JS, no framework or backend required.

## Run

Open `index.html` in any browser.

## Prompt used

> Build a tiny single-file HTML/CSS/JavaScript tool for ctaio.dev called “AI Governance Triage”. Audience: CTOs and CAIOs. It should take under 60 seconds, ask 5–6 yes/no questions about sensitive data, autonomous actions, high-impact decisions, human review, audit logs, and ownership, then return Low / Medium / High governance priority plus 3–5 next controls. Keep it visually clean, executive-friendly, mobile responsive, and dependency-free. Do not present it as legal/compliance advice. Use a deterministic scoring model rather than an LLM at runtime, because the tool should help leaders triage a decision rather than imply the model can decide compliance.

## Manual changes after the AI draft

- Tightened the question wording so each answer maps to a concrete control.
- Increased the weight of autonomous actions and high-impact decisions.
- Made lack of human review, logs, or an accountable owner explicit risk signals.
- Rewrote the result copy to avoid false precision or legal/compliance claims.
- Kept the implementation dependency-free and deliberately avoided an API key or runtime LLM call.
