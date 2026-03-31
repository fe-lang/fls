> **This project is deprecated.** The Fe language server is now built directly into the [`fe` CLI](https://github.com/fe-lang/fe) via the `fe lsp` subcommand. There is no longer a need for a standalone language server binary.
>
> For VS Code support, use the [vscode-fe](https://github.com/fe-lang/vscode-fe) extension, which integrates with the built-in language server automatically.
>
> To install Fe: visit [fe-lang.org](https://fe-lang.org)

---

<p align="center">
    <h2 align="center">FLS (Deprecated)</h2>
    <p align="center">
    <a href="https://github.com/fe-lang/fe">Fe</a> Language Server
    </p>
</p>

This repository contained the original standalone Fe language server. It has been superseded by the language server built into the Fe compiler itself.

## Migration

1. Install the Fe CLI from [fe-lang.org](https://fe-lang.org) or build from source at [github.com/fe-lang/fe](https://github.com/fe-lang/fe)
2. The language server is available via `fe lsp`
3. Install the [vscode-fe](https://marketplace.visualstudio.com/items?itemName=fe-language-team.vscode-fe) extension for VS Code integration
4. The extension automatically discovers the `fe` binary and starts the language server

## License

[Apache 2.0](https://opensource.org/licenses/Apache-2.0)
