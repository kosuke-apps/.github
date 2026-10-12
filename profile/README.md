# Kosuke Apps

Small, single-purpose apps for Mac and iPhone.

Each app does one thing, runs on your device, asks only for the permissions it needs and says why, and is free and open
source under the MIT licence.

## Apps

| App | Platform | What it does |
|---|---|---|
| [Headway](https://github.com/kosuke-apps/Headway) | iPhone | Live Madison, WI bus map: offline map with every route and stop, live buses, trip planner with transfers, and punctuality measured from its own recordings. |
| [NotchShelf](https://github.com/kosuke-apps/NotchShelf) | Mac | Opens the menu bar items hidden behind the MacBook notch, from the notch itself. |
| [Paddock](https://github.com/kosuke-apps/Paddock) | Mac | Menu bar app that runs the shared local Ollama server: on/off, state at a glance, local-only with cloud features off. |
| [SpellBar](https://github.com/kosuke-apps/SpellBar) | Mac | A menu bar app that brings the Japanese IME's conversion key to English typing, in any macOS app. |
| [Tapdeck](https://github.com/kosuke-apps/Tapdeck) | Mac | Audio routing, mixing and recording for macOS: per-app capture, virtual devices and several outputs per mix. |

## Downloads

Where a release exists, its repository's Releases page has the download. Mac apps come as a `.dmg`: open it and drag
the app to Applications. Releases are signed but not notarized, so macOS asks for confirmation the first time: open
**System Settings → Privacy & Security** and choose **Open Anyway**. Each release lists a SHA-256 checksum to verify
the download. Headway for iPhone is an unsigned `.ipa`, installed with a sideloading tool and your own Apple ID.
Otherwise, each README explains how to build the app from source.

## Support and security

Questions and bug reports go to the Issues of the app's repository. Security problems are reported privately; see the
[security policy](https://github.com/kosuke-apps/.github/blob/main/SECURITY.md).

## About

Maintained by [Kosuke Satake](https://github.com/kosuke-satake). The apps are built with the help of Claude (Anthropic)
through Claude Code; design, review and testing are the maintainer's. Anthropic does not endorse these apps.
