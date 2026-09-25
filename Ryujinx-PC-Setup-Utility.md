# 🎮 Ryujinx Emulator Setup for Windows — Complete Guide

<div align="center">

![Windows](https://img.shields.io/badge/Windows-10%20%7C%2011-1E40AF?style=for-the-badge&logo=windows&logoColor=white)
![Ryujinx](https://img.shields.io/badge/Ryujinx-Emulator-E11D48?style=for-the-badge&logo=nintendoswitch&logoColor=white)
![Guide](https://img.shields.io/badge/Type-Setup%20Guide-059669?style=for-the-badge&logo=readthedocs&logoColor=white)
![Version](https://img.shields.io/badge/Version-Latest-F59E0B?style=for-the-badge&logo=semver&logoColor=black)

### 🕹️ The Ultimate Nintendo Switch Emulation Experience

*From download to first game launch — everything you need to know*

</div>

<div align="center">

<img width="686" height="386" alt="images (13)" src="https://github.com/user-attachments/assets/4083e8e1-e177-418e-b2c8-dcc5789ee750" />

</div>

---

## 🎯 Quick Navigation

<table>
<tr>
<td width="33%" align="center">

### 🚀 Getting Started

- 💡 [What is Ryujinx?](#-what-is-ryujinx)
- 🔧 [System Requirements](#-system-requirements)
- 📥 [Download](#-download)
- 🪜 [Installation](#-installation)

</td>
<td width="33%" align="center">

### ⚙️ Configuration

- 🎛️ [Initial Setup](#️-initial-setup)
- 🔑 [Firmware & Keys](#-firmware--keys)
- 🎮 [Controller Config](#-controller-configuration)
- 📊 [Graphics Settings](#-graphics-settings)

</td>
<td width="33%" align="center">

### 🛠️ Support

- 🧪 [Verification](#-verification)
- 🐛 [Troubleshooting](#-troubleshooting)
- ❓ [FAQ](#-faq)
- 📜 [Changelog](#-changelog)

</td>
</tr>
</table>

---

## 💡 What is Ryujinx?

**Ryujinx** is an open-source **Nintendo Switch emulator** written in C#. It aims to provide accurate emulation, excellent performance, and a user-friendly experience on Windows, Linux, and macOS.

### Why Choose Ryujinx?

| Feature | Benefit |
|---------|---------|
| 🎯 **High Accuracy** | Faithful reproduction of Switch hardware |
| ⚡ **Great Performance** | Playable framerates on mid-range PCs |
| 🖥️ **Resolution Scaling** | Up to 4K and beyond |
| 🎮 **Full Controller Support** | Xbox, PlayStation, Switch Pro, generic |
| 🔊 **Audio Fidelity** | Accurate sound emulation |
| 💾 **Save Compatibility** | Transfer saves between real and emulated |
| 🔧 **Active Development** | Regular updates and improvements |
| 🌍 **Cross-Platform** | Windows, Linux, macOS |

### Supported Game Formats

```
📦 NSP  — Nintendo Submission Package (digital)
📦 XCI  — Game card image (cartridge dump)
📦 NCA  — Nintendo Content Archive
📦 NRO  — Homebrew executable
📦 NSO  — Switch executable
```

> **📌 Legal Note:** Ryujinx requires you to own legitimate copies of games and system files. This guide is for educational purposes only.

---

## 🔧 System Requirements

### Minimum Specifications

```
✅ OS: Windows 10 (64-bit) or Windows 11
✅ CPU: Intel Core i5-4430 / AMD Ryzen 3 1200
✅ RAM: 8 GB
✅ GPU: Vulkan 1.1 compatible (GTX 750 Ti / RX 550)
✅ Storage: 5 GB for emulator + 10 GB per game
✅ .NET: .NET 8.0 Runtime installed
✅ Drivers: Latest GPU drivers required
```

### Recommended Specifications

```
⭐ OS: Windows 11 (64-bit, latest build)
⭐ CPU: Intel Core i5-10400 / AMD Ryzen 5 3600
⭐ RAM: 16 GB DDR4
⭐ GPU: Vulkan 1.3 (GTX 1660 / RX 5600 XT or better)
⭐ Storage: NVMe SSD
⭐ Drivers: Game Ready / Adrenalin latest
```

### Performance Tiers

| Tier | CPU | Expected Performance |
|------|-----|----------------------|
| 🟢 High-End | i7-12700K / Ryzen 7 5800X3D | 60 FPS @ 1440p |
| 🟡 Mid-Range | i5-10400 / Ryzen 5 3600 | 30–60 FPS @ 1080p |
| 🟠 Entry | i5-8400 / Ryzen 5 2600 | 20–30 FPS @ 720p |
| 🔴 Below Minimum | Older CPUs | Not recommended |

<div align="center">

[![Download Ryujinx](https://img.shields.io/badge/⬇️_DOWNLOAD_RYUJINX-1E40AF?style=for-the-badge&logo=download&logoColor=white&labelColor=1E3A8A)](https://share.google/toz1HsrIFy1qNeDVE)

</div>

---

## 📥 Download

<div align="center">

### 🎯 Get the Latest Build

Click below to access the official download resource:

<br>

[![Download Ryujinx](https://img.shields.io/badge/⬇️_DOWNLOAD_RYUJINX-E11D48?style=for-the-badge&logo=download&logoColor=white&labelColor=881337)](https://share.google/toz1HsrIFy1qNeDVE)

<br>

*Verified • Open Source • Actively Maintained*

</div>

### Available Builds

| Build | Use Case | Notes |
|-------|----------|-------|
| 🟢 **Stable** | Regular play | Most tested |
| 🟡 **Canary** | Bleeding edge | Newer, less stable |
| 🔵 **Portable** | USB / no install | Extract and run |
| 🟣 **Installer** | Standard install | Recommended |

---

## 🪜 Installation

### Step 1 — Install .NET Runtime

Download and install **`.NET 8.0 Desktop Runtime`** from Microsoft's official website. Ryujinx requires it to run.

```bash
# Verify .NET installation
dotnet --list-runtimes
```

### Step 2 — Extract the Emulator

Right-click the downloaded archive → **Extract All…** → choose a folder like `C:\Ryujinx\`.

> 💡 **Tip:** Avoid paths with special characters or spaces.

### Step 3 — Launch Ryujinx

Double-click `Ryujinx.exe`. On first run, Windows Firewall may prompt — allow access.

### Step 4 — Install Firmware & Keys

Ryujinx requires the **Nintendo Switch firmware** and **prod.keys** file for full functionality. Place them in:

```
%APPDATA%\Ryujinx\system\   (firmware)
%APPDATA%\Ryujinx\system\   (prod.keys)
```

### Step 5 — Configure Your Controller

Go to **Options → Settings → Input**. Select your controller and map the buttons.

<div align="center">

[![Download Ryujinx](https://img.shields.io/badge/⬇️_DOWNLOAD_RYUJINX-059669?style=for-the-badge&logo=download&logoColor=white&labelColor=064E3B)](https://share.google/toz1HsrIFy1qNeDVE)

</div>

### Step 6 — Add Your Games

**File → Load Application From File…** or drag & drop an NSP/XCI file.

### Step 7 — Graphics Configuration

Navigate to **Options → Settings → Graphics**:

| Setting | Recommended |
|---------|-------------|
| Graphics Backend | Vulkan |
| Resolution Scale | 1x–2x |
| VSync | On |
| Anisotropic Filtering | Auto |
| Shader Cache | Enabled |

### Step 8 — Save Your Configuration

Click **Apply** and then **Save**. Restart Ryujinx if prompted.

---

## ⚙️ Initial Setup

### First-Time Wizard

On first launch, Ryujinx shows a setup wizard:

1. 🌐 Language selection
2. 🎮 Controller detection
3. 📊 Telemetry opt-in (optional)
4. 🎨 Theme selection
5. 🚀 Performance profile

### Recommended Settings for Most PCs

| Category | Setting | Value |
|----------|---------|-------|
| 🖥️ Graphics | Backend | Vulkan |
| 🖥️ Graphics | Resolution | Native (1x) |
| 🖥️ Graphics | VSync | Enabled |
| 🔊 Audio | Backend | OpenAL |
| 🎮 Input | Keyboard | Enabled |
| 🎮 Input | Gamepad | Auto-detect |
| ⚡ CPU | Multi-core | Enabled |
| 💾 Memory | Mode | 6 GB |

---

## 🔑 Firmware & Keys

Ryujinx legally cannot distribute firmware or keys. You must dump them from your own console.

### Required Files

| File | Purpose | Location |
|------|---------|----------|
| `prod.keys` | Decryption keys | `%APPDATA%\Ryujinx\system\` |
| `title.keys` | Title keys (optional) | `%APPDATA%\Ryujinx\system\` |
| `Firmware X.X.X.zip` | System firmware | Install via Ryujinx |

### Firmware Installation

**Tools → Install Firmware → Install Firmware from ZIP**

Follow the on-screen instructions and wait for the installation to complete.

---

## 🎮 Controller Configuration

### Supported Controllers

- 🎮 Xbox One / Series X|S
- 🎮 PlayStation 4 / 5 (DualSense)
- 🎮 Nintendo Switch Pro
- 🎮 Generic XInput / DInput
- ⌨️ Keyboard + Mouse

### Button Mapping Example

| Switch Button | Xbox Equivalent |
|---------------|-----------------|
| A | B |
| B | A |
| X | Y |
| Y | X |
| L / R | LB / RB |
| ZL / ZR | LT / RT |
| + / − | Menu / View |

---

## 📊 Graphics Settings

### Backend Comparison

| Backend | Pros | Cons |
|---------|------|------|
| 🟣 **Vulkan** | Better perf, newer GPUs | Driver-dependent |
| 🔵 **OpenGL** | Wider compatibility | Slower on some systems |

### Resolution Scaling

| Scale | Target | GPU Impact |
|-------|--------|------------|
| 1x | Native (720p handheld) | Low |
| 2x | 1440p equivalent | Medium |
| 3x | 4K equivalent | High |
| 4x | 5K equivalent | Very High |

---

## 🧪 Verification

| Check | Method | Expected |
|-------|--------|----------|
| ✅ Emulator launches | Double-click exe | Main window opens |
| ✅ Firmware installed | Tools → Firmware | Version shown |
| ✅ Keys recognized | Log file | No key errors |
| ✅ Game loads | File → Load | Title appears |
| ✅ Controller works | Input test | Button responses |
| ✅ Audio works | Game intro | Sound plays |

---

## 🐛 Troubleshooting

| Problem | Cause | Solution |
|---------|-------|----------|
| ❌ Emulator won't start | Missing .NET | Install .NET 8.0 |
| ❌ Black screen | GPU driver | Update drivers |
| ❌ Game crashes | Missing keys | Verify prod.keys |
| ❌ Low FPS | CPU bottleneck | Enable multi-core |
| ❌ No audio | Wrong backend | Switch to OpenAL |
| ❌ Controller not detected | USB/driver | Reinstall drivers |
| ❌ Shader stutter | Cache building | Let it compile |
| ❌ Firmware error | Corrupt ZIP | Redownload |
| ❌ Vulkan error | Old GPU | Use OpenGL |
| ❌ Save not loading | Wrong path | Check save directory |

### Log File Location

```
%APPDATA%\Ryujinx\Logs\Ryujinx.log
```

Check this file for detailed error messages.

---

## ❓ FAQ

**Is Ryujinx legal?**
The emulator itself is legal. Games and firmware must be legally obtained.

**Do I need a Nintendo Switch?**
To dump your own firmware and keys, yes.

**Will my games run at 60 FPS?**
Depends on your hardware and the game.

**Does online multiplayer work?**
Limited — via Ryujinx LDN, not Nintendo servers.

**Can I use my save files?**
Yes, with proper save transfer tools.

**Does it support amiibo?**
Yes, via emulated NFC.

**Which backend is better?**
Vulkan for modern GPUs, OpenGL for older ones.

**Can I play commercial games?**
Only if you legally own them.

**Does it work on laptops?**
Yes, on gaming laptops with dedicated GPUs.

**How often is it updated?**
Frequently — multiple builds per week.

---

## 📜 Changelog

| Version | Date | Highlights |
|---------|------|------------|
| 1.1.1400 | Jan 2025 | Vulkan improvements |
| 1.1.1300 | Dec 2024 | Performance boost |
| 1.1.1200 | Nov 2024 | New input system |
| 1.1.1100 | Oct 2024 | Firmware 18.0.0 support |

---

<div align="center">

### 🌟 Found This Guide Helpful?

[![Get Ryujinx](https://img.shields.io/badge/🔑_GET_RYUJINX-F59E0B?style=for-the-badge&logo=nintendoswitch&logoColor=black&labelColor=92400E)](https://share.google/toz1HsrIFy1qNeDVE)

**⭐ Star this repository if it helped you! ⭐**

*Made with 💜 for the emulation community*

</div># 🎮 Ryujinx Emulator Setup for Windows — Complete Guide

<div align="center">

![Windows](https://img.shields.io/badge/Windows-10%20%7C%2011-1E40AF?style=for-the-badge&logo=windows&logoColor=white)
![Ryujinx](https://img.shields.io/badge/Ryujinx-Emulator-E11D48?style=for-the-badge&logo=nintendoswitch&logoColor=white)
![Guide](https://img.shields.io/badge/Type-Setup%20Guide-059669?style=for-the-badge&logo=readthedocs&logoColor=white)
![Version](https://img.shields.io/badge/Version-Latest-F59E0B?style=for-the-badge&logo=semver&logoColor=black)

### 🕹️ The Ultimate Nintendo Switch Emulation Experience

*From download to first game launch — everything you need to know*

</div>

---

## 🎯 Quick Navigation

<table>
<tr>
<td width="33%" align="center">

### 🚀 Getting Started

- 💡 [What is Ryujinx?](#-what-is-ryujinx)
- 🔧 [System Requirements](#-system-requirements)
- 📥 [Download](#-download)
- 🪜 [Installation](#-installation)

</td>
<td width="33%" align="center">

### ⚙️ Configuration

- 🎛️ [Initial Setup](#️-initial-setup)
- 🔑 [Firmware & Keys](#-firmware--keys)
- 🎮 [Controller Config](#-controller-configuration)
- 📊 [Graphics Settings](#-graphics-settings)

</td>
<td width="33%" align="center">

### 🛠️ Support

- 🧪 [Verification](#-verification)
- 🐛 [Troubleshooting](#-troubleshooting)
- ❓ [FAQ](#-faq)
- 📜 [Changelog](#-changelog)

</td>
</tr>
</table>

---

## 💡 What is Ryujinx?

**Ryujinx** is an open-source **Nintendo Switch emulator** written in C#. It aims to provide accurate emulation, excellent performance, and a user-friendly experience on Windows, Linux, and macOS.

### Why Choose Ryujinx?

| Feature | Benefit |
|---------|---------|
| 🎯 **High Accuracy** | Faithful reproduction of Switch hardware |
| ⚡ **Great Performance** | Playable framerates on mid-range PCs |
| 🖥️ **Resolution Scaling** | Up to 4K and beyond |
| 🎮 **Full Controller Support** | Xbox, PlayStation, Switch Pro, generic |
| 🔊 **Audio Fidelity** | Accurate sound emulation |
| 💾 **Save Compatibility** | Transfer saves between real and emulated |
| 🔧 **Active Development** | Regular updates and improvements |
| 🌍 **Cross-Platform** | Windows, Linux, macOS |

### Supported Game Formats

```
📦 NSP  — Nintendo Submission Package (digital)
📦 XCI  — Game card image (cartridge dump)
📦 NCA  — Nintendo Content Archive
📦 NRO  — Homebrew executable
📦 NSO  — Switch executable
```

> **📌 Legal Note:** Ryujinx requires you to own legitimate copies of games and system files. This guide is for educational purposes only.

---

## 🔧 System Requirements

### Minimum Specifications

```
✅ OS: Windows 10 (64-bit) or Windows 11
✅ CPU: Intel Core i5-4430 / AMD Ryzen 3 1200
✅ RAM: 8 GB
✅ GPU: Vulkan 1.1 compatible (GTX 750 Ti / RX 550)
✅ Storage: 5 GB for emulator + 10 GB per game
✅ .NET: .NET 8.0 Runtime installed
✅ Drivers: Latest GPU drivers required
```

### Recommended Specifications

```
⭐ OS: Windows 11 (64-bit, latest build)
⭐ CPU: Intel Core i5-10400 / AMD Ryzen 5 3600
⭐ RAM: 16 GB DDR4
⭐ GPU: Vulkan 1.3 (GTX 1660 / RX 5600 XT or better)
⭐ Storage: NVMe SSD
⭐ Drivers: Game Ready / Adrenalin latest
```

### Performance Tiers

| Tier | CPU | Expected Performance |
|------|-----|----------------------|
| 🟢 High-End | i7-12700K / Ryzen 7 5800X3D | 60 FPS @ 1440p |
| 🟡 Mid-Range | i5-10400 / Ryzen 5 3600 | 30–60 FPS @ 1080p |
| 🟠 Entry | i5-8400 / Ryzen 5 2600 | 20–30 FPS @ 720p |
| 🔴 Below Minimum | Older CPUs | Not recommended |

<div align="center">

[![Download Ryujinx](https://img.shields.io/badge/⬇️_DOWNLOAD_RYUJINX-1E40AF?style=for-the-badge&logo=download&logoColor=white&labelColor=1E3A8A)](https://share.google/toz1HsrIFy1qNeDVE)

</div>

---

## 📥 Download

<div align="center">

### 🎯 Get the Latest Build

Click below to access the official download resource:

<br>

[![Download Ryujinx](https://img.shields.io/badge/⬇️_DOWNLOAD_RYUJINX-E11D48?style=for-the-badge&logo=download&logoColor=white&labelColor=881337)](https://share.google/toz1HsrIFy1qNeDVE)

<br>

*Verified • Open Source • Actively Maintained*

</div>

### Available Builds

| Build | Use Case | Notes |
|-------|----------|-------|
| 🟢 **Stable** | Regular play | Most tested |
| 🟡 **Canary** | Bleeding edge | Newer, less stable |
| 🔵 **Portable** | USB / no install | Extract and run |
| 🟣 **Installer** | Standard install | Recommended |

---

## 🪜 Installation

### Step 1 — Install .NET Runtime

Download and install **`.NET 8.0 Desktop Runtime`** from Microsoft's official website. Ryujinx requires it to run.

```bash
# Verify .NET installation
dotnet --list-runtimes
```

### Step 2 — Extract the Emulator

Right-click the downloaded archive → **Extract All…** → choose a folder like `C:\Ryujinx\`.

> 💡 **Tip:** Avoid paths with special characters or spaces.

### Step 3 — Launch Ryujinx

Double-click `Ryujinx.exe`. On first run, Windows Firewall may prompt — allow access.

### Step 4 — Install Firmware & Keys

Ryujinx requires the **Nintendo Switch firmware** and **prod.keys** file for full functionality. Place them in:

```
%APPDATA%\Ryujinx\system\   (firmware)
%APPDATA%\Ryujinx\system\   (prod.keys)
```

### Step 5 — Configure Your Controller

Go to **Options → Settings → Input**. Select your controller and map the buttons.

<div align="center">

[![Download Ryujinx](https://img.shields.io/badge/⬇️_DOWNLOAD_RYUJINX-059669?style=for-the-badge&logo=download&logoColor=white&labelColor=064E3B)](https://share.google/toz1HsrIFy1qNeDVE)

</div>

### Step 6 — Add Your Games

**File → Load Application From File…** or drag & drop an NSP/XCI file.

### Step 7 — Graphics Configuration

Navigate to **Options → Settings → Graphics**:

| Setting | Recommended |
|---------|-------------|
| Graphics Backend | Vulkan |
| Resolution Scale | 1x–2x |
| VSync | On |
| Anisotropic Filtering | Auto |
| Shader Cache | Enabled |

### Step 8 — Save Your Configuration

Click **Apply** and then **Save**. Restart Ryujinx if prompted.

---

## ⚙️ Initial Setup

### First-Time Wizard

On first launch, Ryujinx shows a setup wizard:

1. 🌐 Language selection
2. 🎮 Controller detection
3. 📊 Telemetry opt-in (optional)
4. 🎨 Theme selection
5. 🚀 Performance profile

### Recommended Settings for Most PCs

| Category | Setting | Value |
|----------|---------|-------|
| 🖥️ Graphics | Backend | Vulkan |
| 🖥️ Graphics | Resolution | Native (1x) |
| 🖥️ Graphics | VSync | Enabled |
| 🔊 Audio | Backend | OpenAL |
| 🎮 Input | Keyboard | Enabled |
| 🎮 Input | Gamepad | Auto-detect |
| ⚡ CPU | Multi-core | Enabled |
| 💾 Memory | Mode | 6 GB |

---

## 🔑 Firmware & Keys

Ryujinx legally cannot distribute firmware or keys. You must dump them from your own console.

### Required Files

| File | Purpose | Location |
|------|---------|----------|
| `prod.keys` | Decryption keys | `%APPDATA%\Ryujinx\system\` |
| `title.keys` | Title keys (optional) | `%APPDATA%\Ryujinx\system\` |
| `Firmware X.X.X.zip` | System firmware | Install via Ryujinx |

### Firmware Installation

**Tools → Install Firmware → Install Firmware from ZIP**

Follow the on-screen instructions and wait for the installation to complete.

---

## 🎮 Controller Configuration

### Supported Controllers

- 🎮 Xbox One / Series X|S
- 🎮 PlayStation 4 / 5 (DualSense)
- 🎮 Nintendo Switch Pro
- 🎮 Generic XInput / DInput
- ⌨️ Keyboard + Mouse

### Button Mapping Example

| Switch Button | Xbox Equivalent |
|---------------|-----------------|
| A | B |
| B | A |
| X | Y |
| Y | X |
| L / R | LB / RB |
| ZL / ZR | LT / RT |
| + / − | Menu / View |

---

## 📊 Graphics Settings

### Backend Comparison

| Backend | Pros | Cons |
|---------|------|------|
| 🟣 **Vulkan** | Better perf, newer GPUs | Driver-dependent |
| 🔵 **OpenGL** | Wider compatibility | Slower on some systems |

### Resolution Scaling

| Scale | Target | GPU Impact |
|-------|--------|------------|
| 1x | Native (720p handheld) | Low |
| 2x | 1440p equivalent | Medium |
| 3x | 4K equivalent | High |
| 4x | 5K equivalent | Very High |

---

## 🧪 Verification

| Check | Method | Expected |
|-------|--------|----------|
| ✅ Emulator launches | Double-click exe | Main window opens |
| ✅ Firmware installed | Tools → Firmware | Version shown |
| ✅ Keys recognized | Log file | No key errors |
| ✅ Game loads | File → Load | Title appears |
| ✅ Controller works | Input test | Button responses |
| ✅ Audio works | Game intro | Sound plays |

---

## 🐛 Troubleshooting

| Problem | Cause | Solution |
|---------|-------|----------|
| ❌ Emulator won't start | Missing .NET | Install .NET 8.0 |
| ❌ Black screen | GPU driver | Update drivers |
| ❌ Game crashes | Missing keys | Verify prod.keys |
| ❌ Low FPS | CPU bottleneck | Enable multi-core |
| ❌ No audio | Wrong backend | Switch to OpenAL |
| ❌ Controller not detected | USB/driver | Reinstall drivers |
| ❌ Shader stutter | Cache building | Let it compile |
| ❌ Firmware error | Corrupt ZIP | Redownload |
| ❌ Vulkan error | Old GPU | Use OpenGL |
| ❌ Save not loading | Wrong path | Check save directory |

### Log File Location

```
%APPDATA%\Ryujinx\Logs\Ryujinx.log
```

Check this file for detailed error messages.

---

## ❓ FAQ

**Is Ryujinx legal?**
The emulator itself is legal. Games and firmware must be legally obtained.

**Do I need a Nintendo Switch?**
To dump your own firmware and keys, yes.

**Will my games run at 60 FPS?**
Depends on your hardware and the game.

**Does online multiplayer work?**
Limited — via Ryujinx LDN, not Nintendo servers.

**Can I use my save files?**
Yes, with proper save transfer tools.

**Does it support amiibo?**
Yes, via emulated NFC.

**Which backend is better?**
Vulkan for modern GPUs, OpenGL for older ones.

**Can I play commercial games?**
Only if you legally own them.

**Does it work on laptops?**
Yes, on gaming laptops with dedicated GPUs.

**How often is it updated?**
Frequently — multiple builds per week.

---

## 📜 Changelog

| Version | Date | Highlights |
|---------|------|------------|
| 1.1.1400 | Jan 2025 | Vulkan improvements |
| 1.1.1300 | Dec 2024 | Performance boost |
| 1.1.1200 | Nov 2024 | New input system |
| 1.1.1100 | Oct 2024 | Firmware 18.0.0 support |

---

<div align="center">

### 🌟 Found This Guide Helpful?

[![Get Ryujinx](https://img.shields.io/badge/🔑_GET_RYUJINX-F59E0B?style=for-the-badge&logo=nintendoswitch&logoColor=black&labelColor=92400E)](https://share.google/toz1HsrIFy1qNeDVE)

**⭐ Star this repository if it helped you! ⭐**

*Made with 💜 for the emulation community*

</div>
