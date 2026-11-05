# Ralphael Alcober

Computer engineering senior at Manhattan University, working on distributed GPU training and ML security. Looking for new-grad and internship SWE roles for 2027.

## Research

- **Where distributed GPU training loses time** (paper in draft): 803 measurements across 10 neural network architectures, from 1 to 64 GPUs, on Bridges-2 through NSF ACCESS. Adding GPUs is nearly free, but spreading the same GPUs across more nodes isn't: placement alone can inflate communication cost 6.4×. A predictive model profiles a job on 8 GPUs and forecasts its training time up to 56 GPUs, with 16.4% mean error on architectures it never saw. Every measurement is gated at under 2% run-to-run variance. [Write-up](https://portfolio.berlabs.dev/research/hpc-gpu-training/)
- **Adversarially Robust Industrial Control Systems Intrusion Detection Using a Generative Purification Pipeline** (IEEE CCWC 2026, first author): a GAN purifier in front of a frozen intrusion detector, evaluated against FGSM, PGD, DeepFool, C&W and JSMA. [Paper](https://ieeexplore.ieee.org/document/11393828) · [Write-up](https://portfolio.berlabs.dev/research/adversarial-ics/)

## Work

- **Con Edison**: engineering co-op since Aug 2025. Rewrote a roughly 10-year-old tool whose database had been deprecated. It now screens ~30–40 returned units a week against live data for fault testing, and it's documented and packaged so anyone can run it without writing code.
- **Batcave**: self-hosted personal command center on Cloudflare Workers and D1, with tasks, habits, two-way Google Calendar sync and an AI assistant that works through tool calls. [Repo](https://github.com/23alcor/batcave)
- **BerLabs**: AI newsletter platform. An hourly Python collector pulls from 20+ RSS sources, clusters related coverage and drafts summaries for a private editorial dashboard. Built on Next.js, Cloudflare Workers and D1. [Live](https://news.berlabs.dev)
- **Confiance**: lending app on the XRP Ledger Devnet, built by a team of five in 36 hours at the AI & Fintech XRP Ledger Hackathon in NYC. I built the API and risk engine: OFAC sanctions screening, a score out of 100 and risk-based pricing. [Repo](https://github.com/Jfrancisjr21/xrpl-hackathon)
- **Token Usage**: early macOS prototype that shows how much AI subscription capacity you have left before a big task. Rust collector with a React dashboard in a Tauri shell. [Repo](https://github.com/23alcor/Usage-Token-Visualizer)
- **Notion Webhook Server**: FastAPI backend that reacts to Notion webhooks, summarizes notes with OpenAI and keeps task and calendar blocks current. Runs 24/7 on a Raspberry Pi under systemd, behind a Cloudflare Tunnel. [Repo](https://github.com/23alcor/Notion-Webhook-server)
- **Facial recognition door lock**: two-person course project. On-device OpenCV recognition on a Raspberry Pi drives a servo lock, with no cloud and no face data leaving the device. [Repo](https://github.com/23alcor/facial-recognition-door-lock)
- **capstone-ui**: interactive IEEE 13-bus feeder explorer for a HIL grid fault-detection capstone. [Repo](https://github.com/23alcor/capstone-ui)

## Stack

Python, TypeScript, SQL · PyTorch DDP, NCCL, CUDA, SLURM · FastAPI, Next.js, React · Cloudflare Workers, Linux

## Contact

[Portfolio](https://portfolio.berlabs.dev) · [LinkedIn](https://www.linkedin.com/in/ralphalc/)
