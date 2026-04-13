# digital-buccaneer
Building the infrastructure businesses should own but don't. Local AI, private automation, Fraser Valley BC. Let me show you how.

Digital Buccaneer Ltd.
### Local AI Infrastructure · Private Automation · Fraser Valley, BC

> *Real AI. Real privacy. Real ownership.*

---

## What This Is

This repository is the working foundation of a boutique MSP and local AI deployment practice serving small businesses and residential clients in Maple Ridge and the Fraser Valley.

Everything here — runbooks, Docker Compose stacks, configuration templates, homelab documentation — is built from real infrastructure running in a real environment. This is not theoretical. The lab is the portfolio.

If you are a small business owner, a privacy-conscious professional, or someone who believes your data should stay on hardware you control — this work is built for you.

---

## The Problem I Solve

Two markets in the Fraser Valley share the same blind spot.

**Managed IT providers** are almost entirely cloud-first. Their value proposition is moving your data offsite. For regulated industries — legal, medical, accounting, finance — that is not a solution. It is a liability. Privacy legislation in BC is tightening. Data sovereignty is no longer optional for some industries, and it is becoming a preference in many others.

**Home and commercial automation companies** are selling AI as a feature while deploying none. Every major local integrator mentions AI. None of them are running actual LLMs. None of them offer local voice assistants that preserve privacy. The AI is a marketing layer over 2015 architecture.

No operator in the local market is currently:

- Deploying local LLMs for business intelligence or workflow automation
- Offering privacy-first AI as a core service proposition
- Bridging managed IT and smart automation under one roof
- Providing local voice assistant integration that bypasses cloud services
- Serving privacy-conscious SMBs with an on-premises alternative to cloud AI subscriptions

This is not a feature gap. It is a market category that does not yet exist locally.

---

## Mission

To be the Fraser Valley's most trusted technology partner for businesses and homeowners who believe their data, their infrastructure, and their AI should belong to them — not to a cloud provider, not to a subscription service, and not to a platform they don't control.

**We build real solutions. We teach you how they work. We leave you owning something.**

---

## Services

| Tier | Name | What You Get |
|------|------|--------------|
| 1 | **Starter** | Local AI persona deployed on your existing hardware, setup and training |
| 2 | **Essential** | Hardware upgrade or pre-built workstation, full Ollama stack, knowledge transfer |
| 3 | **Professional** | Dedicated server, multi-user LLM deployment, network segmentation, retainer support |
| 4 | **Premier** | Full rack infrastructure, VMs, VLANs, managed services, ongoing MSP contract |
| + | **Automation** | Home or commercial automation, local voice assistant, Home Assistant integration |
| + | **Research & Intelligence** | Private document analysis, internal research workflows, local LLM pipelines |

---

## Who This Is For

**Priority markets:**
1. Privacy-sensitive SMBs — legal, medical, accounting, real estate
2. Small businesses wanting real AI capability without cloud costs or data exposure
3. Residential clients wanting smart home automation without privacy compromise
4. Businesses currently paying cloud AI subscriptions with no data ownership

---

## Why Local AI

Cloud AI tools are powerful. They are also a trade. Every query you send to a hosted model leaves your building. For most personal use that is an acceptable trade. For a law firm's client files, a medical clinic's patient notes, or a financial advisor's records — it is not.

Local deployment means:
- Your data never leaves your hardware
- No per-seat subscription fees compounding monthly
- No dependency on a vendor's uptime, pricing decisions, or policy changes
- Full control over model selection, system prompts, and access

Modern hardware is capable enough. The models are good enough. The missing piece is someone who knows how to put it together — and can be called when something breaks.

---

## Current Stack (Homelab / Proof of Concept)

**Main Rig — Primary AI Workstation**
- Ryzen 7 5700X3D · 32GB RAM · RX 7700 XT 12GB
- Models: Qwen 2.5 14B (primary), GPT-OSS 20B (dedicated sessions)
- ROCm-accelerated inference via Ollama

**Secondary Rig — Daily Driver AI Machine**
- Ryzen 5 4600G · RTX 3050 8GB · 16GB RAM
- Models: Gemma 3N E4B, Llama 3.2 Vision
- CUDA-accelerated inference via Ollama

**Server — minnowmint**
- i7-4790 · 32GB RAM · Linux Mint
- Running: Proxmox, Home Assistant OS, Jellyfin, Immich, Pi-hole, Prometheus, Grafana, Tailscale, Radarr/Sonarr/Prowlarr, qBittorrent + Gluetun VPN

**Networking**
- OPNsense firewall · VLAN segmentation · default-deny WAN posture

**Local AI Stack**
- Ollama · Open WebUI · SearXNG (self-hosted search) · AnythingLLM (RAG)

---

## What's In This Repo

> *This repo is actively growing. Runbooks and configs are added as they are built and validated.*

- `/runbooks` — Step-by-step deployment guides for repeatable infrastructure tasks
- `/docker-compose` — Production-tested Compose files with annotated configs
- `/homelab` — Infrastructure documentation and architecture notes
- `/local-ai` — Model deployment guides, Open WebUI configs, prompt engineering notes

---

## About

Built by a self-taught infrastructure builder with 4.5 years of hands-on homelab experience — five PCs built from scratch, real networking, real containerization, real local AI deployment. Currently pursuing CompTIA A+, Network+, and Security+ with a target of full independent practice by September 2028.

Also documenting this entire build publicly on **[Minnow Tor](https://youtube.com/@minnowtor)** — no gatekeeping, no paywalls, just the actual work.

**Let me show you how.**

---

*The lab is the portfolio. The work has already started.*

