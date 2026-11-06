# Changelog

## 1.2.0
- Load one or more .NET assemblies (or a folder) — static analysis only, never executes the target.
- Decompile types and members to readable C# (ICSharpCode.Decompiler engine), with graceful per-member degradation.
- IL output view — C#/IL toggle in the document view.
- Visual Studio-native workspace: Assembly Explorer tree with type-kind glyphs and a type-ahead filter, tabbed documents with VS dark theme and VS syntax colors, and a status bar.
- VS code navigation: Go to Definition, Find All References, Call & Type Hierarchy.
- Go-to-All search.
- Project export to a buildable SDK-style C# project — in the UI and via `glass export`.
- The Nebula.NET exposure-report / audit mode.
- CycloneDX 1.5 SBOM export, via `glass sbom`.
- Assembly and public-API diffing, secret scanning, authenticity checking, and NuGet resolution.
- In-app feedback / bug reporting; anonymous usage telemetry with opt-out.
- Self-contained builds for **Windows (win-x64), Linux (linux-x64), and macOS (osx-x64 and osx-arm64)** — no .NET runtime required.

*Coming next:* VB output view, synthetic PDB generation, and full docking.
