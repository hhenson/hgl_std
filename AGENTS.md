# Standard-library rules

- Before every push, check the branch's PR state on GitHub. If its previous PR
  is merged, fetch `origin/main`, start a fresh `codex/` branch from it, and carry
  forward only the new changes. Do not push follow-up commits to a merged PR's
  branch; open a new PR for the fresh branch.
- Keep documents and discussions terse. Avoid extended dialogue.
- Label agreed decisions and proposed behavior. Keep open questions and decision
  checklists in this repository's issue tracker, outside specification and
  explanation documents.
- Put contracts, examples/APIs, and useful diagrams in `spec/`. Add explanations
  under `explanations/` only when needed.
- Put HGL declarations and bodies under `hgl/`, required native implementation
  under `native/`, and ordinary implementation tests under `tests/`.
- Build on the language and mandatory core. Do not redefine core identities or
  change their applicable contracts.
- Keep runtime conformance expectations in core. Test this library's additional
  behavior here, including any required native implementation.
- Keep target internals in their adapter and require no historical repository
  or experiment record to understand a library contract.
- Introduce modules and native dependencies only with an explicit contract.
