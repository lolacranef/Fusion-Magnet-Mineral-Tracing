# Data, Methods and Sources

*Companion to [CONCEPT.md](CONCEPT.md). It explains how the rule-gap matrix is built, what each verdict rests on, and where the evidence comes from. Rule terms checked 9 November 2026. Research, not legal advice.*

## 1. What the dataset is

The core dataset is a **rule × region matrix**: 13 rules assessed against 4 mining regions, giving 52 cells. Each cell records whether a rule reaches the harm documented in that region, and what slips through if it doesn't.

### Units of analysis

| Dimension | Count | Items |
|---|---|---|
| Rules | 13 | Dodd-Frank §1502 · EU Conflict Minerals Regulation · CSDDD · EU Forced Labour Regulation · EU Battery Regulation due diligence · Tariff Act §307 · UFLPA · German LkSG · Japan HRDD Guidelines · OECD Minerals Guidance · Targeted sanctions (US/EU) · China rare earth export controls · Producer-country enforcement |
| Regions | 4 | Kachin State, Myanmar · Shan State & Wa, Myanmar · Bangka Belitung, Indonesia · Rubaya, North Kivu, DRC → Rwanda |
| Minerals | 5 | Yttrium / heavy rare earths · other rare earths · tin · niobium · tantalum |
| Magnet types | 2 | REBCO high-temperature superconducting (HTS) tape · Nb₃Sn / NbTi low-temperature superconducting wire |

### Record structure

**Rule profile** (one per rule)

| Field | Meaning |
|---|---|
| Minerals covered | Which minerals the rule names, or "all" when it covers harm instead of a mineral list |
| Where | Geographic scope |
| Who must act | The party that carries the legal duty |
| What it requires | Disclosure, due diligence, ban, licence, etc. |
| Status | In force, in force from a date, being amended, or voluntary |
| Sources | Citations for the rule's terms |

**Region profile** (one per region)

| Field | Meaning |
|---|---|
| What is mined | Minerals and deposit type |
| Who controls it | State, company or armed group in control of extraction |
| Documented harm | Specific reported abuses, with figures where available |
| Where it goes | Trade route, and the processing step where origin is lost |
| Fusion link | Which magnet technology uses the mineral |
| Sources | Citations for the above |

**Matrix cell** (one per rule × region)

| Field | Meaning |
|---|---|
| Verdict | One of the six values in §2 |
| What it says here | How the rule's scope applies to this region and mineral |
| What the gap lets through | The specific harm or trade the rule fails to catch, in plain terms |
| Cell sources | Extra citations when the cell relies on facts beyond the rule and region profiles (used mainly for sanctions and producer-country enforcement) |

Each region also has a **coverage tally** (a count of verdicts) and one **suggested side-by-side**, a pair of rules whose contrast best shows the gap.

## 2. Methods

### 2.1 Choosing regions

A region is included if it meets all three tests:

1. It produces a mineral that goes into a fusion superconducting magnet: REBCO tape (yttrium, gadolinium, other rare earths) or Nb₃Sn / NbTi wire (tin, niobium).
2. Credible reporting (an NGO, the UN, a major news outlet or a government) documents serious harm there: forced or child labour, armed-group financing, or major environmental damage.
3. The mineral leaves the region through a route where its origin can be lost, such as separation, smelting or re-export through a third country.

The four regions are illustrations of how the rules fail, not a full survey of fusion's mineral supply. Brazil, which supplies about 90% of niobium, and lower-risk rare earth sources are deliberately left out.

### 2.2 Choosing rules

Rules are included if they could plausibly reach at least one of the regions through a mineral list, a harm type (forced labour, human rights or environmental harm), a geographic programme, or a trade control. The set mixes binding law, voluntary standards (OECD, Japan) and non-legal tools (sanctions, Chinese export licensing, local enforcement), because the audience decides between all of these.

### 2.3 Assigning a verdict

Each cell is scored by taking four questions in order:

1. **Is there any link?** If the rule has no plausible connection to the region (for example, Chinese rare earth controls applied to Indonesian tin), the verdict is **Not relevant**.
2. **Is it binding?** If the rule only recommends action, the verdict is **Voluntary only**.
3. **Is it in force?** If it would cover the case but only from a future date, the verdict is **Not yet in force**. This takes priority over scope, so a future rule that fits fully is still "Not yet in force".
4. **Does the scope fit?** This is checked against mineral, geography, the party with the duty, and type of harm:
   - All four fit today → **Applies**
   - Some fit, or only in some cases (only the importer of raw ore, only direct suppliers, only forced labour and not pollution) → **Partly reaches**
   - Ruled out on any one of them → **Doesn't reach**

Fusion supply chains get one extra check: whether the duty sits at the point where fusion buyers actually purchase (finished tape, wire or magnets) or only at the raw-ore importer. Several "Partly reaches" verdicts come from this.

### 2.4 Writing "What the gap lets through"

Each gap statement names what happens in practice: who can buy what without being asked about it. Statements stay within what the rule text and the cited reporting support. Where a rule fits on paper but is hard to enforce (for example §307, where origin is lost in Chinese separation), the problem is written into the gap rather than used to lower the verdict.

### 2.5 Checking rule terms

Rule scopes, thresholds and dates were checked against the cited sources on 9 November 2026. Three rules were changing at that date and need re-checking before anyone cites them: Dodd-Frank §1502 (future uncertain), the German LkSG (amendment in the Bundestag), and the EU Battery Regulation (scope reduction under negotiation).

### 2.6 Tally check

The coverage tallies in CONCEPT.md were recounted from the matrix rows and all four match:

| Region | Applies | Partly | Not yet | Voluntary | Doesn't | Not relevant |
|---|---|---|---|---|---|---|
| Kachin | 0 | 5 | 1 | 2 | 5 | 0 |
| Shan & Wa | 1 | 3 | 2 | 2 | 5 | 0 |
| Bangka Belitung | 1 | 4 | 1 | 2 | 3 | 2 |
| Rubaya | 2 | 3 | 2 | 2 | 3 | 1 |
| **Total (52 cells)** | **4** | **15** | **6** | **8** | **16** | **3** |

Only 4 of 52 cells apply fully today. Two of those are §307, which applies wherever forced labour is documented, and one is local enforcement in Indonesia.

## 3. Sources

### 3.1 Source types and how they are used

| Type | Used for | Examples |
|---|---|---|
| Legal text | Rule scope | EU Reg. 2017/821 |
| Law firm and government briefings | Rule status, thresholds, dates | Skadden, Covington, Mayer Brown, CRS, Troutman |
| NGO investigations | Documented harm, control of mines | Global Witness, Amnesty, SHRF via BHRRC |
| UN reporting | Harm in Myanmar | UN rights report via Khaosod |
| News | Harm, trade flows, enforcement actions | Reuters, AP, Irrawaddy, Antara, Mining.com |
| Government statistics | Import shares, production | USGS |
| Industry and market analysis | Market shares, industry standards | SFA Oxford, International Tin Association |

### 3.2 Rule sources

| Rule | Sources | Date |
|---|---|---|
| Dodd-Frank §1502 | [Skadden](https://www.skadden.com/insights/publications/2026/05/conflict-minerals-disclosures-due-june-1-2026) · [Ropes & Gray](https://www.ropesgray.com/en/insights/viewpoints/102kbie/is-u-s-conflict-minerals-disclosure-nearing-an-end) · [Claigan FAQ](https://www.claigan.com/conflict-minerals-faq/) | May 2026 |
| EU Conflict Minerals Regulation | [Reg. 2017/821 Art. 1](https://legislation.gov.uk/eur/2017/821/article/1/data.pdf) · [Ropes & Gray on CAHRA list](https://www.ropesgray.com/en/insights/alerts/2020/12/conflict-minerals-compliance-european-commission-publishes-global-list-of-conflict-affected) · [Reed Smith](https://www.reedsmith.com/articles/the-eu-new-mandatory-supply-chain-diligence-rules-batteries-raw-materials/) | 2017 text; 2020 alert |
| CSDDD (EU 2026/470) | [Covington](https://www.cov.com/news-and-insights/insights/2026/02/eu-csddd-csrd-omnibus-published-in-official-journal-transposition-delegated-acts-and-guidelines-are-next) | Feb 2026 |
| EU Forced Labour Regulation | [Mayer Brown](https://www.mayerbrown.com/en/insights/publications/2026/06/the-eu-forced-labour-regulation-10-questions-every-general-counsel-should-be-asking) | Jun 2026 |
| EU Battery Regulation | [A&L Goodbody](https://www.algoodbody.com/insights-publications/batteries-due-diligence-a-two-year-pause-and-reduced-scope) · [Reed Smith](https://www.reedsmith.com/articles/the-eu-new-mandatory-supply-chain-diligence-rules-batteries-raw-materials/) | — |
| Tariff Act §307 | [CRS IF11360](https://www.everycrsreport.com/files/2026-07-09_IF11360_c9e63009c902a08f9494a2def20f5e391c71b6fa.html) | Jul 2026 |
| UFLPA | [Troutman](https://www.troutman.com/insights/dhs-adds-43-companies-to-uflpa-entity-list-in-largest-ever-single-expansion-effective-august-3/) | Aug 2026 |
| German LkSG | [Taylor Wessing](https://www.taylorwessing.com/en/insights-and-events/insights/2026/01/lksg) | Jan 2026 |
| Japan HRDD Guidelines | [HREDD tracker](https://hredd-org.pages.dev/tracker/japan-hrdd-guidelines) | — |
| OECD Minerals Guidance | [International Tin Association](https://www.internationaltin.org/oecd/) | — |
| Targeted sanctions | Cited per region in the matrix cells (see §3.3) | — |
| China rare earth export controls | [TariffCenter guide](https://tariffcenter.ai/blog/china-2026-rare-earth-export-controls-guide) | 2026 |
| Producer-country enforcement | Cited per region in the matrix cells (see §3.3) | — |

### 3.3 Region sources

**Kachin State, Myanmar**
- Harm and illegality: [Mongabay on Global Witness](https://news.mongabay.com/2022/08/toxic-rare-earth-mines-fuel-deforestation-rights-abuses-in-myanmar-report-says/) (Aug 2022) · [Khaosod on UN report](https://www.khaosodenglish.com/news/international/2026/08/28/un-myanmar-rights-crisis-hits-new-low-as-minorities-face-brutal-abuses/amp/) (Aug 2026) · [BNI](https://www.bnionline.net/en/node/113988)
- Control and trade: [NBC/CNBC](https://www.nbcsandiego.com/news/business/money-report/how-a-war-torn-myanmar-plays-a-critical-role-in-chinas-rare-earth-dominance/3854510/?os=ave)
- Import share: [USGS Mineral Commodity Summaries 2025, yttrium](https://pubs.usgs.gov/periodicals/mcs2025/mcs2025-yttrium.pdf)
- Sanctions: [The Star](https://www.thestar.com.my/news/world/2026/04/27/eu-extends-sanctions-against-myanmar-by-a-year) (Apr 2026) · [ThePrint](https://theprint.in/world/us-lifts-some-myanmar-sanctions-after-general-asked-trump-for-relief/2702840) (Jul 2025)

**Shan State & Wa, Myanmar**
- Forced labour: [BHRRC on SHRF report](https://www.bhrrc.org/de/neuste-meldungen/myanmar-uwsa-alleged-of-trafficking-scam-workers-into-chinese-operated-rare-earth-mines/) (May 2026)
- Mine expansion and pollution: [Karen News](https://karennews.org/?p=12460) · [Irrawaddy](https://www.irrawaddy.com/?p=153906) · [Khaosod on UN report](https://www.khaosodenglish.com/news/international/2026/08/28/un-myanmar-rights-crisis-hits-new-low-as-minorities-face-brutal-abuses/amp/)
- Tin and the 2023 suspension: [Irrawaddy on Wa tin](https://www.irrawaddy.com/?p=127037) · [Mining Weekly](https://www.miningweekly.com/article/tin-shipments-from-myanmars-wa-state-due-to-resume-tin-group-says-2025-07-16) (Jul 2025)
- Sanctions: [The Star](https://www.thestar.com.my/news/world/2026/04/27/eu-extends-sanctions-against-myanmar-by-a-year) (Apr 2026)

**Bangka Belitung, Indonesia**
- Background and ILO child labour figure: [Tin mining in Indonesia](https://wiki.riteme.site/wiki/Tin_mining_in_Indonesia)
- Pit deaths: [Eco-Business](https://www.eco-business.com/ms/news/grim-toll-from-indonesias-abandoned-mines-may-get-even-worse-report/)
- Corruption case: [VOI](https://voi.id/en/amp/491796) (Jul 2025)
- Mine shutdown order: [Antara](https://en.antaranews.com/news/383205/govt-calls-for-shutdown-of-1000-illegal-tin-mines-in-bangka-belitung) (Sep 2025)

**Rubaya, North Kivu, DRC → Rwanda**
- Abuses under M23: [Amnesty](https://www.amnestyusa.org/reports/drc-we-didnt-come-to-play-m23-abuses-at-artisanal-mines-and-the-trafficking-of-gold-and-coltan-to-rwanda/) (Sep 2026)
- Accidents and conditions: [Global Witness](https://globalwitness.org/en/press-releases/deadly-drc-mine-disaster-highlights-human-cost-of-coltan/) · [AP via Africanews](https://www.africanews.com/amp/2025/05/19/congos-coltan-miners-dig-for-worlds-tech-amid-struggles/) (May 2025)
- Levies and M23 administration: [Reuters via Monitor](https://www.monitor.co.ug/uganda/news/inside-the-mine-that-feeds-the-tech-world-and-funds-congo-s-rebels-5154474)
- Niobium market share: [SFA Oxford](https://www.sfa-oxford.com/market-news-and-insights/niobium-swing-producer-cbmm-driving-the-future-of-advanced-materials/)
- Sanctions: [Mining.com](https://www.mining.com/web/us-sanctions-armed-group-mining-firms-over-illicit-congo-minerals) (Aug 2025) · [AllAfrica / Global Witness](https://allafrica.com/stories/202504280598.html) (Apr 2025)

## 4. Limitations and known gaps

### Evidence to strengthen before publication

| Issue | Where | Suggested fix |
|---|---|---|
| The EU Conflict Minerals Regulation is cited from legislation.gov.uk, which hosts the UK retained version, not the EU text | Rule profile | Cite EUR-Lex (CELEX 32017R0821) |
| The Bangka background and the ILO 2015 figure are cited to a Wikipedia mirror | Bangka region | Cite the ILO study and Wikipedia directly; note the figure dates from 2015 |
| China's export controls rest on one commercial blog | Rule profile | Add MOFCOM announcements or a law firm briefing |
| The Japan guidelines are cited to an unofficial tracker | Rule profile | Add the METI guideline text and a source on the review timeline |
| The fusion link (CFS, Proxima, Tokamak Energy and STEP using REBCO; ITER using Nb₃Sn) has no citation | All regions | Add company, ITER and STEP technical sources |
| The Kachin "half the world's heavy rare earths" and Rubaya "15% of world coltan" figures are each tied to a group of sources, not one specific source | Region profiles | Pin each figure to one specific source |
| The EU CAHRA list source is from 2020 | Rule profile | Confirm the list is still maintained and current |
| Targeted sanctions and producer-country enforcement have no rule-level citation | Rule profiles | Acceptable as umbrella categories; the cell-level sources carry the evidence |

### Consistency notes

- **UFLPA in Bangka and Rubaya** is scored "Doesn't reach", but the gap text says "Not relevant". Under the verdict rules in §2.3, step 1 would score it "Not relevant". It's currently scored "Doesn't reach" to show that the strongest US import tool is limited to one geography. Choose one approach and apply it to all regions.
- **Battery Regulation** is scored "Doesn't reach" in every region, which is consistent: it's ruled out by mineral, not by lack of a link.

### Scope limits

- The matrix measures whether a rule reaches a harm on paper. It does not measure how strongly the rule is enforced, apart from where the gap text says so.
- It covers four regions with high, documented risk. It is not an estimate of how much fusion magnet material comes from them.
- Rule terms are as of 9 November 2026. Several rules are mid-change.
- This is research, not legal advice.

## 5. Updating the matrix

1. Re-check each rule profile's **Status** against its sources, starting with the three that are mid-change (§2.5).
2. Re-run the verdict questions (§2.3) for any rule whose scope or start date has changed.
3. Recount the tallies (§2.6).
4. Change the "checked" date at the top of both files.
