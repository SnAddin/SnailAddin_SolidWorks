# Snail Addin

> A powerful export toolkit for SolidWorks.  
> One click to export your parts, assemblies, and drawings.

[![Latest Release](https://img.shields.io/github/v/release/YOUR_USERNAME/SnailAddin?style=flat-square)](https://github.com/YOUR_USERNAME/SnailAddin/releases/latest)
[![Downloads](https://img.shields.io/github/downloads/YOUR_USERNAME/SnailAddin/total?style=flat-square)](https://github.com/YOUR_USERNAME/SnailAddin/releases)
[![Platform](https://img.shields.io/badge/platform-Windows%2010%2F11%20x64-blue?style=flat-square)]()
[![SolidWorks](https://img.shields.io/badge/SolidWorks-2020%2B-red?style=flat-square)]()

---

## 📥 Download

**Latest version**: [v1.0.0.0](https://github.com/YOUR_USERNAME/SnailAddin/releases/latest)

| File | Size | Description |
|---|---|---|
| `SnailAddin_Setup_1.0.0.0.exe` | ~25 MB | Windows installer (64-bit) |


---

## ✨ Key Features

- **One-click export** to STP, IGS, X_T, PDF, DWG, and DXF
- **Batch export** from Excel/TXT lists, or scan open assemblies and folders
- **Smart duplicate handling** — auto adds suffixes when names conflict
- **Export report** — per-file status and timestamps after each batch
- **Seamless integration** — runs inside a dedicated SolidWorks tab

---

## 💻 System Requirements

| Item | Requirement |
|---|---|
| Operating System | Windows 10 / 11 (64-bit) |
| SolidWorks | 2020 or later (64-bit) |
| .NET Framework | 4.8 or later |
| Disk Space | ~50 MB |
| Internet | Required for license activation |

---

## 🚀 Installation

1. **Download** the latest `SnailAddin_Setup_x.x.x.x.exe` from the [Releases](https://github.com/YOUR_USERNAME/SnailAddin/releases/latest) page.
2. **Close SolidWorks** — all SolidWorks windows must be closed before installation.
3. **Run the installer** — double-click the `.exe` and follow the wizard.
   - If Windows shows a UAC prompt, click **Yes**.
   - If SmartScreen warns about an unknown publisher, click **More info** → **Run anyway**.
4. **Launch SolidWorks** — look for the **Snail Addin** tab in the CommandManager.

> See the full [Installation Guide](https://snaddin.com/docs/installation) for detailed steps and screenshots.

---

## 🔑 License Activation

### Free Edition
Works out of the box, no activation needed.  
Batch export limit: **27 files per task**.

### Pro Edition
After purchase, you will receive a license key by email.

1. Open SolidWorks → **Snail Addin** tab
2. Click **Like me**
3. Paste your license key (`SNL1-P-XXXX-XXXX-XXXX-XXXX`)
4. Click **Activate**

Your license is bound to **1 device**. To move it to another computer, click **Deactivate** first.

---

## 🆚 Free vs Pro

| Feature | Free | Pro |
|---|:---:|:---:|
| Export STP / IGS / X_T / PDF / DWG / DXF | ✅ | ✅ |
| Batch export limit per task | 27 files | 500 files |
| Scan assembly & drawing folders | ✅ | ✅ |
| Export report | ✅ | ✅ |
| Devices per license | — | 1 device |
| License validity | Free forever | 30 days |
| Price | **$0** | **$4.9** |

**Get Pro**: https://snaddin.com/buy

---

## ❓ FAQ

<details>
<summary><b>The Snail Addin tab doesn't appear in SolidWorks</b></summary>

**Cause**: The plugin was not registered, or SolidWorks was running during installation.

**Fix**:
1. Close SolidWorks completely
2. Run the installer again
3. Open SolidWorks

If it still doesn't appear, run the following in an **Administrator Command Prompt**:

"C:\Windows\Microsoft.NET\Framework64\v4.0.30319\regasm.exe" /codebase "C:\Program Files\SnailAddin\MainAddin.dll"

Then restart SolidWorks.

</details>

<details>
<summary><b>Installation fails with ".NET Framework 4.8 required"</b></summary>

Install .NET Framework 4.8 from Microsoft:  
https://dotnet.microsoft.com/download/dotnet-framework/net48

Restart your computer, then run the installer again.

</details>

<details>
<summary><b>Activation fails with "Network error"</b></summary>

1. Check your internet connection
2. Make sure `snaddin.com` is not blocked by a firewall or proxy
3. Try again

If the problem persists, contact support.

</details>

<details>
<summary><b>Activation fails with "Machine code mismatch"</b></summary>

The license is already bound to a different machine.

1. On the original machine, click **Deactivate** in the "Like me" window
2. Then activate on the new machine

If the original machine is unavailable, contact support.

</details>

<details>
<summary><b>"Unknown publisher" warning during installation</b></summary>

The installer is not code-signed yet.  
Click **More info** → **Run anyway**. This is safe.

</details>

---

## 🗑️ Uninstallation

1. Close SolidWorks
2. Open **Settings** → **Apps** → **Installed apps** (Windows 11)  
   or **Control Panel** → **Programs and Features** (Windows 10)
3. Find **Snail Addin** → click **Uninstall**

**Note**: Your license file (`%LOCALAPPDATA%\SnailAddin\license.dat`) is **not** removed on uninstall. Reinstalling will automatically restore your license.

To completely remove all traces:

%LOCALAPPDATA%\SnailAddin

Delete this folder manually.

---

## 📞 Support

- 🌐 **Website**: https://snaddin.com
- 📖 **Documentation**: https://snaddin.com/docs
- 📧 **Email**: support@snaddin.com
- 🐛 **Bug reports**: [Open an issue](https://github.com/YOUR_USERNAME/SnailAddin/issues)
- 💡 **Feature requests**: [Open an issue](https://github.com/YOUR_USERNAME/SnailAddin/issues)

When reporting a bug, please include:
- SolidWorks version (Help → About SolidWorks)
- Windows version
- A screenshot of the error
- The log file at `%LOCALAPPDATA%\SnailAddin\SnailAddin_Log.txt`

---

## 📝 Version History

### v1.0.0.0 — 2026-09-25
- 🎉 Initial release
- Support for exporting STP, IGS, X_T, PDF, DWG, DXF
- Batch export with scan and report
- 30-day Pro license with 1-device binding

---

## 📄 License

**Snail Addin** is commercial software.  
Copyright © 2026 Snaddin. All rights reserved.

This repository contains **only release binaries and documentation**.  
The source code is not publicly available.

See the [LICENSE](LICENSE) file for details.

---

## ⚠️ Disclaimer

This software is provided "as is", without warranty of any kind.  
Always back up your SolidWorks files before batch operations.
