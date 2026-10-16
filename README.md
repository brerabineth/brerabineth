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

no socials. no DMs. the work is the identity.
