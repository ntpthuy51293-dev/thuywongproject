# Bottleneck Scan #1: Economy + Technology (3 Oct 2026)

> **Research, not financial advice.** This is a first-pass scan built from public web sources on 3 Oct 2026. Numbers come from the linked sources and were not independently audited. Many of the names below have already moved a lot; check price, valuation and your own risk tolerance before acting on anything here.

## The big picture in one paragraph

The dominant economic and technology story of 2026 is the AI infrastructure build-out. UBS estimates hyperscaler capex at about **$1.0 trillion in 2026 and $1.45 trillion in 2027**, with Amazon, Alphabet and Microsoft spending roughly **102% of their cloud revenue on capex** ([Yahoo Finance, 22 Aug 2026](https://finance.yahoo.com/technology/ai/articles/ai-absurd-spending-boom-hyperscalers-162709082.html)). Money is no longer the constraint. Physical things are: power equipment, memory, packaging, lasers, materials and skilled labor. The pattern analysts keep pointing out is **"cascading constraints": solving one bottleneck exposes the next one** ([404K Semi-AI Weekly, 2 Oct 2026](https://404kresearch.substack.com/p/404k-semi-ai-weekly-oct-2-2026-bottlenecks)). For an investor looking for early trends, the useful question is **which bottleneck is next, and who owns the scarce supply there.**

## Bottleneck map

| # | Theme | The bottleneck | How long it lasts (per sources) | Stage |
|---|---|---|---|---|
| 1 | Power generation | Gas turbines are sold out; grid hookups take 5-6 years | Slots booked into 2031-2034 | Well known |
| 2 | Grid equipment | Large transformers and the special steel inside them | Lead times 3-5 years | Known, still under-appreciated |
| 3 | Memory | HBM / DRAM for AI chips | Allocated through 2026, tight into 2027 | Well known, very priced in |
| 4 | Chip packaging | TSMC CoWoS capacity, then ABF substrates and glass cloth beneath it | Substrate shortage projected through 2028 | Moving down the stack now |
| 5 | Optical networking | Indium phosphide (InP) lasers and substrates | Demand exceeds supply by 30%+ | Hot since Mar 2026 |
| 6 | Data center power and cooling | Liquid cooling, 800V DC power delivery | Rack power heading to 1 MW | Cooling known; 800V DC early |
| 7 | Critical materials | Copper deficit; rare-earth magnets controlled by China | Multi-year | Known, policy-driven |
| 8 | Nuclear fuel | Uranium enrichment and conversion | US deficit of ~11 million SWU/year | Early-to-mid |
| 9 | Labor | Electricians and grid construction crews | Ongoing | Under-appreciated |

---

## 1. Power generation: turbines are sold out

**The bottleneck.** Grid interconnection now takes 5-6 years in key markets, so data center developers try to build their own gas generation, and then find turbine makers are just as constrained. A turbine slot for 2031 has become a strategic asset ([Supercomputing News](https://www.supercomputing.news/ai/ai-data-center-power-bottleneck-gas-turbine-slot)).

**Companies working on it**

| Company | Ticker | Evidence |
|---|---|---|
| GE Vernova | GEV | Q2 2026 orders **+88% to $24.2B**, backlog **$176B**; 116 GW of gas turbines under contract or reserved, targeting 125 GW by year end; raising output from ~3 GW to ~5 GW per quarter; FY26 free cash flow guidance more than doubled to $11.5-12.5B ([BigGo Finance, 22 Jul 2026](https://finance.biggo.com/news/US_GEV_2026-07-22)) |
| Siemens Energy | ENR (Frankfurt) / SMEGF | 69 GW gas turbine backlog plus 26 GW of slot reservations (Aug 2026 investor presentation, via [Supercomputing News](https://www.supercomputing.news/ai/ai-data-center-power-bottleneck-gas-turbine-slot)) |
| Mitsubishi Heavy Industries | 7011 (Tokyo) | Lead times stretched to 5+ years; contracts for 2031-2034 deliveries (same source) |

**Read.** The bottleneck is real and long-lasting, but these are now consensus winners. Upside comes from execution on the capacity ramp, not from discovery.

## 2. Grid equipment: transformers and electrical steel

**The bottleneck.** Transformer lead times went from 24-30 months to **3-5 years**, and "more than half" of US data centers planned for 2026 face delay or cancellation because of it. Supply is limited by a small number of manufacturers and by **grain-oriented electrical steel (GOES)**, which comes from only a few mills worldwide ([Orban Labs, 19 Apr 2026](https://orbanlabs.com/journal/036-transformer-shortage-deepens)). Hitachi Energy reported wait times over 30 months ([Nikkei Asia](https://asia.nikkei.com/business/energy/wait-times-for-hitachi-energy-transformers-hit-more-than-30-months)).

**Companies working on it**

| Company | Ticker | Evidence |
|---|---|---|
| Hitachi (Hitachi Energy) | 6501 (Tokyo) / HTHIY | $6B investment over 3 years plus 15,000 hires, including a $457M Virginia plant ([Orban Labs](https://orbanlabs.com/journal/036-transformer-shortage-deepens)) |
| Eaton | ETN | Named as gaining pricing power (same source) |
| Hyundai Electric | 267260 (Seoul) | Named as benefiting from margin expansion (same source) |
| Cleveland-Cliffs | CLF | **Only US producer** meeting DoD/DOE spec for DR-GOES transformer steel; won a sole-source contract worth up to $400M (2 Jul 2026, deliveries through 2030) ([Hoodline](https://hoodline.com/2026/07/cleveland-cliffs-snags-400-million-defense-steel-deal-to-keep-transformers-on/)); also building a $150M transformer plant ([Utility Dive](https://www.utilitydive.com/news/cleveland-cliffs-confirms-150-million-electric-transformer-weirton-plant/723363/)) |

**Read.** Electrical steel is a "bottleneck under the bottleneck." CLF is mostly a cyclical auto-steel company, so the GOES story is a small part of the business. That makes it interesting as an option but noisy as a pure play.

## 3. Memory: HBM

**The bottleneck.** HBM was fully allocated through 2026 with tightness into 2027; Micron sold its entire 2026 HBM supply in advance ([Fusion Worldwide](https://info.fusionww.com/blog/inside-the-ai-bottleneck-cowos-hbm-and-2-3nm-capacity-constraints-through-2027)).

| Company | Ticker | Evidence |
|---|---|---|
| Micron | MU | FQ4 2026 revenue **$54.2B (+379% y/y)**, gross margin ~87%; guiding FQ1 2027 to **$61.5B** ([Micron press release via Nasdaq, 30 Sep 2026](https://www.nasdaq.com/press-release/micron-technology-inc-reports-record-fiscal-fourth-quarter-and-full-year-2026-results)); collected $12.3B in customer deposits in the quarter ([404K](https://404kresearch.substack.com/p/404k-semi-ai-weekly-oct-2-2026-bottlenecks)) |
| SK hynix | 000660 (Seoul) | Shipping HBM4 since Q4 2025 ([Fusion Worldwide](https://info.fusionww.com/blog/inside-the-ai-bottleneck-cowos-hbm-and-2-3nm-capacity-constraints-through-2027)) |
| Samsung | 005930 (Seoul) | HBM3E in mass production, ramping HBM4 (same source) |

**Read.** This is the most visible bottleneck of the cycle and memory is historically the most cyclical part of semis. Margins near 87% are extraordinary; the key risk for a one-year hold is the supply response. Not an "early" idea anymore.

## 4. Chip packaging: from CoWoS down to substrates

**The bottleneck.** TSMC's CoWoS advanced packaging is sold out and gates finished AI accelerators even when chips are available ([Fusion Worldwide](https://info.fusionww.com/blog/inside-the-ai-bottleneck-cowos-hbm-and-2-3nm-capacity-constraints-through-2027)). The constraint is now moving **one layer down**: IC substrates are lengthening lead times and capping packaging throughput ([404K](https://404kresearch.substack.com/p/404k-semi-ai-weekly-oct-2-2026-bottlenecks)). ABF substrate shortages are projected to worsen through 2027-2028, and makers have orders booked into 2029-2030 ([Troy Technical, 23 Aug 2026](https://troy-technical.com/2026/08/23/abf-substrate-shortages-projected-through-2028-amid-ai-boom-taiwanese-japanese-korean-manufacturers-secure-orders-until-2030/)). DigiTimes reports low-expansion "T-glass" fiberglass cloth used in substrates is also short through 2028 ([DigiTimes, 14 Aug 2026](https://www.digitimes.com/news/a20260814PD224/demand-ic-substrate-2028-fiberglass-cloth-infrastructure.html)).

| Company | Ticker | Evidence |
|---|---|---|
| TSMC | TSM | UBS raised 2027-28 capex forecasts to $90B / $105B; HPC ~74% of 2027 revenue ([404K](https://404kresearch.substack.com/p/404k-semi-ai-weekly-oct-2-2026-bottlenecks)) |
| Ajinomoto | 2802 (Tokyo) | Holds ~95% of the ABF film market ([Troy Technical](https://troy-technical.com/2026/08/23/abf-substrate-shortages-projected-through-2028-amid-ai-boom-taiwanese-japanese-korean-manufacturers-secure-orders-until-2030/)) |
| Ibiden | 4062 (Tokyo) | Expanding ABF substrate capacity (same source) |
| Unimicron | 3037 (Taiwan) | Expanding ABF substrate capacity (same source) |
| Samsung Electro-Mechanics | 009150 (Seoul) | Expanding ABF substrate capacity (same source) |
| Nittobo | 3110 (Tokyo) | Main T-glass cloth maker *(inferred from DigiTimes headline; article was paywalled, so verify)* |

**Read.** This is where "next bottleneck" logic points most clearly in semis. Most of these names trade in Tokyo, Taipei or Seoul, which means less US retail attention and possibly less pricing-in, but also currency and access friction.

## 5. Optical networking: indium phosphide lasers

**The bottleneck.** Copper links can't keep up inside AI clusters, so traffic is moving to optics. The scarce input is **indium phosphide (InP)** laser capacity: transceiver demand is reported at about 2x supply ([Futurum](https://futurumgroup.com/insights/nvidias-4b-optics-bet-signals-photonics-as-ais-next-bottleneck/)). On 2 Mar 2026 Nvidia invested **$2B each in Coherent and Lumentum** plus multibillion-dollar purchase commitments (same source). Lumentum's CEO says it is shipping **30%+ below demand** even with 50% capacity growth, and China produces ~69% of refined indium and cut InP exports 72% ([Tom's Hardware, 31 Jul 2026](https://www.tomshardware.com/tech-industry/semiconductors/lumentum-ceo-says-the-indium-phosphide-shortage-will-become-worse-than-memory)).

| Company | Ticker | Evidence |
|---|---|---|
| Lumentum | LITE | "Virtual monopoly" on high-power InP lasers ([Motley Fool, 13 Aug 2026](https://www.fool.com/investing/2026/08/13/the-next-big-ai-market-bottleneck-is-here-8-stocks/)); $2B Nvidia investment |
| Coherent | COHR | Vertically integrated, co-packaged optics; $2B Nvidia investment ([Futurum](https://futurumgroup.com/insights/nvidias-4b-optics-bet-signals-photonics-as-ais-next-bottleneck/)) |
| AXT | AXTI | InP substrate maker; Q2 revenue +164% to $47.6M; Q4 InP price hikes >10%, the largest on record; **stock up ~399% YTD** as of 17 Aug ([24/7 Wall St.](https://247wallst.com/investing/2026/08/17/axt-soars-again-on-monday-to-lead-optics-stocks-coherent-and-lumentum-rally-on-indium-phosphide-price-hikes/)). Key risk: its InP production is in China and needs export permits ([Tom's Hardware](https://www.tomshardware.com/tech-industry/semiconductors/lumentum-ceo-says-the-indium-phosphide-shortage-will-become-worse-than-memory)) |
| Marvell | MRVL | Optical DSP leader; Nvidia invested $2B and integrated it into NVLink ([Motley Fool](https://www.fool.com/investing/2026/08/13/the-next-big-ai-market-bottleneck-is-here-8-stocks/)) |
| Applied Optoelectronics | AAOI | Key Microsoft transceiver supplier, building in-house laser capacity (same source) |
| Corning | GLW | AI data centers need far more fiber strands (same source) |

**Read.** The theme is real and backed by Nvidia's own money, but much of it has already run. AXTI is the clearest example of a "bottleneck under the bottleneck" trade, and also shows how fast such trades get crowded.

## 6. Data center power and cooling

**The bottleneck.** Racks are heading toward 1 MW, which air cooling and today's 54V power distribution can't handle. That pushes the industry to liquid cooling and **800V DC** power architectures ([DCD](https://www.datacenterdynamics.com/en/news/nvidia-prepares-data-center-industry-for-1mw-racks-and-800-volt-dc-power-architectures/)).

| Company | Ticker | Evidence |
|---|---|---|
| Vertiv | VRT | Q4 2025: organic orders **+252%**, backlog **$15B**, book-to-bill 2.9x; 2026 guidance $13.25-13.75B sales; bought PurgeRite (~$1B) for liquid cooling services ([Data Center Frontier](https://www.datacenterfrontier.com/machine-learning/article/55357689/vertivs-ai-infrastructure-surge-record-orders-liquid-cooling-expansion-and-grid-scale-power-reshape-data-center-growth)) |
| Navitas Semiconductor | NVTS | Nvidia 800V DC partner; showed an 800V-to-6V GaN power board at Computex (Jun 2026) ([Semiconductor Today](https://www.semiconductor-today.com/news_items/2026/jun/navitas-030626.shtml)). Small, speculative, revenue still early |

**Read.** Cooling is consensus. 800V DC is a genuine early-stage architecture shift; the winners aren't settled yet. Worth a dedicated deep dive.

## 7. Critical materials: copper and rare earths

**Copper.** Refined copper deficit estimates for 2026 run from 150k tonnes (ICSG) to 400k+ tonnes (UBS). AI data centers use 30-47 tonnes of copper per MW, and new mines take ~17 years to develop; Grasberg disruption alone removes 500k+ tonnes ([Skillings](https://www.skillings.net/copper-supply-forecast-2026-ai-data-center-demand-vs-market-deficit/)). Obvious exposure: Freeport-McMoRan (FCX, operator of Grasberg, so both beneficiary and hit), Southern Copper (SCCO). *These two are named from general knowledge, not from the source; verify current exposure.*

**Rare-earth magnets.** China controls ~90% of magnet production and 91% of refining, and has tightened export controls since April 2025 ([S&P Global](https://www.spglobal.com/energy/en/news-research/latest-news/metals/012726-rare-earth-supply-bottlenecks-set-to-persist-in-2026)). Humanoid robots could widen the deficit ([CRU](https://www.crugroup.com/en/communities/thought-leadership/2026/humanoid-robots-can-widen-the-projected-rare-earth-supply-deficit/)).

| Company | Ticker | Evidence |
|---|---|---|
| MP Materials | MP | Pentagon took a 15% stake ($400M) and a 10-year offtake with a **$110/kg price floor**; Apple $500M magnet deal; targeting ~10,000 t/yr magnets by 2028; Q2 2026 revenue +89% to $108.5M; US defense rules phase out Chinese magnets from 1 Jan 2027 ([InvestorPlace, Sep 2026](https://investorplace.com/hypergrowthinvesting/2026/09/china-targeted-mp-materials-for-a-reason/)) |
| Lynas Rare Earths | LYC (ASX) | Largest non-China producer *(general knowledge; verify)* |

**Read.** MP has a government-backed price floor, which reduces downside on price but not on execution. The 1 Jan 2027 defense deadline is a dated catalyst inside a one-year window.

## 8. Nuclear fuel: enrichment

**The bottleneck.** US enrichment capacity is ~4.3M SWU/year against ~15.6M SWU of reactor demand, and Russia, which held nearly half of global capacity, is being banned. In Jan 2026 DOE awarded $2.7B across three $900M task orders. Analysts flag **conversion** (the step before enrichment) as a further constraint with no major Western expansion announced ([EnkiAI](https://enkiai.com/nuclear/uranium-enrichment-companies-west/)).

| Company | Ticker | Evidence |
|---|---|---|
| Centrus Energy | LEU | $900M DOE task order to expand HALEU at Piketon, Ohio; target 12 t/yr by 2029 ([EnkiAI](https://enkiai.com/nuclear/uranium-enrichment-companies-west/)) |
| Cameco | CCJ | One of the few Western uranium conversion operators *(general knowledge; verify)* |

**Read.** This is a slower-moving, policy-driven bottleneck. Small modular reactors get the headlines, but they all need fuel first, which is why fuel is the more defensible angle.

## 9. Labor: electricians and grid crews

**The bottleneck.** Skilled trades are becoming a site-selection constraint for data centers ([build.inc](https://build.inc/insights/data-center-construction-labor-shortage-2026); [DCD](https://www.datacenterdynamics.com/en/analysis/construction-worker-shortage-us-data-center/)). Transformer factories are also limited by coil-winding labor ([Manufacturing Mag](https://www.manufacturingmag.com/article/grid-transformer-shortage-three-year-backlog-coil-winding-labor)).

| Company | Ticker | Evidence |
|---|---|---|
| Quanta Services | PWR | Q2 2026 revenue **$9.56B (+41%)**, record backlog **$53.4B**, FY26 guidance raised to $39.3-39.7B; self-performs 80-85% of work with its own crews, which Bernstein called a key advantage ([Crypto Briefing, 2 Oct 2026](https://cryptobriefing.com/quanta-services-record-revenue-data-centers)) |

---

## Shortlist: most promising early-trend ideas

Ranked by how long the bottleneck should last versus how much the market seems to have noticed. "Early" here means the constraint is documented but the trade is not yet as crowded as memory or turbines.

1. **Chip substrates and materials (Ibiden 4062, Unimicron 3037, Ajinomoto 2802, Nittobo 3110).** Shortage projected through 2028, orders booked to 2029-30, and the constraint is visibly moving down from CoWoS to here. Mostly non-US listings, so likely less crowded. *Next step: check each company's AI exposure and valuation.*
2. **800V DC power delivery (Navitas NVTS, plus a survey of other GaN/SiC and power-system players).** A real architecture change pushed by Nvidia and Google with no settled winners yet. High risk, high uncertainty. *Next step: map the full supplier list and who has design wins.*
3. **Transformer steel and grid equipment (Cleveland-Cliffs CLF, Hitachi 6501, Hyundai Electric 267260).** 3-5 year lead times and a near-monopoly on US transformer steel. *Next step: size how much of CLF's earnings GOES could become.*
4. **Rare-earth magnets (MP Materials MP).** Government price floor plus a dated catalyst (1 Jan 2027 defense phase-out) inside a one-year window.
5. **Nuclear fuel (Centrus LEU, Cameco CCJ).** Structural US deficit, DOE money committed, conversion flagged as the next choke point. Longer horizon, better for an annual than a quarterly hold.

**Already-recognized leaders (strong, but no longer early):** GE Vernova (GEV), Micron (MU), Vertiv (VRT), Lumentum (LITE), Coherent (COHR), AXT (AXTI), Quanta (PWR). Good to own the theme, but most of the bottleneck is likely in the price.

## Risks that cut across everything

- **AI spending has to pay off.** Goldman Sachs puts the hurdle at about $1.42T of cumulative AI revenue in 2028-2030 to earn a 15% return on capex, with no contracted backlog guaranteeing it ([404K](https://404kresearch.substack.com/p/404k-semi-ai-weekly-oct-2-2026-bottlenecks)). If hyperscalers cut capex, every name above is hit, early-trend ones hardest.
- **Bottlenecks end.** Shortages bring new capacity, and suppliers' pricing power fades. Memory is the classic example.
- **Price growth is not volume growth.** Some revenue growth is price inflation masking slower unit growth ([404K](https://404kresearch.substack.com/p/404k-semi-ai-weekly-oct-2-2026-bottlenecks)).
- **China policy.** Rare earths, indium and AXT's own factories depend on Chinese export decisions.

## Signals to track each quarter

- Hyperscaler capex guidance (Amazon, Microsoft, Alphabet, Meta earnings)
- GE Vernova and Siemens Energy turbine slot reservations
- TSMC CoWoS capacity commentary and substrate-maker lead times
- Lumentum and Coherent supply-vs-demand gap; InP substrate prices
- Micron and SK hynix pricing and customer deposits (early warning of the memory cycle turning)
- Transformer lead times; DOE enrichment awards; China export-control changes
