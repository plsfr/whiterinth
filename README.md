<div align="center">

<h1>Whiterinth</h1>

<p><strong>A stripped-back, monochrome fork of Modrinth App.</strong></p>

<p>
  <a href="https://github.com/modrinth/code/releases/tag/v0.23.5"><img alt="Based on Modrinth App v0.23.5" src="https://img.shields.io/badge/Modrinth%20App-v0.23.5-555555?style=flat-square"></a>
  <img alt="Monochrome interface" src="https://img.shields.io/badge/interface-monochrome-555555?style=flat-square">
  <img alt="Advertising removed" src="https://img.shields.io/badge/advertising-removed-555555?style=flat-square">
  <img alt="Minimal launcher" src="https://img.shields.io/badge/launcher-minimal-555555?style=flat-square">
</p>

<p>
  <a href="#what-is-whiterinth">About</a> ·
  <a href="#what-changed">What changed</a> ·
  <a href="#install-on-windows">Install</a> ·
  <a href="#build-from-source">Build from source</a> ·
  <a href="#credits-and-licensing">Credits &amp; licensing</a>
</p>

</div>

---

> [!NOTE]
> Whiterinth is an unofficial, independently maintained fork of [Modrinth App](https://github.com/modrinth/code). It is not affiliated with or endorsed by Modrinth.

## What is Whiterinth?

Whiterinth is a minimal, monochrome take on the Modrinth launcher, based on the official **Modrinth App v0.23.5** — the latest upstream release at the time of writing.

The interface uses a consistent grayscale palette across its panels and surfaces. Advertising and extra sidebar content are removed, leaving a cleaner launcher focused on managing and playing Minecraft.

## What changed

- **Monochrome interface.** App panels and UI surfaces use a grayscale palette throughout.
- **Advertising removed.** In-app advertising visuals have been removed.
- **Hosting shortcut removed.** The Modrinth Hosting button is no longer shown in the left sidebar.
- **News column removed.** The launcher no longer displays the news column.

The project keeps the familiar Modrinth App foundation and its core launcher experience.

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

Whiterinth is built on the work of the Modrinth developers and contributors. See the [official Modrinth App source](https://github.com/modrinth/code).

Licensing terms vary by package. See the [copying and branding guidelines](COPYING.md), [desktop license](apps/app/LICENSE), [frontend license](apps/app-frontend/LICENSE), and [third-party notices](THIRD-PARTY-NOTICES.md).
