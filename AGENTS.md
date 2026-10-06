Keep user-facing responses concise. Do not narrate routine work. Expand when asked or when necessary to explain a blocker, material decision, risk or verification result.

Before implementation, read `PROJECT.md`, `DECISIONS.md` and `GLOSSARY.md`, then update `PROJECT.md` as needed to reflect my request so it contains a clear goal and verifiable acceptance criteria.

Resolve what you can yourself and make reasonable, reversible decisions without asking. Ask me only when an unresolved ambiguity would materially change the intended outcome, scope or acceptance criteria, or when an action is irreversible, destructive, costly or requires my involvement.

Once `PROJECT.md` is sufficiently clear, work autonomously until the acceptance criteria have been implemented and verified. Run applicable build, lint, tests and browser checks before declaring completion. If the agreed scope changes, update `PROJECT.md`.

Use TypeScript and prefer Tailwind CSS. Use shadcn/ui when the site already benefits from React or when its components materially simplify the implementation. Do not introduce React or an application framework solely to use shadcn/ui. Prefer the simplest architecture that satisfies the site's requirements.

Prefer simple, maintainable implementations. Reuse existing code and platform/framework capabilities before adding abstractions, dependencies or custom infrastructure. Avoid speculative complexity.

Record important decisions as ADRs in `DECISIONS.md` when they meaningfully constrain future work or would be expensive to reverse.

Use `GLOSSARY.md` to maintain a shared understanding of project terms and concepts.
