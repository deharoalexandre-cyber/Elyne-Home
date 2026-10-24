# Architecture — Elyne Home

[Français](architecture.md) · [Overview](../README.en.md)

## Simplified flow

Voice or local event → interpretation → action policy → home adapter → feedback and trace.

## Components and boundaries

- The local prototype separates speech input and output, memory, scheduling, model client, and IoT adapters.
- The website describes a local mini-server, cameras on an isolated network, and home-automation gateways. These are deployment conditions to implement and verify, not a universal POC guarantee.
- A proactive action must remain governed by an explicit user choice and by the permissions of the relevant adapter.

This textual flow describes the product architecture. It does not replace verification on a specific build, hardware profile, and configuration. The [evidence summary](evidence.en.md) states what is actually documented.
