![Sylinko](https://github.com/Sylinko/.github/blob/main/images/banner.webp)

<div align="center">

**Seamless Connection, Infinite Possibilities.**

[Website](https://sylinko.com) • [Everywhere](https://github.com/Sylinko/Everywhere) • [Documentation](https://everywhere.sylinko.com) • [Contact](mailto:contact@sylinko.com)

</div>

Sylinko builds open-source tools that bring AI into everyday desktop work. Our main project is **Everywhere**, alongside Avalonia libraries, developer tools, and the package infrastructure that supports it.

## Everywhere

<a href="https://github.com/Sylinko/Everywhere">
  <img src="https://github.com/Sylinko/.github/blob/main/images/everywhere-link.webp" width="50%" alt="Everywhere" />
</a>

An AI assistant that works with the context of your current app. Bring it up with a shortcut to understand what is on screen, ask questions, and use tools without leaving your workflow.

- **App context:** work with selected text and on-screen content.
- **Model choice:** connect multiple model providers, custom endpoints, or local models.
- **Tools and agents:** use browser, filesystem, terminal, and MCP tools to act on your requests.

Available for **Windows and macOS**, with Linux support in development.

[Source](https://github.com/Sylinko/Everywhere) • [Downloads](https://everywhere.sylinko.com/download) • [Docs](https://everywhere.sylinko.com) • [Issues](https://github.com/Sylinko/Everywhere/issues)

## Avalonia libraries

Libraries we develop or maintain for desktop UI, including projects from our maintainers.

| Project | Focus |
| --- | --- |
| [LiveMarkdown.Avalonia](https://github.com/DearVa/LiveMarkdown.Avalonia) | Markdown rendering for streaming AI responses, maintained by DearVa. |
| [Motion.Avalonia](https://github.com/Sylinko/Motion.Avalonia) | Declarative layout transitions, seekable animations, and timeline playback with live Avalonia controls. |
| [ClassicDiagnostics.Avalonia](https://github.com/Sylinko/ClassicDiagnostics.Avalonia) | Classic F12 developer tools for Avalonia 12 and later. |
| [CSharpMath.Avalonia](https://github.com/Sylinko/CSharpMath.Avalonia) | Our fork of CSharpMath's existing Avalonia integration, updated for Avalonia 12. |
| [shad-ui](https://github.com/Sylinko/shad-ui) | Our fork of the existing shad-ui library, with new controls, performance improvements, and visual refinements toward a Luma-inspired style. |

## Tools and documentation

| Project | Focus |
| --- | --- |
| [jsonl-viewer](https://github.com/Sylinko/jsonl-viewer) | A JSONL viewer for exploring logs. [Open the viewer](https://jsonl.sylinko.com). |
| [everywhere-website](https://github.com/Sylinko/everywhere-website) | Everywhere's website and documentation. [Visit the site](https://everywhere.sylinko.com). |

## NuGet feed and dependency packages

[**nuget-feed**](https://github.com/Sylinko/nuget-feed) provides a mature, low-cost workflow for publishing and hosting NuGet packages. We use it for Sylinko's internal dependency releases and share the implementation so others can use it as a reference or reuse it directly for their own feeds.

The workflow combines GitHub Actions, GitHub Releases, and Cloudflare: producer repositories build the packages, reviewed manifests record their provenance and hashes, and Cloudflare serves the feed metadata. It supports package search, autocomplete, and registration metadata without a dedicated package server.

**Feed URL:** [`https://nuget.sylinko.com/v3/index.json`](https://nuget.sylinko.com/v3/index.json)

We publish dependencies independently so applications can consume a versioned package instead of rebuilding the same upstream sources on every build.

| Repository | Role |
| --- | --- |
| [Microsoft.ML](https://github.com/Sylinko/Microsoft.ML) | Our ML.NET fork, including the tokenizer packages used by Everywhere. |
| [MessagePack-CSharp](https://github.com/Sylinko/MessagePack-CSharp) | Our MessagePack fork for Everywhere's serialization needs. |
| [Porta.Pty](https://github.com/Sylinko/Porta.Pty) | Our PTY fork and platform-specific assets for terminal integration. |
| [EverythingNetCore](https://github.com/Sylinko/EverythingNetCore) | Our maintained Everything integration for Windows file search. |
| [OfficeCLI](https://github.com/Sylinko/OfficeCLI) | NuGet packaging of unmodified [iOfficeAI/OfficeCLI](https://github.com/iOfficeAI/OfficeCLI), allowing .NET applications to share its managed dependencies. |

Forks and packaging repositories retain their upstream attribution and applicable licenses. Packages may contain changes specific to our applications; each producer repository documents its integration and publishing details.

## Open and traceable builds

We aim to keep our build and release processes public, transparent, and traceable, in keeping with the spirit of open source. Public workflows make packaging steps inspectable; release manifests connect dependency packages to their source commits, CI runs, and artifact hashes. This lets users follow how the binaries they consume were produced, alongside the source code and upstream attribution.

## Contribute

For our public application and library projects, bug reports, documentation improvements, examples, and pull requests are welcome. Start with the relevant project's README and issue tracker, or contact us at [contact@sylinko.com](mailto:contact@sylinko.com).

The `nuget-feed` repository is maintained primarily for internal use and does not accept general public contributions or third-party package submissions. Its public implementation is available for reference and reuse; please follow each repository's own contribution policy.

---

<div align="center">
  <p>Built with ❤️ by the Sylinko Team</p>
</div>
