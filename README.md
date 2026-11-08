Unraid docker templates
=======================

This repository holds Docker templates for Docker images to be used in unRAID 6 (beta 8 or later). 

Installation
------------

 * Go to the unRAID control panel -> extensions -> Docker
 * In the textarea for *Template repositories* add `https://github.com/rgabrielson11/unraid-docker-templates` and press save

The templates below then appear when adding a new container.

Templates
---------

All live in `robert/`. Secrets (API keys, tokens, passwords) are always blank: fill them in when installing.

| File | Container | Description |
|---|---|---|
| `atv-optimizer.xml` | atv-optimizer | ATV Optimizer (shield_optimizer v2) desktop app running in a KasmVNC browser desktop. |
| `bazarr.xml` | bazarr | Bazarr is a companion application to Sonarr and Radarr. |
| `blockbusterr.xml` | blockbusterr | Automatically discovers trending, popular, and highly-rated movies and TV shows (via Trakt, TMDB, or Simkl) and adds them to Radarr/Sonarr,  |
| `chrome-tuner.xml` | ChromeTuner | Single-tuner virtual HDHomeRun: a Chrome tab as an Emby Live TV channel ([source](https://github.com/rgabrielson11/chrome-tuner)). |
| `crowbarr-cuda.xml` | Crowbarr-CUDA | Audio-grounded subtitle synchronization and transcription for Sonarr, Radarr and Bazarr. |
| `email-podcast-brief.xml` | email-podcast-brief | Polls a Gmail inbox for a specific subject line and generates a private podcast feed (audio via Kokoro TTS). |
| `glances-exporter.xml` | glances-exporter | Headless Glances instance in standalone mode, dedicated to exporting CPU/RAM/GPU/process stats to InfluxDB every 5s. |
| `gpu-process-exporter.xml` | gpu-process-exporter | Tiny sidecar that polls "nvidia-smi --query-compute-apps" every 5s and writes the GPU process count to InfluxDB (measurement "gpu", field "p |
| `hisense-ac.xml` | hisense-ac | hisense-ac-bridge patched for hismart-us Fahrenheit units. |
| `influxdb.xml` | influxdb | InfluxDB is an open source time series database with no external dependencies. |
| `kopia-sync-status.xml` | kopia-sync-status | Tiny static-file server exposing the Kopia-to-Backblaze-B2 sync status. |
| `mcp-ssh-unraid.xml` | mcp-ssh-unraid | Exposes an MCP stdio server (@aiondadotcom/mcp-ssh) over HTTP/SSE via supergateway, so this Unraid box can be driven over SSH by an MCP clie |
| `recipe-planner.xml` | recipe-planner | Self-hosted, pantry-first weekly dinner planner for a household. |
| `roborock-local-server.xml` | roborock-local-server | Local Roborock cloud emulator (HTTPS + MQTT) for the Qrevo Curv 2 Flow. |
| `searxng.xml` | SearXNG | SearXNG self-hosted metasearch engine. |
| `speaches.xml` | speaches | OpenAI-compatible speech-to-text (faster-whisper) server. |
| `storage-exporter.xml` | storage-exporter | Tiny sidecar that reads Unraid's own cached array/disk status (/var/local/emhttp/disks.ini) every 30s and writes per-disk temperature, capac |
| `subdefaults.xml` | subdefaults | Makes English SDH the default subtitle and merges English forced (foreign-dialogue) lines into it. |
| `whisper-asr.xml` | whisper-asr | Whisper ASR webservice (faster-whisper engine, GPU). |
