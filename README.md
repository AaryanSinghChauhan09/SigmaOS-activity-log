# SigmaOS activity log

This crate is currently an identity scaffold. Its `no_std` library constructs
a `Component` with the fixed name `SigmaOS Component`; it does not record,
persist, query, or display user activity.

The package has no external dependencies. The inline unit test checks the
scaffold's fixed name and is not evidence of an activity logging workflow.

## Build

```sh
cargo check --lib
```

## License

Apache-2.0. See [`Cargo.toml`](Cargo.toml).
