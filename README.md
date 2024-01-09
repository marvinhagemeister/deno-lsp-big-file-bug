## Steps to reproduce

1. Clone this repository
2. Open the file `bar.ts` in vscode
3. `deno` lsp process never seems to settle

This effect can be worsened by folding all scopes via the `Fold All` vscode command, closing vscode and re-opening it. It will have saved the fold state.
