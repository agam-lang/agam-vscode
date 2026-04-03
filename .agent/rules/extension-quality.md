# Extension Quality Rules

- The extension must not slow down VS Code startup by more than 100ms.
- All TextMate grammar rules must be tested against real .agam files from the core repo.
- LSP features must gracefully degrade when the language server is unavailable.
