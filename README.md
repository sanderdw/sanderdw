# Hi, I'm Sander 👋

I build things that make invisible stuff visible, energy data, sound, space and the human body.

[![Buy me a coffee](https://img.shields.io/badge/Buy%20me%20a%20coffee-f59e0b?style=flat-square&logo=data:image/svg%2Bxml;base64,PHN2ZyB4bWxucz0iaHR0cDovL3d3dy53My5vcmcvMjAwMC9zdmciIHZpZXdCb3g9IjAgMCAyNCAyNCI%2BPHBhdGggZmlsbD0id2hpdGUiIGQ9Ik0yLDIxSDIwVjE5SDJNMjAsOEgxOFY1SDIwTTIwLDNINFYxM0E0LDQgMCAwLDAgOCwxN0gxNEE0LDQgMCAwLDAgMTgsMTNWMTBIMjBBMiwyIDAgMCwwIDIyLDhWNUMyMiwzLjg5IDIxLjEsMyAyMCwzWiIvPjwvc3ZnPg%3D%3D)](https://bunq.me/sanderdw)

---
## 🧊 [Iceberg Data Platform](https://github.com/sanderdw/iceberg-data-platform)

[![Stars](https://img.shields.io/github/stars/sanderdw/iceberg-data-platform?style=flat-square&color=0ea5e9)](https://github.com/sanderdw/iceberg-data-platform)
[![License](https://img.shields.io/badge/license-Apache--2.0-0ea5e9?style=flat-square)](https://github.com/sanderdw/iceberg-data-platform/blob/main/LICENSE)

**An open lakehouse you actually own.** [Apache Iceberg](https://iceberg.apache.org) as the table
format, with every other building block open source and replaceable:
[Apache Polaris](https://polaris.apache.org), [Keycloak](https://www.keycloak.org),
[RustFS](https://rustfs.com), PostgreSQL, [marimo](https://marimo.io) and DuckDB, connected through
open interfaces (Iceberg REST, S3, OIDC and MCP). It runs on a single laptop with one command.

Use it as a reference architecture, a classroom, or a personal lab to learn Iceberg hands-on.

`Python` `FastAPI` `Apache Iceberg` `Apache Polaris` `Keycloak` `DuckDB` `marimo` `RustFS` `PostgreSQL` `MCP` `Docker`

[**Repo**](https://github.com/sanderdw/iceberg-data-platform) · [**Presentation**](https://sanderdw.github.io/iceberg-data-platform/) · [**Article on Medium**](https://medium.com/@sanderdw/e89c5d0bed98)

<a href="https://github.com/sanderdw/iceberg-data-platform"><img src="https://raw.githubusercontent.com/sanderdw/iceberg-data-platform/main/docs/portal.png" width="640" alt="Iceberg Data Platform administration portal"></a>

---

## 🕹️ [AWTRIX NG TC002](https://github.com/sanderdw/awtrix-ng-tc002)

[![Stars](https://img.shields.io/github/stars/sanderdw/awtrix-ng-tc002?style=flat-square&color=22c55e)](https://github.com/sanderdw/awtrix-ng-tc002)
[![License](https://img.shields.io/badge/license-PolyForm--Noncommercial-22c55e?style=flat-square)](https://github.com/sanderdw/awtrix-ng-tc002/blob/main/LICENSE.md)

An unofficial port of Blueforcer's [AWTRIX NG](https://github.com/Blueforcer/awtrix-ng) to the
Ulanzi TC002 pixel clock, using its native **52 × 16** matrix. The upstream core, renderer, Berry
scripting, HTTP API, web UI and MQTT run directly on the clock, with the exact upstream MQTT topics
and Home Assistant discovery. A one-line installer builds and flashes the firmware, and can restore
stock just as easily.

`C++` `Python` `CMake` `MQTT` `Home Assistant` `Linux/ARMv7`

[**Repo**](https://github.com/sanderdw/awtrix-ng-tc002) · [**AWTRIX NG**](https://blueforcer.github.io/awtrix-ng/)

<a href="https://github.com/sanderdw/awtrix-ng-tc002"><img src="https://raw.githubusercontent.com/sanderdw/awtrix-ng-tc002/main/docs/tc002.jpg" width="640" alt="AWTRIX NG running on a Ulanzi TC002"></a>

---

## 🎵 [VoltViz](https://github.com/sanderdw/voltviz)

[![Stars](https://img.shields.io/github/stars/sanderdw/voltviz?style=flat-square&color=8b5cf6)](https://github.com/sanderdw/voltviz)
[![License](https://img.shields.io/badge/license-MIT-8b5cf6?style=flat-square)](https://github.com/sanderdw/voltviz/blob/main/LICENSE)

A dynamic, real-time music visualizer inspired by Winamp & Sonique. Synchronize with your system
audio, microphone or [Music Assistant](https://music-assistant.io) (through
[Sendspin](https://www.sendspin-audio.com)) and watch your music come alive, **50+ visualization
styles** and switchable Modern / Win95 / Winamp / CRT interface skins.

`React` `TypeScript` `Three.js` `WebGL` `Vite` `Docker`

[**Repo**](https://github.com/sanderdw/voltviz) · [**voltviz.com**](https://voltviz.com)

<a href="https://voltviz.com"><img src="https://raw.githubusercontent.com/sanderdw/voltviz/main/images/voltviz.png" width="640" alt="VoltViz"></a>

---

## 🏠 [Home Assistant Apps](https://github.com/sanderdw/hassio-addons)

[![Stars](https://img.shields.io/github/stars/sanderdw/hassio-addons?style=flat-square&color=41bdf5)](https://github.com/sanderdw/hassio-addons)
[![License](https://img.shields.io/badge/license-MIT-41bdf5?style=flat-square)](https://github.com/sanderdw/hassio-addons/blob/main/LICENSE)

An add-on repository for [Home Assistant](https://www.home-assistant.io) bundling four apps:

- **VoltViz**, the music visualizer above, running right inside Home Assistant
- **DSMR Reader**, extract, store and visualize data from your smart meter's DSMR protocol
- **DSMR Datalogger**, the standalone logger that feeds it
- **Metabase**, the easy, open source way for everyone to ask questions and learn from data

`Python` `Shell` `Docker` `Home Assistant`

[**Repo**](https://github.com/sanderdw/hassio-addons) · [**Community forum**](https://community.home-assistant.io/u/sanderdw/activity/topics)

[![Open your Home Assistant instance and show the add add-on repository dialog with a specific repository URL pre-filled.](https://my.home-assistant.io/badges/supervisor_add_addon_repository.svg)](https://my.home-assistant.io/redirect/supervisor_add_addon_repository/?repository_url=https%3A%2F%2Fgithub.com%2Fsanderdw%2Fhassio-addons)

<a href="https://github.com/sanderdw/hassio-addons"><img src="https://github.com/sanderdw/hassio-addons/blob/main/images/dsmr_reader.png" width="640" alt="DSMR Reader running in Home Assistant"></a>

<a href="https://github.com/sanderdw/hassio-addons"><img src="https://github.com/sanderdw/hassio-addons/blob/main/images/metabase.png" width="640" alt="Metabase running in Home Assistant"></a>

---

## 🚀 [On a Space Journey](https://onaspacejourney.com)

> Travel through space and discover countries, the moon and all the planets!

A free voyage of discovery for kids: spin the globe, fly to the moon and the planets, and steer
everything with your hand via the webcam. No install, no account, just open it in a browser.

`Three.js` `globe.gl` `d3` `MediaPipe Hands` `WebGL` `Vite`

[**onaspacejourney.com**](https://onaspacejourney.com) ENG · [**opruimtereis.nl**](https://opruimtereis.nl) NL

<a href="https://onaspacejourney.com"><img src="https://onaspacejourney.com/og-image-en.png" width="640" alt="On a Space Journey"></a>

---

## 🫀 [Body Journey](https://onabodyjourney.com)

> Travel through your body: peel away the skin and discover muscles, organs and bones!

A free journey of discovery through the human body for kids: peel away skin, muscles and organs
layer by layer, point at bones and muscles, and control everything with your hand via the webcam.

`Three.js` `MediaPipe Hands` `WebGL` `Vite`

[**onabodyjourney.com**](https://onabodyjourney.com) ENG · [**oplijfreis.nl**](https://oplijfreis.nl) NL

<a href="https://onabodyjourney.com"><img src="https://onabodyjourney.com/og-image-en.png" width="640" alt="Body Journey"></a>

---

<sub>[GitHub](https://github.com/sanderdw) · [LinkedIn](https://www.linkedin.com/in/sanderdw/) · [Buy me a coffee ☕](https://bunq.me/sanderdw)</sub>
