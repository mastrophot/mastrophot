### Max Butrik

On-chain infrastructure, Rust/WASM smart contracts, autonomous execution agents, and deep-sky astrophotography.

<p>
  <a href="https://x.com/mastr0phot"><img src="https://img.shields.io/badge/X-@mastr0phot-111827?style=flat-square&logo=x&logoColor=white" alt="X" /></a>
  <a href="https://t.me/mastrophot"><img src="https://img.shields.io/badge/Telegram-@mastrophot-111827?style=flat-square&logo=telegram&logoColor=38BDF8" alt="Telegram" /></a>
  <a href="https://www.linkedin.com/in/maxbutrik/"><img src="https://img.shields.io/badge/LinkedIn-Max_Butrik-111827?style=flat-square&logo=linkedin&logoColor=38BDF8" alt="LinkedIn" /></a>
  <a href="https://mastrophot.github.io/lastkey-bunker/"><img src="https://img.shields.io/badge/Live_App-LastKey_Bunker-111827?style=flat-square&logo=near&logoColor=00F5D4" alt="LastKey Bunker" /></a>
</p>

---

#### Featured Work

**[lastkey-bunker](https://github.com/mastrophot/lastkey-bunker)** — *Self-Custodial Zero-Signature Multichain Crypto Bunker & Automatic Inheritance on NEAR MPC*  
Non-custodial cold bunker, 1-click emergency panic switch, and dead-man's switch inheritance across **Bitcoin (SegWit)**, **Ethereum / EVM**, **Solana**, and **NEAR** governed by an immutable Rust smart contract ([`aegis.okgoogleok.testnet`](https://testnet.nearblocks.io/address/aegis.okgoogleok.testnet), `0` access keys) and **NEAR Chain Signatures (`v1.signer`)**.
- **Zero-Signature Privacy**: Deterministic MPC derivation (`aegis/{owner}/{epoch}`) keeps deposit addresses unexposed on-chain until Emergency Panic or Automatic Inheritance.
- **On-Chain WASM Bytecode Verifiers**: Pure Rust parsers verify raw unsigned transactions inside WASM before signing — Bitcoin BIP-143 SegWit preimage + outputs, EVM EIP-1559 RLP, Solana compiled instructions (`ComputeBudget` fee-drain ban), and NEAR Borsh.
- **Least-Privilege Execution**: Stateless 24/7 keepers on a scoped `FunctionCall` key (`0` transfer rights) with per-vault gas escrow, 72h policy/timer timelock, client-side `AES-256-GCM` / `X25519` notes, and zero-metadata Telegram alerts.
- **[Live App ↗](https://mastrophot.github.io/lastkey-bunker/)** · **[Source & Verifiers ↗](https://github.com/mastrophot/lastkey-bunker)** · **[On-Chain Contract ↗](https://testnet.nearblocks.io/address/aegis.okgoogleok.testnet)**

---

#### Selected Repositories

| Repository | Scope | Stack |
| :--- | :--- | :--- |
| **[lastkey-bunker](https://github.com/mastrophot/lastkey-bunker)** | Zero-signature multichain cold bunker, panic evacuation & autonomous inheritance with 4-chain WASM verifiers. | `Rust` `WASM` `NEAR MPC` |
| **[near-mcp-contract-security](https://github.com/mastrophot/near-mcp-contract-security)** | MCP server for automated smart contract vulnerability inspection, access-key auditing, and risk scoring. | `TypeScript` `MCP` `NEAR` |
| **[near-mcp-wallet-manager](https://github.com/mastrophot/near-mcp-wallet-manager)** | Guardrailed MCP wallet execution interface with scoped key permissions and pre-dispatch validation. | `TypeScript` `MCP` `RPC` |
| **[near-langchain-tx-builder](https://github.com/mastrophot/near-langchain-tx-builder)** | Transaction construction, dry-run simulation, and schema validation pipeline for autonomous agents. | `Python` `NEAR` `Agents` |
| **[near-developer-suite-vscode](https://github.com/mastrophot/near-developer-suite-vscode)** | VS Code extension suite for inspecting on-chain state, decoding transaction receipts, and contract deployment. | `TypeScript` `VS Code` |
| **[near-contract-size-check-action](https://github.com/mastrophot/near-contract-size-check-action)** | CI/CD GitHub Action enforcing WASM binary size budgets and deterministic build checks. | `JavaScript` `CI/CD` |
| **[near-fastapi](https://github.com/mastrophot/near-fastapi)** | Asynchronous REST microservice for indexing and querying NEAR RPC state. | `Python` `FastAPI` |
| **[medicaid-fraud-signal-engine](https://github.com/mastrophot/medicaid-fraud-signal-engine)** | Analytical CLI engine extracting statistical anomaly signals from large public datasets. | `Python` `Data` |

---

#### Stack & Primitives

```text
Languages     Rust · WebAssembly (WASM) · TypeScript · JavaScript (Node.js) · Python · Solidity · SQL
Cryptography  Threshold ECDSA (Secp256k1) · Ed25519 / X25519 · AES-256-GCM · BIP-143 PSBT · EIP-1559 RLP · Borsh
Infrastructure NEAR Protocol (Chain Signatures / MPC) · Bitcoin SegWit · EVM · Solana · Model Context Protocol (MCP)
```
