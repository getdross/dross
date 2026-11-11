# Yosr Dross

Public release archives for Yosr Dross (`dross`), the developer disk cleaner for macOS.

This repository holds compiled macOS archives. It does not contain the source.

v0.4.0 is macOS. The Homebrew formula installs the Apple Silicon archive on Apple Silicon and the Intel archive on Intel. Deletion moves files to the Trash unless permanent deletion is chosen explicitly. It covers JVM (Maven, Gradle) and .NET project artifacts, the `maven`, `gradle`, and `nuget` caches, and Docker Desktop, OrbStack, Colima, and Podman (sized; safe leftovers pruned ask-first through each runtime's own CLI).

```sh
brew tap getdross/tap
brew trust getdross/tap
brew install dross
"$(brew --prefix)/bin/dross" --version
```

`brew trust` is required once on Homebrew 7. No GitHub login is required.

Website: <https://dross.yosr.ai>

| Mac | Archive |
| --- | --- |
| Apple Silicon | `dross-cli-aarch64-apple-darwin.tar.xz` |
| Intel | `dross-cli-x86_64-apple-darwin.tar.xz` |

Both files are on the [v0.4.0 release](https://github.com/getdross/dross/releases/tag/v0.4.0). Each archive includes the `LICENSE`.

License: [Yosr Dross License](https://dross.yosr.ai/trust/). Free to use; the source is private.

Bug reports: email (see the site).
