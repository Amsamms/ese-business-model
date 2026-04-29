# Model B — EPROM-Hosted Corporate SaaS for EGPC Refineries

## Positioning (one line)

> "ESE delivers AI-powered engineering intelligence to Egypt's petroleum refineries, hosted on EPROM's Cairo data center, with every byte of your plant data staying inside Egypt. Your refinery, your data, our AI — Egyptian sovereign operations intelligence."

---

## 1. Product definition (what EPROM sells)

Two simple SaaS SKUs, priced for Egyptian economic reality. Delivered via EPROM-hosted cloud platform (Claude API initially, self-host only when volume justifies). Each customer gets an isolated tenant (separate DB schema, AI credits pool, admin panel).

| SKU | Price (list, EGP/yr) | Scope | Target buyer |
|---|---|---|---|
| **ESE Refinery Starter** | **100,000** | Up to 10 named users/site. All ESE engineering apps (heater, pump, massmole, 4 optimizers + v2 expansion). Shared EPROM KB. AI quota 50K units/yr. Standard SLA, business-hours email support. Annual contract. | First-time refinery pilot. Entry point for any EGPC subsidiary. |
| **ESE Refinery Professional** | **200,000** | Up to 25 named users/site. All apps. **Custom RAG ingestion** up to 2,000 pages of customer SOPs/manuals. AI 150K units/yr. Priority SLA, phone + email support. Quarterly engineering review. Annual contract. | Refinery with active usage, wants plant-specific KB. |

**Add-on: Additional Seats** — +10 users for 50,000 EGP/yr on either tier.
**Add-on: Ingestion Pack** — one-time 150,000 EGP per 2,000 pages of additional document ingestion.

**Launch pricing:** First 3 pilots 50% discount Y1 in exchange for case-study rights = 50K / 100K EGP real Y1. Low risk, easy yes for procurement managers.

## 2. Target customers & TAM

Egypt has ~10-12 EGPC downstream refining subsidiaries. This is the addressable market — focused, bounded, relationship-driven.

| Priority | Customer | Rationale | Entry SKU | Steady-state target |
|---|---|---|---|---|
| 1 | **MIDOR** | 170K bbl/d, $2.2B modernized, EGPC 78%, Alexandria neighbor, digital-forward | Starter Y1 → Professional Y2 | 200K/yr |
| 2 | **CORC** (Mostorod + Tanta) | 142K bbl/d, EGP 4.47B capex, already AVEVA/EPROM relationship | Starter Y1 → Professional Y2 | 200K/yr |
| 3 | **ANOPC / ASORC** | $3B Assiut hydrocracker, EPROM O&M contract, Metwally's domain — direct path | Starter Y2 (after ANOPC trial) | 200K/yr |
| 4 | **APC** (Alexandria Petroleum) | Mature refiner, Alex proximity, follows MIDOR's lead | Starter Y2 | 100K/yr |
| 5 | **SOPC** | Suez Canal corridor | Starter Y2 | 100K/yr |
| 6 | **Ameriya Petroleum** | Free Zone, adjacent to MIDOR | Starter Y3 | 100K/yr |
| 7 | **GPC** (El Nasr) | EGPC subsidiary | Starter Y3 | 100K/yr |
| 8 | **SIDPEC** | Petrochemical variant, adjacent to EPROM Sidi Krir | Starter Y3 | 100K/yr |
| 9-10 | **+2 smaller EGPC subsidiaries** | BAPETCO, Khalda, or similar | Starter Y3 | 100K/yr each |

### TAM (Egyptian Economic Reality)

| Tier | Customers | Avg ticket | Annual total |
|---|---|---|---|
| Professional (active, expanding) | 4 (MIDOR, CORC, ANOPC, APC) | 200K/yr | 800K |
| Starter (first-time) | 6 (SOPC, Ameriya, GPC, SIDPEC, +2) | 100K/yr | 600K |
| Ingestion add-ons | 2-3 engagements/yr | 150K each | 300-450K |
| **Total addressable steady-state** | **10 companies** | | **~1.7-1.85M EGP/yr** |

**Realistic capture Y3:** 70-80% = **~1.2-1.5M EGP/yr**. This is the honest ceiling for Egypt's petroleum sector right now.

**Critical insight:** This TAM alone does NOT justify a self-hosted GPU server. Model B stays lean — Claude API → RunPod when volume hits — until Model C (on-prem appliance, deferred to Y2-3) places hardware at customer sites on their budget.

## 3. Pricing rationale

### Why 100K-200K EGP/yr?

This is the real budget ceiling for Egyptian EGPC subsidiaries buying non-mission-critical software. Validated through EPROM's direct operational experience with these companies:

| Benchmark | Reality check |
|---|---|
| AVEVA PI System (enterprise) | $500K-2M/yr — PIPELINE-level spend, not departmental. SEPARATE budget line from software tools. |
| Egyptian refinery software PO history | Department-level tools: 50K-300K EGP. Plant-level: 1M-5M. Only pipeline/corporate: 10M+. |
| EGPC subsidiary discretionary IT budget | ~500K-2M EGP/yr TOTAL across all software tools. ESE gets a slice, not the whole pie. |
| Competitor: manual consultants | EPROM already charges 200-500K/yr for engineering consulting to these same companies. ESE as AI tool priced BELOW EPROM's own human services = internally consistent. |

### Why this pricing WORKS

1. **Below tender threshold.** Deals under ~500K EGP can often be direct awards (Law 182/2018 Art 20) — no 6-9 month tender cycle. Speed matters more than ticket size.
2. **Easy procurement yes.** 100K EGP/yr = department manager can approve. 3M+ EGP/yr = board-level decision. We want the fast yes.
3. **Land-and-expand.** Start at 100K Starter. Prove value. Upgrade to 200K Professional. Add seat packs. Add ingestion packs. ARR grows WITHIN each account.
4. **10 companies × 150K avg = 1.5M EGP/yr steady state.** Lean enough to run on cloud AI, profitable at ~50% gross margin.
5. **Pricing matches Egypt 2026 reality.** EGP devaluation (30→50/USD in 2024-2026), subsidy pressure, IOC arrears, tight budgets. Software spend is first cut. Must be undeniable value at the price point.

### Pricing principles
- Annual contracts, net-60 payment
- First 3 pilots 50% off Y1 for case-study rights
- Annual escalator: CPI-Egypt (no +2% at this price point — keep it simple)
- Seat add-ons: 5,000 EGP/seat/yr (10-pack minimum at 50K)
- No long-term lock-in — product quality IS the retention strategy

## 4. Marketing & sales

Lean marketing — relationship-based, not ad-spend heavy. EPROM already has the relationships; ESE is an add-on conversation, not a cold sale.

### Y1 go-to-market

| Channel | Action | Cost EGP | Timing |
|---|---|---|---|
| **Elyamani-led EGPC outreach** | Demo meetings MIDOR + CORC + ASORC. CEO Asaad attends first meeting | 50K | Y1Q3 |
| EGYPS 2027 booth | ESE section within EPROM booth, live AI demo | 400K | Y1Q4 (Feb 2027) |
| Direct LinkedIn + Arabic tech press | Egypt Oil & Gas feature. CEO Asaad + Metwally thought leadership | 100K | Ongoing |
| Arabic website + demos | Arabic-first landing page, demo videos | 150K one-time | Q2 2026 |

**Y1 marketing: ~700K EGP.** Down from the original 1.85M — relationship-driven, not spray-and-pray.

### Y2-3 (case-study driven)
- MIDOR case study published (Q2 Y2)
- ESE Customer Day Cairo (invite-only, 15 EGPC subsidiary VPs)
- Giza Systems channel partnership (Y2) for EGPC subsidiaries without EPROM direct relationship
- Y2 marketing: ~500K, Y3: ~600K

### Sales motion
- **Direct relationship** for MIDOR, CORC, ANOPC/ASORC — Ahmed + Elyamani + CEO Asaad cover
- **Channel through Giza Systems** for SOPC, GPC, Ameriya, others
- Typical cycle: 3-5 mo for Starter (sub-500K direct award, no tender). 6-12 mo if tender required.

## 5. Cash flow (quarterly, EGP thousands)

### Revenue — realistic ramp (3 pilots Y1, 7 companies Y2, 10 Y3)

| Quarter | Event | Revenue (EGP K) |
|---|---|---|
| Y1Q1-Q2 | Pre-launch, product hardening | 0 |
| Y1Q3 | First pitch meetings | 0 |
| Y1Q4 | **3 pilots signed** (MIDOR, CORC, ANOPC at 50K each). 50% on signature | 75 |
| **Y1 total** | | **75** |
| Y2Q1 | 3 pilots renew at full price (200K total). +2 new Starter (APC, SOPC at 50K) | 250 |
| Y2Q2 | +1 new Starter (Ameriya at 50K). First ingestion pack sold (MIDOR, 150K) | 200 |
| Y2Q3 | MIDOR + CORC upgrade to Professional (incremental 100K each). Recurring base builds | 350 |
| Y2Q4 | +1 new Starter (GPC at 100K). Second ingestion pack (CORC, 150K) | 350 |
| **Y2 total** | | **1,150** |
| Y3Q1 | 7 companies recurring (3 Professional + 4 Starter). +1 new (SIDPEC, 100K) | 450 |
| Y3Q2 | 8 companies recurring. ANOPC upgrades to Professional (+100K). Ingestion SIDPEC (150K) | 550 |
| Y3Q3 | 9 companies recurring. +1 new (BAPETCO, 100K). Ingestion ANOPC (150K) | 600 |
| Y3Q4 | 10 companies steady state (4 Professional + 6 Starter). 2 ingestion packs/yr | 650 |
| **Y3 total** | | **2,250** |
| **3-yr total** | | **3,475** |

### Costs — cloud-first, lean team

| Category | Y1 | Y2 | Y3 | Notes |
|---|---|---|---|---|
| Team salaries | 600 | 1,200 | 1,800 | See hiring plan — 4→7→10 FTE lean |
| Claude API / RunPod hosting | 50 | 180 | 360 | API costs scale with users. Migrate to RunPod when >5 companies |
| Existing EC2 + cloud infra | 36 | 60 | 90 | Already running; marginal cost only |
| Marketing & sales | 700 | 500 | 600 | Relationship-driven, low spend |
| Customer acquisition (travel, demos) | 100 | 200 | 300 | Site visits, POC setup |
| Legal / EULA / contracts | 150 | 50 | 50 | Y1: EULA templates + simple SaaS terms |
| ITIDA registration | 50 | — | — | One-time |
| Ingestion delivery (COGS) | 0 | 100 | 150 | Contractor OCR + curation per engagement |
| Misc / contingency (10%) | 170 | 230 | 335 | |
| **Total** | **1,856** | **2,520** | **3,685** | |

### Net cash flow

| Year | Revenue | Costs | Net |
|---|---|---|---|
| Y1 | 75 | 1,856 | **-1,781** |
| Y2 | 1,150 | 2,520 | **-1,370** |
| Y3 | 2,250 | 3,685 | **-1,435** |
| **3-yr cumulative** | 3,475 | 8,061 | **-4,586** |

**Honest assessment:** Model B standalone is cash-negative through Y3 at this pricing level. It requires Model A (individual SaaS) to carry the shared costs OR it's the EGPC strategic play that EPROM subsidizes for 2-3 years as market entry. **This is the economic reality of selling software to Egyptian petroleum in 2026.**

**Break-even realistically Y4-Y5** when 10 companies at steady state (1.8M/yr revenue) cover the lean team (2M/yr costs). The gap is small enough to close with 2-3 ingestion packs or seat expansions per year.

## 6. ROI / payback

| Metric | Conservative | Realistic | Aggressive |
|---|---|---|---|
| Y3 revenue | 1,800 | 2,250 | 3,000 |
| Y3 costs | 3,200 | 3,685 | 4,500 |
| 3-yr net | -5,500 | **-4,586** | -2,500 |
| Payback | Y5+ | Y4-Y5 | Y4 |
| Y5 run-rate ARR | ~1.5M | ~1.8M | ~2.5M |
| Y5 net | ~+200K | ~+500K | ~+1M |

**Model B ROI is NOT a standalone financial return story.** It's a **strategic market-entry investment**: establish ESE inside EGPC refineries at a price they can say yes to, build references, then expand via Model C (on-prem appliance at 8-18M) and Model D (Giza channel at larger scale).

**The real return:** 10 EGPC refinery references = the credential to sell Model C at 10× the ticket size.

## 7. Hiring — lean team

At 100K-200K/company pricing, Model B cannot support a large dedicated team. It LEVERAGES existing EPROM engineering (Ahmed + Amr + Tariq + Aya) and Model A shared hires.

### Y1 (2 dedicated hires, partial year)

| Mo | Hire | EGP/mo | Annual | Why |
|---|---|---|---|---|
| M3 | Customer Success / Account Manager | 25K | 250K (partial) | Onboarding 3 pilots, SLA, relationship management |
| M5 | BDR / Sales support (part-time) | 15K | 150K (partial) | EGPC pipeline tracking, tender docs, meeting prep |

**Y1 dedicated salary: ~400K.** Plus 200K allocation from Model A shared team.

### Y2 (+2 hires)

| Mo | Hire | EGP/mo | Why |
|---|---|---|---|
| M13 | Backend Dev (mid) | 40K | v2 stabilization, tenant provisioning, ingestion pipeline |
| M15 | Solutions Engineer (junior) | 30K | Pre-sales demos, POC setup, on-site onboarding |

**Y2 dedicated: ~1.2M EGP** (4 FTE). Model A shared allocation reduces to 100K.

### Y3 (+1 hire)
- 1× Data Engineer (mid, 45K) — scale ingestion across 10 tenants

**Y3 dedicated: ~1.8M EGP** (5 FTE). Total team including Model A overlap: ~7 people.

**Key difference from original:** No 17-person organization. No senior ML engineer. No DevOps. No enterprise sales lead at 120K/mo. Cloud AI removes the need for self-host expertise. Relationship sales removes the need for a dedicated enterprise rep.

## 8. Certifications + legal (lightweight)

At this price point, ISO 27001 is overkill. Focus on legally-operational essentials.

| Item | Cost EGP | Timeline | Why |
|---|---|---|---|
| EULA + SaaS Terms of Service | 80 | 1-2 mo | Contract template, reusable for all customers |
| Commercial Register update (add software activity) | 20 | 2-4 wk | If not already covered |
| ITIDA registration (voluntary) | 50 | 4-6 wk | Credibility + grant eligibility |
| Copyright (Law 82/2002) — code + docs | 10 | 1-3 mo | Standard IP protection |
| Trademark "ESE" | 15 | 6-12 mo | File early, use upon application |
| **Total Y1 legal** | **~175K EGP** | | |

**Deferred to Model C:** ISO 27001 (~500K), subsidiary incorporation (~1M), DPA/privacy framework, pen-test certs. These only make sense at Model C ticket sizes (8M+).

**Why no subsidiary Y1?** At 1.8M/yr TAM, a separate legal entity with 500K/yr overhead burns 28% of revenue on admin. Run ESE as a business line within EPROM with separate P&L tracking until Y3+.

## 9. Infrastructure — cloud-first, hardware reference included

**Strategy: Cloud-first in Y1-Y3. NO self-hosted GPU purchase.** The TAM (1.8M EGP/yr) doesn't justify it. But when management asks "what WOULD hardware cost?", this section answers with real numbers.

### AI Backend Phases

| Phase | AI Backend | Monthly Cost | Annual | When |
|---|---|---|---|---|
| **Current** | Claude Haiku 4.5 API | ~$35 (1,820 EGP) | ~22K EGP | Now (23 users) |
| **Model B Y1** | Claude API, prompt caching | ~$200-400 (10-21K EGP) | ~120-250K EGP | Y1 (3 companies, ~30 users) |
| **Model B Y2** | Claude API or RunPod Qwen3-32B | ~$800-1,500 (42-78K EGP) | ~500-940K EGP | Y2 (7 companies, ~70 users) |
| **Model B Y3** | RunPod Qwen3-32B or self-host IF Model C justifies | ~$2,000-3,000 (104-156K EGP) | ~1.2-1.9M EGP | Re-evaluate Y2Q4 |

### Why cloud-first for Model B

| Reason | Detail |
|---|---|
| **TAM too small** | 1.8M EGP/yr steady state does NOT amortize 5-7M EGP hardware |
| **Payback math** | 5.7M ÷ 1.8M = **3.2+ years** just to recover hardware cost — before team, marketing, or any other costs |
| **Risk** | Self-host is a fixed sunk cost. Cloud scales down if pilots don't convert |
| **Trigger** | Self-host only when Model C (on-prem at 8-18M per deal) places hardware on customer budget |

### Self-host hardware capital costs (REFERENCE — when management asks "what if?")

All prices Egypt landed (30-50% customs markup). 1 USD ≈ 52 EGP (April 2026). For detailed component breakdown see Model A Section 9.

**Tier 3 — Qwen3-32B on 4× A100 80GB (entry self-host)**

| Component | Cost (EGP) |
|---|---|
| Dell PowerEdge R760xa + 2× Xeon Gold 6438Y + 256 GB DDR5 + 4× A100 80GB + 4×1.92TB NVMe | 5,200,000 – 7,280,000 |
| Monthly colocation + electricity | 30,000 – 40,000 |
| Capacity | 80-100 concurrent users |
| Break-even vs cloud (RunPod at ~90K/mo) | **5-7 years** — cloud wins |

**Tier 2 — GLM 5.1 INT4 on 8× A100 80GB (mid-tier)**

| Component | Cost (EGP) |
|---|---|
| Dell PowerEdge XE9680 + 2× Xeon Gold 6442Y + 512 GB DDR5 + 8× A100 80GB SXM4 + 4×3.84TB NVMe | 10,400,000 – 14,560,000 |
| Capacity | GLM 5.1 INT4, 20-30 concurrent |
| Break-even vs cloud | **3-5 years** |

**Tier 1 — GLM 5.1 FP8 on 8× H200 141GB (best quality)**

| Component | Cost (EGP) |
|---|---|
| Dell PowerEdge XE9680 + 2× Xeon Gold 6548Y+ + 1 TB DDR5 + 8× H200 141GB SXM5 + 8×3.84TB NVMe + 2×100GbE | 18,200,000 – 23,400,000 |
| Capacity | GLM 5.1 FP8, 30-40 concurrent |
| Break-even vs cloud | **2-3 years** |

### Individual GPU pricing (Egyptian market, April 2026)

| GPU | VRAM | USD | EGP Landed | Source |
|---|---|---|---|---|
| NVIDIA A100 80GB PCIe | 80 GB | $15K-17K | ~1,135,000 | ServerBasket Egypt |
| NVIDIA H100 80GB SXM5 | 80 GB | $35K-40K | ~1.8M-2.1M | OEM (in-server) |
| NVIDIA H200 141GB SXM5 | 141 GB | $35K-45K | ~1.8M-2.3M | OEM (in-server) |
| NVIDIA RTX 4090 24GB | 24 GB | $2.1K-3K | 110K-155K | Baraka / Compumarts |
| NVIDIA RTX 5090 32GB | 32 GB | $3K-3.85K | 157K-200K | Compumarts / Baraka |

### Egyptian hardware vendors

- **Caironix Egypt** — Dell, Supermicro, NVIDIA, HP (caironix.com)
- **Elite Technology Egypt** — Dell, NVIDIA, HP (elite.com.eg)
- **ServerBasket Egypt** — Dell, HP, NVIDIA, Supermicro (serverbasket.net/eg)
- **Lenovo Egypt** — Lenovo ThinkSystem (lenovo.com/eg)
- **Compumarts Egypt** — consumer GPUs (compumarts.com)
- **Baraka Computer Store** — consumer GPUs (barakacomputer.net)

### Cloud vs. buy break-even summary

| Config | Cloud/yr (RunPod) | Buy (EGP landed) | Break-even | Verdict |
|---|---|---|---|---|
| 2× A100 (Qwen3-32B) | ~1.08M EGP | 5.2-7.3M | **5-7 yr** | Cloud wins for Model B |
| 8× A100 (GLM 5.1 INT4) | ~4.34M EGP | 10.4-14.6M | **3-5 yr** | Cloud still wins |
| 8× H200 (GLM 5.1 FP8) | ~11.99M EGP | 18.2-23.4M | **2-3 yr** | Buy only at Model C scale |

### Recommendation (unchanged)

- **Y1-Y3:** Claude API → RunPod. Zero hardware capital. Variable cost scales with revenue.
- **Y4+:** Re-evaluate ONLY if Model C has placed on-prem hardware at ≥3 customer sites, creating a shared-infrastructure case. Hardware will be 30-50% cheaper by then (AI depreciation thesis).
- **Self-host only at Model C scale** (8M+ per deal, customer pays hardware). Model B's 1.8M/yr TAM does NOT carry a 5-7M EGP capital purchase.
- **Switching cost:** 2-3 Claude Code sessions to migrate from Claude API to RunPod Qwen3-32B (prompt recalibration only, no code changes).

### Deployment

- Existing EC2/KVM infrastructure (portal, heater, pump, optimizer containers)
- Multi-tenant: separate DB schemas per customer (PostgreSQL), tenant_id on all tables
- No VPN/MPLS at this price point — standard HTTPS + JWT auth
- Customers access via web browser, no on-prem installation
- Law 151/2020: no operational data leaves Egypt. Claude API calls send only engineered prompts, not raw refinery data.

## 10. Quarterly milestones

### Year 1 (Apr 2026 - Mar 2027)

| Q | Milestones | Go/No-go gate |
|---|---|---|
| **Q1** | v2 roadmap final; Arabic landing page live; EULA/SaaS terms drafted; ITIDA application filed | v2 engineering kickoff confirmed |
| **Q2** | v2 alpha (5 new equipment + AI chat working); multi-tenant DB schema designed; hire CS/Account Manager | v2 alpha demo-able internally |
| **Q3** | v2 beta (all 15 equipment); first pitch meetings MIDOR + CORC via Elyamani; EGPS 2027 booth prep; 3 pilot MOUs drafted | ≥3 qualified pilot conversations in flight |
| **Q4** | **3 pilots signed (MIDOR, CORC, ANOPC at 50K EGP each)**; EGYPS 2027 launch; v2 GA | End-Y1: **3 signed pilots** OR revert to Model A-only strategy |

### Year 2 (Apr 2027 - Mar 2028)

| Q | Milestones |
|---|---|
| Q5 | 3 pilots renew at full price + deliver KPIs. 2 new Starter deals (APC, SOPC). First ingestion pack sold (MIDOR) |
| Q6 | MIDOR + CORC upgrade to Professional. MIDOR case study published. ESE Customer Day Cairo (invite-only) |
| Q7 | Ameriya + GPC signed. Giza Systems channel partnership activated. Team grows to 4 FTE |
| Q8 | 7 companies active. Second ingestion pack sold. RunPod migration evaluated based on API spend |

### Year 3 (Apr 2028 - Mar 2029)

| Q | Milestones |
|---|---|
| Q9 | SIDPEC signed (petchem vertical). 8 companies active. ANOPC upgrades to Professional |
| Q10 | BAPETCO/Khalda signed. 9 companies. 2 ingestion packs/yr cadence established |
| Q11 | 10 companies steady state. Evaluate Model C on-prem at MIDOR/ANOPC |
| Q12 | Y3 revenue ≥2M. Cumulative 3-yr net ~-4.5M. Decision gate: continue to Y4-5 profitability or fold into Model C |

## 11. Risks (ranked, with mitigations)

| # | Risk | Likelihood | Impact | Mitigation |
|---|---|---|---|---|
| **1** | **EGPC procurement delays** | HIGH | Y1 revenue → Y2 | Direct award path (Law 182/2018 Art 20) for sub-500K deals — no tender needed |
| **2** | **Egyptian fiscal constraints** (EGPC $5B arrears, tight budgets) | HIGH | Smaller deals, payment delays | 100K entry = department-level approval, not board-level. Easy internal yes |
| **3** | **Metwally champions product without internal reference** | HIGH | Credibility gap | Ingest ANOPC data Q2 internally as R&D validation; free 30-day POC for first 3 pilots |
| **4** | **v2 product slip** (15 equipment in 9 mo) | MED-HIGH | Delayed Q3 pitch | Top-5 equipment Q2; remaining 10 Q3-Q4 incremental |
| **5** | **Competitor response** (MEEG/AVEVA discount or FUD) | MEDIUM | Block 1-2 logos | EPROM direct operational relationship → trust beats brand. Price is already floor-level |
| **6** | **Key-person risk** (Ahmed/Metwally) | MEDIUM | Project stalls | Document in PROGRESS.md; spread customer relationships across team |
| **7** | **Model A doesn't take off** → no user feedback to feed Model B | MEDIUM | Product validated slower | Direct pilot feedback from 3 early customers substitutes for Model A data |
| **8** | **Claude API cost overrun** | LOW | Margin squeeze | Migrate to RunPod when API bill > RunPod cost (~Y2); hard cap per tenant |

## 12. Why EPROM+ESE vs alternatives

**One sentence:** *"ESE is the only AI engineering tool built by Egyptian process engineers, sold at a price Egyptian refineries can actually pay, backed by EPROM's 24-year operational track record inside these same plants."*

| Dimension | EPROM + ESE | MEEG + AVEVA | Generic AI (ChatGPT/Claude) |
|---|---|---|---|
| **Price (per yr)** | 100-200K EGP | 3-18M EGP | $20-200/mo per user |
| **Domain depth** | Egyptian refinery formulas, Arabic UI, local KB | Global generic model | Zero domain knowledge |
| **Data sovereignty** | Egyptian cloud (Claude API prompt-only) | Foreign cloud (AVEVA CONNECT) | US cloud |
| **Relationship** | EPROM already inside ANOPC, MIDOR-neighbor | Reseller without ops context | None |
| **Speed of iteration** | Weekly — user feedback → update in days | Quarterly releases | Outside our control |
| **Why a refinery buys** | "Cheaper than our annual software training budget" | "Enterprise-grade, enterprise-price" | "Not built for refineries" |

## 13. Verdict (with conditions)

### RECOMMENDATION: APPROVE as strategic market-entry investment, not standalone profit center.

Model B is the EGPC play at honest Egyptian pricing. At 100-200K EGP/yr per company, it is cash-negative through Y3. But it achieves what the old 3M+ pricing could not: **actual signed contracts at a price Egyptian refineries can say yes to.**

### Three approval gates

**(a) 3 pilots signed by Y1Q4.** MIDOR + CORC + ANOPC at 50K EGP each (50% launch discount). If not 3, re-evaluate.

**(b) v2 product ready by Y1Q3.** 15 new equipment types + working AI chat = minimum credible demo.

**(c) Model A running in parallel.** Model A carries the shared team costs and provides user feedback to feed Model B's product quality.

### Hard truths Metwally must acknowledge

1. **This is not a cash cow.** At Egypt's real price ceiling, Model B is a strategic investment that builds reference cases for higher-ticket Models C/D.
2. **No self-hosted GPU in Y1-Y3.** The TAM doesn't justify it. Cloud AI keeps costs variable and risk low.
3. **No 17-person organization.** The team is 2-5 people leveraging existing EPROM engineers. Lean by necessity.
4. **The real return is in Y4+.** 10 EGPC refineries as references → Model C on-prem at 8-18M per deal → Model D regional expansion via Giza.

### Bottom line

> "Model B gets ESE inside Egypt's refineries at a price they can actually pay. It won't make money on its own — but it builds the reference base that makes Model C possible. Think of it as the cost of market entry: ~5M EGP over 3 years to establish ESE as the standard AI tool across 10 EGPC refineries. From there, Model C monetizes at 10× the ticket size."

**Recommend:** Run Model B as the strategic EGPC track alongside Model A (cash-flow + feedback). The two together cost ~6.4M over 3 years combined. Model A carries the shared overhead; Model B delivers the enterprise credibility.
