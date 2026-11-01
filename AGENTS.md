# Standard-library rules

- Keep documents and discussions terse. Avoid extended dialogue.
- Separate agreed decisions, proposed behavior, and open questions.
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
