---
layout: default
title: UEHive Documentation
---

# UEHive

UEHive is a native Unreal Engine plugin for MCP-style Blueprint authoring, project-aware memory, internal role-based workers, and reusable in-editor Blueprint and UMG generation.

## Core capabilities

- Native Unreal Engine C++ editor integration
- Blueprint Actor creation directly inside the editor
- Widget Blueprint generation system
- UI layout scaffolds for `menu`, `hud`, `inventory`, `dialog`, and `settings`
- Gameplay interaction scaffolds for overlap-based systems
- Project-aware memory stored under `Saved/Skills`
- Blueprint inspection and reusable skill persistence
- Compile-and-validate workflow inside a live Unreal project
- Internal worker system for controlled generation tasks

## Included showcase content

The current release includes:

- `1` built-in showcase map
- `5` showcase Blueprint examples
- `8` showcase material assets

Showcase examples:

- `Automatic Door`
- `Trigger Light`
- `Rotating Pickup`
- `Patrol Enemy`
- `Procedural Scatter`

## Technical summary

- Unreal Engine target: `5.7`
- Supported development platform: `Windows`
- Distribution method: `Plugin`
- Modules:
  - `UEHiveCore` (`Runtime`)
  - `UEHiveWorker` (`Runtime`)
  - `UEHiveEditor` (`Editor`)
- Current C++ class count: `24`
- Network replicated: `No`

## Release scope

UEHive is an editor-focused productivity plugin. It is designed for Blueprint workflows, gameplay scaffolding, tool development, and repeatable Unreal Editor automation. It is not positioned as a packaged runtime gameplay framework or a full autonomous content generation system.

## Best fit

- Blueprint-heavy prototypes
- Technical design workflows
- Tool-driven Unreal production
- Teams that want native Unreal execution instead of external AI helpers

## Validation summary

The current release has been validated in a live Unreal project for:

- Blueprint actor creation
- Widget Blueprint creation
- UMG scaffold generation
- Gameplay interaction scaffolds
- Built-in showcase authoring

## Contact and support

Use the Fab listing discussion thread or the product support channel associated with the listing for release support.
