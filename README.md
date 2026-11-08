<div align="center">

# Glass.NET

### A free, cross-platform .NET decompiler with a Visual Studio-native UI — by [Delta1 Labs](https://delta1labs.com)

See exactly what a stranger sees when they decompile your .NET assembly.

[**Download**](https://github.com/Delta1-labs/glass-releases/releases/latest) ·
[Website](https://delta1labs.com) ·
[Source](https://github.com/Delta1-labs/glass.net)

</div>

---

This repository hosts the **official builds** of Glass.NET. It's a companion to [Nebula.NET](https://delta1labs.com/products/nebula): a nebula obscures, glass is transparent.

## What is Glass.NET?

A free .NET decompiler and assembly inspector that reconstructs readable C# from compiled IL — in an interface that feels native to Visual Studio developers. It embeds ILSpy's decompilation engine (`ICSharpCode.Decompiler`, MIT) and focuses on what no other free decompiler offers: VS themes, fonts, icons, keybindings, and navigation, on a cross-platform (Windows/Linux/macOS) app.

- **VS-native workspace** — Assembly Explorer, tabbed documents, status bar, VS dark theme + VS syntax colors.
- **Load** a single assembly, a folder, or an app's publish output.
- **Static analysis only** — Glass.NET never executes the assembly it inspects.
- **Free forever** — no license, no trial, no feature gate.

## Download & run

1. Grab the latest build from [Releases](https://github.com/Delta1-labs/glass-releases/releases/latest).
2. Unzip and run Glass (**`Glass.exe`** on Windows) — it's self-contained, so **no .NET runtime is required**.

> Builds are published for **Windows (win-x64), Linux (linux-x64), and macOS (Intel osx-x64 and Apple Silicon osx-arm64)** — the app is built on Avalonia and is cross-platform by design.
> Newly released, unsigned builds may trigger a SmartScreen/antivirus reputation prompt; reputation builds over time.

## Status

Stable (v1.2.0). Loading, decompilation, and the VS-native workspace are joined by full VS code navigation (Go to Definition, Find All References, Call & Type Hierarchy), Go-to-All search, the IL output view, project export to a buildable SDK-style C# project, CycloneDX SBOM export, and the Nebula.NET "exposure report" audit mode — all shipped. See the [changelog](./CHANGELOG.md).

## Links

- 🌐 Website: https://delta1labs.com
- 🧩 Protect your own code: [Nebula.NET](https://delta1labs.com/products/nebula)
- ✉️ Support: support@delta1labs.com

---

<div align="center">
© Delta1 Labs · Glass.NET is free software · embeds ICSharpCode.Decompiler (MIT)
</div>
