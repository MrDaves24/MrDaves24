# Pascal Perrenoud

Software engineer in Switzerland, writing Rust and TypeScript. MSc in computer science with a cybersecurity focus (HEIG-VD); previously research at CSEM. I run [Codexa](https://codexa.ch), a small consultancy doing secure code review, applied cryptography and embedded security — and I'm currently looking for a full-time remote engineering role.

## What I'm building

- **[Theca](https://github.com/theca-cloud)** — self-hosted cloud storage. Rust server ([core](https://github.com/theca-cloud/core): API, WebDAV, S3-backed chunked storage, background jobs, sqlx migrations, OpenAPI, WASM client library), [Svelte web app](https://github.com/theca-cloud/web), [community edition](https://github.com/theca-cloud/ce) shipped as a Docker image. CI on Woodpecker, cargo-deny, release scripts. AGPL-3.0.
- **[mh3-rs](https://github.com/mh3-rs/server)** — a Rust multiplayer server for Monster Hunter Tri, rebuilt from the original network protocol. Async networking, a [tunnel](https://github.com/mh3-rs/tunnel) for side services, [shared](https://github.com/mh3-rs/shared) protocol crate. AGPL-3.0.
- **[gohack26-fhe](https://github.com/MrDaves24/gohack26-fhe)** — talk given at GOHack26 (30 Oct 2026): *Fully Homomorphic Encryption — usage and limitations*. Rust benchmarks with TFHE-rs on a smart-meter workload (18 ns plain vs 33 s encrypted per day; 181 MB server key), Typst slides, research notes on TFHE/BFV/CKKS, attacks and alternatives (TEE, MPC, ZKP).
- **[kaeo](https://github.com/MrDaves24/kaeo)** — tiny Rust CLI: watch files or folders and run a command on change.
- **[pam-web](https://github.com/MrDaves24/pam-web)** — use a website as a PAM module (TypeScript).

## How I work

Rust first, minimal dependencies, strong typing, root-cause fixes over workarounds. Comfortable pairing with AI tools for the boring parts and reviewing the result like any other contributor's code.

## Contact

[codexa.swiss](https://codexa.swiss) · [LinkedIn](https://www.linkedin.com/in/pascal-perrenoud/) · open to remote roles (EU or US hours), employee or contractor.
