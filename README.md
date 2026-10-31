```text
beacon> whoami

  operator    António  //  0xBerk
  location    Portugal
  role        red team  ·  offensive development
  focus       Active Directory  ·  Windows internals
              custom offensive tooling

beacon> certs

  [+] CPTS     Hack The Box            completed
  [+] CRTO     Zero-Point Security     completed
  [~] ODPC     offensive development   in progress
  [~] ARTOC    advanced red team       in progress
```

<p>
<img src="https://img.shields.io/badge/CPTS-certified-9FEF00?style=flat-square&labelColor=111111"/>
<img src="https://img.shields.io/badge/CRTO-certified-cda24c?style=flat-square&labelColor=111111"/>
<img src="https://img.shields.io/badge/ODPC-in_progress-666666?style=flat-square&labelColor=111111"/>
<img src="https://img.shields.io/badge/ARTOC-in_progress-666666?style=flat-square&labelColor=111111"/>
</p>

I work on the offensive side: compromising Active Directory environments and writing the tooling to do it quietly. I care more about understanding why an attack path works than about reaching the flag.

## Active Directory & red team operations

- Kerberos abuse: Kerberoasting, AS-REP roasting, unconstrained / constrained / resource-based delegation
- AD CS abuse with Certipy (ESC1–ESC8)
- ACL abuse and attack path analysis with BloodHound
- Lateral movement, pivoting and tunneling
- C2 operations with Cobalt Strike, with attention to OPSEC

## Offensive development

Small PoCs in C/C++, each one written to understand a technique from the ground up rather than reuse someone else's implementation.

| Area | Projects |
|---|---|
| Process injection | [Classic](https://github.com/0xBerk0/classic-process-injection) · [Early Bird APC](https://github.com/0xBerk0/process-injection-early-bird) · [Process Hollowing](https://github.com/0xBerk0/process-injection-process-hollowing) · [Payload from resources](https://github.com/0xBerk0/process-injection-using-resources) |
| Syscalls & EDR evasion | [Indirect syscalls](https://github.com/0xBerk0/indirect-syscalls) · [Halo's Gate](https://github.com/0xBerk0/HalosGate-research) · [Inline hook finder](https://github.com/0xBerk0/windows-api-hook-finder) |
| PE & PEB internals | [PEB walker](https://github.com/0xBerk0/peb-walker) · [EAT walker](https://github.com/0xBerk0/export-address-table-walker) · [API hashing](https://github.com/0xBerk0/dynamic-imports-with-hashing) · [PE parser](https://github.com/0xBerk0/pe-parser) |

## Stack

**Languages** — `C` `C++` `C#` `Python` `PowerShell` `Go` `Bash`<br>
**Active Directory** — `BloodHound` `Impacket` `Rubeus` `Certipy` `Mimikatz` `PowerView`<br>
**C2** — `Cobalt Strike`<br>
**Pentest** — `Nmap` `Burp Suite` `Metasploit` `SQLMap` `ffuf`

## Latest write-ups

Machines and attack chains documented end to end, dead ends included.

<!-- BLOG-POST-LIST:START -->- [Certified Htb Writeup](https://0xberk0.github.io/posts/certified-htb-writeup/) — Aug 2026 
- [HackTheBox — Monteverde](https://0xberk0.github.io/posts/monteverde-writeup/) — Aug 2026 
- [HackTheBox — Blackfield](https://0xberk0.github.io/posts/blackfield-writeup/) — Jun 2026 
- [HackTheBox — Administrator](https://0xberk0.github.io/posts/Administrator-htb-writeup/) — Jun 2026 
- [HTB Support Writeup](https://0xberk0.github.io/posts/support-htb-writeup/) — Jun 2026 
<!-- BLOG-POST-LIST:END -->

All write-ups: **[0xberk0.github.io](https://0xberk0.github.io)**

<br>

<picture>
  <source media="(prefers-color-scheme: dark)" srcset="https://raw.githubusercontent.com/0xBerk0/0xBerk0/output/github-snake-dark.svg">
  <img alt="contribution graph" src="https://raw.githubusercontent.com/0xBerk0/0xBerk0/output/github-snake.svg">
</picture>

---

<sub>All code is for research and authorized testing only. &nbsp;·&nbsp; struggle. adapt. understand.</sub>
