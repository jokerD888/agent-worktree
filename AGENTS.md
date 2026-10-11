# Repository instructions

- Keep this repository dependency-free and safe to run repeatedly.
- Installers may only manage the `agent-worktree` skill directories; never pollute global instruction files or system PATH.
- Keep the Windows PowerShell and POSIX shell installers and wrappers behaviorally aligned.
- Do not add credentials, personal paths, or generated machine-specific files.
- Test installer and wrapper changes against a temporary directory before committing.
