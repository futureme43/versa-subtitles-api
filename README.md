<!-- file: README.md -->
<div align="center">

# 🎬 Versa Subtitles API

**High-speed, multi-language subtitle acquisition and streaming delivery engine.**

[![Status](https://img.shields.io/badge/Status-Production%20Live-00E5FF?style=for-the-badge)](#)
[![Encoding](https://img.shields.io/badge/Transport-GZIP%20Compressed-0038FF?style=for-the-badge)](#)
[![Format](https://img.shields.io/badge/Format-SubRip%20(.srt)-0055FF?style=for-the-badge)](#)
[![Languages](https://img.shields.io/badge/Languages-36%20Supported-001A88?style=for-the-badge)](#)

[Live Dashboard & Portal](https://subs.versamovies.site) • [Interactive API Docs](https://subs.versamovies.site#docs) • [Report Issue](https://github.com/futureme43/versa-subtitles-api/issues)

</div>

---

## 📸 Platform Overview

<div align="center">
  <img src="assets/screenshots/dashboard.png" alt="Versa Subtitles Command Center" width="850">
  <p><i>Versa Subtitles Command Center — Realtime multi-language subtitle catalog & direct stream download portal.</i></p>
</div>

<br/>

<div align="center">
  <img src="assets/screenshots/languages.png" alt="Language Selection Suite" width="850">
  <p><i>Target Configuration Engine — 36 native locales supported with on-the-fly streaming fallback.</i></p>
</div>

---

## ⚡ Key Highlights

- **Zero-Latency Decompression:** All subtitle assets are stored in optimized GZIP `.srt.gz` streams, compressed down to ~20 KB per file, and automatically decompressed transparently over standard HTTP `Accept-Encoding: gzip`.
- **Extensive Locale Coverage:** 36 international languages supported natively (English through Swahili and Igbo).
- **Universal Matching:** Automated metadata resolution indexed strictly against TMDB movie and TV episode identifiers.
- **Plug-and-Play Integration:** Designed for instant consumption inside Android Media3 / ExoPlayer, React Native, Flutter, Apple AVPlayer, and HTML5 video tracks.

---

## 🌐 Base URL

All requests are served over HTTPS via the production edge network:

```http
[https://subs.versamovies.site](https://subs.versamovies.site)

