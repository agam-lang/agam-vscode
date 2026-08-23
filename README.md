# 💻 Agam Visual Studio Code Extension

> Part of the [agam-lang](https://github.com/agam-lang) organization.  
> Official rich language tooling extension for **Agam** in Visual Studio Code and Cursor, providing syntax highlighting, intelligent autocompletion, real-time diagnostics, and Language Server Protocol (LSP) integration.

---

## ✨ Features

- 🎨 **Dual-Profile Syntax Highlighting**: Seamless TextMate tokenization for both `@lang.base` (Pythonic indentation) and `@lang.advance` (systems/braced syntax) across `.agam` and `.agm` files.
- ⚡ **Language Server Protocol (`agam_lsp`)**:
  - Live compiler diagnostics and error squiggles with span tracking.
  - Go to Definition, Find References, and Document Symbols.
  - Hover documentation with inferred type signatures.
  - Inlay hints for tensor shapes and type annotations.
- 🪄 **Auto-Formatting (`agam_fmt`)**: Code formatting on save with configurable indentation and style guides.
- 🚀 **Build & Run Integration**: Direct command palette triggers for `Agam: Run File (JIT)`, `Agam: Benchmark`, and `Agam: Build Native (AOT)`.
- 🧩 **Productivity Snippets**: Instant boilerplates for tensors, `@gpu` kernels, algebraic effects, and test suites.

---

## 🛠️ Development & Building

```bash
# 1. Install extension dependencies
npm install

# 2. Compile TypeScript extension source
npm run compile

# 3. Package extension into .vsix bundle
npx vsce package
```

Press `F5` inside VS Code to launch the **Extension Development Host** with the live Agam extension loaded.

---

## 📜 License

Dual-licensed under [MIT](LICENSE-MIT) and [Apache 2.0](LICENSE-APACHE).
