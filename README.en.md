# GULZA — Lyric Motion Video Maker

GULZA creates animated lyric and subtitle videos in your browser. You can export the result as MP4.

This fork lets you import an SRT subtitle file directly. You do not need to convert it to LRC first.

**[Open the English app](https://ruruoni1.github.io/gulza/en/)** · [Main repository page in Korean](README.md) · [Original JIZURA](https://github.com/852wa/JIZURA)

Other guides: [한국어](README.ko.md) · [日本語](README.ja.md) · [繁體中文](README.zh-Hant.md) · [简体中文](README.zh-Hans.md) · [Bahasa Indonesia](README.id.md) · [Tiếng Việt](README.vi.md)

## Quick start

1. Import an SRT or LRC file, or type one lyric phrase per line.
2. Optionally import audio and adjust the timing.
3. Choose **Create a variation** to generate a style and arrangement.
4. Preview the result, then export MP4.

The SRT importer keeps subtitle start and end times and the gaps between cues. You can edit their time markers in the lyric field.

## Language and editing

The interface language menu is at the top of the app. Korean is the default language at the root URL.

The **Lyrics language** setting is separate: it selects fonts and text segmentation for your lyrics. Its default is auto-detect.

The editor also provides manual timing, aspect ratios, PNG exports, project JSON, and After Effects JSON export.

## After Effects

The [GULZA ScriptUI panel](GULZA_AE.jsx) and [GULZA CEP panel](GULZA_CEP.zip) are available from this repository. The panels were packaged, but their behavior has not been checked in a running After Effects installation.

GULZA is a fork of [JIZURA](https://github.com/852wa/JIZURA). Source code is under the [MIT License](LICENSE).
