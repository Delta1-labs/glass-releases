# Changelog

## 0.1.0 (preview)
- First public build of Glass.NET.
- Load one or more .NET assemblies (or a folder) — static analysis only, never executes the target.
- Decompile types and members to readable C# (ICSharpCode.Decompiler engine), with graceful per-member degradation.
- Visual Studio-native workspace: Assembly Explorer tree with type-kind glyphs and a type-ahead filter, tabbed documents with VS dark theme and VS syntax colors, and a status bar.
- Windows (win-x64) self-contained build; Linux/macOS builds to follow.

*Coming next:* Go to Definition / Find All References / Go to Implementation / Call & Type Hierarchy, Go-to-All search, IL & VB views, project export, synthetic PDB, and the Nebula.NET exposure-report audit mode.
