# Pyxis

Privacy-first analytics for projects built on Stellar.

Pyxis gives a builder three views of their product without running an analytics stack:

- **API analytics** from the OpenTelemetry metrics their services already emit: request volume, latency percentiles and error rates per route.
- **Web analytics** from a pinned, self-hosted Umami, issued only after the owner proves control of the domain.
- **Wallet funnel** counted from event names alone, labelled as frontend-reported.

## Principles

1. **Honest measurement.** Definitions, approximations and limits are shown next to every number.
2. **Privacy by omission.** If a number would need personal data, it does not exist.
3. **Visible tenant boundaries.** The project comes from the credential, and PostgreSQL row-level security enforces isolation.
4. **Builders first.** From sign-in to a first data point should be fast and copy-pasteable.
5. **Verifiable over impressive.** Every claim maps to something you can test.

## Status

Pyxis is a **testnet MVP in development**. The name is provisional. Nothing here claims customers, adoption, uptime or compliance.

## Where to start

| Repository | What it is |
|---|---|
| [pyxis](https://github.com/pyxis-hq/pyxis) | The application, API, database migrations, alpha SDK and all documentation |

Read the [README](https://github.com/pyxis-hq/pyxis#readme) first, then the [contributing guide](https://github.com/pyxis-hq/pyxis/blob/main/CONTRIBUTING.md). Report security issues privately, as described in the [security policy](https://github.com/pyxis-hq/pyxis/blob/main/SECURITY.md).
