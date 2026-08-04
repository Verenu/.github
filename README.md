# Verenu

We build small desktop software that stays out of the way.

Most tools that touch your voice, your text, or your work want to become a place you go. We would rather build things you barely notice: they sit in the background, do one job when you ask, and hand control back immediately. Nothing here is trying to be a platform.

## What we work on

Right now that means [**Verenu**](https://github.com/MONKE2525E/Verenu), an open-source dictation app for Windows and macOS. You hold a hotkey, talk, let go, and cleaned-up text lands in whatever app already had your cursor. It is built with Tauri, Svelte, Rust, and SQLite.

It is one app, but the way it is built is the point, and it is the same way anything else we make will be built.

## What we want out of our software

**Local by default.** Your data starts on your machine and stays there unless you decide otherwise. Local transcription is a real option, not a checkbox nobody finished. When something does leave your device, it goes straight to the provider you picked, never through a server of ours.

**A boundary you can explain.** If you cannot describe where your data goes in one sentence, we designed it wrong. "Private" is a claim; a documented boundary is a fact. Ours lives in [Data and privacy](https://github.com/MONKE2525E/Verenu/blob/master/docs/DATA_AND_PRIVACY.md).

**Your keys, your accounts.** Bring your own API keys. They are stored in the OS credential store, not in a config file and not on our infrastructure. No account to create, no subscription, no metered middleman between you and a service you are already paying for.

**No telemetry.** We do not watch how you use it. This means we learn about problems the slow way, by people telling us, and we accept that trade.

**Native, not a browser in a trench coat.** Background tools should cost near nothing when idle. That is why we use Tauri over Electron and reach for the OS instead of shipping a runtime to reimplement it.

**Yours to keep.** MIT licensed, no gated features, no phone-home kill switch. If we stop working on something, the thing you installed keeps working and you can fork it.

**Fits the flow you already have.** We would rather integrate with the app you use than convince you to move into ours. Success looks like you forgetting we are running.

## How we decide things

- Fewer features that hold up beats more features that mostly work.
- A setting is a failure to pick a default. Some failures are worth it; most are not.
- If a feature only works by sending more data off the device, it needs to justify itself or not ship.
- Slow and correct beats fast and surprising, especially anywhere text gets modified.
- We would rather delete code than maintain it.

## Where things live

| | |
| --- | --- |
| App, source, releases, and full docs | [MONKE2525E/Verenu](https://github.com/MONKE2525E/Verenu) |
| Install on Windows or macOS | [Installation guide](https://github.com/MONKE2525E/Verenu/blob/master/docs/INSTALL.md) |
| What leaves your device, exactly | [Data and privacy](https://github.com/MONKE2525E/Verenu/blob/master/docs/DATA_AND_PRIVACY.md) |
| Providers and API keys | [API keys](https://github.com/MONKE2525E/Verenu/blob/master/docs/API_KEYS.md) |
| How it is put together | [Architecture](https://github.com/MONKE2525E/Verenu/blob/master/docs/ARCHITECTURE.md) |
| Where we are headed | [Roadmap](https://github.com/MONKE2525E/Verenu/blob/master/docs/ROADMAP.md) |
| Help with something | [Support](https://github.com/MONKE2525E/Verenu/blob/master/docs/SUPPORT.md) |
| Pitch in | [Contributing](https://github.com/MONKE2525E/Verenu/blob/master/docs/CONTRIBUTING.md) |
| This profile | [Verenu/.github](https://github.com/Verenu/.github) |

## Contributing

Bug reports and documentation fixes are as welcome as code. If you are considering something large, open an issue first. Not to gatekeep it, but so nobody spends a weekend on a direction we are about to change. Issues and pull requests belong on [the main repository](https://github.com/MONKE2525E/Verenu).

<sub>Open source under the MIT License.</sub>
