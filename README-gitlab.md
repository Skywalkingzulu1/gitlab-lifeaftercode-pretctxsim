# PreTxSim - Life After Code (GitLab)

## Pitch
Shift-left Web3 DevSecOps: CI mode with JSON risk output

## Core Features
- **Air-gapped simulation** via evm — runs locally, no keys broadcast until accepted
- **RiskInspector**: delegatecalls, selfdestructs, storage writes, allowances, EIP-7702 delegations
- **Local LLM auditor** (Ollama smollm2): advisory PASS/WARN, zero telemetry
- **Proxy gate** at http://127.0.0.1:8545 (drop-in for wallets/bots)

## Quick Start
\\\ash
docker compose up -d
\\\

See [demo_runbook.md](demo_runbook.md) for full details.
