# Data, Methods and Sources

*Companion to [CONCEPT.md](CONCEPT.md) and the [interactive site](https://lolacranef.github.io/Fusion-Magnet-Mineral-Tracing/). It explains how the rule-gap matrix is built, what each verdict rests on, and where every piece of evidence on the site comes from. Rule terms checked 9 November 2026. Research, not legal advice.*

## 1. The dataset

The core dataset is a **rule-by-region matrix**: 13 rules assessed against 4 mining regions, giving 52 cells. Each cell records whether a rule reaches the harm documented in that region, and what slips through if it doesn't.

| Dimension | Count | Items |
|---|---|---|
| Rules | 13 | Dodd-Frank §1502 · EU Conflict Minerals Regulation · EU Battery Regulation due diligence · EU Forced Labor Regulation · Tariff Act §307 import ban · Uyghur Forced Labor Prevention Act · Corporate Sustainability Due Diligence Directive · Supply Chain Due Diligence Act (LkSG) · Human Rights Due Diligence Guidelines · OECD Minerals Due Diligence Guidance · Targeted sanctions · Rare earth export controls · Producer-country enforcement |
| Regions | 4 | Kachin, Myanmar · Shan & Wa, Myanmar · Bangka Belitung, Indonesia · Rubaya, DR Congo → Rwanda |
| Minerals | 5 | Yttrium and heavy rare earths · other rare earths · tin · niobium · tantalum |
| Magnet types | 2 | REBCO high-temperature superconducting tape · Nb₃Sn and NbTi low-temperature superconducting wire |

Each **rule profile** records minerals covered, geographic scope, who must act, what it requires, status and sources. Each **region profile** records what is mined, who controls it, documented harm, the trade route and where origin is lost, and the link to fusion magnets. Each **matrix cell** records a verdict, what the rule says for that region, and what the gap lets through.

## 2. Methods

### 2.1 Choosing regions

A region is included only if it meets all three tests:

1. It produces a mineral used in fusion superconducting magnets: rare earths for REBCO tape, or tin and niobium for Nb₃Sn and NbTi wire.
2. Credible reporting from NGOs, the UN, major news outlets or governments documents serious harm there: forced or child labor, armed-group financing, or major environmental damage.
3. The mineral leaves the region through a route where its origin can be lost, such as separation, smelting or re-export through a third country.

The four regions illustrate how the rules fail. They are not a full survey of fusion's mineral supply. Brazil, which supplies about 90% of the world's niobium, and lower-risk rare earth sources are deliberately left out.

### 2.2 Choosing rules

A rule is included if it could plausibly reach at least one region through a mineral list, a type of harm (forced labor, human rights or environmental harm), a geographic program or a trade control. The set mixes binding law, voluntary standards and non-legal levers such as sanctions, export licensing and local enforcement, because readers choose among all of them.

### 2.3 Deciding a verdict

Each cell is scored by asking four questions in order. The first answer that settles it decides the verdict.

1. **Is there any link?** If not: *Not relevant*.
2. **Is it binding?** If it only recommends action: *Voluntary only*.
3. **Is it in force?** If only from a future date: *Not yet in force*.
4. **Does the scope fit** (mineral, place, who must act, type of harm)? Fits fully: *Applies*. Fits in part or only in some cases: *Partly reaches*. Ruled out: *Doesn't reach*.

One extra check applies to fusion supply chains: does the duty sit where fusion buyers actually purchase (finished tape, wire or magnets), or only with the importer of raw ore? Several "Partly reaches" verdicts come from this check.

### 2.4 Writing the gap

Each gap statement says what happens in practice: who can buy what without being asked about it. Statements stay within what the rule text and the cited reporting support. When a rule fits on paper but is hard to enforce, the difficulty is written into the gap rather than used to lower the verdict.

### 2.5 Checking rule terms and facts

Scopes, thresholds and dates were checked against the cited sources on 9 November 2026. Every documented-harm figure was checked against a primary or major source, and every link was confirmed to load. Rules changing on that date: Dodd-Frank §1502 (future uncertain), Germany's LkSG (amendment before the Bundestag), the EU Battery Regulation (narrower scope under negotiation) and China's Announcement No. 61 (paused until 10 November 2026).

### 2.6 Tally check

| Region | Applies | Partly | Not yet | Voluntary | Doesn't | Not relevant |
|---|---|---|---|---|---|---|
| Kachin | 0 | 5 | 1 | 2 | 5 | 0 |
| Shan & Wa | 1 | 3 | 2 | 2 | 5 | 0 |
| Bangka Belitung | 1 | 4 | 1 | 2 | 3 | 2 |
| Rubaya | 2 | 3 | 2 | 2 | 3 | 1 |
| **All 52 cells** | **4** | **15** | **6** | **8** | **16** | **3** |

## 3. How the site shows the data

| Element | What it shows | Note |
|---|---|---|
| Verdict icons and colors | Shields from violet (protected) to red (unprotected) | Matches the site palette |
| Gap depth (cover strips, bar lengths) | Applies 0 · Partly reaches 1 · Not yet in force or Voluntary only 2 · Doesn't reach 3, averaged over regions where the rule is relevant | A simple score made for the site; not in the research |
| Rule groups | Conflict-mineral rules, forced-labor bans, due diligence laws, other levers | Our own grouping |
| Where the law attaches | Each rule at the link where its main duty falls | Approximate. OECD Guidance spans the chain and is shown at processing; the Battery Regulation is left out |
| Element tiles | Y, Gd, Sn, Nb linked to regions | Shan and Wa shown as "RE" (rare earths in general). No region is documented as a gadolinium source |
| Supply map | Mines, processing, tape and wire makers, fusion builders | Solid routes are documented; dotted routes are typical but untraced. Companies marked "Example" come from general industry knowledge and are not linked to these mines |
| Field strength slider | Power density ∝ B⁴; radius for equal power ∝ B^(−4/3), relative to ITER | Textbook rule of thumb |
| Reactor model | Tokamak parts and coil materials | Checked against ITER and MIT News; simplified sketch, not to scale |
| Rule guide | Plain-language summaries, key terms, investigator uses, official texts | Summaries are ours; linked texts are authoritative |
| Solutions | Recommendations and alternative sources | Facts sourced; recommendations are Coilchain's analysis |
| Photos | Openly licensed photos with credits | None shows a specific abuse described |

## 4. Sources

### 4.1 Rules: official texts and secondary sources

| Rule | Official text and tools | Secondary sources |
|---|---|---|
| Dodd-Frank §1502 (US) | [15 U.S.C. §78m(p): the statute](https://www.law.cornell.edu/uscode/text/15/78m)<br>[17 CFR §240.13p-1: the SEC rule](https://www.law.cornell.edu/cfr/text/17/240.13p-1)<br>[SEC EDGAR filing search](https://www.sec.gov/edgar/search/)<br>[Responsible Minerals Initiative smelter lists](https://www.responsiblemineralsinitiative.org/smelters-refiners-lists/) | [Skadden (May 2026)](https://www.skadden.com/insights/publications/2026/05/conflict-minerals-disclosures-due-june-1-2026)<br>[Ropes & Gray](https://www.ropesgray.com/en/insights/viewpoints/102kbie/is-u-s-conflict-minerals-disclosure-nearing-an-end)<br>[Claigan FAQ](https://www.claigan.com/conflict-minerals-faq/) |
| EU Conflict Minerals Regulation (EU 2017/821) | [Regulation (EU) 2017/821 (EUR-Lex)](https://eur-lex.europa.eu/eli/reg/2017/821/oj) | [Ropes & Gray on the CAHRA list (Dec 2020)](https://www.ropesgray.com/en/insights/alerts/2020/12/conflict-minerals-compliance-european-commission-publishes-global-list-of-conflict-affected)<br>[Reed Smith](https://www.reedsmith.com/articles/the-eu-new-mandatory-supply-chain-diligence-rules-batteries-raw-materials/) |
| EU Battery Regulation due diligence (EU 2023/1542) | [Regulation (EU) 2023/1542 (EUR-Lex)](https://eur-lex.europa.eu/eli/reg/2023/1542/oj) | [A&L Goodbody](https://www.algoodbody.com/insights-publications/batteries-due-diligence-a-two-year-pause-and-reduced-scope)<br>[Reed Smith](https://www.reedsmith.com/articles/the-eu-new-mandatory-supply-chain-diligence-rules-batteries-raw-materials/) |
| EU Forced Labor Regulation (EU 2024/3015) | [Regulation (EU) 2024/3015 (EUR-Lex)](https://eur-lex.europa.eu/eli/reg/2024/3015/oj) | [Mayer Brown (Jun 2026)](https://www.mayerbrown.com/en/insights/publications/2026/06/the-eu-forced-labour-regulation-10-questions-every-general-counsel-should-be-asking) |
| Tariff Act §307 import ban (US) | [19 U.S.C. §1307: the statute](https://www.law.cornell.edu/uscode/text/19/1307)<br>[19 CFR §12.42: CBP's procedure](https://www.law.cornell.edu/cfr/text/19/12.42)<br>[CBP: Withhold Release Orders and Findings](https://www.cbp.gov/trade/forced-labor/withhold-release-orders-and-findings)<br>[CBP e-Allegations portal](https://eallegations.cbp.gov/) | [CRS IF11360 (Jul 2026)](https://www.everycrsreport.com/files/2026-07-09_IF11360_c9e63009c902a08f9494a2def20f5e391c71b6fa.html) |
| Uyghur Forced Labor Prevention Act (US) | [Public Law 117-78 (congress.gov)](https://www.congress.gov/bill/117th-congress/house-bill/6256)<br>[DHS: UFLPA Entity List](https://www.dhs.gov/uflpa-entity-list)<br>[CBP: UFLPA guidance](https://www.cbp.gov/trade/forced-labor/UFLPA) | [Troutman (Aug 2026)](https://www.troutman.com/insights/dhs-adds-43-companies-to-uflpa-entity-list-in-largest-ever-single-expansion-effective-august-3/) |
| Corporate Sustainability Due Diligence Directive (EU 2026/470) | [Directive (EU) 2024/1760, current version (EUR-Lex)](https://eur-lex.europa.eu/eli/dir/2024/1760/oj)<br>[Amending Directive (EU) 2026/470 (EUR-Lex)](https://eur-lex.europa.eu/eli/dir/2026/470/oj/eng) | [Covington (Feb 2026)](https://www.cov.com/news-and-insights/insights/2026/02/eu-csddd-csrd-omnibus-published-in-official-journal-transposition-delegated-acts-and-guidelines-are-next) |
| Supply Chain Due Diligence Act (LkSG) (Germany) | [LkSG, official text in German](https://www.gesetze-im-internet.de/lksg/)<br>[BAFA: overview in English](https://www.bafa.de/EN/Supply_Chain_Act/Overview/overview_node.html)<br>[BAFA: complaints procedure](https://www.bafa.de/EN/Supply_Chain_Act/Complaints_Procedure/complaints_procedure_node.html) | [Taylor Wessing (Jan 2026)](https://www.taylorwessing.com/en/insights-and-events/insights/2026/01/lksg) |
| Human Rights Due Diligence Guidelines (Japan) | [Guidelines, provisional English translation (METI)](https://www.meti.go.jp/policy/economy/business-jinken/guidelines/provisionalenglishtranslation.pdf)<br>[METI: business and human rights](https://www.meti.go.jp/english/policy/economy/biz_human_rights/index.html) | [METI: business and human rights](https://www.meti.go.jp/english/policy/economy/biz_human_rights/index.html) |
| OECD Minerals Due Diligence Guidance (International) | [OECD Guidance: official page](https://www.oecd.org/en/publications/oecd-due-diligence-guidance-for-responsible-supply-chains-of-minerals-from-conflict-affected-and-high-risk-areas_9789264252479-en.html)<br>[Full text (PDF)](https://www.oecd.org/content/dam/oecd/en/publications/reports/2016/04/oecd-due-diligence-guidance-for-responsible-supply-chains-of-minerals-from-conflict-affected-and-high-risk-areas_g1g65996/9789264252479-en.pdf) | [International Tin Association](https://www.internationaltin.org/oecd/) |
| Targeted sanctions (US / EU) | [OFAC: DRC-related sanctions](https://ofac.treasury.gov/sanctions-programs-and-country-information/democratic-republic-of-the-congo-related-sanctions)<br>[OFAC Sanctions List Search](https://sanctionssearch.ofac.treas.gov/)<br>[EU Sanctions Map](https://www.sanctionsmap.eu/) | [The Star (Apr 2026)](https://www.thestar.com.my/news/world/2026/04/27/eu-extends-sanctions-against-myanmar-by-a-year)<br>[ThePrint (Jul 2025)](https://theprint.in/world/us-lifts-some-myanmar-sanctions-after-general-asked-trump-for-relief/2702840)<br>[Mining.com (Aug 2025)](https://www.mining.com/web/us-sanctions-armed-group-mining-firms-over-illicit-congo-minerals)<br>[AllAfrica / Global Witness (Apr 2025)](https://allafrica.com/stories/202504280598.html) |
| Rare earth export controls (China) | [IEA summary of Announcement No. 18](https://www.iea.org/policies/26796-export-controls-on-certain-medium-and-heavy-rare-earth-items)<br>[CSET translation of Announcement No. 61](https://cset.georgetown.edu/publication/mofcom-notice-2025-61)<br>[Pillsbury: the November 2025 suspension](https://www.pillsburylaw.com/en/news-and-insights/china-suspends-export-controls-certain-critical-minerals-related-items.html) | [Holland & Knight on Announcement No. 18 (Apr 2025)](https://www.hklaw.com/en/insights/publications/2025/04/china-imposes-export-controls-on-medium-and-heavy-rare-earth-materials)<br>[Pillsbury on the November 2025 suspension](https://www.pillsburylaw.com/en/news-and-insights/china-suspends-export-controls-certain-critical-minerals-related-items.html) |
| Producer-country enforcement (Local) | [EITI: Myanmar](https://eiti.org/countries/myanmar)<br>[EITI: Indonesia](https://eiti.org/countries/indonesia)<br>[EITI: DR Congo](https://eiti.org/countries/democratic-republic-congo) | [Mongabay on Global Witness](https://news.mongabay.com/2022/08/toxic-rare-earth-mines-fuel-deforestation-rights-abuses-in-myanmar-report-says/)<br>[The Irrawaddy on Wa tin](https://www.irrawaddy.com/?p=127037)<br>[VOI (Jul 2025)](https://voi.id/en/amp/491796)<br>[Antara (Sep 2025)](https://en.antaranews.com/news/383205/govt-calls-for-shutdown-of-1000-illegal-tin-mines-in-bangka-belitung)<br>[Reuters via Monitor](https://www.monitor.co.ug/uganda/news/inside-the-mine-that-feeds-the-tech-world-and-funds-congo-s-rebels-5154474) |

### 4.2 Regions: documented harm

**Kachin, Myanmar**

- *2,700+ rare earth mining pools by March 2022:* [Global Witness, Myanmar's poisoned mountains (Aug 2022)](https://globalwitness.org/en/campaigns/transition-minerals/myanmars-poisoned-mountains) (NGO investigation); [Global Witness, Fuelling the future, poisoning the present (May 2024)](https://globalwitness.org/en/campaigns/transition-minerals/fuelling-the-future-poisoning-the-present-myanmars-rare-earth-boom) (NGO investigation)
- *~½ of world heavy rare earth output came from sites seized in 2024:* [CNBC, quoting CSIS (Jun 2025)](https://www.cnbc.com/2025/06/24/chinas-rare-earth-dominance-myanmar-plays-a-critical-role-.html) (News, citing think tank); [ISP-Myanmar, Rare earth mining in Myanmar's war-torn regions (Jun 2025)](https://ispmyanmar.com/wp-content/uploads/2025/06/Rare-Earth-Mining-in-Myanmars-War-Torn-Regions.pdf) (Research institute)
- *93% of US yttrium compound imports came from China, 2020–23:* [USGS, Mineral Commodity Summaries 2025: Yttrium](https://pubs.usgs.gov/periodicals/mcs2025/mcs2025-yttrium.pdf) (US government data)
- *451 rare earth mines in Kachin's Irrawaddy basin; 260 opened since the 2021 coup:* [Mongabay, reporting Stimson Center satellite data (Oct 2025)](https://news.mongabay.com/2025/10/more-thai-rivers-and-downstream-communities-at-risk-from-myanmars-rare-earth-mines) (News, citing think-tank data); [Global Witness, Myanmar's poisoned mountains (Aug 2022)](https://globalwitness.org/en/campaigns/transition-minerals/myanmars-poisoned-mountains) (NGO investigation)

**Shan & Wa, Myanmar**

- *Forced labor by trafficked workers at a rare earth mine (May 2026):* [Shan Human Rights Foundation (May 2026)](https://shanhumanrights.org?p=5051) (Human rights NGO, first-hand testimony); [The Irrawaddy, via Business & Human Rights Resource Centre (May 2026)](https://www.business-humanrights.org/my/%E1%80%9E%E1%80%90%E1%80%84/myanmar-uwsa-alleged-of-trafficking-scam-workers-into-chinese-operated-rare-earth-mines) (News)
- *63 rare earth mining sites near the Chinese border, most opened after the 2021 coup:* [Yale Environment 360](https://e360.yale.edu/features/myanmar-rare-earth-mining) (Investigative journalism)
- *$40M in losses downstream in Thailand from polluted rivers:* [Mongabay, reporting Stimson Center satellite data (Oct 2025)](https://news.mongabay.com/2025/10/more-thai-rivers-and-downstream-communities-at-risk-from-myanmars-rare-earth-mines) (News, citing think-tank data)

**Bangka Belitung, Indonesia**

- *~6,300 child laborers in informal tin mining (ILO survey, 2014):* [ILO, Sectoral survey of child labour in informal tin mining, Bangka Belitung (Dec 2015)](https://www.ilo.org/publications/sectoral-survey-child-labour-informal-tin-mining-kepulauan-bangka-belitung) (UN agency survey); [UK government K4D review, citing the ILO survey](https://assets.publishing.service.gov.uk/media/5a5f34feed915d7dfb57d02f/209-213-Child-labour-in-mining.pdf) (Government research review)
- *57 deaths in abandoned tin pits, 2014–2020:* [Mongabay, citing JATAM (Jun 2021)](https://news.mongabay.com/2021/06/tin-mines-close-in-on-an-indonesian-hamlet-still-clinging-to-nature) (News, citing watchdog data); [Eco-Business, citing JATAM](https://www.eco-business.com/ms/news/grim-toll-from-indonesias-abandoned-mines-may-get-even-worse-report/) (News)
- *Rp300T in state losses from illegal tin mining, 2015–2022:* [Jakarta Globe](https://jakartaglobe.id/news/mining-tycoon-harvey-moeis-begins-serving-20-years-in-prison-over-rp-300-trillion-tin-corruption-case) (News); [Indonesian National Police (Feb 2025)](https://inp.polri.go.id/artikel/harvey-moeis-prison-sentence-increased-to-20-years-in-tin-corruption-case) (Government)
- *1,000 illegal tin mines targeted in a September 2025 crackdown:* [Antara, Indonesia's state news agency (Sep 2025)](https://en.antaranews.com/news/383205/govt-calls-for-shutdown-of-1000-illegal-tin-mines-in-bangka-belitung) (Government news agency)

**Rubaya, DR Congo → Rwanda**

- *~15% of the world's coltan:* [Reuters (Jan 2026)](https://www.reuters.com/world/africa/more-than-200-killed-coltan-mine-collapse-east-congo-official-says-2026-01-30) (Wire service); [Global Witness, Who buys Rwanda's smuggled coltan?](https://globalwitness.org/en/campaigns/transition-minerals/who-buys-rwandas-smuggled-coltan-the-global-journey-of-conflict-coltan-from-drc-to-the-worlds-electronics) (NGO investigation)
- *$800k a month to M23 from coltan taxes:* [UN Group of Experts on the DRC, S/2024/969 (Dec 2024)](https://documents.un.org/doc/undoc/gen/n24/373/37/pdf/n2437337.pdf) (UN Security Council report); [Global Witness, Who buys Rwanda's smuggled coltan?](https://globalwitness.org/en/campaigns/transition-minerals/who-buys-rwandas-smuggled-coltan-the-global-journey-of-conflict-coltan-from-drc-to-the-worlds-electronics) (NGO investigation)
- *Forced labor and forced recruitment documented by Amnesty (2026):* [Amnesty International, 'We didn't come to play' (Sep 2026)](https://www.amnesty.org/en/documents/afr62/1454/2026/en) (Human rights investigation); [Amnesty International news release (Sep 2026)](https://www.amnesty.org/en/latest/news/2026/09/drc-m23-fighters-abused-miners-and-trafficked-gold-and-coltan-to-rwanda) (Human rights investigation)
- *200+ killed in each of two Rubaya mine collapses in 2026:* [Reuters (Jan 2026)](https://www.reuters.com/world/africa/more-than-200-killed-coltan-mine-collapse-east-congo-official-says-2026-01-30) (Wire service); [Reuters (Mar 2026)](https://www.reuters.com/business/environment/landslide-kills-over-200-people-congos-rubaya-mine-mines-ministry-says-2026-03-04) (Wire service)

### 4.3 Human rights evidence (Why it matters tab)

- **Forced labor:** [Shan Human Rights Foundation (May 2026)](https://shanhumanrights.org?p=5051) · [Amnesty International, 'We didn't come to play' (Sep 2026)](https://www.amnesty.org/en/documents/afr62/1454/2026/en)
- **Killings, torture and detention:** [Amnesty International news release (Sep 2026)](https://www.amnesty.org/en/latest/news/2026/09/drc-m23-fighters-abused-miners-and-trafficked-gold-and-coltan-to-rwanda) · [Full report](https://www.amnesty.org/en/documents/afr62/1454/2026/en)
- **Child labor:** [ILO survey (Dec 2015)](https://www.ilo.org/publications/sectoral-survey-child-labour-informal-tin-mining-kepulauan-bangka-belitung) · [UK government K4D review of the survey](https://assets.publishing.service.gov.uk/media/5a5f34feed915d7dfb57d02f/209-213-Child-labour-in-mining.pdf)
- **Deadly working conditions:** [Reuters (Jan 2026)](https://www.reuters.com/world/africa/more-than-200-killed-coltan-mine-collapse-east-congo-official-says-2026-01-30) · [Reuters (Mar 2026)](https://www.reuters.com/business/environment/landslide-kills-over-200-people-congos-rubaya-mine-mines-ministry-says-2026-03-04) · [Mongabay, citing JATAM (2021)](https://news.mongabay.com/2021/06/tin-mines-close-in-on-an-indonesian-hamlet-still-clinging-to-nature) · [Eco-Business, citing JATAM](https://www.eco-business.com/ms/news/grim-toll-from-indonesias-abandoned-mines-may-get-even-worse-report/)
- **Funding armed groups:** [UN Group of Experts, S/2024/969](https://documents.un.org/doc/undoc/gen/n24/373/37/pdf/n2437337.pdf) · [Global Witness: Who buys Rwanda's smuggled coltan?](https://globalwitness.org/en/campaigns/transition-minerals/who-buys-rwandas-smuggled-coltan-the-global-journey-of-conflict-coltan-from-drc-to-the-worlds-electronics) · [ISP-Myanmar (Jun 2025)](https://ispmyanmar.com/wp-content/uploads/2025/06/Rare-Earth-Mining-in-Myanmars-War-Torn-Regions.pdf)
- **Poisoned land and water:** [Global Witness press release (May 2024)](https://globalwitness.org/en/press-releases/new-investigation-reveals-the-alarming-expansion-of-heavy-rare-earth-mining-in-myanmar-and-the-devastating-cost-for-communities-and-the-environment) · [Mongabay, citing Stimson Center data (Oct 2025)](https://news.mongabay.com/2025/10/more-thai-rivers-and-downstream-communities-at-risk-from-myanmars-rare-earth-mines)

### 4.4 Solutions

- **Close the legal gaps:** [Regulation (EU) 2017/821](https://eur-lex.europa.eu/eli/reg/2017/821/oj) · [DHS: UFLPA Entity List](https://www.dhs.gov/uflpa-entity-list) · [Regulation (EU) 2024/3015](https://eur-lex.europa.eu/eli/reg/2024/3015/oj) · [BAFA: LkSG overview](https://www.bafa.de/EN/Supply_Chain_Act/Overview/overview_node.html) · [METI guidelines](https://www.meti.go.jp/policy/economy/business-jinken/guidelines/provisionalenglishtranslation.pdf) · [OFAC: DRC-related sanctions](https://ofac.treasury.gov/sanctions-programs-and-country-information/democratic-republic-of-the-congo-related-sanctions)
- **Put conditions on public fusion money:** [OECD Guidance](https://www.oecd.org/en/publications/oecd-due-diligence-guidance-for-responsible-supply-chains-of-minerals-from-conflict-affected-and-high-risk-areas_9789264252479-en.html) · [Responsible Minerals Initiative smelter lists](https://www.responsiblemineralsinitiative.org/smelters-refiners-lists/)
- **Questions fusion buyers can put in contracts:** [Rare-earth barium copper oxide (Wikipedia)](https://en.wikipedia.org/wiki/Rare-earth_barium_copper_oxide) · [IPAC'10 paper comparing YBCO and GdBCO tapes](https://proceedings.jacow.org/IPAC10/papers/mopeb058.pdf)
- **Alternative sources:** [Serra Verde: operations](https://www.serraverde.com/operations) · [The Diplomat (May 2026)](https://thediplomat.com/2026/05/will-the-us-serra-verde-acquisition-help-break-chinas-rare-earth-monopoly) · [Mining.com (May 2025)](https://www.mining.com/lynas-becomes-first-producer-of-heavy-rare-earths-outside-china) · [Lynas announcement (PDF)](https://wcsecure.weblink.com.au/pdf/LYC/02947190.pdf) · [GlobalData on the new facility (Oct 2025)](https://finance.yahoo.com/news/lynas-build-hre-separation-facility-115432994.html) · [SFA Oxford on CBMM](https://www.sfa-oxford.com/market-news-and-insights/niobium-swing-producer-cbmm-driving-the-future-of-advanced-materials/) · [Responsible Minerals Initiative smelter lists](https://www.responsiblemineralsinitiative.org/smelters-refiners-lists/) · [ITSCI](https://www.itsci.org/)
- **Incentives for producer countries:** [US State Department: the framework text](https://www.state.gov/regional-economic-integration-framework-between-the-government-of-the-democratic-republic-of-the-congo-and-the-government-of-the-republic-of-rwanda) · [IPIS analysis](https://ipisresearch.be/weekly-briefing/thorny-issues-risk-jeopardising-the-us-brokered-peace-deal-between-the-drc-and-rwanda-but-can-regional-economic-integration-offer-solace) · [European Commission (Feb 2024)](https://ec.europa.eu/commission/presscorner/detail/en/ip_24_822) · [Mongabay (Feb 2025)](https://news.mongabay.com/2025/02/eu-parliament-calls-for-end-to-rwanda-mineral-pact-over-drc-conflict-links) · [Antara (Sep 2025)](https://en.antaranews.com/news/383205/govt-calls-for-shutdown-of-1000-illegal-tin-mines-in-bangka-belitung) · [EITI: Indonesia](https://eiti.org/countries/indonesia) · [EITI: Myanmar](https://eiti.org/countries/myanmar) · [Shan Human Rights Foundation](https://shanhumanrights.org?p=5051)

### 4.5 Reactor and magnet facts

- [ITER: Magnets](https://www.iter.org/machine/magnets): 18 D-shaped toroidal field coils, six ring-shaped poloidal field coils, a central solenoid of six modules, and Nb₃Sn and NbTi conductors cooled to about 4 K (−269 °C).
- [ITER: What is fusion?](https://www.iter.org/fusion-energy/what-fusion): plasma at 150 million °C, about ten times hotter than the Sun's core.
- [MIT News (Sep 2021)](https://news.mit.edu/2021/MIT-CFS-major-advance-toward-fusion-energy-0908): the 20-tesla high-temperature superconducting magnet built by CFS and MIT.
- [Commonwealth Fusion Systems](https://cfs.energy/technology/hts-magnets), [Tokamak Energy](https://tokamakenergy.com/) and [Proxima Fusion](https://www.proximafusion.com/): each describes its high-temperature superconducting magnets.
- [Rare-earth barium copper oxide](https://en.wikipedia.org/wiki/Rare-earth_barium_copper_oxide) and an [IPAC'10 paper](https://proceedings.jacow.org/IPAC10/papers/mopeb058.pdf): REBCO tape can be made with yttrium or gadolinium.

### 4.6 Photo credits

- Luwowo coltan mine near Rubaya, North Kivu, during a UN visit in March 2014, ten years before M23 took control. Photo: [MONUSCO Photos](https://commons.wikimedia.org/wiki/File:SRSG_visits_coltan_mine_in_Rubaya_(13406579753).jpg), [CC BY-SA 2.0](https://creativecommons.org/licenses/by-sa/2.0), via Wikimedia Commons.
- Satellite composite of tin-mining scars on eastern Bangka Island, 2022, from Planet NICFI imagery. Photo: [Nrg800](https://commons.wikimedia.org/wiki/File:BangkaIsland_TinMines_PlanetNICFI_2022.jpg), [CC BY-SA 4.0](https://creativecommons.org/licenses/by-sa/4.0), via Wikimedia Commons.
- A floating tin-dredging pontoon (ponton timah apung) moored on shore, Bangka, 2020. Photo: [Cun Cun](https://commons.wikimedia.org/wiki/File:Ponton_timah_apung.jpg), [CC BY-SA 4.0](https://creativecommons.org/licenses/by-sa/4.0), via Wikimedia Commons.
- The Kok River at Tha Ton, Thailand. It rises in Shan State, and Thai communities downstream now report contamination linked to rare earth mines. Photo from 2007, before the mining boom. Photo: [Vyacheslav Argenberg](https://commons.wikimedia.org/wiki/File:Tha_Ton,_Bridge_over_Kok_River,_Mae_Ai,_Thailand.jpg), [CC BY 4.0](https://creativecommons.org/licenses/by/4.0), via Wikimedia Commons.

## 5. Limitations

### Corrections from the source check (9 November 2026)

- **Shan and Wa:** "rare earth sites rose from 12 to 85 after the coup" could not be traced to any source. Replaced with the satellite count of 63 sites near the Chinese border (Shan Human Rights Foundation and Stimson Center, via Yale Environment 360).
- **Shan and Wa:** pollution of the Salween River is not documented, because the river is not monitored. The documented case is the Kok River, with about $40 million in losses downstream in Thailand.
- **Bangka Belitung:** "240,000 hectares of mangrove damaged" could not be traced to a primary source; Walhi has reported 400 hectares. Replaced with the September 2025 crackdown on 1,000 illegal mines.
- **Bangka Belitung:** the 57 deaths in abandoned pits (JATAM, 2014–2020) are not broken down by age. "Mostly children" applies to the national total of 168.
- **Rubaya:** "child labor is common" had no strong source. Replaced with the two 2026 mine collapses reported by Reuters.
- **Kachin:** toxic waste in the N'Mai Kha is described by Global Witness as residents' fear, not a measured finding. The tile now uses Stimson Center mine counts.
- **Rubaya:** "Rwanda-backed M23" is now "an armed group the UN says is backed by Rwanda (Rwanda denies it)".
- **Weaker sources replaced:** a Wikipedia mirror (now the ILO survey), legislation.gov.uk (now EUR-Lex), an unofficial Japan tracker (now METI), a commercial blog on China (now IEA, CSET, Pillsbury and Holland & Knight), Karen News, BNI and an AP article republished by Africanews.

### Evidence still to strengthen

- The UK STEP program's magnet technology could not be confirmed from its own site.
- SPARC's 12.2-tesla field and REBCO's operating temperature of about 20 K come from general knowledge.
- The EU list of conflict-affected areas is cited from a 2020 source; confirm it is still maintained.
- Companies marked "Example" on the supply map come from general industry knowledge.

### Consistency notes

- **UFLPA in Bangka Belitung and Rubaya** is scored "Doesn't reach," but its gap text says the rule is not relevant. Under the verdict steps it would score "Not relevant." It is kept as "Doesn't reach" to show that the strongest US import tool is limited to one geography.
- **The EU Battery Regulation** is scored "Doesn't reach" everywhere, which is consistent: it is ruled out by mineral.

### Scope limits

- The matrix measures whether a rule reaches a harm on paper, not how strongly it is enforced, except where the gap text says so.
- It covers four high-risk regions; it does not estimate how much fusion magnet material comes from them.
- Rule terms are as of 9 November 2026. This is research, not legal advice.

## 6. Keeping it current

1. Re-check each rule's status, starting with those that are changing (2.5).
2. Re-run the verdict steps (2.3) for any rule whose scope or start date has changed.
3. Recount the tallies (2.6).
4. Update the "checked" date on the site and in these documents.
