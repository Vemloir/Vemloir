### AI inference optimization engineer

Building inference engines from scratch — hand-written CUDA kernels, no PyTorch/TensorRT in the hot path.

#### [LumenLLM](https://github.com/Vemloir/LumenLLM)

**Rust + CUDA** inference engine for NVIDIA Blackwell (SM120), built to run 35B-class MoE models on a single **16 GB** GPU. Native NVFP4/FP8, hand-written kernels, explicit VRAM/RAM placement per component. On an RTX 5070 Ti it **beats vLLM** on decode and prefill for models that fit — and runs several vLLM OOMs on outright.

#### [Varmlen](https://github.com/Vemloir/Varmlen-Client-Linux)

Open-source **xray-core** VPN clients ([Linux](https://github.com/Vemloir/Varmlen-Client-Linux) · [Windows](https://github.com/Vemloir/Varmlen-Client-Windows) · [Android](https://github.com/Vemloir/Varmlen-Client-Android)) with per-app/per-domain split tunneling, built on Tauri 2 + SvelteKit.

#### [Aegis VPN](https://github.com/Vemloir/AegisVPN)

A VPN subscription platform on **Xray (VLESS + Reality)**: a Telegram bot storefront with an inline admin panel ([@AegisEcoVPN_bot](https://t.me/AegisEcoVPN_bot)) plus a fleet of VPS nodes that each pull signed config snapshots over outbound HTTPS and reconcile state themselves — no inbound control port open on any exit server. Telegram Stars payments, per-server access control, multi-server subscriptions.

<br>

<picture>
  <source media="(prefers-color-scheme: dark)" srcset="languages-dark.svg">
  <source media="(prefers-color-scheme: light)" srcset="languages-light.svg">
  <img src="languages-light.svg" alt="Top languages" width="860">
</picture>
