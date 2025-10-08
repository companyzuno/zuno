# 🌌 ZUNO Token

Welcome to the official repository of **ZUNO ($ZUNO)** — the meme token you can actually trust, built on **Solana**.  

ZUNO is not here to reinvent the wheel or promise the “next generation” of anything.  
It’s a meme token — but one with full transparency, fixed supply, and verifiable vesting.

---

## 🧠 Core Principles

- ✅ **Fixed supply** — No mint authority  
- ✅ **No freeze authority** — Tokens cannot be frozen  
- ✅ **Immutable metadata** — Permanently locked on-chain  
- ✅ **Transparent vesting** — All contracts publicly visible on Streamflow  
- ✅ **Public SNS & GitHub verification**

---

## 📜 Overview

| Parameter | Value |
|------------|--------|
| **Blockchain** | Solana |
| **Ticker** | $ZUNO |
| **Total Supply** | 10,000,000,000 $ZUNO |
| **Mint Authority** | ❌ Revoked |
| **Freeze Authority** | ❌ Disabled |
| **Metadata** | 🔒 Immutable |
| **SNS ID** | [zuno_guru.sol](https://www.sns.id/domain/zuno_guru) |
| **Website** | [https://zuno.guru](https://zuno.guru) |

---

## 📊 Token Allocation & Distribution

| Section | % of Total Supply | % Unlock at TGE | Cliff | Unlock Duration | Frequency | Notes | SNS | Vesting Contract |
|----------|------------------|----------------|--------|------------------|------------|--------|------|------------------|
| **Liquidity (Active)** | 7% | 100% | 0 | – | Instant | Added at launch on Meteora DEX for initial liquidity depth. | [liquidity.zuno_guru.sol](https://solscan.io/account/HTvjzsfX3yU6BUodCjZ5vZkUrAxMDTrBs3CJaq43ashR) | — |
| **Liquidity Reserve (Locked)** | 10% | 0% | 0 | 24 months | Quarterly | 1B $ZUNO locked in reserve wallet, released quarterly to stabilize liquidity. | [reserve.zuno_guru.sol](https://solscan.io/account/EZdakQv1REa9MteMvNn1dhMrgsYGqwfs53NJrtpMC731) | [Streamflow Contract](https://app.streamflow.finance/contract/solana/mainnet/4D87Yj1dXHoxXXxLPDfuXMngypCuYBNipD8AEt8TWLrV) |
| **Liquidity Management Wallet** | 3% | 100% | 0 | – | Unlocked | 300M $ZUNO for active liquidity balancing and market depth optimization. | [reserve_mgmt.zuno_guru.sol](https://solscan.io/account/EXAMPLE_MGMT) | — |
| **Advertisement Treasury** | 10% | 0% | 0 | 12 months | Monthly | Linear unlock for marketing and campaigns. | [adv_reasury.zuno_guru.sol](https://solscan.io/account/8X9qqThz75JwXKjZ7qnQ75PAtgZVAvLPj8PgMcHHkuaJ) | [Streamflow Contract](https://app.streamflow.finance/contract/solana/mainnet/6yghMEMixLCWS84CBbxVLStd24BPmtmj5p16hqXiT7BL) |
| **Creator & ZunoCo 1** | 22.5% | 0% | 0 | 24 months | Monthly | Linear monthly unlock for founders & ops. | [czc1.zuno_guru.sol](https://solscan.io/account/8tBqpnBMBjhNyuubmW5FZLYq8u2ohn2kTPVRjHM3nJ8c) | [Streamflow Contract](https://app.streamflow.finance/contract/solana/mainnet/F8i6JxUPR7Jyuvfhftmx9xG4ZMUTCZKqT8XU9qnQLWCV) |
| **Creator & ZunoCo 2** | 22.5% | 0% | 0 | 24 months | Monthly | Linear monthly unlock for strategic team. | [czc2.zuno_guru.sol](https://solscan.io/account/JCXxpkH8M2BXop9nUQ2rdhoHJQctk5wSHQTDk22AE64g) | [Streamflow Contract](https://app.streamflow.finance/contract/solana/mainnet/3uK1TjtgVseNFr7dfj6JzcZdoLH2zzuy3tSevN7s9NWx) |
| **Creator & ZunoCo 3** | 7.5% | 0% | 0 | 24 months | Quarterly | Unlock for project contributors & advisors. | [czc3.zuno_guru.sol](https://solscan.io/account/BixWz3vsKcCoyi45BmYz8yyoFgCJDepxUFX249m5tiFq) | [Streamflow Contract](https://app.streamflow.finance/contract/solana/mainnet/f3rSPQKCwWtH4uN5qa7pMUchfi1xsijabmCJHiEbpim) |
| **Developments** | 10% | 0% | 0 | 12 months | Monthly | Ecosystem & infrastructure development. | [dev4.zuno_guru.sol](https://solscan.io/account/6p346vqTDdFxncz2QN4cfh5MCZ93PZYz8oo1i9cQzvi3) | [Streamflow Contract](https://app.streamflow.finance/contract/solana/mainnet/zJ9JWUfwNVQ61QxrktYJsrx5dacP9Xv9AbWH667PKDR) |
| **Service Providers** | 0.5% | 0% | 0 | 12 months | Monthly | Payments to auditors, legal, and services. | [sp.zuno_guru.sol](https://solscan.io/account/7u4PWjGqKzYKjPurEeTgGe9XipBaVNKp8eSqHaHfjRxu) | [Streamflow Contract](https://app.streamflow.finance/contract/solana/mainnet/GRwD7ssWtrXqR4c6wd57Q7Z8C3USPRH6QHSmsQMMWHGZ) |
| **Staking Rewards** | 7% | 0% | 0 | 24 months | Monthly | Rewards for staking participants via Streamflow. | [staking_rewards.zuno_guru.sol](https://solscan.io/account/EXAMPLE_STAKE) | [Streamflow Contract](https://app.streamflow.finance/staking/solana/mainnet/DhsyDTQAhPZbUWAff92FZzUctGzWBrwzrqpvsC6ipb5c) |


[^dlmm]: LP model is **Meteora DLMM** (per-bin **NFT** positions). LP lock % on scanners may appear **N/A/0%** by design.
---

## 🏦 Liquidity Structure

### ℹ️ DLMM LP Token Model (Meteora)

Our liquidity pool uses **Meteora DLMM**, which **does not issue a single LP token**.  
Each liquidity position is an **NFT** spanning specific price bins. Because of this,
third-party scanners that rely on a unified “LP token supply / LP locked %” may show
**0% or N/A** for LP lock — this is **expected for DLMM pools** and does not imply
unlocked liquidity.

💧 Liquidity in ZUNO is multi-layered:  
- **7% active** — launched on Meteora DEX (live trading pool).  
- **10% reserve** — 1B $ZUNO locked, unlocking quarterly for 24 months.  
- **3% management wallet** — 300M $ZUNO for DEX depth control.  

All reserves are verifiable on-chain under the SNS identity  
🔗 [zuno_guru.sol](https://www.sns.id/domain/zuno_guru).

---

## 🪙 Staking

- 7% of total supply is allocated for staking rewards.  
- Distributed linearly over 24 months via **Streamflow Finance** smart contracts.  
- Pools will be live soon on Streamflow — links will be added post-deployment.

---

## 🔒 Security & Transparency

| Category | Status |
|-----------|--------|
| Mint Authority | Revoked ✅ |
| Freeze Authority | Disabled ✅ |
| Metadata | Immutable ✅ |
| Token Source | Public on GitHub ✅ |
| Audits | In progress 🔍 |
| SNS | [zuno_guru.sol](https://www.sns.id/domain/zuno_guru) |
| Website | [https://zuno.guru](https://zuno.guru) |

---

## 🌍 Official Links

- 🌐 Website — [zuno.guru](https://zuno.guru)  
- 🐦 Twitter — [x.com/zuno_guru](https://x.com/zuno_guru)  
- 💬 Telegram — [t.me/zuno_guru](https://t.me/zuno_guru)
- 🎵 TikTok — [tiktok.com/@zunoguru](https://www.tiktok.com/@zunoguru)
- 💻 GitHub — [companyzuno/zuno](https://github.com/companyzuno/zuno)  
- 💧 Meteora Pool — [Official ZUNO Pool](https://www.meteora.ag/dlmm/7jfWod7G5YTFuhtvtKeKgRWipoMhS2LpSMAS1fVyo6WM)

---

## ⚠️ Disclaimer

ZUNO Tokens are intended as an expression of support for the ideas and community of **“$ZUNO”**,  
and are **not** investment instruments or securities.  

**Zuno Company LLC** owns the “ZUNO” brand, SNS ID, and domain **zuno.guru**.  
The company does not request personal information from holders and does not guarantee price performance.  
Always verify all official information from the channels listed above.

---

