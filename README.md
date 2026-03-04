# leaksnyak

Low-level Windows developer. Studying NT kernel internals, driver development, and native API mechanics.
Currently working with C / C++ and the WDK.

---

## Stack

![C](https://img.shields.io/badge/C-555?logo=c&logoColor=white)
![C++](https://img.shields.io/badge/C++-00599C?logo=cplusplus&logoColor=white)
![Windows](https://img.shields.io/badge/Windows%20Kernel-0078D4?logo=windows&logoColor=white)
![WDK](https://img.shields.io/badge/WDK-10.0-blue)
![WinDbg](https://img.shields.io/badge/WinDbg-333?logoColor=white)
![x64 ASM](https://img.shields.io/badge/x64%20ASM-lightgrey)

---

## Current projects

- **[ring0exec](https://github.com/leaksnyak-fake/ring0exec)** — kernel-mode process spawner via SSDT-resolved `NtCreateUserProcess`

---

## Focus areas

- NT kernel internals — SSDT, EPROCESS, KTHREAD, PEB, TEB, KPCR
- Kernel driver development (WDK) — DriverEntry, I/O dispatch, pool allocations
- Native API — undocumented `Nt*` / `Zw*` syscalls, syscall index resolution
- SSDT hooking and inline hooking techniques
- x64 Windows memory model — VAD trees, section objects, process address space
- Process and thread internals — `NtCreateUserProcess`, `PS_CREATE_INFO`, `PS_ATTRIBUTE_LIST`
- PE format internals — export directory, relocation, image mapping
- Malware research and analysis — behavioral analysis, anti-debug techniques, PEB manipulation
- Anti-analysis bypass — `BeingDebugged`, `NtGlobalFlag`, heap flags, timing checks
- Kernel debugging — WinDbg, live kernel debug, crash dump analysis (BSOD triage)

---

## GitHub Stats

![Stats](https://github-readme-stats.vercel.app/api?username=leaksnyak-fake&show_icons=true&theme=dark&hide_border=true&count_private=true)
![Langs](https://github-readme-stats.vercel.app/api/top-langs/?username=leaksnyak-fake&layout=compact&theme=dark&hide_border=true)
