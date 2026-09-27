<!--
SPDX-License-Identifier: MPL-2.0
Thanks for contributing to GSBot! Before opening this PR please confirm:
-->

## Summary

<!-- What does this change do, and why? Link any issues it resolves. -->

## Checklist

- [ ] I have read CONTRIBUTING.md and accept MPL-2.0 for code / CC-BY-SA-4.0
      for docs.
- [ ] All new source files carry an `SPDX-License-Identifier` header.
- [ ] `just fmt && just lint && just test` pass locally (or CI would pass them).
- [ ] If this changes the scoring kernel (`src/domain.rs`):
      - [ ] Pure/total; no I/O, no panics.
      - [ ] Tests pin the behaviour before and after.
      - [ ] The C-ABI in `mod ffi` either stays stable or is versioned.
- [ ] If this adds an open-standard integration (feeds/catalogues/safety):
      - [ ] STANDARDS.adoc updated with ✅/🧪/🔭 status.
      - [ ] No proprietary lock-in; feeds are RSS/Atom/ActivityStreams/OpenAPI/etc.
- [ ] If this is data curation: every new number is cited (LCA study, brand
      report, regulator feed, peer-reviewed source).
- [ ] I have not introduced Python or any other banned-language file (the
      Hypatia scanner will flag this as CRITICAL).

## Testing

<!-- Which commands did you run? Which fixtures did you use? -->

## Screenshots / transcripts (if UX changes)

<!-- Paste Discord output snippets or dashboard screenshots. -->

## Notes for reviewers

<!-- Axial trade-offs, things to watch for, future work. -->
