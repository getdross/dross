# dross

Public release archives for the dross developer disk cleaner.

This repository holds compiled macOS archives. It does not contain the source.

v0.2.2 is macOS. The Homebrew formula installs the Apple Silicon archive on Apple Silicon and the Intel archive on Intel. Deletion moves files to the Trash unless permanent deletion is chosen explicitly.

```sh
brew tap getdross/tap
brew trust getdross/tap
brew install dross
"$(brew --prefix)/bin/dross" --version
```

`brew trust` is required once on Homebrew 7. No GitHub login is required.

| Mac | Archive |
| --- | --- |
| Apple Silicon | `dross-cli-aarch64-apple-darwin.tar.xz` |
| Intel | `dross-cli-x86_64-apple-darwin.tar.xz` |

Both files are on the [v0.2.2 release](https://github.com/getdross/dross/releases/tag/v0.2.2).
