```mermaid
%%{init: {'flowchart': {'nodeSpacing': 25, 'rankSpacing': 35}}}%%
graph TD;
AegisVPN[Aegis VPN] --> Varmlen[Varmlen]
Varmlen --> platforms
AegisVPN ~~~ LumenLLM[LumenLLM]

subgraph platforms[Platforms]
    direction LR
    VarmlenLinux[Linux]
    VarmlenWindows[Windows]
    VarmlenAndroid[Android]
end

click AegisVPN "https://github.com/Vemloir/AegisVPN" "Aegis VPN — VPN subscription service"
click Varmlen "https://github.com/Vemloir/Varmlen-Client-Linux" "Varmlen — xray-core client"
click VarmlenLinux "https://github.com/Vemloir/Varmlen-Client-Linux" "Linux"
click VarmlenWindows "https://github.com/Vemloir/Varmlen-Client-Windows" "Windows"
click VarmlenAndroid "https://github.com/Vemloir/Varmlen-Client-Android" "Android"
click LumenLLM "https://github.com/Vemloir/LumenLLM" "LumenLLM — Rust + CUDA inference engine"
```

#### [LumenLLM](https://github.com/Vemloir/LumenLLM)

**Rust + CUDA** inference engine for NVIDIA Blackwell (SM120), built to run 35B-class MoE models on a single **16 GB** GPU. Native NVFP4/FP8, hand-written kernels, explicit VRAM/RAM placement per component. On an RTX 5070 Ti it **beats vLLM** on decode and prefill for models that fit — and runs several vLLM OOMs on outright.

#### [Varmlen](https://github.com/Vemloir/Varmlen-Client-Linux)

Open-source **xray-core** VPN clients ([Linux](https://github.com/Vemloir/Varmlen-Client-Linux) · [Windows](https://github.com/Vemloir/Varmlen-Client-Windows) · [Android](https://github.com/Vemloir/Varmlen-Client-Android)) with per-app/per-domain split tunneling, built on Tauri 2 + SvelteKit.

#### [Aegis VPN](https://github.com/Vemloir/AegisVPN)

Production VPN subscription platform on **Xray (VLESS + Reality)** and **Hysteria2**, live at [aegisvpn.org](https://aegisvpn.org). Every node pulls signed config over outbound HTTPS and reconciles itself — **no inbound port open** on any exit server.

<br>

<picture>
  <source media="(prefers-color-scheme: dark)" srcset="languages-dark.svg">
  <source media="(prefers-color-scheme: light)" srcset="languages-light.svg">
  <img src="languages-light.svg" alt="Top languages" width="860">
</picture>
