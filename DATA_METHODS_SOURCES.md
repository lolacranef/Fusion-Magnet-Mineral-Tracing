# Data, Methods and Sources

*Companion to [CONCEPT.md](CONCEPT.md) and the [interactive site](https://lolacranef.github.io/Fusion-Magnet-Mineral-Tracing/). It explains how the stress test is built, how each result and leak is decided, and where every piece of evidence comes from. Rule terms checked 9 November 2026. Research, not legal advice.*

## 1. The dataset

The core dataset is a **stress test**: 13 rules tested against the documented abuses in 4 mining regions. A rule is tested in a region only if the abuse's real route passes it, giving 45 tests; the other 7 pairs are recorded as not tested, with the reason. Each test records whether the rule would stop the abuse and, if not, exactly how it gets through.

| Dimension | Count | Items |
|---|---|---|
| Rules | 13 | Dodd-Frank §1502 · EU Conflict Minerals Regulation · Corporate Sustainability Due Diligence Directive · Supply Chain Due Diligence Act (LkSG) · OECD Minerals Due Diligence Guidance · Human Rights Due Diligence Guidelines · Industry schemes and company codes · Tariff Act §307 import ban · EU Forced Labor Regulation · Uyghur Forced Labor Prevention Act · Targeted sanctions · China's rare earth controls · Producer and transit country controls |
| Regions | 4 | Kachin, Myanmar · Shan & Wa, Myanmar · Bangka Belitung, Indonesia · Rubaya, DR Congo → Rwanda |
| Tests | 45 | Rule and region pairs where the abuse's route passes the rule |
| Minerals | 5 | Yttrium and heavy rare earths · other rare earths · tin · niobium · tantalum |
| Magnet types | 2 | REBCO high-temperature superconducting tape · Nb₃Sn and NbTi low-temperature superconducting wire |

Each **rule profile** records minerals covered, geographic scope, who must act, what it requires, status and sources. Each **region profile** records what is mined, who controls it, documented harm, and the trade route with the steps where origin is lost. Each **test** records the result, what the rule would require there, how the abuse gets through, the leak type, who opens the leak, the step in the route, the evidence type, sources, and the fix that would hold.

## 2. Methods

### 2.1 Choosing regions

A region is included only if it meets all three tests:

1. It produces a mineral used in fusion superconducting magnets: rare earths for REBCO tape, or tin and niobium for Nb₃Sn and NbTi wire.
2. Credible reporting from NGOs, the UN, major news outlets or governments documents serious harm there: forced or child labor, armed-group financing, or major environmental damage.
3. The mineral leaves the region through a route where its origin can be lost, such as separation, smelting or re-export through a third country.

The four regions illustrate how the rules fail. They are not a full survey of fusion's mineral supply. Brazil, which supplies about 90% of the world's niobium, and lower-risk rare earth sources are deliberately left out.

### 2.2 Choosing rules

The set covers what a buyer, investigator or regulator could actually use against these abuses: company sourcing duties (disclosure and due diligence laws, voluntary standards, and the industry schemes and supplier codes those laws lean on), border bans, sanctions, and state controls in producer, transit and processing countries. The EU Battery Regulation, in earlier versions of this research, was dropped: it covers none of these minerals, so no abuse here could ever meet it.

### 2.3 Running a stress test

Each test starts from the documented abuse, not from the rule, and follows the mineral along its real route. Four questions are asked in order; the first answer that settles it decides the result.

1. **Does the abuse's route pass this rule?** The rule must put a sourcing, import, dealing or disclosure duty on someone the mineral actually passes, for this kind of harm. If not: *Not tested*, with the reason.
2. **Is it binding?** If it only recommends action: *No legal duty*.
3. **Is it in force?** If only from a future date: *Not yet in force*.
4. **Would it stop the documented abuse?** If nothing on the route defeats it: *Holds*. If it fits and has a working procedure but the evidence it needs is blocked by the route: *Holds on paper*. If a named feature of the rule, a company practice, an industry scheme or a government action lets the abuse through: *Leaks*.

### 2.4 Naming the leak

Every failed test records how the abuse gets through, in one or two sentences naming the actor and the step; the leak type; who opens it; where in the route it happens; and the evidence. "Documented" means a named source shows it happening on this route. "Structural" means the rule's text allows it and the route makes it likely, but no case has been published. Statements never go beyond what the rule text and the cited reporting support.

### 2.5 Leak types

| Leak type | What happens | Tests |
|---|---|---|
| Fixed lists | The rule names minerals, countries or companies, and the trade routes around the list. | 6 |
| Mixing | Ore is blended with other supply, so no single shipment can be traced back to the mine. | 1 |
| Laundering paperwork | A legal document, such as a permit, tag or certificate, covers ore it shouldn't. | 4 |
| Certificate accepted as proof | The rule or the buyer accepts an industry audit, and the audit doesn't test this risk. | 2 |
| Third-party buyer | An unlisted company buys from the sanctioned one, and everyone downstream deals only with it. | 1 |
| State-held data | A government records where the ore came from but doesn't share it. | 2 |
| State capture or non-enforcement | Officials issue cover, take part, or don't enforce. | 4 |
| Not knowing is safe | Duties stop at the first supplier unless the buyer already knows of a problem, so not asking is the safe choice. | 5 |
| Size threshold | The companies closest to the risk are too small to be covered. | 4 |
| Wrong harm | The rule only bites on one kind of harm, and the harm here is another kind. | 4 |
| Proof burden | Authorities must tie a mine to specific goods before acting, and the route makes that close to impossible. | 4 |
| No legal duty | The rule only recommends. | 8 |

### 2.6 Who opens the leak

| Who opens it | Meaning | Tests | Documented |
|---|---|---|---|
| The rule's own design | Scope, lists and thresholds written into the rule | 16 | 7 |
| Governments | Officials who issue cover, keep data secret, or don't enforce | 18 | 11 |
| Companies | Buyers and suppliers that don't ask, or accept paper | 6 | 6 |
| Industry schemes | Audits and tags accepted as proof | 4 | 3 |
| Armed groups | Groups that run the mines and decide what leaves | 1 | 1 |

### 2.7 Checking rule terms and facts

Scopes, thresholds and dates were checked against the cited sources on 9 November 2026. Rules changing on that date: Dodd-Frank §1502 (future uncertain), Germany's LkSG (amendment before the Bundestag), the EU Conflict Minerals Regulation (under review) and China's Announcement No. 61 (paused until 10 November 2026).

### 2.8 Tally

| Region | Holds | Holds on paper | Not yet in force | No legal duty | Leaks | Not tested |
|---|---|---|---|---|---|---|
| Kachin | 0 | 0 | 2 | 2 | 6 | 3 |
| Shan & Wa | 0 | 1 | 2 | 2 | 8 | 0 |
| Bangka Belitung | 0 | 1 | 2 | 2 | 5 | 3 |
| Rubaya | 0 | 1 | 2 | 2 | 7 | 1 |
| **All 52 pairs** | **0** | **3** | **8** | **8** | **26** | **7** |

## 3. How the site shows the data

| Element | What it shows | Note |
|---|---|---|
| Result icons and colors | Shields from violet (holds) to red (leaks); grey for not tested | Matches the site palette |
| Leak score (cover strips, bar lengths) | Holds 0 · Holds on paper 1 · Not yet in force or No legal duty 2 · Leaks 3, averaged over regions where the rule is tested | A simple score made for this site |
| Rule groups | Disclosure & due diligence laws, Voluntary standards & industry schemes, Border bans, Sanctions & state controls | Our own grouping |
| Where the abuse gets through | Each failed test placed at the route step where the abuse gets through | Steps read from each region's documented route |
| Leak map filter | Highlights tests by who opens the leak | Uses the 'opened by' field of each test |
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
| Corporate Sustainability Due Diligence Directive (EU 2026/470) | [Directive (EU) 2024/1760, current version (EUR-Lex)](https://eur-lex.europa.eu/eli/dir/2024/1760/oj)<br>[Amending Directive (EU) 2026/470 (EUR-Lex)](https://eur-lex.europa.eu/eli/dir/2026/470/oj/eng) | [Covington (Feb 2026)](https://www.cov.com/news-and-insights/insights/2026/02/eu-csddd-csrd-omnibus-published-in-official-journal-transposition-delegated-acts-and-guidelines-are-next) |
| Supply Chain Due Diligence Act (LkSG) (Germany) | [LkSG, official text in German](https://www.gesetze-im-internet.de/lksg/)<br>[BAFA: overview in English](https://www.bafa.de/EN/Supply_Chain_Act/Overview/overview_node.html)<br>[BAFA: complaints procedure](https://www.bafa.de/EN/Supply_Chain_Act/Complaints_Procedure/complaints_procedure_node.html) | [Taylor Wessing (Jan 2026)](https://www.taylorwessing.com/en/insights-and-events/insights/2026/01/lksg) |
| OECD Minerals Due Diligence Guidance (International) | [OECD Guidance: official page](https://www.oecd.org/en/publications/oecd-due-diligence-guidance-for-responsible-supply-chains-of-minerals-from-conflict-affected-and-high-risk-areas_9789264252479-en.html)<br>[Full text (PDF)](https://www.oecd.org/content/dam/oecd/en/publications/reports/2016/04/oecd-due-diligence-guidance-for-responsible-supply-chains-of-minerals-from-conflict-affected-and-high-risk-areas_g1g65996/9789264252479-en.pdf) | [International Tin Association](https://www.internationaltin.org/oecd/) |
| Human Rights Due Diligence Guidelines (Japan) | [Guidelines, provisional English translation (METI)](https://www.meti.go.jp/policy/economy/business-jinken/guidelines/provisionalenglishtranslation.pdf)<br>[METI: business and human rights](https://www.meti.go.jp/english/policy/economy/biz_human_rights/index.html) | [METI: business and human rights](https://www.meti.go.jp/english/policy/economy/biz_human_rights/index.html) |
| Industry schemes and company codes (Private) | [RMI: smelter and refiner lists](https://www.responsiblemineralsinitiative.org/smelters-refiners-lists/)<br>[ITSCI](https://www.itsci.org/)<br>[Implementing Decision (EU) 2025/2071 (EUR-Lex)](https://eur-lex.europa.eu/eli/dec_impl/2025/2071/oj/eng) | [Global Witness, The ITSCI laundromat (Apr 2022)](https://globalwitness.org/en/campaigns/transition-minerals/the-itsci-laundromat/)<br>[ITSCI response to Global Witness (Jun 2026)](https://www.itsci.org/2026/06/12/itsci-response-to-global-witness-report-on-rwandas-coltan/)<br>[European Commission on RMAP recognition (Oct 2025)](https://policy.trade.ec.europa.eu/news/first-supply-chain-due-diligence-scheme-recognised-under-conflict-minerals-regulation-facilitate-2025-10-17_en)<br>[Reuters via SDCExec (Nov 2016)](https://www.sdcexec.com/risk-compliance/news/12283021/for-apple-and-others-tin-supply-chain-has-ties-to-rebelheld-myanmar-mine) |
| Tariff Act §307 import ban (US) | [19 U.S.C. §1307: the statute](https://www.law.cornell.edu/uscode/text/19/1307)<br>[19 CFR §12.42: CBP's procedure](https://www.law.cornell.edu/cfr/text/19/12.42)<br>[CBP: Withhold Release Orders and Findings](https://www.cbp.gov/trade/forced-labor/withhold-release-orders-and-findings)<br>[CBP e-Allegations portal](https://eallegations.cbp.gov/) | [CRS IF11360 (Jul 2026)](https://www.everycrsreport.com/files/2026-07-09_IF11360_c9e63009c902a08f9494a2def20f5e391c71b6fa.html) |
| EU Forced Labor Regulation (EU 2024/3015) | [Regulation (EU) 2024/3015 (EUR-Lex)](https://eur-lex.europa.eu/eli/reg/2024/3015/oj) | [Mayer Brown (Jun 2026)](https://www.mayerbrown.com/en/insights/publications/2026/06/the-eu-forced-labour-regulation-10-questions-every-general-counsel-should-be-asking) |
| Uyghur Forced Labor Prevention Act (US) | [Public Law 117-78 (congress.gov)](https://www.congress.gov/bill/117th-congress/house-bill/6256)<br>[DHS: UFLPA Entity List](https://www.dhs.gov/uflpa-entity-list)<br>[CBP: UFLPA guidance](https://www.cbp.gov/trade/forced-labor/UFLPA) | [Troutman (Aug 2026)](https://www.troutman.com/insights/dhs-adds-43-companies-to-uflpa-entity-list-in-largest-ever-single-expansion-effective-august-3/) |
| Targeted sanctions (US / EU) | [OFAC: DRC-related sanctions](https://ofac.treasury.gov/sanctions-programs-and-country-information/democratic-republic-of-the-congo-related-sanctions)<br>[OFAC Sanctions List Search](https://sanctionssearch.ofac.treas.gov/)<br>[EU Sanctions Map](https://www.sanctionsmap.eu/) | [OFAC: UWSA Kingpin Act designation (Jun 2003)](https://ofac.treasury.gov/recent-actions/20030602)<br>[The Star (Apr 2026)](https://www.thestar.com.my/news/world/2026/04/27/eu-extends-sanctions-against-myanmar-by-a-year)<br>[ThePrint (Jul 2025)](https://theprint.in/world/us-lifts-some-myanmar-sanctions-after-general-asked-trump-for-relief/2702840)<br>[Mining.com (Aug 2025)](https://www.mining.com/web/us-sanctions-armed-group-mining-firms-over-illicit-congo-minerals)<br>[AllAfrica / Global Witness (Apr 2025)](https://allafrica.com/stories/202504280598.html) |
| China's rare earth controls (China) | [IEA: Regulations on the Management of Rare Earths](https://www.iea.org/policies/25387-regulations-on-the-management-of-rare-earths)<br>[IEA summary of Announcement No. 18](https://www.iea.org/policies/26796-export-controls-on-certain-medium-and-heavy-rare-earth-items)<br>[CSET translation of Announcement No. 61](https://cset.georgetown.edu/publication/mofcom-notice-2025-61)<br>[Pillsbury: the November 2025 suspension](https://www.pillsburylaw.com/en/news-and-insights/china-suspends-export-controls-certain-critical-minerals-related-items.html) | [Holland & Knight on Announcement No. 18 (Apr 2025)](https://www.hklaw.com/en/insights/publications/2025/04/china-imposes-export-controls-on-medium-and-heavy-rare-earth-materials)<br>[Pillsbury on the November 2025 suspension](https://www.pillsburylaw.com/en/news-and-insights/china-suspends-export-controls-certain-critical-minerals-related-items.html)<br>[Faegre Drinker on the October 2024 regulations](https://www.faegredrinker.com/en/insights/publications/2024/10/china-issues-regulations-on-rare-earth-administration)<br>[Global Times via GlobalSecurity on imported ore (Aug 2025)](https://www.globalsecurity.org/wmd/library/news/china/2025/08/china-250822-globaltimes01.htm) |
| Producer and transit country controls (Local) | [EITI: Myanmar](https://eiti.org/countries/myanmar)<br>[EITI: Indonesia](https://eiti.org/countries/indonesia)<br>[EITI: DR Congo](https://eiti.org/countries/democratic-republic-congo)<br>[UN Comtrade](https://comtradeplus.un.org/) | [Mongabay on Global Witness](https://news.mongabay.com/2022/08/toxic-rare-earth-mines-fuel-deforestation-rights-abuses-in-myanmar-report-says/)<br>[The Irrawaddy on Wa tin](https://www.irrawaddy.com/?p=127037)<br>[VOI (Jul 2025)](https://voi.id/en/amp/491796)<br>[Antara (Sep 2025)](https://en.antaranews.com/news/383205/govt-calls-for-shutdown-of-1000-illegal-tin-mines-in-bangka-belitung)<br>[Reuters via Monitor](https://www.monitor.co.ug/uganda/news/inside-the-mine-that-feeds-the-tech-world-and-funds-congo-s-rebels-5154474)<br>[Swissinfo on the UN Group of Experts (Jul 2025)](https://www.swissinfo.ch/eng/international-geneva/un-experts-warn-congos-conflict-minerals-slipping-into-global-market/89978793)<br>[Mining.com: seized smelters handed to PT Timah (Oct 2025)](https://www.mining.com/web/indonesia-hands-over-six-seized-tin-smelters-to-state-miner) |

### 4.1a Stress test evidence

**Kachin**

- [Covington on the 2026 CSDDD amendment (Feb 2026)](https://www.cov.com/news-and-insights/insights/2026/02/eu-csddd-csrd-omnibus-published-in-official-journal-transposition-delegated-acts-and-guidelines-are-next): EU CSDDD
- [Global Witness, Myanmar's poisoned mountains (Aug 2022)](https://globalwitness.org/en/campaigns/transition-minerals/myanmars-poisoned-mountains): German LkSG, OECD Guidance, US §307 ban, EU Forced Labor ban, Producer & transit states
- [BAFA: LkSG overview](https://www.bafa.de/EN/Supply_Chain_Act/Overview/overview_node.html): German LkSG
- [Business & Human Rights Resource Centre, summary of the 2024 Global Witness follow-up](https://www.bhrrc.org/en/latest-news/myanmar-boom-in-illegal-rare-earth-mining-linked-to-supply-chain-of-major-ev-and-wind-turbine-companies-through-china-global-witness-follow-up-investigation-reveals/): OECD Guidance, Industry schemes
- [METI guidelines (provisional English translation)](https://www.meti.go.jp/policy/economy/business-jinken/guidelines/provisionalenglishtranslation.pdf): Japan guidelines
- [Global Witness, Fuelling the future, poisoning the present (May 2024)](https://globalwitness.org/en/campaigns/transition-minerals/fuelling-the-future-poisoning-the-present-myanmars-rare-earth-boom): Industry schemes
- [The Star: EU extends Myanmar sanctions (Apr 2026)](https://www.thestar.com.my/news/world/2026/04/27/eu-extends-sanctions-against-myanmar-by-a-year): Sanctions
- [ThePrint: US lifts some Myanmar sanctions (Jul 2025)](https://theprint.in/world/us-lifts-some-myanmar-sanctions-after-general-asked-trump-for-relief/2702840): Sanctions
- [CNBC, citing Chinese customs data and CSIS (Jun 2025)](https://www.cnbc.com/2025/06/24/chinas-rare-earth-dominance-myanmar-plays-a-critical-role-.html): Sanctions, China RE controls
- [Faegre Drinker: China's Regulations on Rare Earth Administration (Oct 2024)](https://www.faegredrinker.com/en/insights/publications/2024/10/china-issues-regulations-on-rare-earth-administration): China RE controls
- [Global Times via GlobalSecurity: rare earth quota and traceability rules extended to imported ore (Aug 2025)](https://www.globalsecurity.org/wmd/library/news/china/2025/08/china-250822-globaltimes01.htm): China RE controls
- [Reuters via Bangkok Post: KIA allows export of rare earth stockpiles to China (Mar 2025)](https://bangkokpost.com/world/2988924/myanmar-rebel-group-allows-export-of-rare-earth-inventories-to-china-sources-say): Producer & transit states
- [EITI: Myanmar](https://eiti.org/countries/myanmar): Producer & transit states

**Shan & Wa**

- [Reuters via SDCExec: For Apple and others, tin supply chain has ties to rebel-held Myanmar mine (Nov 2016)](https://www.sdcexec.com/risk-compliance/news/12283021/for-apple-and-others-tin-supply-chain-has-ties-to-rebelheld-myanmar-mine): Dodd-Frank §1502, Industry schemes, Sanctions, China RE controls
- [Fortune: Apple, GE supply chains and the Wa mine (Nov 2016)](https://fortune.com/2016/11/29/apple-ge-supply-chain-myanmar): Dodd-Frank §1502
- [European Commission: first due diligence scheme recognised under the Conflict Minerals Regulation (Oct 2025)](https://policy.trade.ec.europa.eu/news/first-supply-chain-due-diligence-scheme-recognised-under-conflict-minerals-regulation-facilitate-2025-10-17_en): EU Conflict Minerals
- [Implementing Decision (EU) 2025/2071 (EUR-Lex)](https://eur-lex.europa.eu/eli/dec_impl/2025/2071/oj/eng): EU Conflict Minerals
- [Regulation (EU) 2017/821 (EUR-Lex)](https://eur-lex.europa.eu/eli/reg/2017/821/oj): EU Conflict Minerals
- [Covington on the 2026 CSDDD amendment (Feb 2026)](https://www.cov.com/news-and-insights/insights/2026/02/eu-csddd-csrd-omnibus-published-in-official-journal-transposition-delegated-acts-and-guidelines-are-next): EU CSDDD
- [BAFA: LkSG overview](https://www.bafa.de/EN/Supply_Chain_Act/Overview/overview_node.html): German LkSG
- [The Irrawaddy on Wa tin](https://www.irrawaddy.com/?p=127037): OECD Guidance, Producer & transit states
- [OECD Minerals Due Diligence Guidance](https://www.oecd.org/en/publications/oecd-due-diligence-guidance-for-responsible-supply-chains-of-minerals-from-conflict-affected-and-high-risk-areas_9789264252479-en.html): OECD Guidance
- [METI guidelines (provisional English translation)](https://www.meti.go.jp/policy/economy/business-jinken/guidelines/provisionalenglishtranslation.pdf): Japan guidelines
- [Shan Human Rights Foundation (May 2026)](https://shanhumanrights.org?p=5051): US §307 ban, EU Forced Labor ban, US UFLPA, Producer & transit states
- [Assent: CBP detention order on artisanal gold from the DRC (2019)](https://www.assent.com/blog/customs-enforcement-gold-drc/): US §307 ban
- [CBP: Withhold Release Orders and Findings](https://www.cbp.gov/trade/forced-labor/withhold-release-orders-and-findings): US §307 ban
- [DHS: UFLPA Entity List](https://www.dhs.gov/uflpa-entity-list): US UFLPA
- [OFAC: Kingpin Act designation of the United Wa State Army (Jun 2003)](https://ofac.treasury.gov/recent-actions/20030602): Sanctions
- [US Treasury: designations of the UWSA's financial network (2008)](https://home.treasury.gov/news/press-releases/hp1268): Sanctions
- [Mining.com: Myanmar's tin exports set to rise as Wa hub resumes mining](https://www.mining.com/web/myanmars-tin-exports-set-to-rise-as-major-hub-resumes-mining): Sanctions, Producer & transit states
- [Faegre Drinker: China's Regulations on Rare Earth Administration (Oct 2024)](https://www.faegredrinker.com/en/insights/publications/2024/10/china-issues-regulations-on-rare-earth-administration): China RE controls
- [Global Times via GlobalSecurity: rare earth quota and traceability rules extended to imported ore (Aug 2025)](https://www.globalsecurity.org/wmd/library/news/china/2025/08/china-250822-globaltimes01.htm): China RE controls

**Bangka Belitung**

- [Ropes & Gray on SEC non-enforcement](https://www.ropesgray.com/en/insights/viewpoints/102kbie/is-u-s-conflict-minerals-disclosure-nearing-an-end): Dodd-Frank §1502
- [Regulation (EU) 2017/821 (EUR-Lex)](https://eur-lex.europa.eu/eli/reg/2017/821/oj): EU Conflict Minerals
- [VOI: smelter officials charged; shell companies in the Timah case](https://voi.id/en/amp/411563): EU Conflict Minerals, OECD Guidance, Industry schemes
- [Tempo: prosecutors seize five smelters in the PT Timah case (Apr 2024)](https://en.tempo.co/amp/1859157/ago-seizes-5-smelter-companies-in-pt-timah-graft-case): EU Conflict Minerals, Industry schemes
- [Covington on the 2026 CSDDD amendment (Feb 2026)](https://www.cov.com/news-and-insights/insights/2026/02/eu-csddd-csrd-omnibus-published-in-official-journal-transposition-delegated-acts-and-guidelines-are-next): EU CSDDD
- [BAFA: LkSG overview](https://www.bafa.de/EN/Supply_Chain_Act/Overview/overview_node.html): German LkSG
- [OECD Minerals Due Diligence Guidance](https://www.oecd.org/en/publications/oecd-due-diligence-guidance-for-responsible-supply-chains-of-minerals-from-conflict-affected-and-high-risk-areas_9789264252479-en.html): OECD Guidance
- [METI guidelines (provisional English translation)](https://www.meti.go.jp/policy/economy/business-jinken/guidelines/provisionalenglishtranslation.pdf): Japan guidelines
- [ILO, child labour survey in Bangka Belitung tin mining (Dec 2015)](https://www.ilo.org/publications/sectoral-survey-child-labour-informal-tin-mining-kepulauan-bangka-belitung): US §307 ban, EU Forced Labor ban
- [Jakarta Globe: Harvey Moeis begins 20-year sentence](https://jakartaglobe.id/news/mining-tycoon-harvey-moeis-begins-serving-20-years-in-prison-over-rp-300-trillion-tin-corruption-case): Producer & transit states
- [Tempo: prosecutors let seized smelters resume operating (2024)](https://en.tempo.co/read/1859856/tin-corruption-ago-allows-seized-smelter-companies-to-resume-operation): Producer & transit states
- [Mining.com: Indonesia hands seized tin smelters to PT Timah (Oct 2025)](https://www.mining.com/web/indonesia-hands-over-six-seized-tin-smelters-to-state-miner): Producer & transit states
- [Mongabay, citing JATAM (Jun 2021)](https://news.mongabay.com/2021/06/tin-mines-close-in-on-an-indonesian-hamlet-still-clinging-to-nature): Producer & transit states

**Rubaya**

- [Ropes & Gray on SEC non-enforcement](https://www.ropesgray.com/en/insights/viewpoints/102kbie/is-u-s-conflict-minerals-disclosure-nearing-an-end): Dodd-Frank §1502
- [Global Witness, Who buys Rwanda's smuggled coltan? (Jun 2026)](https://globalwitness.org/en/campaigns/transition-minerals/who-buys-rwandas-smuggled-coltan-the-global-journey-of-conflict-coltan-from-drc-to-the-worlds-electronics): Dodd-Frank §1502, EU Conflict Minerals, Industry schemes, Sanctions, Producer & transit states
- [ITSCI's response to Global Witness (Jun 2026)](https://www.itsci.org/2026/06/12/itsci-response-to-global-witness-report-on-rwandas-coltan/): EU Conflict Minerals, Industry schemes
- [Swissinfo on the UN Group of Experts report (Jul 2025)](https://www.swissinfo.ch/eng/international-geneva/un-experts-warn-congos-conflict-minerals-slipping-into-global-market/89978793): EU Conflict Minerals, Producer & transit states
- [European Commission: first due diligence scheme recognised under the Conflict Minerals Regulation (Oct 2025)](https://policy.trade.ec.europa.eu/news/first-supply-chain-due-diligence-scheme-recognised-under-conflict-minerals-regulation-facilitate-2025-10-17_en): EU Conflict Minerals
- [Covington on the 2026 CSDDD amendment (Feb 2026)](https://www.cov.com/news-and-insights/insights/2026/02/eu-csddd-csrd-omnibus-published-in-official-journal-transposition-delegated-acts-and-guidelines-are-next): EU CSDDD
- [BAFA: LkSG overview](https://www.bafa.de/EN/Supply_Chain_Act/Overview/overview_node.html): German LkSG
- [Global Witness, The ITSCI laundromat (Apr 2022)](https://globalwitness.org/en/campaigns/transition-minerals/the-itsci-laundromat/): OECD Guidance, Industry schemes
- [OECD Minerals Due Diligence Guidance](https://www.oecd.org/en/publications/oecd-due-diligence-guidance-for-responsible-supply-chains-of-minerals-from-conflict-affected-and-high-risk-areas_9789264252479-en.html): OECD Guidance
- [METI guidelines (provisional English translation)](https://www.meti.go.jp/policy/economy/business-jinken/guidelines/provisionalenglishtranslation.pdf): Japan guidelines
- [Amnesty International, 'We didn't come to play' (Sep 2026)](https://www.amnesty.org/en/documents/afr62/1454/2026/en): US §307 ban, EU Forced Labor ban, US UFLPA
- [Assent: CBP detention order on artisanal gold from the DRC (2019)](https://www.assent.com/blog/customs-enforcement-gold-drc/): US §307 ban
- [DHS: UFLPA Entity List](https://www.dhs.gov/uflpa-entity-list): US UFLPA
- [Mining.com: US sanctions armed group and mining firms over Congo minerals (Aug 2025)](https://www.mining.com/web/us-sanctions-armed-group-mining-firms-over-illicit-congo-minerals): Sanctions
- [AllAfrica / Global Witness: EU sanctions and smuggling (Apr 2025)](https://allafrica.com/stories/202504280598.html): Sanctions
- [European Commission: EU–Rwanda raw materials partnership (Feb 2024)](https://ec.europa.eu/commission/presscorner/detail/en/ip_24_822): Producer & transit states
- [Mongabay: European Parliament calls for suspension (Feb 2025)](https://news.mongabay.com/2025/02/eu-parliament-calls-for-end-to-rwanda-mineral-pact-over-drc-conflict-links): Producer & transit states

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

Each recommendation names the leak it has to survive. The facts are sourced; the recommendations are Coilchain's own analysis.

**Close the loopholes in the law**

- *Follow the ore, not the customs origin.* Write duties and presumptions around where ore was mined, not where it was last processed. Today separation in China and tagging in Rwanda give the metal a new origin, and every rule tested accepts it. Must hold against: Mixing and state-held data: the duty has to reach the processor's feed records, or it stops at the separator. [DHS: UFLPA Entity List](https://www.dhs.gov/uflpa-entity-list)
- *Add rare earths, niobium, and finished tape and wire to the EU Conflict Minerals Regulation.* The regulation is under review in 2026. Today it skips rare earths entirely and covers only ores and metals. Must hold against: Fusion buyers import finished wire and tape, so adding minerals without products changes nothing for them. [Regulation (EU) 2017/821](https://eur-lex.europa.eu/eli/reg/2017/821/oj)
- *Make industry certificates rebuttable.* Since October 2025 the EU accepts RMAP smelter audits as compliance. Recognition should require mine-level origin for high-risk areas, and lapse for any smelter or refiner that buys from exporters under investigation. Must hold against: Certificate accepted as proof: Wa tin passed through a certified smelter, and Rubaya coltan through tagged exporters. [European Commission (Oct 2025)](https://policy.trade.ec.europa.eu/news/first-supply-chain-due-diligence-scheme-recognised-under-conflict-minerals-regulation-facilitate-2025-10-17_en)
- *Replace fixed lists with risk-based scope.* Dodd-Frank names ten countries and four metals, so Wa and Bangka tin produce clean filings and niobium is never asked about. Must hold against: Fixed lists: any list of places or names invites routing around it. [15 U.S.C. §78m(p)](https://www.law.cornell.edu/uscode/text/15/78m)
- *Make the duty to look upstream automatic for critical minerals.* Germany's LkSG only reaches past the first supplier once a buyer has 'substantiated knowledge', and the CSDDD covers only the largest companies from 2029. A sector rule for named minerals should require tracing to the smelter or separator, whatever the buyer's size. Must hold against: Not knowing is safe, and size thresholds: today the safest strategy is not to ask. [BAFA: LkSG overview](https://www.bafa.de/EN/Supply_Chain_Act/Overview/overview_node.html)
- *Cover the harm that is actually happening.* Import bans only bite on forced labor. Kachin's harm is pollution and armed-group revenue; Bangka's is hazardous child labor. Neither reliably counts as forced labor. Must hold against: Wrong harm: a ban that fits one kind of abuse leaves the others legal to import. [Regulation (EU) 2024/3015](https://eur-lex.europa.eu/eli/reg/2024/3015/oj)
- *Make Japan's guidelines binding.* Japan hosts the largest REBCO tape makers. Its review ends in 2026, with any bill in 2027. Must hold against: No legal duty: without a law, the tape makers closest to the separators can decline to name them. [METI guidelines](https://www.meti.go.jp/policy/economy/business-jinken/guidelines/provisionalenglishtranslation.pdf)

**Enforce what already exists**

- *Sanction the trade, not only the group.* The UWSA has been on the US sanctions list since 2003, yet tin from its mine reaches buyers through smelters that aren't listed. In 2025 the US showed buyers can be targeted when it sanctioned two Hong Kong buyers of Congolese minerals. Must hold against: Third-party buyer: unless smelters and traders are designated, the sanctioned group's output is clean one step later. [OFAC (Jun 2003)](https://ofac.treasury.gov/recent-actions/20030602) · [Mining.com (Aug 2025)](https://www.mining.com/web/us-sanctions-armed-group-mining-firms-over-illicit-congo-minerals)
- *Use region-wide detention orders.* In 2019 CBP held artisanal gold from the DRC until importers showed it was clean. The same tool fits coltan exported through Rwanda and rare earths from Wa-held mines. Must hold against: Proof burden: product-by-product cases fail once ore is mixed. A region-wide order shifts the burden to the importer. [Assent on the 2019 gold order](https://www.assent.com/blog/customs-enforcement-gold-drc/)
- *Ask for China's origin records.* China now logs imported ore, including Myanmar feed, in a state traceability system. Governments negotiating rare earth supply could ask for origin disclosure to buyers. Must hold against: State-held data: the record exists; the leak is that it isn't shared. [Faegre Drinker (Oct 2024)](https://www.faegredrinker.com/en/insights/publications/2024/10/china-issues-regulations-on-rare-earth-administration)
- *Restore enforcement of Dodd-Frank reports.* SEC staff stopped enforcing the detailed report in 2017, so filers can declare tagged Rwandan coltan conflict-free without independent checks. Must hold against: Non-enforcement: a disclosure rule nobody checks becomes a certificate. [Ropes & Gray](https://www.ropesgray.com/en/insights/viewpoints/102kbie/is-u-s-conflict-minerals-disclosure-nearing-an-end)

**Put conditions on public fusion money**

- *Require separator and smelter names, and their feed by country.* Fusion buys small volumes and much of it is publicly funded, so a condition on grants and contracts costs little and reaches nearly every magnet maker. Must hold against: Origin reset: a separator's name alone tells you nothing. Its feed records do. [OECD Guidance](https://www.oecd.org/en/publications/oecd-due-diligence-guidance-for-responsible-supply-chains-of-minerals-from-conflict-affected-and-high-risk-areas_9789264252479-en.html)
- *Don't accept tags or audit certificates alone for high-risk areas.* Require independent evidence behind them: exporter mass-balance checks, satellite monitoring of mine sites, and geochemical fingerprinting where it exists. Must hold against: Laundering paperwork: in Rwanda and Bangka the documents were the cover. [Global Witness, The ITSCI laundromat](https://globalwitness.org/en/campaigns/transition-minerals/the-itsci-laundromat/)
- *Tie milestone payments to independent audits and annual public reports.* This mirrors steps 4 and 5 of the OECD framework and gives the public a record to check. Must hold against: Not knowing is safe: public reports make silence visible.

**Questions fusion buyers can put in contracts**

- *Which separator or smelter produced the yttrium, gadolinium, tin or niobium in this tape or wire?.*
- *What share of that plant's feed last year was imported, and from which countries?.* A separator's location says nothing about where its ore was dug. Must hold against: Origin reset at processing
- *Does the plant mix feed from Myanmar, the DRC, Rwanda or informal mines with other supply?.* Yunnan Tin mixed Wa ore with Chinese ore, which made shipments untraceable. Must hold against: Mixing [Reuters via SDCExec (2016)](https://www.sdcexec.com/risk-compliance/news/12283021/for-apple-and-others-tin-supply-chain-has-ties-to-rebelheld-myanmar-mine)
- *Beyond an audit certificate or a tag, what shows the mine of origin?.* Must hold against: Certificate accepted as proof
- *Can we audit the chain of custody, or receive the auditor's report?.*
- *Can the tape use a different rare earth if the source is high-risk?.* REBCO tape can be made with several rare earths. Yttrium (YBCO) and gadolinium (GdBCO) are both in commercial use, which gives buyers room to switch. [Rare-earth barium copper oxide (Wikipedia)](https://en.wikipedia.org/wiki/Rare-earth_barium_copper_oxide) · [IPAC'10 paper comparing YBCO and GdBCO tapes](https://proceedings.jacow.org/IPAC10/papers/mopeb058.pdf)

**Alternative sources**

- *Serra Verde, Brazil: heavy rare earths from ionic clay.* In commercial production since early 2024, producing a concentrate that includes dysprosium, terbium and yttrium. Targets 6,400 metric tons of rare earth oxides a year by the end of 2027. [Serra Verde: operations](https://www.serraverde.com/operations) · [The Diplomat (May 2026)](https://thediplomat.com/2026/05/will-the-us-serra-verde-acquisition-help-break-chinas-rare-earth-monopoly)
- *Lynas, Malaysia: heavy rare earth separation outside China.* Produced the first separated dysprosium outside China in May 2025. Plans announced in October 2025 add yttrium and gadolinium separation within about two years. Must hold against: State-held data: a separator outside China can be asked for its feed records, and buyers can see the answer. [Mining.com (May 2025)](https://www.mining.com/lynas-becomes-first-producer-of-heavy-rare-earths-outside-china) · [Lynas announcement (PDF)](https://wcsecure.weblink.com.au/pdf/LYC/02947190.pdf) · [GlobalData on the new facility (Oct 2025)](https://finance.yahoo.com/news/lynas-build-hre-separation-facility-115432994.html)
- *Brazilian niobium instead of Rubaya coltan.* About 90% of the world's niobium comes from Brazil, mainly from CBMM, so niobium can usually be sourced away from conflict areas. Must hold against: Laundering paperwork: buy from a named mine, not from 'Rwandan' supply. [SFA Oxford on CBMM](https://www.sfa-oxford.com/market-news-and-insights/niobium-swing-producer-cbmm-driving-the-future-of-advanced-materials/)
- *Tin from smelters that disclose their feed.* Audits and tags alone have failed: Wa tin passed through a certified smelter, and Rubaya coltan through tagged exporters. Buy from smelters that report feed by country and mine, and use tagging only with independent checks behind it. Must hold against: Mixing and laundering paperwork [Responsible Minerals Initiative smelter lists](https://www.responsiblemineralsinitiative.org/smelters-refiners-lists/) · [ITSCI](https://www.itsci.org/)

**Incentives for producer and transit countries**

- *DR Congo and Rwanda: make the Washington Accords pay only for clean supply.* The December 2025 Regional Economic Integration Framework commits both governments to ensure the minerals trade no longer funds armed groups. Investment and market access could be tied to independent checks, such as UN Group of Experts findings. Must hold against: Laundering paperwork: market access should depend on independent checks, not Rwanda's own export certificates. [US State Department: the framework text](https://www.state.gov/regional-economic-integration-framework-between-the-government-of-the-democratic-republic-of-the-congo-and-the-government-of-the-republic-of-rwanda) · [IPIS analysis](https://ipisresearch.be/weekly-briefing/thorny-issues-risk-jeopardising-the-us-brokered-peace-deal-between-the-drc-and-rwanda-but-can-regional-economic-integration-offer-solace)
- *Rwanda: condition the EU raw materials partnership.* The EU and Rwanda signed a raw materials partnership in February 2024. In February 2025 the European Parliament called for it to be suspended until Rwanda stops exporting minerals from M23-held areas. Must hold against: State capture: a partnership with the transit state rewards the laundering unless it is conditioned. [European Commission (Feb 2024)](https://ec.europa.eu/commission/presscorner/detail/en/ip_24_822) · [Mongabay (Feb 2025)](https://news.mongabay.com/2025/02/eu-parliament-calls-for-end-to-rwanda-mineral-pact-over-drc-conflict-links)
- *Indonesia: reward legal, verified tin.* Indonesia has convicted those behind illegal tin trading and moved against 1,000 illegal mines. Buyers could offer long-term contracts or price premiums for tin verified at the mine site, and funders could support reclamation of abandoned pits that have killed dozens. Must hold against: Laundering paperwork: the permits themselves were the cover, so rewards must rest on mine-site checks. [Antara (Sep 2025)](https://en.antaranews.com/news/383205/govt-calls-for-shutdown-of-1000-illegal-tin-mines-in-bangka-belitung) · [EITI: Indonesia](https://eiti.org/countries/indonesia)
- *Myanmar: avoid deals that launder the trade, and back independent monitoring.* There is no legitimate government partner, and Myanmar has been suspended from the EITI since the coup. Support for community monitors and satellite tracking keeps evidence flowing. Must hold against: State capture: in Kachin and Wa the armed group is the regulator, so no local certificate means anything. [EITI: Myanmar](https://eiti.org/countries/myanmar) · [Shan Human Rights Foundation](https://shanhumanrights.org?p=5051)

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

### Evidence limits

- Some of the strongest documented cases are dated: the Reuters investigation tracing Wa tin through Yunnan Tin is from 2016. The structure it showed (mixing, certificates accepted as proof, Myanmar outside fixed lists) is unchanged, but current smelter sourcing should be re-checked.
- Global Witness's 2026 findings on ITSCI tags in Rwanda are disputed by ITSCI. Both are cited.
- Whether specific smelters in the PT Timah case held RMAP status, and whether any Chinese separator processing Myanmar ore is on the UFLPA Entity List, could not be confirmed. The tests that depend on this are marked structural.
- CBP's public list of detention orders could not be searched as text, so this research does not claim that no order covers these minerals.

### Scope limits

- The stress test asks whether a rule would stop a documented abuse on its real route. It does not estimate how much fusion magnet material comes from these regions.
- Pairs marked "not tested" are not counted as gaps. They show where a rule could never apply, which is a different finding from a leak.
- Rule terms are as of 9 November 2026, and several rules are changing.
- This is research, not legal advice.

## 6. Keeping it current

1. Re-check each rule's status, starting with those that are changing (2.7).
2. Re-run the stress test steps (2.3) for any rule whose scope, enforcement or start date has changed, and for any new evidence on a route.
3. Regenerate the data sections of this file and CONCEPT.md from the site data, and check the tally (2.8).
4. Update the "checked" date on the site and in these documents.
