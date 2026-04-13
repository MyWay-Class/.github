# MyWayClass Organization Hub

This repository is the entry point for the organization profile and collaboration rules.

- The profile-facing introduction uses [`profile/README.md`](./profile/README.md).
- The repository-facing introduction uses this file.
- English versions are available in [`README.en.md`](./README.en.md) and [`profile/README.en.md`](./profile/README.en.md).

## One-Liner

An AI education platform that turns lectures into restructured learning flows instead of passive consumption.

## Key Points

- Convert lecture audio to text with STT
- Chunk content into meaningful units
- Use RAG to find evidence-backed segments
- Use AI for summaries, quizzes, Q&A, and short-form generation
- Keep every result linked to the original lecture

## Collaboration Principles

- Read the documentation first, then edit code.
- Keep instructions short, but make scope and acceptance criteria explicit.
- Record rationale in `docs/dev-logs/` after each change.

## AI Collaboration

- Write instructions in a short `goal / target / acceptance criteria / references` format.
- Include file names and line numbers when asking for analysis.
- Keep conventions in documents and only reference paths in task instructions.
- Use worktrees to compare up to two solutions when it is actually useful.
- Do not trust results blindly; check the docs, types, and validation output together.
- Record the chosen path and summary in `docs/dev-logs/`.

See [`profile/README.md`](./profile/README.md) for the full introduction.

## License

This project is an entry for the 2026 KIT Vibecoding Competition.
