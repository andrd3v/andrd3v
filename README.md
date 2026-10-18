<h1 align="center">Ilya Andr</h1>

<p align="center">
Writing exploits and tooling in <b>C</b> and <b>Objective-C</b>. Middle iOS R&D Engineer @ Positive Technologies.
</p>

<p align="center">
  <a href="https://andrd3v.github.io"><img src="https://img.shields.io/badge/-Website-000000?style=for-the-badge&logo=githubpages&logoColor=white"></a>
  <a href="https://t.me/andrd3v"><img src="https://img.shields.io/badge/-Telegram-2CA5E0?style=for-the-badge&logo=telegram&logoColor=white"></a>
  <a href="https://x.com/andrd3v"><img src="https://img.shields.io/badge/-X-000000?style=for-the-badge&logo=x&logoColor=white"></a>
  <a href="https://www.linkedin.com/in/iandrd3v/"><img src="https://img.shields.io/badge/-LinkedIn-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white"></a>
  <a href="mailto:xqandr@yandex.ru"><img src="https://img.shields.io/badge/-Email-D44638?style=for-the-badge&logo=maildotru&logoColor=white"></a>
</p>

---

<details>
<summary><b>My CVEs</b> <a href="https://andrd3v.github.io/cves/">Full details here</a></summary>
<br>

| CVE | Component | CVSS | Impact |
|:----|:----------|:----:|:-------|
| CVE-2026-84625 | Sandbox Profiles | 9.1 | An app may be able to fingerprint the user |
| CVE-2026-43783 | DesktopServices | 7.8 | A malicious app may be able to gain root privileges |
| CVE-2026-84606 | iCloud | 7.5 | An app may be able to identify a user across reinstalls |
| CVE-2026-84623 | Power Management | 7.5 | An app may be able to fingerprint the device |
| CVE-2026-43792 | Safari | 6.5 | An app may be able to access sensitive user data |
| CVE-2026-43796 | Game Center | 5.5 | An app may be able to access sensitive user data |
| CVE-2026-43664 | Accessibility | 5.5 | An app may be able to access sensitive user data |
| CVE-2026-86905 | Authentication Services | 5.5 | An app may be able to delete credentials stored in Keychain |
| CVE-2026-86878 | Camera | 5.5 | An app may be able to access sensitive user data |
| CVE-2026-65345 | Storage | 5.5 | An app may be able to access user-sensitive data |
| CVE-2026-28882 | libxpc | 4.0 | An app may be able to enumerate installed apps and running processes |
| — | Spotlight | — | Acknowledged for assistance (xattr manipulation outside app sandbox) |

</details>

<details>
<summary><b>Projects</b></summary>
<br>

### Security Research

| Repository | Description |
|:-----------|:-----------|
| [CVE-2026-43783](https://github.com/andrd3v/CVE-2026-43783) | macOS < 26.6 LPE via DesktopServicesHelper XPC |
| [macOS-classroom-ransomware](https://github.com/andrd3v/macOS-classroom-ransomware) | Screen lock from sandboxed app via loginwindow endpoint leak |
| [dcdev](https://github.com/andrd3v/dcdev) | Full reverse engineering of Apple DeviceCheck token generation |
| [tfp_and_pft_detect](https://github.com/andrd3v/tfp_and_pft_detect) | Detecting task_for_pid & pid_for_task via CS_INVALID_ALLOWED |
| [touchbarHUD](https://github.com/andrd3v/touchbarHUD) | Touch Bar debug HUD via unauthenticated XPC service |
| [receipt_parser](https://github.com/andrd3v/receipt_parser) | iOS App Store PKCS7 receipt parser |

### Low-Level Tooling

| Repository | Description |
|:-----------|:-----------|
| [mem](https://github.com/andrd3v/mem) | Cross-process memory read/write for iOS & macOS |
| [remote_call](https://github.com/andrd3v/remote_call) | Cross-process function calls on arm64 via thread_set_state |
| [injector](https://github.com/andrd3v/injector) | dylib injection via remote_call + dlopen, no shellcode |
| [titanium](https://github.com/andrd3v/titanium) | In-place tweak injection with CoreTrust bypass & opainject |
| [IL2Cpp-Dictionary](https://github.com/andrd3v/IL2Cpp-Dictionary) | IL2CPP Dictionary & monoArray for external memory access |

### Game Modding

| Repository | Description |
|:-----------|:-----------|
| [Excalibur_v.3.0](https://github.com/andrd3v/Excalibur_v.3.0) | iOS ImGui HUD overlay (latest) |
| [Excalibur_v.2.0](https://github.com/andrd3v/Excalibur_v.2.0) | Excalibur v2 |
| [Excalibur](https://github.com/andrd3v/Excalibur) | Excalibur v1 |
| [cops](https://github.com/andrd3v/cops) | Critical Ops external |
| [cops_archive](https://github.com/andrd3v/cops_archive) | Critical Ops archive |
| [so2_ex](https://github.com/andrd3v/so2_ex) | SO2 external (TrollStore) |
| [so2](https://github.com/andrd3v/so2) | SO2 tweak |
| [mobile_legend](https://github.com/andrd3v/mobile_legend) | Mobile Legends |

### macOS Apps

| Repository | Description |
|:-----------|:-----------|
| [Melatonin](https://github.com/andrd3v/Melatonin) | Fix overnight battery drain |
| [FileWatcher](https://github.com/andrd3v/FileWatcher) | XPC daemon + client for Desktop file monitoring |

</details>
