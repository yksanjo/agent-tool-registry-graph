# agent-tool-registry-graph

Registry and capability graph for agent tools, versions, and dependencies.

## Scope

Tool manifests, capability indexing, and compatibility metadata.

## Capabilities

- Tool manifests, capability indexing, and compatibility metadata.
- Semantic discovery and ranking for best-fit tool selection.
- Dependency graph checks and deprecation lifecycle handling.
- Signed metadata and provenance checks for trusted tool execution.

## Repository Layout

- `src/main.py` entrypoint and lightweight service bootstrap
- `src/project_profile.py` canonical project metadata
- `src/service_contract.py` baseline domain contract shape
- `tests/` smoke and contract tests
- `docs/` architecture and roadmap

## Quick Start

```bash
python3 -m venv .venv
source .venv/bin/activate
pip install -e .[dev]
pytest -q
python -m src.main
```
