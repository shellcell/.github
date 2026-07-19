<div align="center">

<picture>
  <source media="(prefers-color-scheme: dark)" srcset="/assets/shellcell_white.png">
  <source media="(prefers-color-scheme: light)" srcset="/assets/shellcell_black.png">
  <img alt="shell" src="/assets/shellcell_black.png">
</picture>

# shellcell

Command line tools for snails

</div>

## Tools

| Project | What it does |
| --- | --- |
| [ExEx](https://github.com/shellcell/exex) | Executable Explorer for inspecting and understanding executable files. |
| [ttysvg](https://github.com/shellcell/ttysvg) | Records terminal sessions as SVG animations. |
| [cnvrt](https://github.com/shellcell/cnvrt) | An interactive CLI for file conversion. |
| [snailrace](https://github.com/shellcell/snailrace) | Benchmarking tool. |

## Install

### Homebrew (macOS / Linux)

From [`shellcell/homebrew-tap`](https://github.com/shellcell/homebrew-tap):

```sh
brew install shellcell/tap/exex
brew install shellcell/tap/ttysvg
brew install shellcell/tap/cnvrt
brew install shellcell/tap/snailrace
```

### Linux packages (apt / dnf / apk)

apt, dnf and apk repositories are served from
[packages.shellcell.dev](https://packages.shellcell.dev), where you enable the
shellcell repository once, then install any tool by name (e.g. `apt install
exex`). The page has copy-paste setup for each distribution.

### Arch (AUR)

Each tool is on the [AUR](https://aur.archlinux.org) as `<tool>` (builds from
source) and `<tool>-bin` (prebuilt). With an AUR helper (e.g. `paru` or `yay`):

```sh
paru -S ttysvg       # or ttysvg-bin
```

### Other

Each tool can also be installed with `go install`, and every
[release](https://github.com/shellcell) ships prebuilt binaries with man pages
and shell completions. See each project's README for details.
