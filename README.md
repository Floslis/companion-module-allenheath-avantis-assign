# Bitfocus Companion module: Allen & Heath Avantis assign

**English** · [Deutsch](README.de.md)

A [Bitfocus Companion](https://bitfocus.io/companion) module that does what the official Avantis module can't: **switch the assign of an input to aux mixes**, with live feedback from the desk. Perfect for talkback on a Stream Deck.

> [!NOTE]
> **In development.** Nothing to install yet. Watch or star the repo to get notified. Built on the protocol work from **[allenheath-talkback](https://github.com/Floslis/allenheath-talkback)**, documented in **[avantis-protocol](https://github.com/Floslis/avantis-protocol)**.

[![Support me on Ko-fi](https://ko-fi.com/img/githubbutton_sm.svg)](https://ko-fi.com/floslist)

## Why

The official [Avantis module](https://github.com/bitfocus/companion-module-allenheath-avantis) talks MIDI over TCP. That covers faders, mutes and scenes, but MIDI can't assign an input to a mix. This module uses the desk's native protocol (the one Director and Mixing Station use) for exactly that, and works alongside the official module.

## Planned

**Actions**
- [ ] Assign input → aux / stereo aux: on, off, toggle
- [ ] Groups of mixes in one press (e.g. "Band", "MD"), like in allenheath-talkback
- [ ] Send level input → aux

**Feedbacks**
- [ ] Button lights when an assign is on, live from the desk, even when changed on the desk
- [ ] Mix names from the desk as button text

**Also**
- [ ] Find the desk on the network automatically
- [ ] Presets for a talkback page
- [ ] Release in the Companion module store

## Status

| | |
|---|---|
| Protocol (connect, heartbeat, assign, live state) | ✅ working in [allenheath-talkback](https://github.com/Floslis/allenheath-talkback) |
| Companion module | 🚧 not started yet |
| Tested | Avantis firmware V2.01 Rev. 97241 |

Want to help or test? Open an issue.

## License

[MIT](LICENSE) · Not affiliated with Allen & Heath or Bitfocus · A project by **[FLOTECH](https://flotech.dev)**
