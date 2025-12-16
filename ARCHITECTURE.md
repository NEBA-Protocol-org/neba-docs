markdown
# NEBA Protocol Architecture

## System Overview

NEBA implements a three-layer architecture for AI-powered reward distribution:

### Layer 1: Data Collection
- Solana RPC nodes monitor on-chain activity
- Behavioral metrics aggregated every 30-60 minutes
- Privacy-preserving data vectorization

### Layer 2: AI Computation
- LLM-agnostic API integration (Claude, GPT-4, Llama)
- Multi-dimensional behavioral analysis
- Reward multiplier calculation (0.8x - 2.5x)

### Layer 3: Verification
- Decentralized oracle consensus (5-of-7 nodes)
- Fraud proof challenge periods
- Circuit breaker enforcement

## Component Interaction
```
Blockchain → Data Pipeline → AI Engine → Oracle Network → Smart Contract
```

## Security Model

- Hard-coded emission caps
- Statistical anomaly detection
- Rate limiting (±20% variance)
- Multi-sig governance
5. Commit:
•	Message: docs: add system architecture overview
•	Click "Commit new file"
