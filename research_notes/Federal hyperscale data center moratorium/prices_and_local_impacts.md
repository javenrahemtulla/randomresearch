# Electricity Prices, Emissions, Local Impacts of US Hyperscale Data Center Growth, and the Economic Stakes of Halting It (as of Oct 2, 2026)

Note on method: Several primary sources (Utility Dive, PolitiFact, St. Louis Fed, Data Center Watch, GMU, MyChesCo) were blocked by the network proxy during this session, so some figures below come from search-result summaries of those pages, not full-text reads. They are flagged "(snippet)" where this matters. The report writer should treat them as reliable in direction but confirm exact numbers where possible.

## 1. Electricity price impacts

### Takeaway
The strongest quantitative link between data centers and higher prices is in PJM's capacity market. PJM's Independent Market Monitor (Monitoring Analytics) attributes about $23B in capacity costs across the 2025/26 to 2027/28 auctions, plus $6.3B in the July 2026 auction (2028/29), to existing and forecast data center load, for a cumulative total near $30B. It also judged those auctions "not competitive" because of forecast data center demand. Retail bills in PJM states rose by double-digit dollar amounts per month in 2025 and 2026. However, a national LBNL/Brattle study finds that 2019-2024 load growth did not raise state average prices, so the evidence is strongest in PJM and weaker nationally.

### Cited Findings
**PJM capacity market and IMM**
- PJM BRA for 2028/29 (results published Jul 14, 2026): procured 138,318 MW, cleared at the FERC-approved cap (~$325/MW-day) across the RTO, and came in 6,831 MW short of the reliability requirement. This was the second straight shortfall (2027/28 was short ~6,500 MW). — [PJM press release, Jul 14, 2026](https://www.pjm.com/-/media/DotCom/about-pjm/newsroom/2026-releases/20260714-pjm-capacity-auction-procures-138318-mw-of-generation-resources.pdf); [Enel North America, Jul 23, 2026](https://www.enelnorthamerica.com/insights/blogs/pjm-2028-2029-capacity-auction-results); [Sierra Club NJ, Jul 2026](https://www.sierraclub.org/new-jersey/blog/2026/07/pjm-auction-hits-price-cap-again-and-falls-short-projected-power-supply)
- 2028/29 auction total value was $16.4B, of which the IMM attributed about $6.3B (~38%) to existing and projected data center demand. — [Industrial Info Resources (snippet)](https://www.industrialinfo.com/iirenergy/industry-news/article/report-data-centers-create-about-us63-billion-in-electric-costs-for-pjm-customers--360334); [ai2.work (secondary)](https://ai2.work/blog/pjm-s-record-auction-pins-6-3b-of-data-center-costs-on-ratepayers)
- IMM estimate: existing and projected data center growth added more than $23.1B to capacity-market revenues across the 2025/26, 2026/27 and 2027/28 auctions. Adding the $6.3B from 2028/29 brings the cumulative total to about $30B. The IMM concluded that the 2025/26, 2026/27 and 2027/28 auctions "were not competitive, primarily as a result of the inclusion of forecast demand for data centers." — [MyChesCo summarizing IMM (snippet)](https://www.mychesco.com/a/news/regional/pjm-power-costs-jump-50-as-data-centers-drive-capacity-surge/); [Utility Dive (snippet)](https://www.utilitydive.com/news/data-center-pjm-wholesale-market/828917/)
- IMM State of the Market, H1 2026: total PJM wholesale cost rose 50.3% year over year. Capacity cost rose 207.1%, from $6.39/MWh to $19.61/MWh. Including forecast data center load in the capacity market added $11.11/MWh, or 9.7% of total wholesale cost, in H1 2026. — [MyChesCo (snippet), ~Aug 2026](https://www.mychesco.com/a/news/regional/pjm-power-costs-jump-50-as-data-centers-drive-capacity-surge/)
- IMM 2025 statement: "data center load growth is the primary reason for recent and expected capacity market conditions, including total forecast load growth, the tight supply and demand balance, and high prices." — quoted in [PolitiFact, Jun 12, 2026 (snippet)](https://politifact.com/factchecks/2026/jun/12/elizabeth-warren/data-centers-rising-electricity-costs/)
- Earlier IMM figure: data centers accounted for 63% of the price increase in the 2025/26 auction, or $9.3B. — [IEEFA](https://ieefa.org/resources/projected-data-center-growth-spurs-pjm-capacity-prices-factor-10); [Introl (secondary)](https://introl.com/blog/virginia-sb-253-data-center-electricity-rate-shift-2026)
- 2026/27 auction (Jul 2025): cleared at the $329.17/MW-day cap with a total of $16.1B, for June 2026 to May 2027. Bills were projected to rise a further 1.5% to 5% from summer 2026. Ratepayers across the region pay about $1.4B more in capacity costs starting June 2026. — [Maryland Matters / Ohio Capital Journal, Jul 23, 2025](https://marylandmatters.org/2025/07/23/energy-bills-likely-to-tick-up-again-in-2026-after-electricity-auction-clears-at-maximum-price/); [IEEFA](https://ieefa.org/resources/projected-data-center-growth-spurs-pjm-capacity-prices-factor-10)
- NRDC projects $100B to $163B in cumulative PJM capacity costs through 2033 without regulatory intervention. — [Introl summarizing NRDC (secondary)](https://introl.com/blog/virginia-sb-253-data-center-electricity-rate-shift-2026)

**State residential bills**
- Maryland: following the 2025/26 capacity auction, bills rose about 11% (~$14/month) in Pepco territory and about 19% (~$21/month) in BGE territory. These increases took effect June 2025. — [Maryland Matters, Jul 2025](https://marylandmatters.org/2025/07/23/energy-bills-likely-to-tick-up-again-in-2026-after-electricity-auction-clears-at-maximum-price/); [Renewable Energy World](https://www.renewableenergyworld.com/policy-regulation/it-is-unacceptable-maryland-legislators-react-to-pjm-price-increases/)
- IEEFA: capacity prices raise the average residential bill by about $18/month in western Maryland and about $16/month in Ohio. — [IEEFA](https://ieefa.org/resources/projected-data-center-growth-spurs-pjm-capacity-prices-factor-10)
- Virginia: the SCC's Dominion rate case order (Nov 25, 2025) approved $565.7M in new revenue for 2026 and $209.9M for 2027. Dominion had requested $822M and $346M. The base-rate change adds $11.24/month to the average residential bill in 2026 and $2.36 in 2027, or about $16/month including the fuel rider. The SCC also created a new large-load rate class (GS-5) for data centers with stronger financial commitments and shifted cost allocation away from residential customers. — [SCC order PDF](https://npr.brightspotcdn.com/b6/ac/706130b64d2b8eee6a9832b97e48/20251125-virginiascc-dominionenergyruling.pdf); [SELC, Nov 25, 2025](https://www.selc.org/press-release/dominion-customers-to-see-rate-increase-though-scc-takes-steps-designed-to-ensure-data-centers-pay-fair-share/); [Inside Climate News](https://insideclimatenews.org/?p=104496)
- Virginia SB 253 (2026 session): an amendment by Sen. Louise Lucas would shift grid and capacity costs to large-load customers. It was estimated to cut average household bills by $5.52/month and raise data center rates by about 15.8%. — [Introl (secondary)](https://introl.com/blog/virginia-sb-253-data-center-electricity-rate-shift-2026)
- National: EIA's Dec 2025 STEO forecasts the average US residential price at 18.02 ¢/kWh in 2026, up from 17.29 ¢ in 2025 (+4.2%). — [ConsumerAffairs citing EIA](https://www.consumeraffairs.com/news/your-electric-bill-will-probably-go-up-in-2026-heres-why-122325.html)

**Wholesale prices near data centers and forward projections**
- Bloomberg News analysis (Sept 2025) of tens of thousands of grid nodes: wholesale prices were up as much as 267% for a single month versus five years earlier in areas near significant data center activity, and more than 70% of nodes with price increases were within 50 miles of a data center. — [Bloomberg](https://www.bloomberg.com/graphics/2025-ai-data-centers-electricity-prices/); [Sherwood News](https://www.sherwood.news/tech/electricity-prices-surge-up-to-267-in-markets-near-data-centers-in-the-past)
- NC State / Carnegie Mellon (Open Energy Outlook, Aug 2025): growth in data centers and crypto mining through 2030 could raise average US electricity generation costs by 8% and power-sector GHG emissions by 30%. Central and Northern Virginia could see cost increases above 25% by 2030, the highest of any region in the model. — [CMU](https://www.cmu.edu/work-that-matters/energy-innovation/data-center-growth-could-increase-electricity-bills-8); [Axios Raleigh, Aug 28, 2025](https://axios.com/local/raleigh/2025/08/28/data-centers-will-cause-higher-electricity-prices-study-finds-north-carolina-state)

**Counter-evidence**
- LBNL/Brattle: states with load spikes in 2019-2024 saw lower average prices. The main rate drivers were transmission and distribution spending ("poles and wires") and disaster hardening. The authors note that a rapid infrastructure buildout for data centers could raise prices going forward. — [Ohio Manufacturers' Assn](https://www.ohiomfg.com/our-communities/study-data-centers-not-driving-electricity-price-increases-grid-costs-are/); [AOGR](https://www.aogr.com/web-exclusives/exclusive-story/study-finds-no-link-between-data-centers-and-electricity-costs); [PolitiFact, Jun 12, 2026 (snippet)](https://politifact.com/factchecks/2026/jun/12/elizabeth-warren/data-centers-rising-electricity-costs/)

### Inferences
- PJM is where the attribution is cleanest: an official market monitor puts a dollar figure (about $30B cumulative across 4 auctions) on data center-driven capacity costs. Outside PJM, the link to retail prices is contested and depends on how utilities allocate costs.
- Two consecutive auctions have cleared at the cap and still fallen short of the reliability requirement. That suggests prices are capped rather than resolved: the price cap hides scarcity, and the risk shifts to reliability.
- Utilities and states are responding with large-load tariffs (Virginia GS-5, SB 253), which shows regulators accept that cost shifting to residential customers is occurring.

### Gaps
- Georgia: I found no sourced 2025-26 Georgia Power residential rate figure tied to data centers in this session (the 2025 rate freeze and 2026 certification of ~10 GW of new capacity were not verified).
- No AEP Ohio-specific 2026 bill figure, and no full-text read of the IMM H1 2026 State of the Market report (the numbers come from a news summary).

## 2. Fossil lock-in and emissions

### Takeaway
Data center load growth is the stated rationale for keeping coal plants open through DOE 202(c) emergency orders. J.H. Campbell has now been ordered to run until Nov 14, 2026, through six successive orders, and the D.C. Circuit has vacated the first one. It is also driving a large gas buildout: 99 to 74 tracked projects totaling 126 to 143 GW, which could raise power-sector CO2 by about 20%. On-site turbines, most notably xAI's in Memphis and Southaven, are creating local air and noise harms. Academic modeling projects about $20B per year in health costs by 2030.

### Cited Findings
- J.H. Campbell (1,560 MW coal, West Olive, MI) was scheduled to retire May 31, 2025. DOE Order 202-25-3 (May 2025) kept it available, and DOE has renewed the order repeatedly. The sixth order runs to Nov 14, 2026, about 1.5 years past the approved retirement date. — [Michigan AG bulletin](https://content.govdelivery.com/accounts/MIAG/bulletins/429cfba); [ELPC](https://elpc.org/news/ten-groups-push-back-against-trumps-illegal-campbell-plant-extension/); [RTO Insider](https://www.rtoinsider.com/tag/j-h-campbell-plant)
- The D.C. Circuit vacated DOE's first Campbell order as an unlawful use of FPA 202(c) (per search summary, 2026). Sierra Club and Earthjustice argued against the coal extensions in court in May 2026. — [Michigan AG](https://content.govdelivery.com/accounts/MIAG/bulletins/429cfba); [Sierra Club, May 2026](https://www.sierraclub.org/press-releases/2026/05/sierra-club-and-earthjustice-argue-against-illegal-coal-plant-extensions)
- April 2025 executive orders promoting coal cited the surge in demand from data centers as a key rationale. — [Sidley](https://energyinfrastructurepulse.sidley.com/category/coal/)
- Gas buildout:
  - The Environmental Integrity Project (Jul 2026) reviewed 74 gas projects planned to serve data centers directly (behind the meter): about 143 GW and about 662M tons/yr of GHG. — [Gas Processing News, Jul 2026](https://www.gasprocessingnews.com/news/2026/07/report-gas-plants-for-us-data-centers-to-be-major-source-of-climate-change-linked-emissions/)
  - BloombergNEF (Aug 2026) tracked 126 GW of planned on-site gas across 99 plants. At standard run rates these would emit about 318M t CO2/yr and could lift US power-sector emissions by about 20%. — [Fortune, Aug 18, 2026](https://fortune.com/2026/08/18/data-center-gas-plants-to-boost-u-s-power-emissions-by-20/?rand=8593); [Insurance Journal](https://amp.insurancejournal.com/news/national/2026/08/19/882130.htm)
  - Two of the largest projects are an Amazon-backed 7.65 GW private gas plant (GW Ranch, TX) and a 9.2 GW Ohio project involving SoftBank. Data centers are projected to burn about 15 Bcf/d of gas by 2035. — [Fortune, Aug 2026](https://fortune.com/2026/08/18/data-center-gas-plants-to-boost-u-s-power-emissions-by-20/?rand=8593); [ARY (secondary)](https://arynews.tv/amazon-massive-private-gas-plant-new-data-centers)
- xAI, Memphis and Southaven:
  - The Mississippi Environmental Quality Permit Board unanimously approved 41 gas turbines for xAI affiliate MZX Tech in Southaven on Mar 10, 2026. These replace 27 turbines that had been running without permits to power Colossus 2 in Memphis.
  - Residents report jet-engine-like droning that disrupts sleep, plus particulate emissions.
  - The SELC, on behalf of the NAACP, Young Gifted & Green and the Safe and Sound Coalition, appealed the permit in April 2026.
  - EPA stated on Jan 15, 2026 that such generators are not exempt from permitting.
  - Sources: [Mississippi Free Press](https://www.mississippifreepress.org/mississippi-permit-board-grants-xais-request-for-41-southaven-gas-turbines-to-power-memphis-data-center/); [WLOX, Apr 9, 2026](https://www.wlox.com/2026/04/09/activist-groups-appeal-mississippi-approval-xai-turbines/); [Tennessee Lookout, Mar 18, 2026](https://tennesseelookout.com/2026/03/18/a-battle-over-data-centers-heats-up-along-the-mississippi-tennessee-state-line/); [UNC Civil Rights Law journal, May 2026](https://journals.law.unc.edu/nccivilrightslaw/2026/05/musk-mucking-up-memphis/)
- Caltech/UC Riverside, "The Unpaid Toll" (arXiv, Dec 9, 2024): US data center air pollution (from power plants and backup generators) could cause up to about 1,300 premature deaths per year by 2030, with public health costs approaching $20B/yr. That burden is about double the US steel industry's and rivals all vehicles in California. A related estimate puts health costs already incurred by Big Tech data center buildouts at $5.4B. — [Caltech](https://eas.caltech.edu/news/air-pollution-and-the-public-health-costs-of-ai); [UCR](https://webarchive.ucr.edu/news.ucr.edu/articles/2024/12/09/ais-deadly-air-pollution-toll.html); [Harvard tagteam feed](https://tagteam.harvard.edu/hub_feeds/3415/feed_items/13234948/content)
- NC State/CMU: data center growth could raise power-sector GHG emissions by 30% by 2030. — [CMU](https://www.cmu.edu/work-that-matters/energy-innovation/data-center-growth-could-increase-electricity-bills-8)

### Inferences
- Behind-the-meter gas avoids interconnection queues and much of the usual grid planning process. That is the main mechanism of new fossil lock-in, alongside 202(c) coal retentions.
- Section 202(c) orders spread their costs across the whole region (Campbell's costs are allocated across MISO), so they also act as a price channel.

### Gaps
- No verified total count of 202(c) orders or of coal capacity retained nationally as of Oct 2026. I did not obtain the Campbell order cost figures (Consumers Energy has reported net costs in the tens of millions per quarter, but this was not verified this session).
- No updated (2026) peer-reviewed health cost estimate was found.

## 3. Water, noise, land use, and local opposition

### Takeaway
Local opposition has grown from a nuisance into a structural barrier. Data Center Watch counts about $130B in projects blocked or delayed in Q1 2026 and $68B in Q2 2026 (its earlier report cited $64B for 2023 to early 2025). Organized groups grew from 396 to 833 across 49 states. Water, noise and electricity bills are the main grievances.

### Cited Findings
- Data Center Watch (10a Labs), Q1 2026: at least 75 projects worth about $130B were blocked or delayed in one quarter, roughly the scale of all of 2025. Active opposition groups grew from 396 (end 2025) to 833 (end Q1 2026) across 49 states. More than 300 state data center bills were filed in the first six weeks of 2026, and statewide moratorium proposals came up in 14 states from both parties. The report calls this "a structural shift rather than a cyclical spike." — [Data Center Watch Q1 2026](https://datacenterwatch.org/q1-2026); [The Next Web](https://thenextweb.com/news/data-center-opposition-75-projects-blocked-q1-2026); [Newsweek](https://www.newsweek.com/data-center-projects-face-unprecedented-surge-in-blocks-and-delays-study-12240534)
- Data Center Watch, Q2 2026: 45 projects worth $68B were blocked or delayed between April and June 2026, more than half of all large developments in that window. — [AI Weekly](https://aiweekly.co/alerts/data-center-watch-45-us-ai-data-center-projects-worth-68b-blocked-or-delayed-in); [Fortune, Jun 16, 2026](https://www.fortune.com/2026/06/16/data-center-opposition-construction-delays-blocks-report/)
- Water:
  - A mid-sized data center uses about 300,000 gal/day, and a large hyperscale facility up to about 5M gal/day.
  - US data centers consumed 17.4B gallons directly in 2023, projected to reach 38-73B gallons by 2028 (attributed to EPA/LBNL).
  - A Georgia development used about 30M gallons without paying for it during a drought while residents faced restrictions and low water pressure.
  - Sources: [SoftwareSeni (secondary)](https://www.softwareseni.com/water-noise-power-the-real-community-costs-of-data-centers); [Fortune, May 13, 2026](https://dc.fortune.com/2026/05/13/data-center-georgia-arizona-water-wars/); [Harvard tagteam / Politico-sourced](https://tagteam.harvard.edu/hub_feeds/3382/feed_items/18265742)
- A 2026 AGU Advances study documented major gaps in how tech companies disclose water use. — [arXiv 2603.02705](https://arxiv.org/abs/2603.02705v1)
- Noise: residents near xAI's Southaven turbines describe constant jet-engine-like droning (see Section 2). — [Mississippi Free Press](https://www.mississippifreepress.org/xai-faces-fierce-opposition-over-southaven-mississippi-power-plant-permit/)
- Land use: JLARC (Dec 2024) found Northern Virginia hosts the world's largest data center market and that development is spreading to rural counties. Its land-use and noise findings were not re-verified in full text this session. — [JLARC report via Fredericksburg](https://www.fredericksburgva.gov/DocumentCenter/View/28959/JLARC---Data-Centers-Study_Report_120924)

### Inferences
- Local and state friction is already acting as a decentralized partial moratorium: about $200B was delayed or blocked in H1 2026 alone. A federal moratorium would formalize and extend a trend that already exists.

### Gaps
- I could not access the full Data Center Watch report to break down the reasons (water, noise, bills, tax) by share, or how many projects were ultimately cancelled versus only delayed.

## 4. Economic stakes of a moratorium

### Takeaway
AI and data center capex is the main driver of current US growth. Estimates range from about one-third of 2026 GDP growth (ING) and about 1.4 percentage points (Bridgewater) to about 92% of H1 2025 growth (Furman). Goldman Sachs is a key dissent: it estimates only about 0.1 pp after accounting for imports. Construction jobs are large but temporary, while permanent jobs are few: Virginia has about 59k construction jobs and 15k operations jobs, and a typical facility employs about 50 people. Tax revenue is real, but Virginia's exemption returns about $0.48 per $1 forgone. Bubble and debt risks (BIS, Fed, BofA) cut both ways for a moratorium.

### Cited Findings
**GDP contribution**
- Jason Furman (Harvard): information processing equipment and software were 4% of GDP but 92% of GDP growth in H1 2025. Excluding them, growth would have been about 0.1% annualized. Furman cautions that without the AI boom, lower rates and electricity prices might have offset roughly half of that. — [Fortune, Oct 7, 2025](https://fortune.com/2025/10/07/data-centers-gdp-growth-zero-first-half-2025-jason-furman-harvard-economist)
- Bridgewater (Jan 2026): AI capex adds about 140 bp to US growth in 2026. — [Bridgewater](https://www.bridgewater.com/research-and-insights/the-macro-implications-of-the-ai-capex-boom)
- ING (James Knightley, via WSJ): AI investment accounts for about one-third of 2026 US GDP growth. — [AI Weekly summarizing WSJ](https://aiweekly.co/alerts/wsj-ing-says-the-us-ai-investment-craze-now-accounts-for-a-third-of-american)
- St. Louis Fed (Jan 2026) tracks AI's contribution to GDP growth. I could not read the full text. — [St. Louis Fed](https://www.stlouisfed.org/on-the-economy/2026/jan/tracking-ai-contribution-gdp-growth)
- Goldman Sachs dissent: AI spending adds only about 0.1 pp to measured 2026 GDP growth because much of the equipment is imported. — [FourWeekMBA (secondary)](https://fourweekmba.com/ai-ai-gdp-load-bearing-us-economy-bloomberg-morgan-stanley-brid/)
- Capex scale: Morgan Stanley expects about $805B in 2026 capex from Amazon, Alphabet, Meta, Microsoft and Oracle, rising to about $1.1T in 2027. Other estimates put 2026 AI infrastructure spending at $630-725B. — [AI2.work (secondary)](https://ai2.work/blog/the-700b-ai-infrastructure-bet-reshaping-gdp-forecasts); [Medium (secondary)](https://medium.com/@svnkrmkr/ai-bubble-2026-is-it-real-capex-fed-warnings-gpu-lifespans-b5db2178d350)

**Jobs and taxes**
- Virginia data centers support about 74,000 jobs: about 59,000 construction jobs (12-18 month projects, up to about 1,500 workers per site) and about 15,000 operations jobs. A typical facility employs about 50 full-time workers, half of them contractors. — [GMU CARE STEP Brief 05, Sep 3, 2026 (snippet)](https://care.gmu.edu/wp-content/uploads/STEP_Brief_05_Data_Centers_2026-09-03.pdf)
- Virginia's sales and use tax exemption cost about $2.7B over FY2015-2024 and $928M in FY2023 alone. JLARC estimates about $0.48 in other state revenue per $1 exempted. JLARC (Dec 2024) also found data centers to be major local property tax contributors (for example, in Loudoun and Prince William counties). — [GMU brief (snippet)](https://care.gmu.edu/wp-content/uploads/STEP_Brief_05_Data_Centers_2026-09-03.pdf); [JLARC report](https://www.fredericksburgva.gov/DocumentCenter/View/28959/JLARC---Data-Centers-Study_Report_120924); [12 On Your Side, Dec 10, 2024](https://www.12onyourside.com/2024/12/10/data-centers-drive-virginia-energy-demand-jlarc-study-says/)
- Industry-commissioned figure: Virginia data centers supported $17B in economic output in 2021. — [Data Center Knowledge](https://datacenterknowledge.com/colocation/report-data-centers-virginia-supported-17-billion-economic-output-2021)

**Bubble and financial risk**
- The BIS likened the AI capex surge to historical manias. It warned that "disappointment in returns could trigger a sudden pullback in financing and turn the capex boom into a protracted investment bust." The Fed has listed AI among its top financial-stability risks. — [AI Weekly](https://aiweekly.co/alerts/bis-and-oracle-filings-amplify-warnings-on-ai-capex-bubble); [Medium (secondary)](https://medium.com/@svnkrmkr/ai-bubble-2026-is-it-real-capex-fed-warnings-gpu-lifespans-b5db2178d350)
- BofA (Dec 2025) warned of an "air pocket" in 2026 data center debt, noting that "monetization is to be determined, and power is the bottleneck." About $100B in off-balance-sheet data center debt is involved. — [Fortune, Dec 3, 2025](https://www.fortune.com/2025/12/03/is-ai-a-bubble-bofa-says-air-pocket-in-2026-data-center-debt)

### Inferences
- A sudden federal moratorium would hit the single largest current source of US GDP growth. Even the import-adjusted view (Goldman) implies a smaller but still visible drag on construction, electrical equipment and local tax bases.
- The jobs argument is weak on permanent employment (about 50 per facility) and strong on temporary construction. Tax incentives cut net fiscal gains, as Virginia's $0.48 per $1 shows.
- Bubble risk complicates the economic case. A moratorium could precipitate a capex bust, or it could limit stranded assets and stranded utility investment that ratepayers would otherwise fund.

### Gaps
- No verified national figure for US data center jobs or total state and local tax revenue in 2026.
- No published economic model of a federal moratorium's GDP impact was found.
- No full-text read of the St. Louis Fed or GMU analyses (both were blocked).
