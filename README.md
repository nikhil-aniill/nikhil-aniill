<!-- GitHub Profile README -->

# hey, i'm nikhil 👋

learning malware development on the side.
working through **maldev academy** (180 modules) and completing the Objectives in Rust.

not an expert. still figuring things out.

---

## what i'm building

![maldev-rs](https://img.shields.io/badge/maldev--rs-Rust-orange?style=flat-square&logo=rust)
![status](https://img.shields.io/badge/status-learning-yellow?style=flat-square)
![mde](https://img.shields.io/badge/tested%20against-MDE%20P2-5c2d91?style=flat-square&logo=microsoftdefender)

a Rust repo where i reimplement MDA techniques as i learn them.
each folder has the code + notes on what MDE detected vs missed.

[→ maldev-rs](https://github.com/nikhil-aniill/maldev-rs)

---

## progress through maldev academy

| area | modules | status |
|------|---------|--------|
| PE header parsing & string hashing | 47–48 | ✅ done 🔄 in progress |
| IAT hiding & API hashing | 49–56, 79 | 🔄 in progress |
| API hooking | 57–61 | ⬜ upcoming |
| Syscalls (Hell's Gate, HellsHall, indirect) | 62–68, 87–88 | ⬜ upcoming |
| Anti-analysis & anti-debug | 69–77, 124 | ⬜ upcoming |
| NTDLL unhooking | 82–86 | ⬜ upcoming |
| ETW bypass | 102–107 | ⬜ upcoming|
| AMSI bypass | 108–110 |⬜ upcoming |
| Process injection (APC, hollowing, stomping…) | 45–46, 118–135 | ⬜ upcoming |
| Sleep obfuscation (Ekko, Zilean, Foliage) | 143–146, 149 | ⬜ upcoming |
| C2 integration & BOFs | 112–113, 139–141 | ⬜ upcoming |
| Credential dumping | 160–168 | ⬜ upcoming |
| Persistence | 173–180 | ⬜ upcoming |

---

## stack

`Rust` `C` `C++` `Win32 API` `NT API` `Visual Studio 2022` `x64 Windows` `MDE P2`

---

## lab setup

- M365 Business Basic tenant with MDE P2 trial
- Windows 11 Enterprise VMs (onboarded, snapshotted)
- testing detections, hunting in advanced hunting, watching what fires vs what doesn't
- device group set to semi-approval so payloads survive long enough to observe

---

## notes

everything here is for authorized security research / learning.
i test against my own lab — not production, not anyone else's systems.

if something in my code is wrong or there's a better way to do it, open an issue.
i'm still learning and would genuinely appreciate the feedback.

---

<!-- GitHub stats -- update your username below -->
![GitHub Stats](https://github-readme-stats.vercel.app/api?username=nikhil-aniill&show_icons=true&theme=github_dark&hide_border=true&bg_color=0d1117)
