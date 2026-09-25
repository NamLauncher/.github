# NamLauncher

NamLauncher builds tools for playing and managing Minecraft Java Edition with separate, easy-to-maintain instances. The launcher brings together game versions, supported mod loaders, content, Java runtimes, logs, and updates.

Current stable launcher line: **1.3.1**

- [Official website and downloads](https://namlauncher.nattapat2871.me)
- [Installation guide](https://namlauncher.nattapat2871.me/how-to-install)
- [Release history](https://namlauncher.nattapat2871.me/changelog)

## Repository map

- **NamLauncher/NamLauncher** — proprietary Electron launcher, release integration, and verified embedded snapshots.
- **NamLauncher/website** — canonical private website/API/Admin/Discord platform source.
- **NamLauncher/platform** — private compatibility mirror of the website platform; product changes originate in `NamLauncher/website`.
- **NamLauncher/minecraft-companions** — GPL-3.0-only Minecraft Companion source and bundle tooling.
- **NamLauncher/operations** — deployment configuration and operational runbooks.
- **NamLauncher/.github** — organization profile and shared GitHub configuration.
- **NamLauncher/launcher-migration-archive** — archived migration history; not an active source of truth.
- **NamLauncher/winget-pkgs** — WinGet packaging/upstream work, separate from the application source.
- **NamLauncher/demo-repository** — demonstration repository; not part of the production release chain.

The NamLauncher Game Companion adds launcher branding and in-game presentation for supported Minecraft and loader combinations. The launcher downloads and verifies the matching artifact from the official website. Legacy-supported versions keep their frozen companion source, while maintained combinations use the current 1.3.1 companion line.

Production secrets, `.env` files, databases, runtime logs, downloaded release binaries, OAuth sessions, and machine-local workspaces are intentionally not stored in these source repositories.

Created by [nattapat2871](https://nattapat2871.me). NamLauncher is independent and is not affiliated with Mojang or Microsoft.
