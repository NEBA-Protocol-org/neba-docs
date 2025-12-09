# NEBA Protocol - Documentation

Comprehensive technical documentation for developers and integrators.

## Quick Links

- [Introduction](./docs/introduction.md)
- [Architecture Overview](./docs/architecture.md)
- [AI Engine](./docs/ai-engine.md)
- [Smart Contracts](./docs/contracts.md)
- [API Reference](./docs/api.md)
- [Integration Guide](./docs/integration.md)

## Getting Started

NEBA Protocol enables AI-adaptive reward distribution for your platform. This documentation covers:

- Protocol architecture and design principles
- Smart contract integration
- AI model interaction patterns
- Oracle network participation
- Governance mechanisms

## Documentation Structure
```
neba-docs/
├── docs/
│   ├── introduction.md       # Protocol overview
│   ├── architecture.md        # System design
│   ├── ai-engine.md          # LLM integration details
│   ├── contracts.md          # Smart contract API
│   ├── api.md                # Developer API reference
│   ├── integration.md        # Platform integration guide
│   ├── governance.md         # DAO participation
│   └── security.md           # Security model
├── examples/                  # Code examples
├── tutorials/                 # Step-by-step guides
└── assets/                   # Diagrams and images
```

## Current Status

📝 **Documentation in Progress** - Completion targeted for Q2 2026 testnet launch

## Key Concepts

### LLM-Agnostic Architecture

NEBA supports multiple AI providers with seamless switching:
- Claude AI (Anthropic)
- GPT-4 (OpenAI)
- Llama 3 (Meta)
- Decentralized inference networks (future)

### Epoch-Based Distribution

Rewards calculated and distributed every 30-60 minutes:
1. Behavioral data aggregation
2. AI model computation
3. Oracle network verification
4. On-chain distribution execution

### Economic Security

Multi-layer protection against AI exploits:
- Hard-coded emission caps
- Circuit breaker triggers
- Optimistic verification
- Fraud proof mechanisms

## For Developers

### Prerequisites

- Solana CLI tools
- Rust programming language
- TypeScript/JavaScript knowledge
- Understanding of SPL tokens

### Integration Steps

1. Deploy NEBA reward module to your platform
2. Configure epoch parameters
3. Integrate behavioral data feeds
4. Test on devnet/testnet
5. Launch on mainnet with TVL caps

Detailed guides coming Q2 2026.

## For Oracle Operators

Requirements for running a verification node:
- Minimum 100K NEBA stake
- 24/7 uptime (99.5%+ required)
- Secure server infrastructure
- API access to AI providers

Node operator documentation: Coming Q3 2026

## Contributing

Documentation contributions welcome! Please:
1. Fork this repository
2. Create feature branch
3. Submit pull request
4. Follow markdown formatting guidelines

## Resources

- Website: [nebatoken.org](https://nebatoken.org)
- Whitepaper: [github.com/NEBA-Protocol/neba-whitepaper](https://github.com/NEBA-Protocol/neba-whitepaper)
- Contracts: [github.com/NEBA-Protocol/neba-contracts](https://github.com/NEBA-Protocol/neba-contracts)
- Email: hello@nebatoken.org

## License

MIT License

---

Built for Developers | Powered by Community | Secured by Design
