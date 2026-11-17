# Natuleadan® Andromeda™

> A cybersecurity toolkit written in Rust.

Andromeda is the cybersecurity repository of the Natuleadan constellation. It is written entirely in Rust and focuses on auditing, scanning and hardening tooling.

## What it provides

- Rust-only implementation with no other implementation language.
- Auditing and scanning utilities.
- Hardening and verification tooling.

## Layout

| Path | Purpose |
|---|---|
| `crates/andromeda/` | Library crate |
| `docs/` | Product documentation |
| `tools/` | Validation entry points |

## Development

Requires Rust 1.100 or newer and pnpm. Run the same checks locally that CI
runs before opening a pull request.

```sh
pnpm validate
```

## Documentation

- [Architecture](docs/ARCHITECTURE.md)
- [Contributing](CONTRIBUTING.md)

## License

Apache-2.0. See [LICENSE](LICENSE).
