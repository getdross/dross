# Public pages

Source for the text published on the public GitHub org. The private `README.md` stays the maintainer document.

When this file changes, copy each block below to the path in its heading. Do not add the heading to the published file.

## `getdross/.github` `profile/README.md`

Rendered at <https://github.com/getdross>.

````markdown
# dross

Developer disk cleaner for macOS.

`dross` finds build artifacts such as `node_modules`, `target`, and `.venv`, shows how much space they use, and moves them to the Trash. Permanent deletion is a separate, explicit step.

v0.1.9 runs on Apple Silicon and Intel. The source is not published in this organization.

## Install

```sh
brew tap getdross/tap
brew trust getdross/tap
brew install dross
"$(brew --prefix)/bin/dross" --version
```

`brew trust` is required once on Homebrew 7. No GitHub login is required.

Releases and archives: <https://github.com/getdross/dross>
````

## `getdross/dross` `README.md`

Rendered at <https://github.com/getdross/dross>.

````markdown
# dross

Public release archives for the dross developer disk cleaner.

This repository holds compiled macOS archives. It does not contain the source.

v0.1.9 is macOS. The Homebrew formula installs the Apple Silicon archive on Apple Silicon and the Intel archive on Intel. Deletion moves files to the Trash unless permanent deletion is chosen explicitly.

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

Both files are on the [v0.1.9 release](https://github.com/getdross/dross/releases/tag/v0.1.9).
````
