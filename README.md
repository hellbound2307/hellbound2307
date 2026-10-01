### Marwan Naili — researcher, Algiers (DZ)

I build systems that run unattended, and I measure what they inherit.
Everything runs on-device — a phone, a laptop, no rented GPUs. That constraint is the design, not the compromise.

**Website** · [marwan-naili.me](https://marwan-naili.me/) — [research record](https://marwan-naili.me/research/) — [method paper](https://marwan-naili.me/research/impersonation-infrastructure-method/)

---

**[A] Agentic systems**
Runtime containment, capability security, the parts that only fail under real load.

- [Minis-X](https://github.com/hellbound2307/Minis-X) — agent runtime for Android: on-device model routing, tool execution, Linux sandbox for untrusted code, plugin permissions with a network allowlist enforced below the app layer, encrypted vault, run telemetry. Signed CI builds, verified on-device after every release.

**[B] Applied ML & evaluation**
Retrieval that is allowed to say *I don't know*, and evals that don't flatter me.

- [CyberRAG](https://github.com/hellbound2307/CyberRAG) — retrieval arsenal over WSTG / ATT&CK / field notes. Keyed CVE lookup and concept corpora in separate indexes so a 1,900-record catalogue cannot poison concept queries. Abstention is a valid output.

**[C] Security measurement**
Passive-first. No exploitation, no credential testing, no state-affecting action.

- [DarkTortilla-RAT](https://github.com/hellbound2307/DarkTortilla-RAT-Telegram-Exfiltration-Payload-Extraction-Analysis) — reverse engineering of a commodity Android RAT's Telegram exfiltration channel. Samples in isolation; no live infrastructure contacted.
- [algeria-wilayas](https://github.com/marwangpt237/algeria-wilayas) — 69 wilayas + communes, 2026 reform, reproducible build.

---

<sub>Observed / reported / inferred / unknown are kept apart. A passing command proves the mechanism worked, never that the objective was met.</sub>
