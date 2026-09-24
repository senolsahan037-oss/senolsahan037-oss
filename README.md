## Şenol Şahan — SubverseLab

I build measurement-based tools for music production.

Nothing in these repositories guesses. Each tool answers from numbers measured on
real projects, real records and real masters — or it returns nothing and says
which evidence was missing. A tool that cannot prove its answer does not give one.

I work from Turkey, alone, mostly inside Ableton Live. Before Ableton shipped an
official SDK I reverse-engineered the `.als` format and Remote Scripts to get at
the same data; when the Extensions SDK arrived I moved onto it and kept both paths.

---

### Available for freelance work

I take on contract work in the areas these repositories prove:

- **MCP servers** that let Claude or other agents use your API, database or internal tools — dry-run before every write, verified after
- **Audio software** — JUCE / C++ plugins (VST3, AU), Python DSP and loudness measurement (ITU-R BS.1770)
- **DAW integration** — Ableton Live automation through the Extensions SDK, Remote Scripts and the `.als` format

I work in writing and asynchronously; I do not take calls. To start, [open an issue here](https://github.com/senolsahan037-oss/senolsahan037-oss/issues/new?title=Work%20enquiry) with a few lines on what you need.

---

### Start here

**[Loom](https://github.com/senolsahan037-oss/loom)** — a local MCP server with 55
tools for Ableton Live. It reads your own `.als` archive, measures what you
actually do, and writes MIDI, device chains, automation and locators into a
*running* Live session through an Ableton Extension, verifying every write by
reading it back. AGPL-3.0, headless tests, CI.

---

### The three lines of work

**The spine** — [subverselab-launchpad](https://github.com/senolsahan037-oss/subverselab-launchpad)
The production rules, the validation gate, the deployed services, and the map of
every repository here.

**Tools that run in a browser** — free, no account needed, at [subverselab.com](https://subverselab.com)

| Tool | What it does |
|---|---|
| [Mix Check](https://subverselab.com/tools/subverse-mix-check) | measures a mix or master against genre profiles built from real released masters |
| [Arrangement GPS](https://subverselab.com/tools/arrangement-gps) | arrangement blueprints with an in-browser Web Audio preview |
| [Sensei](https://subverselab.com/tools/sensei) | 8-bar MIDI drum patterns across 22 genre styles |
| [SynthPulse](https://subverselab.com/tools/synthpulse) | 16-step lead and bass patterns, evolved and exported as MIDI |
| [Splitter](https://subverselab.com/tools/subverse-splitter) | stem separation and key/BPM analysis on HT-Demucs |
| [Time & Frequency Sync](https://subverselab.com/tools/time-frequency-sync) | BPM-synced delay and reverb times, key-to-Hz math — audible before you use them |

**Engines that feed Loom** — [sample-reader](https://github.com/senolsahan037-oss/sample-reader)
measures the audio itself rather than the file name ·
[sample-chopper](https://github.com/senolsahan037-oss/sample-chopper) and
[subverselab-sampler](https://github.com/senolsahan037-oss/subverselab-sampler)
cut a record the way it would be cut by hand ·
[crate-agent](https://github.com/senolsahan037-oss/crate-agent) finds and screens
1968–1998 Middle Eastern source records for chopping.

---

### Also here

[rap-voice-clone](https://github.com/senolsahan037-oss/rap-voice-clone) — a
per-artist Turkish rap voice pipeline that trains on a free Kaggle T4. Code and
the mistake ledger only: no audio, no weights, no artist names.

---

*Everything above runs. Where a repository documents something it cannot yet do,
it says so in its own README.*
