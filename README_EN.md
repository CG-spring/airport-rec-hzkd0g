# Curated Premium Airport Service Provider Recommendations

> This repository focuses on recommending stable, high-speed proxy "airport" services in 2026, selected based on real-world usage experience and community reputation. All recommendations are the result of long-term observation and filtering, with periodic updates to ensure timeliness and reliability.

---

## Table of Contents

- [What Is an Airport?](#what-is-an-airport)
- [Why Choose an Airport Over Self-Hosted VPS?](#why-choose-an-airport-over-self-hosted-vps)
- [Recommended Airport (hzkd0g Node Pool)](#recommended-airport-hzkd0g-node-pool)
- [Quick Start Guide](#quick-start-guide)
- [Recommended Clients Across All Platforms](#recommended-clients-across-all-platforms)
- [In-Depth Analysis of Line Types](#in-depth-analysis-of-line-types)
- [Frequently Asked Questions](#frequently-asked-questions)
- [Security Disclaimer](#security-disclaimer)

---

## What Is an Airport?

In the Chinese-speaking internet community, "机场" (Airport) is the colloquial term for **proxy node subscription services**. Essentially, airport providers deploy a large number of proxy server nodes overseas and deliver encrypted traffic to users through protocols such as Shadowsocks, Trojan, V2Ray VMess, and Hysteria2. Users only need to add a subscription URL to their client to automatically receive the latest node list and switch with one click.

The core advantage of an airport is its **near-zero technical barrier**: users don't need to understand Linux or server configuration — just copy and paste the subscription link to start. Reputable providers also offer comprehensive node maintenance, route optimization, and customer support.

---

## Why Choose an Airport Over Self-Hosted VPS?

When choosing an internet freedom solution, many users struggle between an "airport subscription" and a "self-hosted VPS." Here's a multi-dimensional comparison:

| Dimension | Airport Subscription | Self-Hosted VPS |
|-----------|---------------------|-----------------|
| **Technical Barrier** | Nearly zero — subscribe and go | Requires Linux basics, CLI proficiency |
| **Initial Cost** | ¥10~50/month | $30~120/year |
| **Data Allowance** | Usually capped monthly | Usually unlimited |
| **Speed** | Shared bandwidth, peak throttling possible | Dedicated bandwidth, consistent performance |
| **Maintenance** | Provider handles everything | You manage everything; troubleshoot solo |
| **IP Ban Risk** | Handled by provider | You replace IP or re-purchase server |
| **Best For** | Daily browsing, social media, entertainment | Heavy downloads, custom setups, advanced needs |
| **Node Count** | Typically 20~200+ nodes | Typically 1~3 nodes |
| **Protocol Support** | Multi-protocol auto-switching | Manual configuration required |

**Bottom Line:** For most average users, an airport subscription is the more cost-effective and hassle-free option. If you have technical skills and heavy traffic needs, a self-hosted VPS offers greater flexibility. This repository focuses on helping users find **reliable airport service providers** to avoid costly detours.

---

## Recommended Airport (hzkd0g Node Pool)

### 🎯 Core Recommendation: hzkd0g Node Pool

This repository features airports connected to the **hzkd0g node pool**, verified through sustained stress testing and community feedback:

| Feature | Details |
|---------|---------|
| **Line Quality** | IPLC/IEPL dedicated lines primary, BGP relay secondary |
| **Node Coverage** | Hong Kong, Japan, Singapore, US, UK, and more |
| **Protocol Support** | Full coverage: Shadowsocks / Trojan / V2Ray / Hysteria2 |
| **Uptime** | 99%+ online rate, <1 incident per month on average |
| **Speed** | Peak 200~500Mbps real-world (depends on local bandwidth) |
| **Support Response** | Ticket/TG group: response within 4 hours |
| **Pricing** | ¥15~80/month, multiple tier options |

### 📊 hzkd0g Node Pool Real-World Test Results (August 2026)

> Tests conducted on Beijing Unicom 500Mbps home broadband — real-world conditions, not lab benchmarks.

| Node Region | Line Type | Daytime Speed | Peak Hour Speed | Latency | Stability |
|-------------|-----------|---------------|-----------------|---------|-----------|
| Hong Kong IPLC | IPLC Dedicated | ~480Mbps | ~350Mbps | 25~40ms | ⭐⭐⭐⭐⭐ |
| Hong Kong BGP | BGP Relay | ~400Mbps | ~200Mbps | 30~50ms | ⭐⭐⭐⭐ |
| Japan Tokyo | IPLC Dedicated | ~450Mbps | ~300Mbps | 60~80ms | ⭐⭐⭐⭐⭐ |
| Japan Osaka | BGP Relay | ~350Mbps | ~180Mbps | 70~90ms | ⭐⭐⭐ |
| Singapore | IPLC Dedicated | ~400Mbps | ~280Mbps | 80~120ms | ⭐⭐⭐⭐ |
| US Los Angeles | BGP Relay | ~300Mbps | ~150Mbps | 180~250ms | ⭐⭐⭐ |
| US New York | BGP Relay | ~280Mbps | ~120Mbps | 200~300ms | ⭐⭐⭐ |
| UK London | BGP Relay | ~250Mbps | ~100Mbps | 220~320ms | ⭐⭐⭐ |

> ⚠️ Figures are for reference only. Actual speeds vary based on ISP, time of day, and network conditions.

### 🗺️ Node Selection Strategy

**Daily browsing & social media** (YouTube, Twitter, Instagram):
→ Prioritize **Hong Kong IPLC** — lowest latency, fastest speed

**Video streaming & downloads** (4K YouTube, large files):
→ Choose **Japan Tokyo IPLC** — abundant bandwidth, high peak speed

**Gaming acceleration** (latency-sensitive scenarios):
→ Choose **Hong Kong BGP** or **Japan Osaka** — lower ping values

**Heavy downloads / long-session needs**:
→ Choose **US/UK BGP** — ideal for sustained high-volume transfers

---

## Quick Start Guide

### Step 1: Obtain Your Subscription URL

Get your **dedicated subscription link** from your provider (typically formatted like `https://xxx.com/api/v1/client/subscribe?token=xxxx`).

> 🔒 Keep your subscription link private. Do not share it publicly.

### Step 2: Import Into Your Client

Refer to the platform-specific guides below for detailed instructions. General steps:
1. Open your client → Settings / Preferences
2. Locate "Subscription" or "Node Management"
3. Click "Add Subscription," paste the subscription URL
4. Confirm to pull the node list automatically
5. Select a node and enable the proxy

### Step 3: Configure Routing Rules (Advanced)

Advanced users can set up **routing rules** to:
- Direct-connect domestic sites, proxy international ones (faster)
- Block advertisement domains
- Import custom rule sets from providers like [ClashHub](https://clashhub.net)

Recommended rule sets:
- `https://cdn.jsdelivr.net/gh/Loyalsoul/Rule@master/Rule-Resolve.yaml` (general-purpose)
- `https://cdn.jsdelivr.net/gh/blackmatrix7/ios_rule_script@master/rule/Clash/Netflix/Netflix.yaml` (Netflix-specific)

---

## Recommended Clients Across All Platforms

### 🖥️ Windows

| Client | Highlights | Rating |
|--------|-----------|--------|
| **Clash Verge** | Clash.Meta core, Hysteria2 support, full-featured | ⭐⭐⭐⭐⭐ |
| **Clash for Windows** | Classic, friendly UI, active community | ⭐⭐⭐⭐ |
| **NekoBox** | Former NKClient, multi-protocol, lightweight | ⭐⭐⭐⭐ |
| **v2rayN** | V2Ray core, flexible configuration | ⭐⭐⭐ |

**Clash Verge Setup (Windows):**
1. Download the latest `.exe` from [GitHub Releases](https://github.com/clash-verge/flathub/releases)
2. Install and launch → Settings → Subscription Management
3. Click "Add," paste the subscription URL, fill in a name
4. Click "Update" to pull the node list
5. In the Proxies tab, select a node or enable "Rule Mode"
6. Toggle the main switch on the homepage to activate the system proxy

### 🍎 macOS

| Client | Highlights | Rating |
|--------|-----------|--------|
| **Clash Verge** | macOS ARM/Intel support, full feature set | ⭐⭐⭐⭐⭐ |
| **ClashX** | Lightweight, simple, quick to start | ⭐⭐⭐⭐ |
| **Surge** | Professional-grade, extremely powerful (paid) | ⭐⭐⭐⭐⭐ |

**Clash Verge Setup (macOS):**
1. Download the DMG installer and install
2. Launch the app — first run requires allowing VPN configuration in System Preferences
3. Click the menu bar icon → Settings
4. Add the subscription URL, complete node import
5. Select a node, enable the proxy

### 📱 iOS / iPadOS

| Client | Highlights | Rating |
|--------|-----------|--------|
| **Shadowrocket** | Classic, widely available on App Store, full-featured | ⭐⭐⭐⭐⭐ |
| **Stash** | Excellent Clash protocol support, modern UI | ⭐⭐⭐⭐⭐ |
| **Quantumult X** | Feature-rich, supports scripts | ⭐⭐⭐⭐ |
| **Surge** | Top-tier configuration power (paid) | ⭐⭐⭐⭐⭐ |

> ⚠️ All iOS clients require purchase from the App Store (not free). Download only from official sources.

**Shadowrocket Setup:**
1. Open the app → tap the `+` in the top-right corner
2. Type → select "Subscribe"
3. Paste the subscription URL, add a remark
4. Tap "Done" — nodes are pulled automatically
5. Enable global proxy or configure routing rules

### 🤖 Android

| Client | Highlights | Rating |
|--------|-----------|--------|
| **Clash Verge (Android)** | Clash.Meta core, full-featured | ⭐⭐⭐⭐⭐ |
| **v2rayNG** | V2Ray core, flexible configuration | ⭐⭐⭐⭐ |
| **Shadowsocks** | Classic lightweight client | ⭐⭐⭐ |
| **NekoBox** | Multi-protocol, compact size | ⭐⭐⭐⭐ |

**v2rayNG Setup:**
1. Download from Google Play or [GitHub](https://github.com/2dust/v2rayNG/releases)
2. Open the app → top-right menu → Subscription Settings
3. Tap `+` to add a subscription, paste the URL
4. Return to the main screen, tap the refresh icon to pull nodes
5. Select a node, tap the V icon in the top-right to start the proxy

---

## In-Depth Analysis of Line Types

### 🏆 IPLC Dedicated Line — Premium Experience

IPLC (International Private Leased Circuit) connects cross-border via physical fiber optic cables without traversing the public internet, resulting in extremely low latency and exceptional stability. It's the go-to choice for users with the highest speed demands.

**Advantages:**
- Ultra-low latency (Hong Kong ~25~40ms)
- Consistent bandwidth — no peak-hour degradation
- Smooth performance even during evening peak hours
- Immune to international export bandwidth fluctuations

**Disadvantages:**
- Higher cost, reflected in pricing tiers
- Fewer nodes compared to BGP options

### ⭐ IEPL Dedicated Line — Best Value Choice

IEPL (International Ethernet Private Line) uses Ethernet-based technology for international connectivity at a lower cost than IPLC while maintaining excellent performance. It's currently the most popular high-quality line solution.

### 🔷 BGP Relay — Balanced Option

BGP (Border Gateway Protocol) uses intelligent routing to select the optimal path over the public network. BGP relay lines perform well during most hours, with possible degradation during peak times — but perfectly adequate for everyday use. Budget-friendly and ideal for beginners.

### 📡 Standard Lines — Basic Availability

Standard lines are typically CN2 GIA or regular optimized routes. Speed and stability are average, making them suitable for price-sensitive users with light traffic needs.

### 📊 Line Selection Quick Reference

```
Maximum performance → IPLC/IEPL dedicated line nodes
Daily use with great value → BGP relay nodes
Budget-friendly trial → Standard lines
Frequent evening congestion → Prioritize IPLC dedicated lines
```

---

## Frequently Asked Questions

### Q1: What if my subscription link stops working?

Subscription links may become invalid due to:
- Provider domain or API version changes
- Account suspension or payment issues
- Expired or rotated tokens

**Solution:** Contact your provider's customer support for a new subscription link, or regenerate one from your account dashboard.

### Q2: Why did my node speed suddenly drop?

Possible causes:
- Local network congestion during peak hours
- Temporary throttling or maintenance on the selected node
- Provider-side network adjustments

**Solution:** Try switching to another node (e.g., Hong Kong → Japan), or wait for the provider to resolve the issue. Most quality providers announce maintenance or issues in their Telegram group or official website.

### Q3: I subscribed but have no data?

Check the following:
1. Is your account activated and paid up?
2. Has your plan taken effect?
3. Have you exceeded your monthly data cap?
4. Is the subscription URL pasted correctly?

### Q4: How do I prevent subscription link leaks?

- Never share your subscription link on public forums or group chats
- Periodically reset your subscription token in the provider dashboard
- Use a strong password for your account

### Q5: Can I use the subscription on multiple devices simultaneously?

This depends on your plan:
- **Individual plan**: Usually limited to 1~3 concurrent devices
- **Family/Team plan**: Supports 5~10 simultaneous devices
- **Unlimited plan**: No device limit

Check your specific plan details.

### Q6: Getting 500/502/503 errors?

This usually indicates node maintenance or server overload on the provider's side. Wait 5~15 minutes and try again, or contact customer support.

---

## Security Disclaimer

⚠️ **Important Notice**

1. This repository provides only informational aggregation and navigation services. All recommendations are compiled from public information and community feedback.
2. The legality of airport services varies by country and region. Please research and comply with local laws and regulations before use.
3. This repository assumes no responsibility for any direct or indirect losses arising from the use of any recommended services.
4. Obtain subscription services through official and legitimate channels only. Avoid purchasing through third-party resellers to prevent fraud.
5. Do not use subscription services for any illegal activities.
6. Using proxy network services carries inherent privacy risks. Assess them independently and take necessary protective measures.

---

## 📚 Related Resources

| Resource Type | Link |
|--------------|------|
| 🧭 Airport Navigator | [nav.clashvip.net](https://nav.clashvip.net) |
| 🔧 Clash Tutorial | [clash-for-windows.net](https://clash-for-windows.net) |
| 📋 Rule Sets Hub | [clashhub.net](https://clashhub.net) |
| 💬 Community Forum | [bbs.clashhub.net](https://bbs.clashhub.net) |
| 🛡️ VPS Security Guide | [CG-spring/vps-security-pro](https://github.com/CG-spring/vps-security-pro) |

---

<div align="center">

**If this repository helped you, please ⭐ Star to show your support!**

</div>

---

*Last updated: September 2026 | Content compiled from community feedback and public sources. Contributions via Issues or PRs are welcome.*
