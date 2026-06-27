# agent_nodes

Agent workflow repository wired into SuperPlane.

- `open-pr`, `comment-on-pr`, `fetch-issue` GitHub HTTP nodes
- Render API service deploy + info

## AI-free templated factory

Turn a GitHub issue into a deterministic spec + plan + code stub with an auto-opened PR —
no LLM, no API keys, no cost. Label an issue `factory`, run the workflow manually, or run
`bash scripts/factory.sh <issue-number>` locally.

📖 **See [docs/factory.md](docs/factory.md) for full usage.**
