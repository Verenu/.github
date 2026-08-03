<div align="center">
  <img src="https://raw.githubusercontent.com/Verenu/.github/main/assets/verenu-banner.svg" alt="Verenu - voice that stays in your flow" width="100%" />
</div>

<p align="center">
  <a href="https://github.com/MONKE2525E/Verenu"><img alt="Explore Verenu" src="https://img.shields.io/badge/explore-Verenu-2b2422?style=for-the-badge&labelColor=f5d4c5"></a>
  <a href="https://github.com/MONKE2525E/Verenu/blob/master/docs/INSTALL.md"><img alt="Install" src="https://img.shields.io/badge/install-guide-d97757?style=for-the-badge&labelColor=f5d4c5"></a>
  <a href="https://github.com/MONKE2525E/Verenu/blob/master/docs/DATA_AND_PRIVACY.md"><img alt="Privacy" src="https://img.shields.io/badge/privacy-local--first-376d6a?style=for-the-badge&labelColor=d8e6e2"></a>
</p>

<p align="center"><strong>Talk once. Keep moving.</strong><br/>Verenu is an open-source desktop dictation app for Windows and macOS. Hold a hotkey, speak naturally, and drop clean text into the app that already has your focus.</p>

<p align="center">
  <a href="https://verenu.com">Website</a> /
  <a href="https://github.com/MONKE2525E/Verenu">Source code</a> /
  <a href="https://github.com/MONKE2525E/Verenu/blob/master/docs/ROADMAP.md">Roadmap</a> /
  <a href="https://github.com/MONKE2525E/Verenu/blob/master/docs/SUPPORT.md">Support</a>
</p>

<br/>

<img src="https://raw.githubusercontent.com/Verenu/.github/main/assets/verenu-flow.svg" alt="How Verenu works: hold the hotkey, capture locally, transcribe and clean, then paste into the focused app" width="100%" />

## What makes Verenu different

<table>
  <tr>
    <td width="33%" valign="top">
      <h3>Speak naturally</h3>
      <p>Hold-to-record dictation with a global hotkey. Your thoughts go straight back into the work, without a copy-paste detour.</p>
    </td>
    <td width="33%" valign="top">
      <h3>Shape the output</h3>
      <p>Use cleanup levels, snippets, a personal dictionary, and app-specific profiles to make the result sound like you.</p>
    </td>
    <td width="33%" valign="top">
      <h3>Choose your boundary</h3>
      <p>Run local Parakeet V3 transcription or bring your own keys for Groq, OpenAI, or Google. No subscription and no telemetry from Verenu.</p>
    </td>
  </tr>
</table>

<img src="https://raw.githubusercontent.com/Verenu/.github/main/assets/verenu-privacy.svg" alt="Verenu privacy model: data stays on your device by default and leaves only for the provider you choose" width="100%" />

## Start here

| If you want to... | Go here |
| --- | --- |
| Try the app or read the full product README | [Verenu on GitHub](https://github.com/MONKE2525E/Verenu) |
| Install it on Windows or macOS | [Installation guide](https://github.com/MONKE2525E/Verenu/blob/master/docs/INSTALL.md) |
| Understand exactly what leaves your device | [Data and privacy](https://github.com/MONKE2525E/Verenu/blob/master/docs/DATA_AND_PRIVACY.md) |
| Configure providers and API keys | [API keys](https://github.com/MONKE2525E/Verenu/blob/master/docs/API_KEYS.md) |
| Tune cleanup, snippets, or your dictionary | [Feature docs](https://github.com/MONKE2525E/Verenu/tree/master/docs) |
| Contribute code or documentation | [Contributing](https://github.com/MONKE2525E/Verenu/blob/master/docs/CONTRIBUTING.md) |

## Built for a native desktop feel

<p>
  <img alt="Tauri" src="https://img.shields.io/badge/Tauri-2b2422?style=flat-square&logo=tauri&logoColor=fffaf2">
  <img alt="Svelte" src="https://img.shields.io/badge/Svelte-c7553d?style=flat-square&logo=svelte&logoColor=fffaf2">
  <img alt="Rust" src="https://img.shields.io/badge/Rust-7e7266?style=flat-square&logo=rust&logoColor=fffaf2">
  <img alt="SQLite" src="https://img.shields.io/badge/SQLite-376d6a?style=flat-square&logo=sqlite&logoColor=fffaf2">
</p>

Verenu uses Tauri, Svelte, Rust, and SQLite to keep the app fast, native, and small. It avoids bundling an entire browser-shaped runtime for a tool that mostly needs to listen, think, and paste.

## The short version

1. Your microphone input starts local.
2. You choose whether transcription is local or handled by a provider.
3. Cleanup is optional and configurable.
4. The finished text returns to the app that had focus.
5. Settings, history, keys, snippets, and dictionary data stay on your machine.

For the complete boundary map, read [Data and privacy](https://github.com/MONKE2525E/Verenu/blob/master/docs/DATA_AND_PRIVACY.md). Provider policies still apply to anything you choose to send to them.

## Repository map

- [Verenu](https://github.com/MONKE2525E/Verenu) is the app, source code, release flow, and detailed documentation.
- [Verenu/.github](https://github.com/Verenu/.github) is the organization profile and shared presentation layer.

<p align="center">
  <sub>Open source under the MIT License.</sub>
</p>
