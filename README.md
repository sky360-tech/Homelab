# 🧪 My Home Lab  Setup

This repo documents and contains the Docker Compose files powering my self-hosted home lab.

## 🔧 Home Lab Overview

| Machine        | Specs                                  | Purpose |
|----------------|-----------------------------------------|---------|
| OMV Server     | i3 (4th gen), 16 GB DDR3, 250 GB HDD, 500 GB HDD, 500 GB HDD| NAS + Docker Host |
| Proxmox Server 1 | i5 (4th gen), 250 GB HDD, 256 GB SSD | VMs: Kali Purple, Windows, TrueNAS |
| Proxmox Server 2 | Lenovo RD630, 2×E5-2640, 8 GB, 250 GB SSD | More VMs |

## 🧩 Services

- 📀 [ARM (Auto Ripping Machine)](docker-compose/arm.yml)
- 📺 [Jellyfin](docker-compose/jellyfin.yml)
- 🎵 [Navidrome](docker-compose/navidrome.yml)
- 📸 [Photoprism](docker-compose/photoprism.yml)
- 🎧 [Plex](docker-compose/plex.yml)
- ⚡ [Stable Diffusion (AUTOMATIC1111)](docker-compose/stable-diffusion.yml)
- 📡 [Pi-hole](docker-compose/pihole.yml)
- 🌐 [NGINX Proxy Manager](docker-compose/nginx-proxy.yml)
- 🧠 [Ollama](docker-compose/ollama.yml)
- 🎬 [Sonarr, Radarr, Homarr](docker-compose/arr-stack.yml)

## 🧰 Networking

- Google Wi-Fi (Router)
- TP-Link 5-Port Gigabit Switch
- Cisco Linksys Gigabit Router (Bridge Mode)

---

> **Disclaimer:** All UUIDs and IPs have been scrubbed for privacy. Replace with your own values.
