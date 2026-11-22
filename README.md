# 🧪 ScrewLab · lab

Benchmarks, scripts and configs from the [ScrewLab YouTube channel](https://www.youtube.com/@ScrewLab-in). Everything here was run on real hardware, and every number should be reproducible.

## Test bench

AMD RX 7800 XT 16 GB · Ryzen 5 7600X · see [`hardware.md`](hardware.md) for the full spec, driver and ROCm versions.

## What's in here

| Folder | What you'll find |
|---|---|
| [`benchmarks/llm`](benchmarks/llm) | Tokens/sec, VRAM use and quality notes for local LLMs |
| [`benchmarks/image-gen`](benchmarks/image-gen) | It/s and timings for SD, SDXL, Flux and friends |
| [`scripts`](scripts) | The exact scripts used to run the tests |
| [`dotfiles`](dotfiles) | Hyprland / CachyOS rice (coming soon) |
| [`homelab`](homelab) | Docker compose files and notes from homelab builds |
| [`raspberry-pi`](raspberry-pi) | Pi projects and setup notes |
| [`videos`](videos) | One folder per video, linked from its description |

## Video index

| # | Video | Folder |
|---|---|---|
| 001 | _first video goes here_ | [`videos/001-...`](videos) |

## Reproduce a result

Each benchmark file lists the model, quantization, backend version and the command used. Run the matching script from `scripts/`, then open an issue or PR if your numbers differ. Different cards are very welcome.

## License

Scripts are MIT. Results and notes are CC BY 4.0, so reuse them, just credit ScrewLab.
