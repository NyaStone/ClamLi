# ClamLi

This VScode extention aims at making writing ClamAV files easier to read and write.

## Features and Planned ones

- [x] Provide a grammar file for .ldb files
- [ ] Provide linting/intellisense for .ldb files
- [ ] Provide usefull macros 

## Instalation

Download the latest [release](https://github.com/NyaStone/ClamLi/releases).

Install the extention from the install binary.
```bash
code --install-extension .\clamli-v0.0.1.vsix
```

List and uninstall extensions.
```bash
code --list-extension
>ms-vscode-remote.remote-wsl
>someone.clamli

code --uninstall-extension someone.clamli
>Uninstalling someone.clamli...
>Extension 'someone.clamli' was successfully uninstalled!
```

## Known Issues

Not on VSCode marketplace yet.
Macro/.ndb files support missing.
Icon signatures for PE files not supported.
Improvements to the grammar are needed.
Using regexes to parse potential errors is a bit clunky.