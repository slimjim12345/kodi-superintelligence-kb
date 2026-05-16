# Ingestion & Compilation Scripts

## How ingestion works (future automation)
1. Agent 2 researches/verifies source
2. Raw content pulled into `/sources/raw/`
3. Agent 3 compiles using LLM synthesis prompts → `/wiki/compiled/`
4. Agent 4 polishes for clarity

**Example workflow (manual for now):**
- Add URL or file to `/sources/raw/`
- Run: `Agent 3: compile [path]`

Full Python/CLI automation coming in v0.2.

See Agent 2/3/4 packets for exact prompts.