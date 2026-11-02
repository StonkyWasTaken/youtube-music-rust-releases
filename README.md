# YouTube Music Rust

An independent, experimental Windows desktop client for YouTube Music, built with Rust and WebView2.

## Download

**[Download for Windows x64](https://github.com/StonkyWasTaken/youtube-music-rust-releases/releases/latest/download/YouTube-Music-Rust-Setup.exe)**

[Release notes and all downloads](https://github.com/StonkyWasTaken/youtube-music-rust-releases/releases/latest)

Install the update-enabled version once. Later releases are detected automatically and shown as **Update available** in the app and in a Windows notification. You can also choose **Application → Check for updates…**. Updates download and install only after you confirm.

## Included

- YouTube Music playback with an English interface and a separate profile.
- Integrated settings and plugin panel, artwork scroll-wheel volume control, and optional Discord Rich Presence.
- Experimental ports of desktop plugins, including the original In player ad blocker mode.
- Saves the current song and queue, starting the song at 0:00 when reopened.
- Signed update packages, with signature verification before installation.

This is a work in progress; full parity with the original app has not been reached. Windows installers do not yet have an Authenticode certificate; updater signatures are a separate mechanism.

## Source and licensing

This repository contains public downloads, release notes and license notices. The application source is maintained in a separate private repository.

Based in part on [pear-devs/pear-desktop](https://github.com/pear-devs/pear-desktop), version 3.12.0. MIT attribution is included in [LICENSE](LICENSE) and [UPSTREAM-LICENSE](UPSTREAM-LICENSE), and alongside the downloadable installer.

Unofficial project. Not affiliated with Google or YouTube.