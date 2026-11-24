# About this copy

This is a trimmed copy of the Impeccable skill from
https://github.com/pbakaus/impeccable (`.agents/skills/impeccable`), kept at
https://github.com/arynbht/impeccable on the `rivetari` branch so a Rivetari skills
lock can pin it. Impeccable is Copyright 2025 Paul Bakaus and licensed under the
Apache License 2.0 (`LICENSE`); `NOTICE.md` is the upstream notice, unchanged.

Changes from upstream, made by arynbht:

- `reference/hooks.md` is removed. It told the agent how to wire the design detector
  into harness settings files, which a Rivetari task must never edit.
- `SKILL.md`: the Hooks paragraph is replaced by one that runs the detector by hand
  instead, and a note at the top points here.
- `reference/doctor.md`: `doctor --fix` runs only when the user asks, because an
  `auto` finding can rewrite a harness's hook manifest.
- `LICENSE`, `NOTICE.md` and this file are copied in so an installed copy carries them.

Nothing else differs from the upstream commit the branch is based on.
