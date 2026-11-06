# Ralphael Alcober

[<img src="assets/globe.svg" width="16" height="16" align="absmiddle" alt=""> portfolio.alcoberlabs.xyz](https://portfolio.alcoberlabs.xyz) · [<img src="assets/linkedin.svg" width="16" height="16" align="absmiddle" alt=""> LinkedIn](https://www.linkedin.com/in/ralphalc/)

Looking for new-grad and internship software engineering roles for 2027. I'm a computer engineering senior at Manhattan University who builds software projects, with a background in distributed systems and ML security.

## Experience

- **Con Edison**: engineering co-op since Aug 2025. Rewrote a roughly 10-year-old tool whose database had been deprecated. It now screens ~30–40 returned units a week against live data for fault testing, and it's documented and packaged so anyone can run it without writing code.
- **Manhattan University**: undergraduate researcher since Feb 2025, working across ML security and distributed systems. I lead a team of undergraduate researchers building PyTorch training and data pipelines for adversarial ML on industrial control system data, and I also research distributed GPU training.

## Software projects

- [Repo](https://github.com/23alcor/batcave) · **Batcave**: self-hosted personal command center on Cloudflare Workers and D1, with tasks, habits, two-way Google Calendar sync and an AI assistant that works through tool calls.
- [Live](https://news.berlabs.dev) · **BerLabs**: AI newsletter platform. An hourly Python collector pulls from 20+ RSS sources, clusters related coverage and drafts summaries for a private editorial dashboard. Built on Next.js, Cloudflare Workers and D1.
- [Repo](https://github.com/Jfrancisjr21/xrpl-hackathon) · [Live](https://confiance.alcoberlabs.xyz) · **Confiance**: lending app on the XRP Ledger Devnet, built by a team of five in 36 hours at the AI & Fintech XRP Ledger Hackathon in NYC. I built the API and risk engine: OFAC sanctions screening, a score out of 100 and risk-based pricing.
- [Repo](https://github.com/23alcor/Usage-Token-Visualizer) · **Token Usage**: early macOS prototype that shows how much AI subscription capacity you have left before a big task. Rust collector with a React dashboard in a Tauri shell.
- [Repo](https://github.com/23alcor/capstone-ui) · [Live](https://capstone.alcoberlabs.xyz) · **capstone-ui**: interactive IEEE 13-bus feeder explorer for a HIL grid fault-detection capstone.

## Research background

- [Write-up](https://portfolio.alcoberlabs.xyz/research/hpc-gpu-training/) · **Distributed systems**: studied where multi-GPU training loses time across 803 measurements, from 1 to 64 GPUs, on Bridges-2 through NSF ACCESS. Spreading the same GPUs across more nodes can inflate communication cost 6.4×. Paper in draft.
- [Paper](https://ieeexplore.ieee.org/document/11393828) · [Write-up](https://portfolio.alcoberlabs.xyz/research/adversarial-ics/) · **ML security**: first-author paper at IEEE CCWC 2026 on defending industrial control system intrusion detection from adversarial attacks. A GAN purifier sits in front of a frozen detector, evaluated against FGSM, PGD, DeepFool, C&W and JSMA.

## Stack

Python, TypeScript, SQL · FastAPI, Next.js, React · Cloudflare Workers, Linux · PyTorch DDP, NCCL, CUDA, SLURM
