# pally-automation-enclave-deploy-dev

This repository is the public development deploy repo for the Pally automation
enclave.

It intentionally contains release-tagged deployment metadata only:

- `tinfoil-config.yml` pinned to an exact private GHCR image digest
- Git tags and GitHub releases consumed by Tinfoil
- measured deployment artifacts attached to each release
- public GitHub artifact attestations generated in this repository for client verification

Source code and image builds live in the private repo:

- `pally-ai/pally-automation-enclave`
