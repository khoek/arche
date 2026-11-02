# Arche

Arche is the small, product-neutral infrastructure layer used by Arcadia and
other GCP services. It contains Firestore connection/document helpers and
Axum HTTP server/proxy primitives. It has no application identities, OAuth
clients, passwords, or Arcadia data.

The crates are intentionally ordinary workspace members so applications can
use them from a Git dependency or vendor a release when reproducibility needs
it.

```sh
cargo test --workspace
```
