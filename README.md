<h1 align="center">p34t1k</h1>
<p align="center">Security research, red-team tooling, CTF/cert prep — and a couple of things I actually ship.</p>

<p align="center">
  <a href="https://github.com/p34t1k/MControlCenter"><img alt="MControlCenter" src="https://img.shields.io/github/stars/p34t1k/MControlCenter?style=flat-square&label=MControlCenter"></a>
  <a href="https://github.com/p34t1k/ultron"><img alt="ultron" src="https://img.shields.io/github/stars/p34t1k/ultron?style=flat-square&label=ultron"></a>
  <img alt="repos" src="https://img.shields.io/badge/repos-152-blue?style=flat-square">
  <img alt="archived forks" src="https://img.shields.io/badge/archived%20forks-140-lightgrey?style=flat-square">
</p>

## 🔨 Featured — things I built and maintain

These are the only two repos I'm actively developing; everything else below is either a small script or reference material I keep around.

<table>
<tr>
<td width="50%" valign="top">

### [MControlCenter](https://github.com/p34t1k/MControlCenter)
Linux control center for MSI laptops — power modes, fan curves, charge limit, keyboard RGB, battery calibration, dGPU boot mode. A community-maintained fork with real hardware support I reverse-engineered myself (no reused private MSI credentials). Public CI across 5 distros.

`#personal` `#hardware` `#kde` `#linux`

</td>
<td width="50%" valign="top">

### [ultron](https://github.com/p34t1k/ultron)
Local, offline-first voice assistant — mic → whisper → LLM → TTS, with hands-on-the-system actions gated behind a spoken confirmation. Runs entirely on-device.

`#personal` `#ai` `#automation` `#voice-assistant`

</td>
</tr>
</table>

## 🧰 Smaller personal scripts

Public, written by me, each does one small job:

- [Default_Camera_Changer.sh](https://github.com/p34t1k/Default_Camera_Changer.sh) — swaps the default camera to USB so I don't have to do it manually before every call
- [DigiSpark-ReverseShell](https://github.com/p34t1k/DigiSpark-ReverseShell) — a basic DigiSpark HID injection payload
- [php-reverse-shell](https://github.com/p34t1k/php-reverse-shell) — a minimal PHP reverse shell

Reference collections I maintain:

- [Web-Pentesting-Books](https://github.com/p34t1k/Web-Pentesting-Books) — a collection of web pentesting books
- [learn-aws](https://github.com/p34t1k/learn-aws) — AWS concepts with worked examples

(A few other personal repos — `job-search`, `Linkedin-Post-automation`, `KDE-Connect-Custom-Setup` — are private, plus an empty `test` scratch repo; not listed here since there's nothing public to see.)

## 📚 How the other 140+ repos are organized

The rest of this account is years of accumulated security-research material — red-team tooling, CTF/cert prep, reference clones. **All 140 forks are archived** (checked commit history on every one, confirmed zero original edits from me), kept around purely as searchable reference, not as active projects. Archiving is reversible (`gh repo unarchive <repo>`).

Everything is tagged with GitHub topics on two independent axes, classified from actual repo content rather than just names:

**Nature** — what kind of thing it is (one or more per repo):

| Tag | Meaning | Count |
|---|---|---|
| [`personal`](https://github.com/p34t1k?tab=repositories&topic=personal) | Something I actually wrote myself (not a fork) | 12 |
| [`tool`](https://github.com/p34t1k?tab=repositories&topic=tool) | Runnable software — forked or written, does a task | 85 |
| [`reference`](https://github.com/p34t1k?tab=repositories&topic=reference) | Non-executable knowledge: guides, cheatsheets, mindmaps, writeups, exam prep | 53 |
| [`payload`](https://github.com/p34t1k?tab=repositories&topic=payload) | Raw exploit code / shellcode / malware samples / ransomware PoCs — handle with care | 7 |

**Domain** — what it's about (zero or more per repo):

<details>
<summary>Expand full domain breakdown (click)</summary>

| Tag | Count | Tag | Count |
|---|---|---|---|
| [`red-team`](https://github.com/p34t1k?tab=repositories&topic=red-team) | 44 | [`web-security`](https://github.com/p34t1k?tab=repositories&topic=web-security) | 25 |
| [`windows`](https://github.com/p34t1k?tab=repositories&topic=windows) | 13 | [`osint`](https://github.com/p34t1k?tab=repositories&topic=osint) | 12 |
| [`cert-prep`](https://github.com/p34t1k?tab=repositories&topic=cert-prep) | 10 | [`hid-hacking`](https://github.com/p34t1k?tab=repositories&topic=hid-hacking) | 9 |
| [`evasion`](https://github.com/p34t1k?tab=repositories&topic=evasion) | 9 | [`mobile-security`](https://github.com/p34t1k?tab=repositories&topic=mobile-security) | 9 |
| [`malware-analysis`](https://github.com/p34t1k?tab=repositories&topic=malware-analysis) | 8 | [`social-engineering`](https://github.com/p34t1k?tab=repositories&topic=social-engineering) | 7 |
| [`wifi-hacking`](https://github.com/p34t1k?tab=repositories&topic=wifi-hacking) | 7 | [`bug-bounty`](https://github.com/p34t1k?tab=repositories&topic=bug-bounty) | 7 |
| [`cloud-security`](https://github.com/p34t1k?tab=repositories&topic=cloud-security) | 7 | [`active-directory`](https://github.com/p34t1k?tab=repositories&topic=active-directory) | 6 |
| [`ctf`](https://github.com/p34t1k?tab=repositories&topic=ctf) | 4 | [`hardware-iot`](https://github.com/p34t1k?tab=repositories&topic=hardware-iot) | 4 |
| [`forensics`](https://github.com/p34t1k?tab=repositories&topic=forensics) | 2 | [`honeypot`](https://github.com/p34t1k?tab=repositories&topic=honeypot) | 2 |

</details>

**Going forward**: every new repo (created or forked) gets tagged with one nature + relevant domain topic(s) at creation time — `gh repo edit <repo> --add-topic <tag>`. Keeps this list from rotting back into chaos.

---

- 👋 Hi, I'm @p34t1k
- 👀 Interested in cyber security
</content>
