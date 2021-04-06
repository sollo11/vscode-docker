# mez-editor README

Personal extension

# How to deploy

- Install vsce

    ```
    npm install -g vsce
    ```

- Get a token from `https://dev.azure.com/meziantou/_usersSettings/tokens` (scope `Azure Repos VSCode extension` - reuse `Publish Marketplace (mez-editor)`)
- `vsce login meziantou` + overwrite PAT with new token
- Run `vsce publish` or `vsce publish minor` to publish
