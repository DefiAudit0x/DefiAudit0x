<div align="center">

# DefiAudit

**DeFi Security Researcher · Solidity & EVM + Sui Move · Founder of [@DefiAudit-Labs](https://github.com/DefiAudit-Labs)**

[![Twitter](https://img.shields.io/badge/X-@DeFiAudit-1DA1F2?style=flat-square&logo=x&logoColor=white)](https://x.com/DeFiAudit)
[![Telegram](https://img.shields.io/badge/Telegram-@DefiAudit0x-26A5E4?style=flat-square&logo=telegram&logoColor=white)](https://t.me/DefiAudit0x)
[![GitHub Org](https://img.shields.io/badge/Org-DefiAudit_Labs-181717?style=flat-square&logo=github&logoColor=white)](https://github.com/DefiAudit-Labs)
[![Email](https://img.shields.io/badge/Email-defiaudit@gmail.com-EA4335?style=flat-square&logo=gmail&logoColor=white)](mailto:defiaudit@gmail.com)
[![Open to Audit Engagements](https://img.shields.io/badge/Open%20to-Audit%20Engagements-2ea043?style=flat-square)](#availability)

![Profile Views](https://komarev.com/ghpvc/?username=DefiAudit0x&style=flat-square&color=blue)
![GitHub followers](https://img.shields.io/github/followers/DefiAudit0x?style=flat-square&label=Followers)

</div>

---

I research smart-contract vulnerabilities, build reproducible security tests, and help Web3 teams turn findings into practical fixes.

My focus is **Solidity / EVM security, Sui Move security, DeFi and cross-chain attack surfaces, protocol invariants, and secure systems engineering.**

---

## Availability

[![Open for engagements](https://img.shields.io/badge/Status-Open%20for%20Engagements-2ea043?style=for-the-badge)](https://x.com/DeFiAudit)

Currently available for **smart-contract security reviews and audit engagements** — independent or team-based, full-scope or targeted modules.

- **Engagement types:** solo audits, second-pass verification, invariant & fuzzing strategy (Foundry / Echidna / Medusa), secure-upgrade reviews.
- **Competitive:** audit contests and bug bounties — HackenProof, Code4rena, Sherlock, Cantina, Immunefi.
- **Response:** usually within 24 hours — X or Telegram are fastest.

---

## What I do

- Manual smart-contract review and business-logic analysis — full-module reads on both EVM and Sui Move codebases, pinned to exact deployed commits.
- Bug bounty hunting on HackenProof: cross-chain bridges, CLMM / DEX accounting, and lending protocols.
- Foundry-based exploit reproduction, invariant testing, and regression tests.
- Fuzzing and static analysis with Medusa, Echidna, and Slither — and active upstream contributions to those tools.
- Public security research and educational audit write-ups.
- Security-minded engineering for systems that handle untrusted data and real-world risk.

## Bug bounty track record

Active on [HackenProof](https://hackenproof.com) (`defiaudit`) under responsible disclosure. Per program policy, targets and technical details remain unnamed until triage completes — resolved reports will be linked here after public disclosure.

| # | Platform | Severity | Status | Scope hint |
| - | -------- | -------- | ------ | ---------- |
| 1 | HackenProof | Low | Submitted | CLMM protocol — math rounding accounting |

## Open-source security contributions

Patches to the tools I rely on — **5 merged · 10 in review**:

| Repository | Contribution | Status |
| --- | --- | --- |
| [crytic/medusa #838](https://github.com/crytic/medusa/pull/838) | Fail-fast fuzz test utils — `require()` on setup failures halts immediately | ✅ Merged |
| [foundry-rs/foundry #16696](https://github.com/foundry-rs/foundry/pull/16696) | Preserve NatSpec characters inside fenced code blocks | ✅ Merged |
| [vyncint/termlens #158](https://github.com/vyncint/termlens/pull/158) | Support `no-default-features` builds | ✅ Merged |
| [oscarbol09/audiobard #23](https://github.com/oscarbol09/audiobard/pull/23) | Fix CRLF paragraph boundary parsing | ✅ Merged |
| [crytic/echidna #1610](https://github.com/crytic/echidna/pull/1610) | Deterministic boolean corpus coverage counts | ✅ Merged |
| [crytic/slither #3093](https://github.com/crytic/slither/pull/3093) | New detector: quantum-vulnerable signature schemes (`ecrecover` / `ECDSA.recover`) | In review |
| [crytic/slither #3094](https://github.com/crytic/slither/pull/3094) | Merge inherited `using-for` directives instead of overwriting them | In review |
| [crytic/medusa #839](https://github.com/crytic/medusa/pull/839) | On-chain fuzzing (fork mode) documentation guide | In review |
| [crytic/echidna #1609](https://github.com/crytic/echidna/pull/1609) | Isolate shrinking worker state in the UI | In review |
| [cross-chain-payments #8](https://github.com/vijaymark/cross-chain-payments/pull/8) | Escrow boundary & fuzz tests for StreamEscrow / MilestoneEscrow | In review |
| [crytic/medusa #844](https://github.com/crytic/medusa/pull/844) | Decouple `RandomValueGenerator` from the `ValueMutator` interface (part of #809) | In review |
| [crytic/medusa #845](https://github.com/crytic/medusa/pull/845) | Array structure mutations (swap / insert / delete) in `MutateAbiValue` | In review |
| [crytic/medusa #846](https://github.com/crytic/medusa/pull/846) | Move ABI argument encoding/decoding helpers to their own file (part of #809) | In review |
| [crytic/echidna #1631](https://github.com/crytic/echidna/pull/1631) | Cap generated `msg.value` at the sender's balance — fixes zero-balance sender panic (#1556) | In review |
| [crytic/echidna #1632](https://github.com/crytic/echidna/pull/1632) | Document the JSON output format accurately — schema field-by-field against the code (#1463) | In review |

Claimed upstream issues with root-cause triage: [echidna #1556](https://github.com/crytic/echidna/issues/1556), [echidna #1463](https://github.com/crytic/echidna/issues/1463), [medusa #809](https://github.com/crytic/medusa/issues/809).

Also an active answerer on foundry-rs/foundry GitHub Q&A discussions.

## Selected work

| Project | What it demonstrates |
| --- | --- |
| [Audit-Reports](https://github.com/DefiAudit0x/Audit-Reports) | Public audit methodology, findings, and sanitized case studies. |
| [EVM Audit Lab](https://github.com/DefiAudit0x/evm-audit-lab) | Reproducible Solidity vulnerability labs (14 labs, Foundry-tested) with a 3-gate Slither CI. |
| [smart-contract-auditor](https://github.com/DefiAudit0x/smart-contract-auditor) | Multi-pass analysis tool: static pre-scan modules, CVSS 4.0 scoring, Foundry-verified benchmarks, SARIF export. |
| [DefiAudit Labs organization](https://github.com/DefiAudit-Labs) | The home for DefiAudit research, tools, and reports. |

## Technical focus

`Solidity` · `EVM` · `Sui Move` · `Foundry` · `Medusa` · `Echidna` · `Slither` · `XCM / Bridges` · `Python` · `TypeScript`

## Audit approach

1. Establish scope, trust boundaries, assumptions, and a numbered hypothesis ledger.
2. Trace privileged flows, accounting, external calls, oracle dependencies, and upgrade paths.
3. Reproduce material findings with a minimal characterization-test PoC, pinned to the exact audited commit — passing on the buggy code, failing only under the narrow fix.
4. Describe impact and exploitability precisely, without overstating claims — severity argued in both directions (why it is not higher, and why it is not N/A).
5. Propose a narrow remediation and verify it with regression tests.

## Responsible disclosure

I do not publish private client details, credentials, or weaponized exploit instructions without authorization. Public reports are labeled clearly as **client-approved**, **contest-based**, **educational**, or **independent research**.

## Contact

- X: [@DeFiAudit](https://x.com/DeFiAudit)
- Telegram: [@DefiAudit0x](https://t.me/DefiAudit0x)
- Email: [defiaudit@gmail.com](mailto:defiaudit@gmail.com)
- GitHub: [DefiAudit0x](https://github.com/DefiAudit0x)
- Bug bounty: HackenProof — `defiaudit`

---

> The goal is not only to find bugs, but to make protocols more resilient.
