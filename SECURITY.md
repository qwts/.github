# Security policy

This policy applies to every repository under the `qwts` account unless the
repository carries its own `SECURITY.md`.

## Reporting a vulnerability

**Do not open a public issue for a vulnerability.**

Use GitHub's private vulnerability reporting on the affected repository:
**Security tab → Report a vulnerability**. Private reporting is enabled on
all `qwts` repositories.

Include what you can: affected repo and version/commit, reproduction steps,
and impact as you understand it. Reports are acknowledged as they are read;
this is a single-maintainer account, so please allow a reasonable window
before any disclosure.

## Scope notes

- Dependency-level advisories are tracked automatically (Dependabot +
  osv-scanner in CI per ENG-0005); a report is still welcome if you believe
  an advisory is exploitable in context here.
- Secrets accidentally committed to any repo: report privately as above —
  push protection is enabled, but history may predate it.
