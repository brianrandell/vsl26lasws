# Recommended Tools — Windows

## Prerequisites

### WinGet

[WinGet](https://learn.microsoft.com/windows/package-manager/winget/) is the Windows Package Manager CLI, built by Microsoft.

**Windows 11:** WinGet is included out of the box with the App Installer package. Open a terminal and run `winget --version` to confirm it's available.

**Windows 10:** WinGet is available but may not be pre-installed. To get it:

1. Install the [App Installer](https://apps.microsoft.com/detail/9NBLGGH4NNS1) from the Microsoft Store.
2. If the Microsoft Store version is outdated, download the latest `.msixbundle` release from the [winget-cli GitHub releases](https://github.com/microsoft/winget-cli/releases) page.

After installation, open a new terminal and verify by running:

```powershell
winget --version
```

## Tools

[Oh-my-Posh](https://ohmyposh.dev/) — A prompt theme engine for any shell

```powershell
winget install JanDeDobbeleer.OhMyPosh
```

[Atuin](https://atuin.sh/) — Magical shell history search & sync

```powershell
winget install atuinsh.atuin
```

[Visual Studio Code](https://code.visualstudio.com/) — Lightweight, powerful code editor by Microsoft

```powershell
winget install Microsoft.VisualStudioCode
```

[Git](https://git-scm.com/) — Distributed version control system

```powershell
winget install Git.Git
```
