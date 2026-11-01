# Resume Personal Digital Platform

Updated: 2026-11-01 (Asia/Kolkata).
Status: repository created; first runnable increment not yet implemented.

A link-only message pointing to this repository or this file means: read this checkpoint and resume the small-step architecture and pair-programming discussion. Read live remote state and relevant open PRs before acting.

## Latest checkpoint — 2026-11-01

This section supersedes older setup/publication status below.

### IntelliJ context restoration

- Fetched origin and verified live main and codex/iteration-1 at fd0eb7b19ff2804f9f863fe23a6cfe3c963aa1c3. The local checkout was already clean on codex/iteration-1 with origin/codex/iteration-1 as its upstream; no switch or reset was needed. Local main remains older; use the fetched origin/main when comparing.
- Live PR checks confirm implementation PRs #1/#2 and planning PRs #6/#7/#8 are merged, with no open PRs in either repository at this check.
- Read current implementation main README/RESUME and the authoritative planning main handoff, requirements, decisions 001–004, explorations 001–004, checkpoint and open questions. Planning origin/main was fetched and verified at 6505e63b02b3bf82ab377e48f8e5f392800918ae; its older local working branch was left untouched. This was context restoration, not a renewed historical audit.
- No applicable AGENTS.md files were found during initial inspection. Subsequently added root AGENTS.md at the user's request, linking to existing records and recording lasting working instructions.
- Environment reports OpenJDK/java/javac 27.0.1.0.3 and Gradle 9.8.2. Maven is not on PATH. Gradle's initial sandbox native-library failure did not recur outside the sandbox. No tools were installed or IntelliJ configuration changed.
- Pending recommendation: use the installed JDK directly for a dependency-free CLI experiment, deferring a build tool and permanent Java baseline. A small explicit fixture convention (title heading plus authored recap section), title matching, and selected-note-only display are proposed experiment choices, not approved product formats or defaults.
- No Java implementation or runnable tests exist; no behavior tests were run. Next: obtain the user's go-ahead for the concrete sample-only CLI increment, then explain and implement small steps, run the success/clarification/failure examples, and discuss scope limitations.
- The user authorized committing and pushing the root AGENTS.md and restoration checkpoint together on codex/iteration-1. These documentation changes form this commit; verify its publication with git status and the remote branch tip when resuming. Documentation diff checks passed; no implementation was started and no unrelated local work was present. No new PR or merge is included in this step. Implementation approval remains pending.

- The user cloned this repository in IntelliJ and committed/pushed the root .gitignore on codex/first-recap-slice. It excludes .idea/, *.iml and .DS_Store. The remote diff was reviewed: only those ignore rules were added before this checkpoint update.
- Implementation PR #1 and planning PRs #6/#7 are merged. The user explicitly authorized creating and merging the setup/checkpoint PRs and creating a new working branch.
- The next working branch is codex/iteration-1, to be created from updated main after the setup PR merges. Verify its existence and current state remotely; fetch and switch locally without discarding changes.
- No platform Java code or runnable tests exist from this work. Java version, build tool and implementation structure remain undecided. IDE-generated files are local and ignored; no automated platform scaffolding has occurred.
- Next: read the planning records, inspect installed Java/build tools, explain the proposed first run, then agree the minimum setup and work through one small increment together. Do not treat branch/setup approval as authorization for a large autonomous implementation.
- Update this checkpoint after meaningful outcomes and before breaks; keep detailed design rationale in the private planning repository. Future implementation commits/pushes/merges require their applicable user authorization.

## Start here

1. Read this file and README.md, check current branches/PRs and local changes/instructions.
2. Read the [planning handoff](https://github.com/saharshpoddarorg/personal-digital-platform-planning/blob/main/RESUME.md) and its authoritative records. That repository is private; disclose access limitations rather than inventing its contents.
3. Briefly report what is implemented, what is only proposed, and the next small step. Do not restart the historical audit or require a finalized architecture.
4. If implementation is still unstarted, ask for the still-needed authorization to begin the first increment; then inspect existing Java/tools and explain the minimum setup before a small change.

## Current checkpoint

- The user created this PUBLIC repository on 2026-10-31, intending to showcase it on a résumé. Public visibility is intentional.
- The initial main README was verified. No platform implementation or runnable tests were produced in this session.
- The user requested durable resume checkpoints here and an update to the existing planning handoff.
- This request authorizes these documentation updates/publication through branches and PRs. It does not authorize implementation, tool installation, IntelliJ configuration or PR merges.
- Planning PR #6 was verified merged. Earlier design proposals remain proposals regardless of merge status.
- The separate canonical vault has not been created by this work and is not needed for sample-only experimentation.
- Keep public checkpoints limited to project context. Do not copy private knowledge, credentials or private planning evidence into this repository.

## Next proposed increment

A small local Java command-line experiment:

    Topic: strategy
    Execution: NON_AI
    1. Strategy pattern
    2. Strategy pattern — Java example
    Other: enter another topic or note reference

    Choice: 1
    Recap: [existing authored recap from the selected sample note]
    Source: samples/strategy-pattern.md

This is illustrative, not executed output. Search a few clearly labelled sample Markdown notes, allow match selection OR free text, then return existing authored recap material and its source. Samples are fixtures, not canonical vault knowledge. Alternative topics are searched again; exact references are validated; neither creates a note. Missing material and technical failures must be distinguished; no silent AI generation.

Selected-note-only scope is an experiment proposal, not an approved product default. Demonstrate its limitations before revisiting scope. Java is the first recommended candidate because the user understands it; version, build tool, dependencies and interfaces remain open. Inspect installed tooling before proposing installation. Do not generate a large scaffold or empty implementations for every mode.

## Working agreement

- PKM and Learning first; other domains remain future candidates.
- Pair program and explain one small behavior at a time: input, observable output, and relevant Java code together, roughly one screen where practical.
- Demonstrate -> discuss minimum design -> implement an authorized small increment -> run -> review -> record outcome.
- Distinguish accepted requirements, provisional choices, assistant proposals and unresolved questions.
- Interpretation and execution vary independently. Non-AI, bounded-AI and agent-led options are desired where useful; no requirement for three copies of every workflow. Mode is visible and is not permission.
- Authored knowledge differs from generated content and derived views. The vault must remain independently useful.
- Stable identity and exact reviewed-version checks are provisional defaults, not selected storage mechanics.
- Use branches and PRs, never direct main pushes. Commit/push and merge require their applicable explicit authorization; permission to edit is not blanket publication permission.
- Keep changes small and explained. Do not copy the experimental learning-assistant architecture.

## Checkpoint maintenance

Update this file after each meaningful completed step, design decision or change in direction, and before a planned break/handoff. Do not create a new resume file per session. Preserve detailed rationale in the authoritative planning records; keep this file a compact implementation checkpoint.

Record:
- branch, commit and PR links with live status checked at the time;
- implemented behavior versus proposed work, validation run and its result;
- outstanding local/uncommitted/unpushed work and where it lives;
- decisions and their status, authorization boundaries, blockers and next concrete action.

Publish authorized checkpoints through branches/PRs. An unmerged PR is not on main: provide its working resume URL and retain that branch while it is used as a handoff. After merge, README and main RESUME become the repository-root entry point. Check for newer branches/PRs on resume.

A checkpoint preserves recorded outcomes and pointers, not every chat sentence or unsaved action. No automatic background saving is configured. When an abrupt interruption happens, inspect Git/local state and open PRs before trusting the last checkpoint.

## Publication and resume entry point

Use main RESUME.md after verifying live publication state:
https://github.com/saharshpoddarorg/personal-digital-platform/blob/main/RESUME.md

The setup/checkpoint PR uses codex/first-recap-slice. Check its merge status before treating this checkpoint as published on main. The user authorized its merge. The next implementation branch is codex/iteration-1.

Planning remains authoritative for requirements, evidence and design history:
https://github.com/saharshpoddarorg/personal-digital-platform-planning
