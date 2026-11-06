# Security policy

Slicekit is a template that you deploy yourself, so a vulnerability in it can affect every project
built from it. Please report problems privately and give us a chance to ship a fix first.

## Reporting a vulnerability

Email [info@slicekit.dev](mailto:info@slicekit.dev) with the subject `Security: <short summary>`. Include:

- what is affected (file, endpoint or module) and the revision you tested
- steps or a proof of concept to reproduce it
- the impact you expect

Please do not open a public issue for a security problem.

## What to expect

- We acknowledge your report within three working days.
- We confirm or dispute the finding and share a rough timeline once we have reproduced it.
- Fixes that adopters must apply manually ship with an upgrade note in the release notes, as described in
  `docs/template-maintenance.md` in the template repository.

## Scope

In scope: the code in the `slicekit` repository and the hosted demo. Out of scope: weaknesses that only
exist in a project after you changed the template, and findings against third-party services.
