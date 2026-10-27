# brerabin

security tooling. detection over prevention.

what lands here: working blue-team tooling, tested end to end before it is
published. static first. nothing executes in your environment, nothing
leaves it either.

the suite so far:

- [hellhound](https://github.com/brerabineth/hellhound) — decoy tripwires that catch ransomware on first touch. go.
- [gravedigger](https://github.com/brerabineth/gravedigger) — first-hour forensic triage for unix hosts. one binary, no agent. rust.
- [coroner](https://github.com/brerabineth/coroner) — client-side ransom-note triage. runs offline, single file. javascript.
- [breraos](https://github.com/brerabineth/breraos) — hardened desktop: cold vault, capture shield, encrypted frame channel. rust + tauri.
- [morgue](https://github.com/brerabineth/morgue) — local triage for infostealer logs. python, stdlib only.
- [familiar](https://github.com/brerabineth/familiar) — audits every MCP config and tool your agent can reach. typescript, zero deps.
- [placebo](https://github.com/brerabineth/placebo) — the fake fix, dissected. triage for paste-and-run commands and the residue they leave. powershell.
- [husk](https://github.com/brerabineth/husk) — first-hour static triage for ELF binaries. one static binary. c.
- [revenant](https://github.com/brerabineth/revenant) — persistence audit for unix hosts. pure bash. nothing leaves the machine.
- [tarot](https://github.com/brerabineth/tarot) — read the package before it reads you. static pre-install triage for npm artifacts. zig.
- [necropsy](https://github.com/brerabineth/necropsy) — the binary post-mortem kit. static triage for ELF, PE and Mach-O. nim.
- [wraith](https://github.com/brerabineth/wraith) — audits the extensions already living in your browser. manifest risk model + js pattern scan. c++.
- [mimic](https://github.com/brerabineth/mimic) — scan the content before your agent swallows it. static triage for indirect prompt injection. java, zero deps.
- [helminth](https://github.com/brerabineth/helminth) — parasite triage for npm machines: worm artifacts, planted persistence, credentials within reach. ruby, one file.
- [seance](https://github.com/brerabineth/seance) — the network speaks for the dead machine. beaconing, DNS tunneling and C2 artifacts from a pcap. perl, one file, no deps.
- [effigy](https://github.com/brerabineth/effigy) — a shortcut that looks like a document is an effigy of it. static triage for windows .lnk droppers: encoded payloads, icon masquerade, tracker droids. c#, single binary.
- [palimpsest](https://github.com/brerabineth/palimpsest) — read the text under the text. static audit for MCP servers: description poisoning, cross-server shadowing, rug pulls caught by a description baseline. lua, one file, zero deps.
- [dirge](https://github.com/brerabineth/dirge) — the bell for the dead letter. offline .eml triage: header forensics, url risk, attachment traps, exit codes a pipeline can gate on. ocaml, one native binary.
- [ossuary](https://github.com/brerabineth/ossuary) — the layers remember. static triage for container images: secrets that survived a later `rm`, build-history abuse, config posture, dockerfile audits. d, one native binary.
- [grimoire](https://github.com/brerabineth/grimoire) — a book of hidden spells. static triage for hostile documents: remote template injection, DDE fields, XLM sheets, Ole10Native packages, vba deobfuscation with payload re-scan, embedded-artifact carving. crystal, one native binary.

- [barbican](https://github.com/brerabineth/barbican) — read the wall before the siege. static audit for nginx and caddy configs: rewrite traversal, legacy tls, header inheritance traps. ada, one native binary.
- [coven](https://github.com/brerabineth/coven) — the circle of jobs around one cauldron; one of them is always a witch. static triage for github actions workflows: expression injection, pwn requests, history scraping, mutable third-party refs. haskell, one binary.

no socials. no DMs. the work is the identity.

