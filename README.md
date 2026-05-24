# <img width="32" height="32" alt="ic" src="https://github.com/user-attachments/assets/bd576e3b-c712-4ae4-9a39-13a88fa83639" /> Ultimate Windows Unattended Installation & Customization Script [ENG]

Welcome to the ultimate, all-in-one solution for deploying a clean, optimized, and highly customized Windows installation. This configuration turns a standard Windows 10/11 Pro setup into a high-performance, distraction-free environment automatically.

Built using the `unattend.xml` framework and enhanced with deep PowerShell, VBScript, and Registry surgery, this script handles everything from bypassing hardware restrictions to fine-tuning the UI.

---

## <img width="30" height="30" alt="moon-stars" src="https://github.com/user-attachments/assets/9ac3361b-2726-425b-9cd9-4f611d35b3c7" /> Key Features

### <img width="30" height="30" alt="broom" src="https://github.com/user-attachments/assets/228b3c18-5e58-4e10-a119-3cdc9e4fba3c" /> **Aggressive Bloatware Removal**
*   **Apps:** Removes 3D Viewer, Bing Search, Clipchamp, Copilot, Cortana, Dev Home, Family, Feedback Hub, Maps, Office, OneDrive, Outlook, Paint, Skype, Solitaire, Teams, Weather, Xbox, and more.
*   **Capabilities:** Disables Fax & Scan, Internet Explorer, Math Input Panel, PowerShell ISE, Steps Recorder, Windows Media Player, and WordPad.
*   **Advanced Features:** Disables **Recall (AI Tracking)**, PowerShell V2, and the legacy Snipping Tool.
*   **Edge:** Patched to be fully uninstallable via Control Panel.

### <img width="30" height="30" alt="shield" src="https://github.com/user-attachments/assets/5c688a51-8a1b-4cda-8a4f-29f7664851ba" /> **Privacy & Performance Tweaks**
*   **Security:** Disables **SmartScreen**, **Fast Startup**, and **BitLocker Device Encryption** (prevents unwanted encryption on Home/Pro).
*   **Privacy:** Blocks telemetry, app suggestions (Consumer Features), Bing results in Search, and "News and Interests" (Widgets).
*   **Windows Update:** Disables automatic reboots. Includes a custom task that **dynamically moves "Active Hours"** to prevent updates during use.

### <img width="30" height="30" alt="palette" src="https://github.com/user-attachments/assets/1478ea54-2ef9-4346-995c-854aeeae4f79" /> **Visual & UI Customization**
*   **Theme:** System-wide **Dark Mode** with a accent color (`#8080FF`).
*   **Taskbar:** Left-aligned (Win11), Search hidden, Task View hidden, and "End Task" enabled in the context menu.
*   **Explorer:** Shows file extensions, launches to **"This PC"**, and restores the **Classic Context Menu** (Windows 10 style).
*   **Start Menu:** Completely empty of pins and advertisements.

### <img width="30" height="30" alt="gear-six" src="https://github.com/user-attachments/assets/33348173-6dac-48ea-a766-5f9c6856c77a" /> **Deployment Enhancements**
*   **Bypass Requirements:** Skips **TPM 2.0, Secure Boot, and RAM** checks (Ideal for older PCs and VMs).
*   **Drivers:** Automatically detects and installs **VMware Tools** or **VirtIO Guest Tools** if ISOs are attached.
*   **System:** Enables **Long File Paths**, sets PowerShell execution policy to `RemoteSigned`, and disables NTFS `LastAccess` timestamps for better SSD performance.

### <img width="30" height="30" alt="user" src="https://github.com/user-attachments/assets/8c27a820-b281-42ee-880d-f3d76b71cf78" /> **User & Account Setup**
*   **Account:** Creates a local Administrator named **"User"** with no password.
*   **Auto-Logon:** Automatically logs in once to finish setup.
*   **Default User Profile:** All registry tweaks are applied to the Default Hive, ensuring any new user created later has the same optimized settings.

---

## <img width="30" height="30" alt="book" src="https://github.com/user-attachments/assets/cd43411d-536e-49ab-a0ce-17931ec549af" /> How to Use

1.  Place the `autounattend.xml` in the **root** of your USB installation drive.
2.  Boot from the USB.
3.  The setup will bypass hardware checks and proceed without asking for a product key (uses Generic Pro Key).
4.  After the first boot, an interactive terminal will appear:
    *   It will display your system info.
    *   If Windows is not activated, it will ask if you want to run **MAS (Microsoft Activation Scripts)**.
    *   Press **[Y]** to activate or **[N]** to skip.

---
**Disclaimer:** *This configuration is optimized for power users. It disables several automated security layers to increase performance and control.*
