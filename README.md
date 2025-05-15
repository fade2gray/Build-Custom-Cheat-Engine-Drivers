# Visual Studio 2019 Setup Guide for Building Custom Cheat Engine Drivers

## ✅ 1. Download Visual Studio 2019 Community Edition

### 📥 Primary Source (Microsoft's Older Downloads)
- Visit: https://visualstudio.microsoft.com/vs/older-downloads/
- Sign in with or create a free Microsoft account.
- Scroll to Visual Studio 2019 and choose Community Edition.

### 🔁 Alternative Mirrors (If the official link doesn’t work)
- TechSpot: https://www.techspot.com/downloads/7241-visual-studio-2019.html
- Internet Archive: https://archive.org/details/vs_community__e8aae2bc1239469a8cb34a7eeb742747

> Tip: Download the bootstrapper (installer), not the full ISO, unless you need offline installation.

---

## ✅ 2. Download Windows Driver Kit for Windows 10, version 2004 (WDK 10.0.19041.0)

- Visit: https://docs.microsoft.com/en-gb/windows-hardware/drivers/other-wdk-downloads/
- Scroll to "WDK for Windows 10, version 2004 (WDK 10.0.19041.0)"
- Download:
  - WDK setup installer
  - Windows 10 SDK (if prompted)

> Note: Ensure SDK and WDK versions match (10.0.19041.0) for compatibility.

---

## ✅ 3. Download `VS2019_setup.vsconfig`

- Download the configuration file to pre-select required components for building CE drivers.
- [Link to be provided]
- Save it to a convenient location.

---

## ✅ 4. Install Visual Studio 2019

- Run the installer downloaded in Step 1.
- Skip workload selection for now.
- Let the base installation complete.

---

## ✅ 5. Import `VS2019_setup.vsconfig`

1. Open Visual Studio Installer.
2. Click the three-dot menu (⋮) next to your installation.
3. Choose "Import configuration..."
4. Select the downloaded `VS2019_setup.vsconfig`.
5. Click "Install" or "Modify".
6. Wait for installation of all required components.

---

## ✅ 6. Install the Windows Driver Kit (WDK)

1. Run the WDK setup installer.
2. Accept license agreement.
3. Install WDK for version 10.0.19041.0.
4. Also install the Windows 10 SDK if prompted.

---

## ✅ (Optional) Final Step: Restart Your PC

- Reboot to ensure all components and settings are fully registered.
