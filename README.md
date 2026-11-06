# Ralphael Alcober

[<img src="assets/globe.svg" width="16" height="16" align="absmiddle" alt=""> portfolio.alcoberlabs.xyz](https://portfolio.alcoberlabs.xyz) · [<img src="assets/linkedin.svg" width="16" height="16" align="absmiddle" alt=""> LinkedIn](https://www.linkedin.com/in/ralphalc/)

Looking for new-grad and internship software engineering roles for 2027. I'm a computer engineering senior at Manhattan University who builds software projects, with a background in distributed systems and ML security.

## Experience

- **Con Edison**: engineering co-op since Aug 2025. Rewrote a roughly 10-year-old tool whose database had been deprecated. It now screens ~30–40 returned units a week against live data for fault testing, and it's documented and packaged so anyone can run it without writing code.

## Software projects

- **Batcave**: self-hosted personal command center on Cloudflare Workers and D1, with tasks, habits, two-way Google Calendar sync and an AI assistant that works through tool calls. [Repo](https://github.com/23alcor/batcave)
- **BerLabs**: AI newsletter platform. An hourly Python collector pulls from 20+ RSS sources, clusters related coverage and drafts summaries for a private editorial dashboard. Built on Next.js, Cloudflare Workers and D1. [Live](https://news.berlabs.dev)
- **Confiance**: lending app on the XRP Ledger Devnet, built by a team of five in 36 hours at the AI & Fintech XRP Ledger Hackathon in NYC. I built the API and risk engine: OFAC sanctions screening, a score out of 100 and risk-based pricing. [Repo](https://github.com/Jfrancisjr21/xrpl-hackathon) · [Live](https://confiance.alcoberlabs.xyz)
- **Token Usage**: early macOS prototype that shows how much AI subscription capacity you have left before a big task. Rust collector with a React dashboard in a Tauri shell. [Repo](https://github.com/23alcor/Usage-Token-Visualizer)
- **Notion Webhook Server**: FastAPI backend that reacts to Notion webhooks, summarizes notes with OpenAI and keeps task and calendar blocks current. Runs 24/7 on a Raspberry Pi under systemd, behind a Cloudflare Tunnel. [Repo](https://github.com/23alcor/Notion-Webhook-server)
- **Facial recognition door lock**: two-person course project. On-device OpenCV recognition on a Raspberry Pi drives a servo lock, with no cloud and no face data leaving the device. [Repo](https://github.com/23alcor/facial-recognition-door-lock)
- **capstone-ui**: interactive IEEE 13-bus feeder explorer for a HIL grid fault-detection capstone. [Repo](https://github.com/23alcor/capstone-ui)

## Research background

- **Distributed systems**: studied where multi-GPU training loses time across 803 measurements, from 1 to 64 GPUs, on Bridges-2 through NSF ACCESS. Spreading the same GPUs across more nodes can inflate communication cost 6.4×. Paper in draft. [Write-up](https://portfolio.alcoberlabs.xyz/research/hpc-gpu-training/)
- **ML security**: first-author paper at IEEE CCWC 2026 on defending industrial control system intrusion detection from adversarial attacks. A GAN purifier sits in front of a frozen detector, evaluated against FGSM, PGD, DeepFool, C&W and JSMA. [Paper](https://ieeexplore.ieee.org/document/11393828) · [Write-up](https://portfolio.alcoberlabs.xyz/research/adversarial-ics/)

## Stack

Python, TypeScript, SQL · FastAPI, Next.js, React · Cloudflare Workers, Linux · PyTorch DDP, NCCL, CUDA, SLURM
