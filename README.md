### AI inference optimization engineer

Building inference engines from scratch — hand-written CUDA kernels, no PyTorch/TensorRT in the hot path.

#### [LumenLLM](https://github.com/Vemloir/LumenLLM)

**Rust + CUDA** inference engine for NVIDIA Blackwell (SM120), built to run 35B-class MoE models on a single **16 GB** GPU. Native NVFP4/FP8, hand-written kernels, explicit VRAM/RAM placement per component. On an RTX 5070 Ti it **beats vLLM** on decode and prefill for models that fit — and runs several vLLM OOMs on outright.

#### [Varmlen](https://github.com/Vemloir/Varmlen-Client-Linux)

Open-source **xray-core** VPN clients ([Linux](https://github.com/Vemloir/Varmlen-Client-Linux) · [Windows](https://github.com/Vemloir/Varmlen-Client-Windows) · [Android](https://github.com/Vemloir/Varmlen-Client-Android)) with per-app/per-domain split tunneling, built on Tauri 2 + SvelteKit.

<br>

<picture>
  <source media="(prefers-color-scheme: dark)" srcset="https://github-readme-stats.vercel.app/api/top-langs/?username=Vemloir&layout=compact&hide_border=true&theme=github_dark&langs_count=6">
  <source media="(prefers-color-scheme: light)" srcset="https://github-readme-stats.vercel.app/api/top-langs/?username=Vemloir&layout=compact&hide_border=true&theme=default&langs_count=6">
  <img src="https://github-readme-stats.vercel.app/api/top-langs/?username=Vemloir&layout=compact&hide_border=true&langs_count=6" alt="Top languages" width="380">
</picture>
