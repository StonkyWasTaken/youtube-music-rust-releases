# Changelog

## 0.3.0

Nine more experimental plugin ports are available; **37 of 40** catalog entries now have executable ports:

- **Album Actions:** like, unlike, dislike or undislike loaded album/playlist tracks, with a load-all control.
- **API Server:** private bearer-token authentication, loopback-only metadata and queue access, playback controls, seeking and volume.
- **Auth Proxy Adapter:** a local SOCKS5 bridge with authenticated upstream connections.
- **Downloader:** source audio or MP3 for the current track using yt-dlp, with an in-app helper installer and SHA-256 verification. Full YouTube support needs Deno or Node; MP3 also requires FFmpeg.
- **In-App Menu:** English application, player and navigation menus inside the player.
- **Performance Improvement:** the upstream RM3 element recycler and CPU Tamer scripts.
- **Scrobbler:** ListenBrainz and Last.fm, actual playback-time accounting and browser authorization for Last.fm.
- **Taskbar Media Control:** previous, play/pause and next buttons in the Windows thumbnail preview.
- **Transparent Player:** transparent backgrounds and native Windows materials.

New plugins start disabled. Configure each through Settings and plugins → Options. Proxy, performance scripts and transparency require a restart. Existing settings, sign-in data, queue and volume preferences are kept. Credentials and API tokens stay in local settings and are not exposed to the remote YouTube page.

Crossfade, Music Together and macOS Touch Bar remain unavailable. Ports are experimental; complete upstream parity and live service compatibility have not been verified.

[Release notes and downloads](https://github.com/StonkyWasTaken/youtube-music-rust-releases/releases/tag/v0.3.0)

## 0.2.0

- Signed app updates with background availability checks, a Windows notification and an in-app installation prompt.
- Integrated settings/plugin panel and optional restart after changes.
- Custom Discord activity name and title.
- Artwork mouse-wheel volume control synchronized with the native slider.
- English interface, In player ad blocking and a centered square play icon.
- Song/queue restoration, starting the song at 0:00 after reopening.

[Release notes and downloads](https://github.com/StonkyWasTaken/youtube-music-rust-releases/releases/tag/v0.2.0)
