### Hi, I'm the founder of NorthNarrow 👋

**[NorthNarrow](https://github.com/northnarrow/northnarrow-new)** is an open-source **endpoint detection and response (EDR) agent for Linux**, written in Rust, with eBPF sensors and BPF-LSM enforcement in the kernel.

- **Everything stays on the host:** no telemetry, no vendor cloud. Every decision is made and explained on the machine.
- **It defends itself against root:** BPF-LSM refuses signals, ptrace, file tampering and foreign BPF programs outside a signed maintenance window.
- **Signed evidence:** every record goes into hash chains you can verify offline.
- **Verified in a lab you can rerun:** privileged test suites on 5 kernels (5.15 → 7.0) every night.

**Status:** the first alpha, [`v0.1.0-alpha`](https://github.com/northnarrow/northnarrow-new/releases), came out on 23 Nov 2026. It is **observe-only**: it records what it *would* block, so it's safe to try on a throwaway VM. It's self-assessed, and the [known limitations](https://github.com/northnarrow/northnarrow-new/blob/main/docs/operator/KNOWN_LIMITATIONS.md) are listed plainly.

**Since the alpha:** Rust 2024 and a new eBPF toolchain, 0 open Dependabot alerts, sensors that see every CPU on Linux 7.0, lighter sensors, and an OpenSSF Scorecard of 8.2. See [what's new](https://github.com/northnarrow/northnarrow-new#whats-new-since-the-alpha), [what we're working on now](https://github.com/northnarrow/northnarrow-new#working-on-now) and the [roadmap after the alpha](https://github.com/northnarrow/northnarrow-new/blob/main/ROADMAP.md#roadmap-after-v010-alpha).

**How it's built:** I'm a solo founder. I set the direction and make the decisions. The code is written with AI assistance (Claude Code), and every change gets an independent review and a lab test before it lands.

**Want to help?**
- 🧪 Try it with the [alpha tester guide](https://github.com/northnarrow/northnarrow-new/blob/main/docs/operator/ALPHA_TESTER_GUIDE.md) (about an hour, on a VM).
- 🌱 Pick a [good first issue](https://github.com/northnarrow/northnarrow-new/labels/good%20first%20issue). No Rust or eBPF knowledge needed.
- 🔒 Found a vulnerability? Please report it privately, as [SECURITY.md](https://github.com/northnarrow/northnarrow-new/blob/main/SECURITY.md) describes.

<sub>Architect&Claudie</sub>
