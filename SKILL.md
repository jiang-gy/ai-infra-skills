---
name: ai-infra-skills
description: Use this skill for AI infrastructure tasks, including distributed training, distributed inference, GPU/NCCL/RDMA debugging, serving systems, kernel optimization, profiling, CI/CD, architecture review, and AI systems technical communication.
---

# AI Infrastructure Skills

This skill wraps the `ai-infra-skills` repository.

Use this skill when the task involves:

- distributed training
- distributed inference
- pipeline / tensor / data / expert parallelism
- GPU, CUDA, NCCL, RDMA, InfiniBand, NVLink debugging
- large model serving
- kernel optimization
- profiling and performance diagnosis
- AI infra CI/CD
- system design and code review
- technical diagrams and architecture communication

## Runtime Order

When this skill is selected, follow this order:

1. Open `INDEX.md` first.
2. Use `EXPERT_KNOWLEDGE_MAP.md` to find the right domain owner.
3. Read the relevant files under `knowledge/`.
4. Use executable workflows under `.claude/skills/` or `.claude/commands/`.
5. Validate decisions against `.claude/rules/`.
6. If only one file can be opened first, open `INDEX.md`.

## Important Entry Points

- `INDEX.md`: shortest routing entry.
- `CLAUDE.md`: authoritative repository map.
- `KNOWLEDGE_INDEX.md`: topic-level knowledge routing.
- `EXPERT_KNOWLEDGE_MAP.md`: domain owner and knowledge mapping.
- `.claude/skills/`: executable workflows.
- `.claude/commands/`: repeatable command workflows.
- `.claude/rules/`: validation rules.
- `knowledge/`: stable technical references.

## Execution Style

For AI infrastructure tasks:

1. Identify the domain: distributed, hardware, kernels, serving, RL, CI/CD, or communication.
2. Route through `INDEX.md`.
3. Read the matching knowledge docs before proposing solutions.
4. Prefer concrete diagnostic commands, reproducible checks, and rollback-safe fixes.
5. For debugging tasks, separate symptoms, likely causes, validation commands, and fixes.
6. For design or review tasks, separate assumptions, bottlenecks, trade-offs, and risks.
