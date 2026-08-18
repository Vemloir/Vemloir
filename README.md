### AI inference optimization engineer

Building inference engines from scratch — hand-written CUDA kernels, no PyTorch/TensorRT in the hot path.

#### [LumenLLM](https://github.com/Vemloir/LumenLLM)

**Rust + CUDA** inference engine for NVIDIA Blackwell (SM120), built to run 35B-class MoE models on a single **16 GB** GPU. Native NVFP4/FP8, hand-written kernels, explicit VRAM/RAM placement per component. On an RTX 5070 Ti it **beats vLLM** on decode and prefill for models that fit — and runs several vLLM OOMs on outright.

#### [Varmlen](https://github.com/Vemloir/Varmlen-Client-Linux)

Open-source **xray-core** VPN clients ([Linux](https://github.com/Vemloir/Varmlen-Client-Linux) · [Windows](https://github.com/Vemloir/Varmlen-Client-Windows) · [Android](https://github.com/Vemloir/Varmlen-Client-Android)) with per-app/per-domain split tunneling, built on Tauri 2 + SvelteKit.

#### [Aegis VPN](https://github.com/Vemloir/AegisVPN)

A VPN subscription service behind a Telegram bot ([@AegisEcoVPN_bot](https://t.me/AegisEcoVPN_bot)), running **Xray (VLESS + Reality)** across multiple VPS nodes. Each node long-polls a signed control endpoint over outbound HTTPS and reconciles state itself — no inbound control port on any exit server — with Telegram Stars payments and per-server access control.

<br>

<picture>
  <source media="(prefers-color-scheme: dark)" srcset="languages-dark.svg">
  <source media="(prefers-color-scheme: light)" srcset="languages-light.svg">
  <img src="languages-light.svg" alt="Top languages" width="860">
</picture>
