<div align="center">

# 🔥 RUST FPS BOOST

**Windows optimization toolkit for a smoother Rust gaming experience**

[![Windows 10](https://img.shields.io/badge/Windows-10-0078D6?style=flat-square&logo=windows&logoColor=white)](#)
[![Windows 11](https://img.shields.io/badge/Windows-11-0078D6?style=flat-square&logo=windows11&logoColor=white)](#)
[![PowerShell](https://img.shields.io/badge/PowerShell-5.1%2B-5391FE?style=flat-square&logo=powershell&logoColor=white)](#)
[![License](https://img.shields.io/badge/License-MIT-green?style=flat-square)](LICENSE)

</div>

---

## About

**Rust FPS Boost** is a lightweight Windows optimization project focused on reducing unnecessary background activity and keeping your PC responsive while playing Rust.

The project uses transparent PowerShell scripts so you can review every change before applying it.

---

## How to Use

- Download the project to your computer as a ZIP file.
- Extract the project to a separate folder.
- Make sure Windows 10 or Windows 11 is installed.
- Open the project folder and review the included files.
- Run RustMenu as Administrator.
- Restart your computer after completing the optimization.
- Launch Rust and test your FPS using the same graphics settings.

### Clone

```bash
git clone https://github.com/YOUR-USERNAME/rust-fps-boost.git
cd rust-fps-boost
```

### Run

```powershell
Set-ExecutionPolicy -Scope Process Bypass
.\scripts\optimize-windows.ps1
```

---

## Features

- ⚡ **Performance-focused setup** — reduces unnecessary system overhead.
- 🧹 **Temporary file cleanup** — removes user temporary files.
- 🎮 **Gaming-oriented configuration** — keeps the workflow focused on Rust.
- 🪟 **Windows 10 & 11** — designed for modern Windows PCs.
- 🔍 **Transparent scripts** — every PowerShell command can be inspected before execution.
- ↩️ **Reversible workflow** — system-level changes should always have a documented rollback path.

---

## Project Structure

```text
rust-fps-boost/
│
├── .github/
│   └── ISSUE_TEMPLATE/
│
├── assets/
│
├── scripts/
│   ├── cleanup.ps1
│   ├── optimize-windows.ps1
│   └── restore.ps1
│
├── .gitignore
├── LICENSE
└── README.md
```

---

## Performance Testing

For useful before/after results, keep the test conditions consistent.

| Metric | Before | After |
|---|---:|---:|
| Average FPS | — | — |
| 1% Low FPS | — | — |
| Frametime | — | — |
| RAM Usage | — | — |

### Suggested benchmark

```text
CPU:
GPU:
RAM:
Resolution:
Rust graphics preset:
GPU driver:

BEFORE
Average FPS:
1% Low:
Frametime:
RAM:

AFTER
Average FPS:
1% Low:
Frametime:
RAM:
```

Do not report invented or single-frame FPS numbers as guaranteed results.

---

## Recommended Rust Setup

For a consistent benchmark:

- Use the same resolution.
- Keep the same Rust graphics settings.
- Close downloads and unnecessary launchers.
- Disable software you are not using for recording or streaming.
- Repeat the test several times.
- Compare **average FPS** and **1% lows**, not only the highest number shown on screen.

---

## Restore

The included starter optimizer intentionally avoids aggressive permanent registry, boot or network changes.

Run:

```powershell
.\scripts\restore.ps1
```

If you add additional tweaks to the project, document their original values and rollback method in this section.

---

## System Requirements

| Requirement | Supported |
|---|---|
| Windows 10 | ✅ |
| Windows 11 | ✅ |
| PowerShell 5.1+ | ✅ |
| NVIDIA GPU | ✅ |
| AMD GPU | ✅ |
| Intel GPU | ✅ |
| Rust | ✅ |

---

## Safety

Always review system scripts before running them.

Create a restore point or backup important data before adding new Windows tweaks to the project.

This repository does **not** bypass anti-cheat, modify Rust files, or guarantee a specific performance increase.

---

## Contributing

Pull requests are welcome.

Before submitting a change:

1. Explain what the optimization changes.
2. Explain how it can be reverted.
3. Test it on a clean Windows installation when possible.
4. Avoid undocumented registry, boot, security or network modifications.

---

## License

This project is licensed under the **MIT License**.

See [LICENSE](LICENSE) for details.

---

<div align="center">

### 🔥 RUST FPS BOOST

**Clean setup. Transparent tweaks. Smoother gameplay.**

</div>
