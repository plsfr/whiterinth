<div align="center">

<h1>Whiterinth</h1>

<p><strong>A monochrome Minecraft launcher based on Modrinth App.</strong></p>

<p>
  <a href="https://github.com/modrinth/code"><img alt="Upstream: modrinth/code" src="https://img.shields.io/badge/upstream-modrinth%2Fcode-303030?style=flat-square"></a>
  <img alt="Interface: grayscale" src="https://img.shields.io/badge/interface-grayscale-585858?style=flat-square">
  <img alt="Build guide: Windows x64" src="https://img.shields.io/badge/build%20guide-Windows%20x64-707070?style=flat-square">
</p>

<a href="#install-on-windows">Install</a> · <a href="#build-from-source">Build from source</a> · <a href="#credits-and-licensing">Credits &amp; licensing</a>

</div>

---

> [!NOTE]
> **Whiterinth is an unofficial modified fork of Modrinth App.** It is independently maintained and has no official affiliation with or endorsement from Modrinth. [Original Modrinth repository](https://github.com/modrinth/code)

## What changed

- **Monochrome throughout the launcher.** A single grayscale filter covers the desktop interface, including in-app menus, dialogs, and images loaded at runtime. Native system dialogs and external sign-in pages render separately.
- **Fewer promotional interruptions.** The fork removes the embedded ad view, sidebar ads and upsells, ad consent and reporting, and the external survey widget.
- **Its own app identity.** The window, executable, and installer use the Whiterinth name. Launcher data is stored separately under `org.whiterinth.launcher`.

The launcher retains Modrinth service integrations and the familiar workflows for browsing content, managing Minecraft instances, and launching the game. Whiterinth registers the `modrinth:` protocol and `.mrpack` files, so you can choose the default handler in Windows if you have both launchers installed.

## Install on Windows

If a Windows x64 setup executable is attached to a Whiterinth release, download and run it. Otherwise, [build the installer locally](#build-from-source). Open **Whiterinth** from the Start menu after setup. Install Microsoft Edge WebView2 Runtime if prompted.

## Build from source

For the Windows build, use Node.js **24.15 or later**, **pnpm 12.11.2**, the pinned Rust toolchain and **JDK 17**. Install Visual Studio Build Tools with **Desktop development with C++** and a Windows SDK. Set `JAVA_HOME` to the JDK installation directory. Short checkout and Cargo cache paths help avoid Windows path-length errors.

From the repository root in PowerShell, install dependencies and set up the launcher environment:

```powershell
pnpm install --frozen-lockfile
Copy-Item packages/app-lib/.env.prod packages/app-lib/.env
```

Run the launcher in development mode:

```powershell
pnpm app:dev
```

Build an unsigned Windows x64 installer from an x64 build environment:

```powershell
pnpm --filter @modrinth/app run build --bundles nsis
```

The default installer output directory is `target/release/bundle/nsis/`.

| Directory | Role |
| --- | --- |
| [`apps/app`](apps/app/) | Tauri desktop shell and installer configuration |
| [`apps/app-frontend`](apps/app-frontend/) | Vue launcher interface |
| [`packages/app-lib`](packages/app-lib/) | Shared Rust launcher library |

## Credits and licensing

Thanks to the Modrinth developers and contributors who built the original launcher and its shared libraries. [Modrinth source code](https://github.com/modrinth/code)

The applicable terms are defined per package. See the [copying and branding guidelines](COPYING.md), [desktop license](apps/app/LICENSE), [frontend license](apps/app-frontend/LICENSE), and [third-party notices](THIRD-PARTY-NOTICES.md).
