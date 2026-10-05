<div align="center">

# DefiAudit

**Smart Contract Security Researcher · Solidity / EVM · DeFi Security**

Building reproducible security tooling, researching smart-contract vulnerabilities, and contributing to the open-source infrastructure used by security researchers.

[![X](https://img.shields.io/badge/X-@DeFiAudit-000000?style=flat-square&logo=x&logoColor=white)](https://x.com/DeFiAudit)
[![Telegram](https://img.shields.io/badge/Telegram-@DeFiAudit0x-26A5E4?style=flat-square&logo=telegram&logoColor=white)](https://t.me/DeFiAudit0x)
[![GitHub](https://img.shields.io/badge/GitHub-DefiAudit0x-181717?style=flat-square&logo=github&logoColor=white)](https://github.com/DefiAudit0x)

</div>

---

## Core focus

- **Solidity / EVM security**
- **DeFi & cross-chain attack surfaces**
- **Protocol invariants, fuzzing & exploit reproduction**
- **Static analysis and security automation**
- **Sui Move security**
- **Foundry, Echidna, Medusa & Slither**

---

## Selected security work

| Project | What it demonstrates |
| --- | --- |
| [EVM Audit Lab](https://github.com/DefiAudit0x/evm-audit-lab) | Reproducible Solidity vulnerability labs — vulnerable vs. remediated, with exploit and regression tests. |
| [Audit Reports](https://github.com/DefiAudit0x/Audit-Reports) | Public security research, audit methodology, findings and sanitized case studies. |
| [Smart Contract Auditor](https://github.com/DefiAudit0x/smart-contract-auditor) | Multi-pass smart-contract analysis with static pre-scan, CVSS 4.0, SARIF and reproducible benchmarks. |
| [DefiAudit Labs](https://github.com/DefiAudit-Labs) | Research and tooling organization for security-focused projects. |

---

## Open-source security contributions

I don't just audit contracts. **I contribute to the tools and test infrastructure security researchers use to audit them.**

### Crytic ecosystem

- [Echidna #1631](https://github.com/crytic/echidna/pull/1631) — cap generated `msg.value` at the sender's balance.
- [Echidna #1609](https://github.com/crytic/echidna/pull/1609) — isolate shrinking worker state.
- [Echidna #1610](https://github.com/crytic/echidna/pull/1610) — deterministic boolean corpus coverage counts. **Merged**
- [Echidna #1632](https://github.com/crytic/echidna/pull/1632) — document the JSON output schema accurately.
- [Medusa #845](https://github.com/crytic/medusa/pull/845) — array structure mutations for ABI values.
- [Medusa #846](https://github.com/crytic/medusa/pull/846) — separate ABI encoding/decoding helpers.
- [Medusa #844](https://github.com/crytic/medusa/pull/844) — decouple value generation from mutation.
- [Medusa #839](https://github.com/crytic/medusa/pull/839) — on-chain fuzzing / fork-mode documentation.
- [Medusa #838](https://github.com/crytic/medusa/pull/838) — fail-fast fuzz test utilities. **Merged**
- [Slither #3094](https://github.com/crytic/slither/pull/3094) — correctly merge inherited `using-for` directives.
- [Slither #3093](https://github.com/crytic/slither/pull/3093) — quantum-vulnerable signature detector.
- [Foundry #16696](https://github.com/foundry-rs/foundry/pull/16696) — preserve NatSpec characters inside fenced code blocks. **Merged**

- [Cross-chain payments #8](https://github.com/vijaymark/cross-chain-payments/pull/8) — boundary and fuzz tests for `StreamEscrow` and `MilestoneEscrow`, including conservation-of-value and accounting invariants. **Open**

Other merged open-source contributions include [TermLens #158](https://github.com/vyncint/termlens/pull/158) and [AudioBard #23](https://github.com/oscarbol09/audiobard/pull/23).

---

## Security methodology

My workflow is centered on **reproducibility and narrow claims**:

1. Establish scope, trust boundaries and assumptions.
2. Identify privileged flows, accounting, external calls, oracles and upgrade paths.
3. Form explicit vulnerability hypotheses and test them against the code.
4. Reproduce material findings with minimal PoCs.
5. Argue impact and exploitability without overstating severity.
6. Propose narrow remediation and verify it with regression tests.

Tool output is treated as evidence and a lead — not a substitute for protocol reasoning.

---

## Research

Current research areas include:

- Smart-contract vulnerability patterns
- DeFi accounting and invariant failures
- Cross-chain and bridge security
- Fuzzing and property-based testing
- Static-analysis tooling
- Security automation and AI-assisted analysis

---

## Responsible disclosure

Public work is labeled clearly as **independent research**, **educational material**, **contest-based research**, or **client-approved material** where applicable.

I do not publish private client details, credentials, or unauthorized weaponized exploit instructions.

---

## Contact

- X: [@DeFiAudit](https://x.com/DeFiAudit)
- Telegram: [@DeFiAudit0x](https://t.me/DeFiAudit0x)
- Email: [defiaudit@gmail.com](mailto:defiaudit@gmail.com)

> Find the bug. Reproduce it. Explain the root cause. Make the fix testable.
