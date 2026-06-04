# Awesome Crypto Skills [![Awesome](https://awesome.re/badge.svg)](https://awesome.re)

A curated list of open-source AI agent skills for cryptocurrency, Web3, and blockchain operations.

These are installable SKILL.md-based skills that give your AI agent crypto superpowers. Install with one command and your agent can trade tokens, analyze markets, deploy contracts, and more.

## Caution

**These skills are not audited.** Use at your own risk.

- Skills listed here are community-contributed and open-source. They have **not** undergone formal security audits.
- Skills that handle private keys, execute transactions, or interact with DeFi protocols can **result in loss of funds** if misused or compromised.
- Always review a skill's SKILL.md and source code before installing, especially for skills that require wallet access or API keys.
- Some skills may contain bugs, outdated contract addresses, or unsafe patterns. Verify contract addresses on-chain before interacting.
- In April 2026, researchers found that ~12% of skills on community registries contained malicious code (crypto drainers, backdoors). Prefer skills from official sources (Binance, OKX, Coinbase, Uniswap, etc.) when possible.
- Never share private keys, seed phrases, or API secrets with any skill or agent.
- Start with small amounts on testnets before using skills with real funds.

By using any skill from this list, you acknowledge that you understand the risks and take full responsibility for any outcomes.

## Contents

- [Trading & DeFi](#trading--defi)
- [Blockchain Operations](#blockchain-operations)
- [Market Analysis](#market-analysis)
- [Smart Contracts](#smart-contracts)
- [Security & Auditing](#security--auditing)
- [Cross-Chain](#cross-chain)
- [NFTs & Tokens](#nfts--tokens)
- [Wallets & Identity](#wallets--identity)
- [Skill Collections](#skill-collections)

---

## Trading & DeFi

Skills for trading, swaps, lending, yield farming, and DeFi automation.

- **[CTRLabs/ctrl-skill](https://github.com/CTRLabs/ctrl-skill)** - Visual DeFi workflow automation on Base + Ethereum mainnet. Compose triggers (cron, price, balance, `pool.created` for Clanker / Flaunch / Zora / BANKR, `watch.whale`) and actions (Uniswap V4 swaps, USDC payouts, Telegram / Discord notifications) on a canvas; user signs once via EIP-5792, an 8-wallet keeper executes from vault-direct V13 contracts forever under per-swap / per-day caps the user signed
- **[kukapay/crypto-skills: trading-strategist](https://github.com/kukapay/crypto-skills)** - Generate trading strategies with Binance data, technical indicators (RSI, MACD, Bollinger Bands), and sentiment analysis
- **[kukapay/crypto-skills: yield-opportunities](https://github.com/kukapay/crypto-skills)** - Find and analyze DeFi yield opportunities across protocols with risk scoring
- **[kukapay/crypto-skills: meme-scout](https://github.com/kukapay/crypto-skills)** - Scout trending meme coins on DexScreener with risk assessments
- **[Binance Skills Hub: binance](https://github.com/binance/binance-skills-hub)** - Binance CEX trading: search tokens, execute trades, track wallets
- **[Binance Skills Hub: meme-rush](https://github.com/binance/binance-skills-hub)** - Binance meme token trading and discovery
- **[CryptoSkills: uniswap](https://github.com/0xinit/cryptoskills)** - Uniswap V2/V3/V4 swaps, liquidity, and pool management
- **[CryptoSkills: aave](https://github.com/0xinit/cryptoskills)** - Aave lending, borrowing, flash loans, and liquidations
- **[CryptoSkills: compound](https://github.com/0xinit/cryptoskills)** - Compound lending protocol integration
- **[CryptoSkills: curve](https://github.com/0xinit/cryptoskills)** - Curve stableswap and pool operations
- **[CryptoSkills: lido](https://github.com/0xinit/cryptoskills)** - Lido liquid staking (stETH)
- **[CryptoSkills: pendle](https://github.com/0xinit/cryptoskills)** - Pendle yield tokenization, PT/YT trading
- **[CryptoSkills: eigenlayer](https://github.com/0xinit/cryptoskills)** - EigenLayer restaking, AVS, operator delegation
- **[CryptoSkills: morpho](https://github.com/0xinit/cryptoskills)** - Morpho Blue permissionless markets, MetaMorpho vaults
- **[CryptoSkills: maker](https://github.com/0xinit/cryptoskills)** - MakerDAO/Sky DAI vaults, DSR, liquidations
- **[CryptoSkills: drift](https://github.com/0xinit/cryptoskills)** - Drift perpetual futures, spot trading on Solana
- **[CryptoSkills: jupiter](https://github.com/0xinit/cryptoskills)** - Jupiter aggregator, limit orders, DCA, perps on Solana
- **[CryptoSkills: meteora](https://github.com/0xinit/cryptoskills)** - Meteora DLMM, dynamic bonding curves on Solana
- **[CryptoSkills: raydium](https://github.com/0xinit/cryptoskills)** - Raydium AMM, CLMM, LaunchLab on Solana
- **[CryptoSkills: orca](https://github.com/0xinit/cryptoskills)** - Orca Whirlpools, concentrated liquidity on Solana
- **[CryptoSkills: kamino](https://github.com/0xinit/cryptoskills)** - Kamino lending, liquidity strategies on Solana
- **[CryptoSkills: marginfi](https://github.com/0xinit/cryptoskills)** - MarginFi lending, flash loans on Solana
- **[CryptoSkills: pumpfun](https://github.com/0xinit/cryptoskills)** - PumpFun token launches, bonding curves on Solana
- **[OKX Plugin Store: aave-v3-plugin](https://github.com/okx/plugin-store)** - Aave V3 lending and borrowing via OKX
- **[OKX Plugin Store: compound-v3-plugin](https://github.com/okx/plugin-store)** - Compound V3 lending via OKX
- **[OKX Plugin Store: lido-plugin](https://github.com/okx/plugin-store)** - Lido staking via OKX
- **[OKX Plugin Store: hyperliquid-plugin](https://github.com/okx/plugin-store)** - Hyperliquid perpetuals trading
- **[OKX Plugin Store: gmx-v2-plugin](https://github.com/okx/plugin-store)** - GMX V2 perpetuals trading
- **[OKX Plugin Store: polymarket-plugin](https://github.com/okx/plugin-store)** - Polymarket prediction markets
- **[OKX Plugin Store: uniswap-ai](https://github.com/okx/plugin-store)** - Uniswap AI-powered swaps
- **[OKX Plugin Store: raydium-plugin](https://github.com/okx/plugin-store)** - Raydium DEX on Solana
- **[OKX Plugin Store: meteora-plugin](https://github.com/okx/plugin-store)** - Meteora liquidity pools
- **[OKX Plugin Store: orca-plugin](https://github.com/okx/plugin-store)** - Orca DEX on Solana
- **[OKX Plugin Store: pancakeswap-v2-plugin](https://github.com/okx/plugin-store)** - PancakeSwap V2 on BSC
- **[OKX Plugin Store: pancakeswap-v3-plugin](https://github.com/okx/plugin-store)** - PancakeSwap V3 on BSC
- **[OKX Plugin Store: curve-plugin](https://github.com/okx/plugin-store)** - Curve Finance pools
- **[OKX Plugin Store: velodrome-v2-plugin](https://github.com/okx/plugin-store)** - Velodrome V2 on Optimism
- **[OKX Plugin Store: morpho-plugin](https://github.com/okx/plugin-store)** - Morpho lending optimization
- **[OKX Plugin Store: pendle-plugin](https://github.com/okx/plugin-store)** - Pendle yield trading
- **[OKX Plugin Store: etherfi-plugin](https://github.com/okx/plugin-store)** - EtherFi liquid restaking
- **[OKX Plugin Store: kamino-lend-plugin](https://github.com/okx/plugin-store)** - Kamino lending on Solana
- **[OKX Plugin Store: pump-fun-plugin](https://github.com/okx/plugin-store)** - Pump.fun meme token launchpad
- **[OKX Plugin Store: meme-trench-scanner](https://github.com/okx/plugin-store)** - Scan for trending meme tokens
- **[OKX Plugin Store: smart-money-signal-copy-trade](https://github.com/okx/plugin-store)** - Copy trade smart money signals
- **[OKX Plugin Store: top-rank-tokens-sniper](https://github.com/okx/plugin-store)** - Snipe top ranked tokens
- **[0x Agent Skills: 0x-api](https://github.com/0xProject/0x-ai)** - Token swaps using 0x Swap and Gasless APIs on any EVM chain
- **[EmblemCompany: emblem-ai](https://github.com/emblemcompany/agent-skills)** - EmblemAI crypto tooling: swaps, DeFi, NFTs across 7 chains
- **[Uniswap: uniswap-ai](https://github.com/Uniswap/uniswap-ai)** - Official Uniswap AI skills: swap integration, v4 hooks, liquidity planning
- **[GMX: gmx-ai](https://github.com/gmx-io/gmx-ai)** - GMX perpetual trading AI skills
- **[Pendle: pendle-ai](https://github.com/pendle-finance/pendle-ai)** - Pendle yield trading AI skills
- **[KyberSwap: kyberswap-skills](https://github.com/KyberNetwork/kyberswap-skills)** - KyberSwap DEX aggregation skills
- **[Nethermind: defi-skills](https://github.com/NethermindEth/defi-skills)** - DeFi transaction builder (13 protocols, 53 actions)
- **[agiprolabs: claude-trading-skills](https://github.com/agiprolabs/claude-trading-skills)** - 62 trading, DeFi, and quantitative finance skills
- **[hive-intel: hive-agents](https://github.com/hive-intel/hive-agents)** - 17 specialized crypto intelligence agents
- **[openclaw: bankr](https://github.com/openclaw/skills)** - Financial infrastructure for autonomous agents: token launches, trading, yield
- **[Minara-AI: skills](https://github.com/Minara-AI/skills)** - Personal AI CFO: spot trading, perps, limit orders, wallet management
- **[Senpi-ai: senpi-skills](https://github.com/Senpi-ai/senpi-skills)** - 52 autonomous AI trading agents for Hyperliquid
- **[hummingbot: skills](https://github.com/hummingbot/skills)** - Hummingbot algorithmic trading: deploy, LP agent, arbitrage
- **[Crypto.com: crypto-agent-trading](https://github.com/crypto-com/crypto-agent-trading)** - Crypto.com App and Exchange trading skills
- **[MoonPay: prediction-market](https://github.com/moonpay/skills)** - Trade on Polymarket and Kalshi prediction markets
- **[MoonPay: trading-automation](https://github.com/moonpay/skills)** - DCA, limit orders, stop losses via cron

## Blockchain Operations

Skills for reading chain data, sending transactions, and interacting with protocols.

- **[kukapay/crypto-skills: evm-swiss-knife](https://github.com/kukapay/crypto-skills)** - Comprehensive EVM operations via Foundry's cast: balances, contract calls, deployments
- **[Binance Skills Hub: onchain-pay](https://github.com/binance/binance-skills-hub)** - Onchain payment operations via Binance
- **[Binance Skills Hub: binance-agentic-wallet](https://github.com/binance/binance-skills-hub)** - Binance Web3 wallet operations
- **[Binance Skills Hub: query-address-info](https://github.com/binance/binance-skills-hub)** - Query blockchain address information
- **[CryptoSkills: account-abstraction](https://github.com/0xinit/cryptoskills)** - ERC-4337 account abstraction and smart wallets
- **[CryptoSkills: ens](https://github.com/0xinit/cryptoskills)** - ENS domain registration and resolution
- **[CryptoSkills: helius](https://github.com/0xinit/cryptoskills)** - Helius enhanced Solana RPC: parsed transactions, DAS, webhooks
- **[CryptoSkills: squads](https://github.com/0xinit/cryptoskills)** - Squads multisig, smart accounts on Solana
- **[Aptos Agent Skills: ts-sdk-transactions](https://github.com/aptos-labs/aptos-agent-skills)** - Build, sign, and submit Aptos transactions
- **[Aptos Agent Skills: ts-sdk-view-and-query](https://github.com/aptos-labs/aptos-agent-skills)** - Call Move view functions and query on-chain Aptos data
- **[tetherto: wdk-agent-skills](https://github.com/tetherto/wdk-agent-skills)** - Self-custodial wallet operations across 20+ blockchains
- **[drpcorg: drpc-agent-skills](https://github.com/drpcorg/drpc-agent-skills)** - Blockchain RPC access to 200+ networks via DRPC
- **[chainstream-io: skills](https://github.com/chainstream-io/skills)** - On-chain data intelligence and DeFi execution across Solana, BSC, Ethereum
- **[openclaw: erc-8004](https://github.com/openclaw/skills)** - Ethereum agent registry using ERC-8004 standard
- **[openclaw: botchan](https://github.com/openclaw/skills)** - Onchain messaging protocol on Base
- **[openclaw: onchainkit](https://github.com/openclaw/skills)** - Coinbase OnchainKit for building onchain apps
- **[openclaw: ens-primary-name](https://github.com/openclaw/skills)** - Set primary ENS name on Base and L2s
- **[openclaw: clanker](https://github.com/openclaw/skills)** - Deploy ERC20 tokens on Base via Clanker SDK
- **[OKX OnchainOS: okx-agentic-wallet](https://github.com/okx/onchainos-skills)** - OKX wallet lifecycle: auth, balance, portfolio PnL, send, tx history
- **[OKX OnchainOS: okx-onchain-gateway](https://github.com/okx/onchainos-skills)** - Gas estimation, tx simulation, broadcasting
- **[OKX OnchainOS: okx-wallet-portfolio](https://github.com/okx/onchainos-skills)** - Public address balance, token holdings
- **[Coinbase: agentic-wallet-skills](https://github.com/coinbase/agentic-wallet-skills)** - Coinbase wallet: auth, fund, send USDC, trade on Base
- **[Base: skills](https://github.com/base/skills)** - Base L2: deploy contracts, connect network, integrate Base Account SDK
- **[Chainlink: agent-skills](https://github.com/smartcontractkit/chainlink-agent-skills)** - Chainlink CRE onboarding, CCIP cross-chain operations
- **[Solana Foundation: solana-dev-skill](https://github.com/solana-foundation/solana-dev-skill)** - Solana development: Anchor, testing, security, frontend
- **[sendaifun: skills](https://github.com/sendaifun/skills)** - Solana Agent Kit skills for 60+ onchain actions
- **[lxcong: web3-data-skill](https://github.com/lxcong/web3-data-skill)** - Chainbase on-chain data: token holders, wallet analytics, SQL queries

## Market Analysis

Skills for price data, market sentiment, and trading signals.

- **[kukapay/crypto-skills: market-sentiment](https://github.com/kukapay/crypto-skills)** - Aggregate crypto news and perform sentiment analysis (range: -1 to +1)
- **[Binance Skills Hub: crypto-market-rank](https://github.com/binance/binance-skills-hub)** - Crypto market rankings and token data
- **[Binance Skills Hub: query-token-info](https://github.com/binance/binance-skills-hub)** - Query detailed token information
- **[Binance Skills Hub: query-token-audit](https://github.com/binance/binance-skills-hub)** - Query token audit reports
- **[CryptoSkills: chainlink](https://github.com/0xinit/cryptoskills)** - Chainlink oracle price feeds and VRF
- **[CryptoSkills: pyth](https://github.com/0xinit/cryptoskills)** - Pyth Network real-time price feeds
- **[CryptoSkills: the-graph](https://github.com/0xinit/cryptoskills)** - The Graph subgraph indexing and queries
- **[DefiLlama: defillama-skills](https://github.com/DefiLlama/defillama-skills)** - DeFi analytics: TVL, yields, volumes, fees, bridges
- **[Nansen](https://clawhub.com/nansen-devops)** - On-chain analytics and wallet profiling
- **[CoinMarketCap](https://clawhub.com/bryan-cmc)** - Crypto market data and rankings
- **[Kraken: kraken-cli](https://github.com/krakenfx/kraken-cli)** - Kraken exchange CLI with 50 skills
- **[OKX OnchainOS: okx-dex-market](https://github.com/okx/onchainos-skills)** - Real-time prices, K-line charts, wallet PnL
- **[OKX OnchainOS: okx-dex-signal](https://github.com/okx/onchainos-skills)** - Smart money/whale/KOL signal tracking
- **[OKX OnchainOS: okx-dex-token](https://github.com/okx/onchainos-skills)** - Token search, metadata, market cap, holder analysis
- **[OKX OnchainOS: okx-dex-trenches](https://github.com/okx/onchainos-skills)** - Meme pump/trenches token scanning
- **[Bitget: bitget-skill-hub](https://github.com/BitgetLimited/agent_hub)** - 5 analyst skills: macro-analyst, market-intel, news-briefing, sentiment-analyst, technical-analysis
- **[MoonPay: messari-deep-research](https://github.com/moonpay/skills)** - Long-form AI research reports via Messari

## Smart Contracts

Skills for deploying and interacting with smart contracts.

- **[kukapay/crypto-skills: token-minter](https://github.com/kukapay/crypto-skills)** - Generate and deploy custom ERC20 tokens with OpenZeppelin
- **[Aptos Agent Skills: write-contracts](https://github.com/aptos-labs/aptos-agent-skills)** - Generate secure Aptos Move V2 smart contracts
- **[Aptos Agent Skills: deploy-contracts](https://github.com/aptos-labs/aptos-agent-skills)** - Deploy Move contracts to devnet, testnet, or mainnet
- **[Aptos Agent Skills: search-aptos-examples](https://github.com/aptos-labs/aptos-agent-skills)** - Search aptos-core for reference implementations and patterns
- **[Aptos Agent Skills: analyze-gas-optimization](https://github.com/aptos-labs/aptos-agent-skills)** - Analyze and reduce gas costs in Move smart contracts
- **[CryptoSkills: foundry](https://github.com/0xinit/cryptoskills)** - Foundry development framework: forge, cast, anvil
- **[CryptoSkills: hardhat](https://github.com/0xinit/cryptoskills)** - Hardhat development environment
- **[CryptoSkills: openzeppelin](https://github.com/0xinit/cryptoskills)** - OpenZeppelin contract templates and patterns
- **[CryptoSkills: viem](https://github.com/0xinit/cryptoskills)** - viem TypeScript client, ABI typing, transports
- **[CryptoSkills: wagmi](https://github.com/0xinit/cryptoskills)** - wagmi React hooks for Ethereum
- **[CryptoSkills: ethers-js](https://github.com/0xinit/cryptoskills)** - ethers.js v6 Provider, Signer, Contract
- **[CryptoSkills: scaffold-eth-2](https://github.com/0xinit/cryptoskills)** - Scaffold-ETH 2 full-stack dApp
- **[CryptoSkills: solana-kit](https://github.com/0xinit/cryptoskills)** - @solana/kit modern tree-shakeable SDK
- **[CryptoSkills: pinocchio](https://github.com/0xinit/cryptoskills)** - Pinocchio zero-copy Solana programs
- **[vasilyu1983: software-crypto-web3](https://github.com/vasilyu1983/ai-agents-public)** - Comprehensive blockchain development: Solidity, Rust, CosmWasm, TON
- **[openclaw: clanker](https://github.com/openclaw/skills)** - Deploy ERC20 tokens on Base and EVM chains
- **[gabrielkoerich: contract-decoder](https://github.com/gabrielkoerich/skills)** - Smart contract bytecode decoder
- **[aaronjmars: agent-credit](https://github.com/aaronjmars/agent-credit)** - Aave credit delegation for AI agents

## Security & Auditing

Skills for smart contract security analysis and vulnerability detection.

- **[Aptos Agent Skills: security-audit](https://github.com/aptos-labs/aptos-agent-skills)** - Security audit for Move smart contracts before deployment
- **[Aptos Agent Skills: generate-tests](https://github.com/aptos-labs/aptos-agent-skills)** - Generate Move unit tests targeting 100% code coverage
- **[CryptoSkills: solidity-security](https://github.com/0xinit/cryptoskills)** - Smart contract security patterns and vulnerability detection
- **[CryptoSkills: slither](https://github.com/0xinit/cryptoskills)** - Static analysis with Slither
- **[CryptoSkills: echidna](https://github.com/0xinit/cryptoskills)** - Fuzzing with Echidna
- **[CryptoSkills: mythril](https://github.com/0xinit/cryptoskills)** - Security analysis with Mythril
- **[CryptoSkills: certora](https://github.com/0xinit/cryptoskills)** - Formal verification with Certora
- **[CryptoSkills: evm-testing](https://github.com/0xinit/cryptoskills)** - EVM testing: fuzz, invariant, fork testing
- **[openclaw: veil](https://github.com/openclaw/skills)** - Privacy and shielded transactions via ZK proofs
- **[OKX OnchainOS: okx-security](https://github.com/okx/onchainos-skills)** - Security scanning, token risk, phishing detection
- **[OpenZeppelin: openzeppelin-skills](https://github.com/OpenZeppelin/openzeppelin-skills)** - Smart contract security patterns with audited libraries
- **[gabrielkoerich: evm-contract-audit](https://github.com/gabrielkoerich/skills)** - EVM smart contract security audit
- **[gabrielkoerich: solana-best-practices](https://github.com/gabrielkoerich/skills)** - Solana security best practices review

## Cross-Chain

Skills for bridging assets and cross-chain operations.

- **[CryptoSkills: layerzero](https://github.com/0xinit/cryptoskills)** - LayerZero omnichain messaging
- **[CryptoSkills: wormhole](https://github.com/0xinit/cryptoskills)** - Wormhole cross-chain transfers
- **[CryptoSkills: hyperlane](https://github.com/0xinit/cryptoskills)** - Hyperlane cross-chain communication
- **[CryptoSkills: axelar](https://github.com/0xinit/cryptoskills)** - Axelar cross-chain network
- **[EmblemCompany: emblem-ai](https://github.com/emblemcompany/agent-skills)** - Cross-chain swaps and bridges across 7 chains
- **[Chainlink: chainlink-cre-skill](https://github.com/smartcontractkit/chainlink-agent-skills)** - CCIP cross-chain operations
- **[MoonPay: moonpay-swap-tokens](https://github.com/moonpay/skills)** - Swap tokens on same chain or bridge across chains
- **[Circle: bridge-stablecoin](https://github.com/circlefin/skills)** - Crosschain USDC via CCTP

## NFTs & Tokens

Skills for NFT operations and token management.

- **[CryptoSkills: erc721](https://github.com/0xinit/cryptoskills)** - ERC-721 NFT contracts and metadata
- **[CryptoSkills: erc1155](https://github.com/0xinit/cryptoskills)** - ERC-1155 multi-token standard
- **[CryptoSkills: erc20](https://github.com/0xinit/cryptoskills)** - ERC-20 token standard
- **[CryptoSkills: metaplex](https://github.com/0xinit/cryptoskills)** - Metaplex NFT standard on Solana
- **[Binance Skills Hub: binance-tokenized-securities-info](https://github.com/binance/binance-skills-hub)** - Tokenized securities information

## Wallets & Identity

Skills for wallet management and onchain identity.

- **[dAAAb: base-wallet](https://github.com/dAAAb/agent-skills)** - Crypto wallet for AI agents on Base chain
- **[dAAAb: basename-agent](https://github.com/dAAAb/agent-skills)** - Register `.base.eth` names onchain via WalletConnect
- **[dAAAb: nad-wallet](https://github.com/dAAAb/agent-skills)** - Monad chain wallet for the Nad ecosystem
- **[dAAAb: nadname-agent](https://github.com/dAAAb/agent-skills)** - Register `.nad` names on Monad blockchain
- **[dAAAb: walletconnect-agent](https://github.com/dAAAb/agent-skills)** - Connect to any dApp via WalletConnect v2, auto-sign txns
- **[EmblemCompany: emblem-ai-agent-wallet](https://github.com/emblemcompany/agent-skills)** - Agent wallet CLI across 7 blockchains
- **[openclaw: metamask-agent-wallet](https://github.com/openclaw/skills)** - MetaMask wallet automation with permission guardrails
- **[openclaw: agentsbank-sdk](https://github.com/openclaw/skills)** - AgentsBank SDK: secure crypto banking operations
- **[CryptoSkills: privy](https://github.com/0xinit/cryptoskills)** - Privy wallet infrastructure
- **[Coinbase: agentic-wallet-skills](https://github.com/coinbase/agentic-wallet-skills)** - Coinbase wallet: auth, fund, send USDC, trade, x402 payments
- **[TrustWallet: tw-agent-skills](https://github.com/TrustWallet/tw-agent-skills)** - Trust Wallet: wallet-core, barz smart wallet, assets
- **[Bitget: bitget-wallet-skill](https://github.com/bitget-wallet-ai-lab/bitget-wallet-skill)** - Bitget Wallet: token swap, cross-chain bridge, gasless transactions
- **[MetaMask: openclaw-skills](https://github.com/MetaMask/openclaw-skills)** - MetaMask OpenClaw integration
- **[tetherto: wdk-agent-skills](https://github.com/tetherto/wdk-agent-skills)** - Self-custodial wallet across 20+ blockchains
- **[OKX OnchainOS: okx-agentic-wallet](https://github.com/okx/onchainos-skills)** - OKX wallet lifecycle management
- **[MoonPay: moonpay-buy-crypto](https://github.com/moonpay/skills)** - Buy crypto with fiat

## Skill Collections

Repositories containing multiple installable crypto skills.

- **[jiayaoqijia/cryptoskill](https://github.com/jiayaoqijia/cryptoskill)** - 977 skills covering the full crypto stack: exchanges, DeFi, wallets, analytics, trading, identity, payments
- **[CryptoSkills](https://github.com/0xinit/cryptoskills)** - 95 skills: uniswap, aave, compound, curve, lido, foundry, hardhat, solidity-security, slither, echidna, and more
- **[OKX Plugin Store](https://github.com/okx/plugin-store)** - 25+ skills: aave-v3, compound-v3, hyperliquid, gmx-v2, polymarket, uniswap, raydium, meteora, orca, pancakeswap, curve, morpho, pendle, pump-fun, and more
- **[OKX OnchainOS Skills](https://github.com/okx/onchainos-skills)** - 13 skills: agentic-wallet, dex-swap, dex-token, dex-market, dex-signal, dex-trenches, security, defi-invest, defi-portfolio, onchain-gateway, x402-payment, wallet-portfolio, audit-log
- **[Binance Skills Hub](https://github.com/binance/binance-skills-hub)** - 10+ skills: binance, binance-web3, onchain-pay, meme-rush, crypto-market-rank, query-token-info, query-token-audit, query-address-info
- **[kukapay/crypto-skills](https://github.com/kukapay/crypto-skills)** - 6 skills: evm-swiss-knife, market-sentiment, meme-scout, token-minter, trading-strategist, yield-opportunities
- **[Aptos Agent Skills](https://github.com/aptos-labs/aptos-agent-skills)** - 8 skills: write-contracts, generate-tests, security-audit, deploy-contracts, search-aptos-examples, analyze-gas-optimization, modernize-move, use-ts-sdk
- **[EmblemCompany/Agent-skills](https://github.com/emblemcompany/agent-skills)** - 4 skills: emblem-ai, emblem-ai-react, emblem-ai-agent-wallet, emblem-ai-prompt-examples
- **[dAAAb/agent-skills](https://github.com/dAAAb/agent-skills)** - 10+ skills: base-wallet, basename-agent, nad-wallet, nadname-agent, walletconnect-agent, basemail, nadmail, ethermail
- **[0x Agent Skills](https://github.com/0xProject/0x-ai)** - 1 skill: 0x-api (token swaps)
- **[agiprolabs/claude-trading-skills](https://github.com/agiprolabs/claude-trading-skills)** - 62 skills: trading, DeFi, quantitative finance
- **[openclaw/skills](https://github.com/openclaw/skills)** - 10+ skills: bankr, erc-8004, botchan, clanker, onchainkit, endaoment, ens-primary-name, veil, metamask, agentsbank
- **[drpcorg/drpc-agent-skills](https://github.com/drpcorg/drpc-agent-skills)** - Blockchain RPC access to 200+ networks
- **[chainstream-io/skills](https://github.com/chainstream-io/skills)** - On-chain data intelligence and DeFi execution
- **[MoonPay: skills](https://github.com/moonpay/skills)** - 20+ skills: swap, buy, prediction-market, trading-automation, messari-research
- **[Base: skills](https://github.com/base/skills)** - 9 skills for Base L2
- **[Circle: skills](https://github.com/circlefin/skills)** - 4 skills: use-usdc, bridge-stablecoin, use-arc, use-gateway
- **[Chainlink: agent-skills](https://github.com/smartcontractkit/chainlink-agent-skills)** - 2 skills: chainlink-cre-skill, ccip-skill
- **[Uniswap: uniswap-ai](https://github.com/Uniswap/uniswap-ai)** - 8 skills across 5 plugins
- **[KuCoin: kucoin-skills-hub](https://github.com/Kucoin/kucoin-skills-hub)** - 7 skills for KuCoin exchange
- **[Bitget: agent_hub](https://github.com/BitgetLimited/agent_hub)** - 6 skills: trading + 5 analyst skills
- **[Rocket Pool: skills](https://github.com/rocket-pool/skills)** - 7 skills for Rocket Pool staking
- **[DefiLlama: defillama-skills](https://github.com/DefiLlama/defillama-skills)** - 10 skills for DeFi analytics
- **[Minara-AI: skills](https://github.com/Minara-AI/skills)** - Personal AI CFO with trading and wallet skills
- **[Senpi-ai: senpi-skills](https://github.com/Senpi-ai/senpi-skills)** - 52 autonomous Hyperliquid trading agents
- **[hummingbot: skills](https://github.com/hummingbot/skills)** - Algorithmic trading infrastructure skills
- **[Crypto.com: crypto-agent-trading](https://github.com/crypto-com/crypto-agent-trading)** - Crypto.com App and Exchange skills
- **[Solana Foundation: solana-dev-skill](https://github.com/solana-foundation/solana-dev-skill)** - Solana development skills
- **[sendaifun: skills](https://github.com/sendaifun/skills)** - Solana Agent Kit skills
- **[OpenZeppelin: openzeppelin-skills](https://github.com/OpenZeppelin/openzeppelin-skills)** - Smart contract security skills
- **[gabrielkoerich: skills](https://github.com/gabrielkoerich/skills)** - Including crypto: binance-prices, contract-decoder, evm-contract-audit, solana-best-practices

---

## Installation

### Skills CLI

```bash
# Install from GitHub
npx skills add kukapay/crypto-skills
npx skills add https://github.com/binance/binance-skills-hub
npx skills add okx/plugin-store
npx skills add okx/onchainos-skills
npx skills add drpcorg/drpc-agent-skills
npx skills add tetherto/wdk-agent-skills

# Install specific skill
npx skills add kukapay/crypto-skills --skill evm-swiss-knife
npx skills add okx/plugin-store --skill hyperliquid-plugin

# Install to specific agent
npx skills add kukapay/crypto-skills -a claude-code
npx skills add kukapay/crypto-skills -a cursor
```

### CryptoSkills CLI

```bash
# Install single skill
npx cryptoskills install uniswap

# Install multiple
npx cryptoskills install aave foundry solidity-security

# Install all 95 skills
npx cryptoskills install --all
```

## Compatible Agents

These skills work with any agent supporting the Agent Skills specification:

- Claude Code
- OpenClaw
- Cursor
- Codex CLI
- Gemini CLI
- GitHub Copilot
- Windsurf
- Cline
- And 30+ more agents

## Contributing

Contributions welcome! To add a skill:

1. It must be open-source
2. It must use SKILL.md format
3. It must be crypto/web3/blockchain focused
4. Submit a PR with the skill name and description

## License

MIT License - see [LICENSE](LICENSE) for details.
