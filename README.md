# Windows On ARM stuff
A list of applications compatible on my Windows on ARM device. Tested on Surface Pro X, Microsoft SQ2 running Windows 11 - 23H2.

| Program/App  | Arch | Note |
| --- | --- | --- |
| **Browsers** | | |
| MS Edge | ARM64 |
| Firefox | ARM64 | Download from Mozilla, MS Store version is x86 only. Installer is x86 or maybe x64. |
| Firefox Developer Edition | ARM64 | Same as above |
| Chrome (NOT recommended) | x64 | Very slow since it's emulated |
| Chromium | ARM64 | |
| --- | --- | --- |
| **Productivity** |  |  |
| MS Office | ARM64EC | ClickToRun process is still x64 :\(|
| Drawboard PDF | ARM |  |
| PenBook | ARM | No longer getting updates? |
| PDF Ink | ARM | No longer getting updates? |
| LiquidText PDF | ARM64 |  |
| MS Whiteboard | PWA? | |
| MS Journal | ARM64 | |
| Tableau | x64 | Very slow in emulation |
| --- | --- | --- |
| **File management** |  |  |
| 7-Zip | ARM64 |  |
| NanaZip | ARM64 | Basically 7-Zip but better UI |
| OneDrive | ARM64 |  |
| --- | --- | --- |
| **Communications** |  |  |
| Discord | PWA is preferred. Emulation should work but is slow. |  |
| Skype | x64 | (Old UWP version was a 32-bit ARM app, only partially working now) |
| Zoom | ARM64 |  |
| MS Teams | ARM64 |  |
| --- | --- | --- |
| **Media consumption** |  |  |
| Google account sign in is broken for 3rd-party YouTube apps |
| ATube | ARM | Thumbnail broken. Supports modern standby. |
| myTube | ARM | Need to make your own free API key. Supports modern standby. |
| VLC | ARM64 | |
| Spotify | ARM64 |  |
| iTunes | x64 | New Apple Music app can't be installed from the store even though x64 emulation is available. |
| FluentCast Podcast | ARM |  |
| Most media apps should work. If not, browser version works. |  |  |
| --- | --- | --- |
| **System enhancement/Utilities** |  |  |
| PowerToys | ARM64 |  |
| Rufus | ARM64 |  |
| OpenVPN (GUI) | ARM64 |  |
| Energy Star X | ARM64 | Enables EcoQoS/Efficiency Mode for background applications |
| Character Map UWP | ARM64 |  |
| YubiKey Manager | x86 |  |
| --- | --- | --- |
| **Windows Subsystems & Virutalization** |  |  |
| Subsystem for Linux | ARM64 | https://github.com/MustardChef/WSABuilds |
| Subsystem for Android | ARM64 | Besides distros available on MS Store, you can also import your own. Rocky Linux 9 AArch64 works. |
| Hyper-V | ARM64 | Available to install, untested. |
| --- | --- | --- |
| **Development** |  |  |
| Visual Studio Code | ARM64 |  |
| Visual Studio (2022+) | ARM64 |  |
| Python 3.11+ | ARM64 |  |
| OpenJDK (Microsoft Build)[https://www.microsoft.com/openjdk] | ARM64 |  |
| DevToys | ARM64 |  |
| Git (Unofficial beta build)[https://github.com/dennisameling/git/releases] | ARM64 | Git Bash works but Windows Terminal profile is broken. Can fix manually. |
| PowerShell | ARM64 |  |
| Windows Terminal | ARM64 |  |
| --- | --- | --- |
| **Misc.** |  |  |
| Ambie | ARM64 |  |
|  |  |  |
|  |  |  |
|  |  |  |
|  |  |  |
| --- | --- | --- |
