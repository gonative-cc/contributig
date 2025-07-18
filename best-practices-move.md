# Best Practices: Move

- Install move-analyzer LSP server and integrate it with your editor.
  - Emacs: https://github.com/amnn/move-mode. Note, for `move-analzyer`, use the one that it is packaged in the latest Sui testnet [release](https://github.com/MystenLabs/sui/releases) - no need to install it through Cargo. Moreover, the one from `MystenLabs/sui` is [apparently](https://forums.sui.io/t/move-2024-ide-support/45449/21?u=robert) a newer one.
  - VS: https://github.com/movebit/move -- the extension has integrated `move-analzyer`.
- Formatting:
  - indentation: 4 spaces
- Follow [Sui Move conventsion](https://docs.sui.io/concepts/sui-move-concepts/conventions).

dapp / web tools:

- [typemove](https://github.com/sentioxyz/typemove) - generates TypeScript bindings for Move contracts.
- [sui-client-gen](https://github.com/kunalabs-io/sui-client-gen) - a tool for generating TS SDKs for Sui Move smart contracts.

CMD toos:
- [Sui Env reporter](https://github.com/vuvoth/sui-env-report)
