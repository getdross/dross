# dross

Public release archives for the dross developer disk cleaner.

This repository holds compiled macOS archives. It does not contain the source.

Apple Silicon, with no GitHub login:

```sh
brew tap getdross/tap
brew trust getdross/tap
brew install dross
```

`brew trust` is required once on Homebrew 7. An Intel Mac downloads `dross-cli-x86_64-apple-darwin.tar.xz` from the releases on this repository.
