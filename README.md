# The Donald Company — GitHub Profile

This repository maintains The Donald Company's public GitHub organization
profile. The rendered introduction is [`profile/README.md`](profile/README.md).
This root README is for maintainers; it is not an application or model runtime.

## What belongs here

The profile introduces the company, links to public projects, and explains the
relationship between LYLX, Quesar, Abbey/Aviva, ABI, WDBX 3D, and the separate
NYON creative-world work. Repository locations and current capabilities must
remain explicit; do not imply that all linked projects live in this organization
or use one shared license.

## Editing the profile

Update `profile/README.md` for the public-facing introduction. Before committing:

1. Check project links and names against the actual repositories.
2. Separate implemented behavior from proposed architecture and research.
3. Keep model training, memory persistence, hardware detection, and measured
   runtime behavior distinct.
4. Preserve project-specific contribution, licensing, security, and capability
   authorities rather than replacing them with organization-wide promises.
5. Review the Markdown diff and never add credentials, private data, or links
   exposing unpublished projects without explicit authorization.

A docs edit is not approval to deploy a service, change repository visibility,
modify permissions, migrate stored data, or publish model weights.

## Architecture terminology

**LYLX** is the ground-up platform direction. **Quesar** is its largest shared
foundation-model role. **Abbey and Aviva** are its consolidated personality
direction. **ABI** owns dynamic moderation/routing and authorized execution.
**WDBX 3D** owns neural memory/storage and provenance. These definitions do not
promote unfinished capabilities to implemented status.

**NYON** is a separate creative-first game/sandbox project. Its retained Rust
workspace and older Zig sandbox lineage have distinct builds and contracts.
The `quesar.cloud` website is likewise distinct from the Quesar model itself.

## Validation

Review Markdown rendering and run `git diff --check` in a checkout. No product
build or model evaluation is implied by this profile repository. For any linked
project, follow that project's own source, instructions, and verification gates.
