# Standard-library foundation

Date: 2026-11-01. Status: agreed boundary; module inventory remains open.

## Agreed

- **STD-1.** The standard library adds optional behavior above the mandatory core.
- **STD-2.** Portable HGL uses the language and core. Required native parts are
  explicit implementation dependencies.
- **STD-3.** Additional candidates preserve a core operator's identity and
  applicable contract. Library membership grants no selection priority.
- **STD-4.** Use specifications, explanations as needed, and HGL/native code
  with ordinary implementation tests. Keep documentation and discussions terse.
- **STD-5.** Runtime conformance expectations belong to core. Library-specific
  contracts and tests belong here. The repository stands independently of any
  historical source or experiment record.

## Open

- Module names, initial operator inventory, and the native helper interface.
- Packaging and compatibility with the language and core versions.
- The first practical library example after the core eval exercise.
