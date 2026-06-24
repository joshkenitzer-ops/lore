# What Lore Is

The problems with AI tools are well known. We built solutions to the ones that kept getting in the way. Prompts with logic gaps and ambiguous instructions that give the model enough room to hallucinate confidently, or reason itself into the wrong answer. Context that evaporates when a session ends, taking an hour of shared understanding with it. Documents that come out generic, or worse, that read as obviously machine-written: the parallel sentence structures, the borrowed corporate vocabulary, the tells that recruiters and hiring managers have learned to spot. Anyone doing serious work with AI runs into all of these, repeatedly.

Most AI tools are built to show you what the technology can do. Lore tools are built to solve the specific, concrete problems that show up when you're actually using it.

---

Every tool we've built started as something that was genuinely broken. Not a product roadmap item. Not a market opportunity. A real problem that kept costing real time, and an obvious fix that didn't exist yet.

So we built the fix.

Each tool reflects the same underlying understanding: LLMs are powerful and they have known failure modes. Prompts drift. Context disappears. Output needs verification before it can be trusted. Understanding where and how LLMs fail is what makes it possible to build tools that hold up in practice, not just in demos.

---

## The Tools

**Cassandra** finds the ways your prompt will fail before your users do. Prompts break in predictable ways: ambiguous instructions, edge case inputs, injection surfaces, scope creep. Cassandra runs a structured adversarial evaluation and returns findings with severity ratings and recommended fixes. Ship prompts that have been tested, not just written.

**Janus** solves the context reset problem. When a session ends, everything the model knew goes with it. Starting over costs time and kills momentum. Janus captures the full state of a working session in a structured handoff document, so the next conversation starts exactly where the last one ended.

**Hermes** replaces hours of manual resume and cover letter writing with minutes of review. It produces tailored packages from a single verified master document, runs a three-tier adversarial check on every output, and hands you something close to final. Your job is evaluation, not drafting.

More tools are coming. Each one will follow the same logic: a specific problem, a clear solution, and enough understanding of how LLMs actually work to make the solution hold up.

---

Built by people who use these tools every day and care whether they actually work.

*github.com/joshkenitzer-ops*
