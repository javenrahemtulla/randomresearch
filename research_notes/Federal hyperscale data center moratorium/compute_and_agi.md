# Compute, Data Centers, and AGI: Would a US Hyperscale Moratorium Halt or Slow Frontier AI? (as of Oct 2026)

Research note: several primary sites (epoch.ai, lesswrong.com, congress.gov, sanders.senate.gov, brookings.edu, motherjones.com, asteriskmag) were blocked for full-page fetching in this session. Findings below for those sources come from search-result excerpts of those pages. Treat exact wording as close but not verbatim, and check key numbers against the originals before publication.

## 1. Scaling laws and compute trends: is compute (and power) the binding input?

### Takeaway
The best available evidence says frontier capability has mostly come from growth in compute. Frontier training compute has grown about 5x per year since 2020, and published projections need 1–5 GW single campuses, or multi-GW distributed clusters, by 2027–2030. Power and data-center buildout are widely seen as the main physical constraint on keeping that trend going. Compute is therefore a real bottleneck, though not the only input.

### Cited Findings
- Training compute for frontier language models has grown about 5x per year since 2020, a doubling every ~5.2 months (~0.7 orders of magnitude per year). Data updated Feb 5, 2026. — [Epoch AI, Trends](https://epoch.ai/data/trends)
- The total computing power of the global stock of AI chips is growing about 3.4x per year (doubling every ~6.8 months). — [Epoch AI, Trends](https://epoch.ai/data/trends)
- In a Shapley-value decomposition, 60–95% of language-model performance gains came from more compute and data, and only 5–40% from new algorithms. — [Epoch AI, Algorithmic progress in language models (Ho et al., NeurIPS 2024)](https://epoch.ai/blog/algorithmic-progress-in-language-models)
- Epoch's "Can AI scaling continue through 2030?" (Aug 2024) looked at four constraints: power, chip manufacturing, data, and the "latency wall". It concluded that 2e29 FLOP training runs will likely be feasible by 2030, about 10,000x the frontier at the time. — [Epoch AI](https://epoch.ai/blog/can-ai-scaling-continue-through-2030)
- The same report estimated that 1–5 GW single data-center campuses are likely possible by 2030, enough for training runs of about 1e28 to 3e29 FLOP. A geographically distributed network could draw 2–45 GW and support runs of about 2e28 to 2e30 FLOP. — [Epoch AI](https://epoch.ai/blog/can-ai-scaling-continue-through-2030)
- Power for the largest training runs is "well above 100 MW" today and projected to reach 5 GW or more by 2030. — [arXiv 2507.07765, Distributed and Decentralised Training: Technical Governance Challenges](https://arxiv.org/pdf/2507.07765)
- Epoch's database put the largest known model, Grok 4, at about 5e26 FLOP. A forecast cited on FutureSearch put the median largest run for Aug 2025–Aug 2026 at about 9.5e26 FLOP (p10 3.9e26, p90 3e27) and described growth as "constrained by energy limits". — [FutureSearch forecast](https://futuresearch.ai/app/p/a/rsi-largest-training-compute) (this is a secondary, forecast-type source)
- Anthropic (July 2025, "Build AI in America", submitted to OSTP) projected that one frontier model will need a 2 GW data center in 2027 and a 5 GW one in 2028. It put total US frontier-training demand at 20–25 GW by 2028 and total US AI demand at at least 50 GW by 2028. — [Anthropic](https://anthropic.com/news/build-ai-in-america); [DCD coverage](https://datacenterdynamics.com/en/news/anthropic-us-ai-needs-50gw-of-power-by-2028-frontier-models-will-require-5gw-data-centers/)
- Leopold Aschenbrenner's "Situational Awareness" (June 2024) projected a trillion-dollar, 100 GW training cluster by 2030, which would be more than 20% of US electricity generation. It assumed cluster scale grows about 0.5 OOM per year, from ~10 MW for GPT-4 in 2022 to ~100 MW in 2024. — [Forklog summary](https://forklog.com/en/news/aschenbrenners-picks-and-shovels); [Dwarkesh interview](https://www.dwarkesh.com/p/leopold-aschenbrenner)
- AI 2027's compute forecast assumes global AI-relevant compute grows about 10x from March 2025 to December 2027, reaching about 100M H100-equivalents (~2.25x per year). It gives the leading 2–3 AGI companies 15–20% of that (15–20M H100e) and assumes the US holds ~70% of global AI compute. — [AI 2027 Compute Forecast](https://ai-2027.com/supplements/compute-forecast)

### Inferences
- Every major "fast AGI" scenario (Aschenbrenner, AI 2027, Anthropic's own projections) assumes that much more physical compute keeps arriving: tens of GW and multi-GW campuses by 2027–2028. A policy that blocks new large US facilities therefore attacks an input these scenarios depend on.
- Compute and algorithms are complements, though. Even in Epoch's decomposition, algorithms account for 5–40% of gains, so freezing hardware does not freeze progress.

### Gaps
- Epoch's 2025–2026 updates on whether power has already started to bend the frontier-training trend could not be fetched. Whether 2026 runs above 1e27 FLOP have happened is unconfirmed.
- No reliable public data on how frontier compute splits between pretraining, RL/post-training, and inference in 2026.

## 2. How much frontier capability depends on NEW construction versus existing capacity?

### Takeaway
The US hosts about 75% of global AI-supercomputer performance. The frontier campuses that will train 2027–2028 models are under construction now and were only partly energized as of Sept 2026, so a halt on new and expanding construction would hit exactly the capacity the next 1–2 model generations need. Already-built capacity (several ~0.5–1 GW campuses) is still large and would keep training and serving models.

### Cited Findings
- As of May 2025, the US held about 75% of global GPU-cluster performance and China about 15%. — [Epoch AI data insight](https://epoch.ai/data-insights/ai-supercomputers-performance-share-by-country); [Trends in AI Supercomputers, arXiv 2504.16026](https://arxiv.org/html/2504.16026v2)
- US hyperscalers own more than 60% of global AI compute, and Google about a quarter of it. — [Network World](https://networkworld.com/article/4156949/google-owns-the-most-ai-compute-and-it-built-it-its-way.html)
- Epoch's Frontier Data Centers Hub (around Sept 2026) puts current IT power at:
  - xAI Colossus 2: ~946 MW
  - Anthropic–Amazon New Carlisle: ~910 MW
  - Microsoft Fairwater Atlanta: ~636 MW
  - OpenAI Stargate Abilene: ~421 MW
  
  Projected expansions:
  - New Carlisle: 1,925 MW by 2028
  - Stargate New Mexico: 1,750 MW by 2028
  - Meta Hyperion: 1,632 MW by 2028
  - Colossus 2: 1,531 MW by 2027
  
  — [Epoch AI, Largest AI data centers by power capacity](https://epoch.ai/graphs/largest-ai-data-centers-by-power-capacity)
- When finished, Colossus 2 will hold about 1.4M H100-equivalents, against ~100k for the leading data centers in mid-2024. Meta Hyperion and Microsoft Fairwater are each slated for about 5M H100e. — [Epoch AI, Frontier Data Centers Hub](https://epochai.substack.com/p/introducing-the-frontier-data-centers)
- Global buildout is already slipping. Axios reports that up to half of data-center projects due online in 2026 could face delays, with up to 11 GW of 2026 capacity still "announced" with no sign of construction. Even so, data-center additions set a record in 2025 and 2026 is on track to exceed it. — [Axios, Feb 24 2026](https://axios.com/2026/02/24/ai-data-center-boom-projects-numbers)
- Delayed or cancelled projects totaled $156B in 2025 and $130B in Q1 2026, according to third-party trackers cited by Axios. — [Axios](https://axios.com/2026/02/24/ai-data-center-boom-projects-numbers)

### Inferences
- The leading US labs are each on a path from about 0.4–1 GW now to about 1.5–2 GW by 2027–2028. A moratorium that also blocks expansions of partly built campuses would leave each lab with roughly its current ~0.5–1 GW footprint. By Anthropic's own figures, a 2028 frontier model needs about 5 GW, so the frontier labs would fall short by several times.
- A moratorium that blocks only greenfield projects but lets announced expansions finish would bite much less in 2026–2027. Grandfathering terms are therefore decisive.
- A rough bound, based on Epoch's 5x/yr trend and 3.4x/yr chip-stock trend (my estimate, not a published one): if US frontier compute were frozen in place, the US would lose roughly 0.5–0.7 OOM per year of compute growth. That is most of the hardware share of progress, partly offset by the chip refresh and algorithmic progress covered in section 3.

### Gaps
- No public estimate found of what fraction of US AI compute expected by 2028 is already energized, versus under construction, versus only announced.
- The exact grandfathering and expansion treatment in the federal bill could not be checked against the primary text.

## 3. Substitutes that could undermine a moratorium

### Takeaway
Several substitutes are real and large:
- algorithmic efficiency, roughly a 2.8x per year effective gain
- chip refreshes inside existing buildings, with vendor-claimed 10x per watt gains for inference (much less certain for training)
- distributed training across many smaller sites, which Epoch rates technically feasible even at 10 GW
- sub-threshold facilities
- offshoring to the Gulf and other countries, where multi-GW campuses are already approved

Together they mean a US-only moratorium would slow the frontier, not stop it.

### Cited Findings
- **Algorithmic efficiency.** The compute needed to reach a given language-model performance has halved about every 8 months (95% CI 5–14 months), based on 200+ evaluations from 2012–2023. Most of the gain comes from pretraining. — [Epoch AI](https://epoch.ai/blog/algorithmic-progress-in-language-models)
- **Distributed / decentralized training.**
  - Several labs already train across multiple data centers, for example GPT-4.5 and Gemini 1.5. — [arXiv 2507.07765](https://arxiv.org/pdf/2507.07765)
  - Epoch finds it technically feasible to spread multi-GW training across dozens of sites thousands of km apart. Its example is a 4,800 km network of 23 US sites supporting a 10 GW distributed cluster built near power plants with a few hundred MW of spare capacity each. — [Epoch AI, Could decentralized training solve AI's power problem?](https://epoch.ai/blog/could-decentralized-training-solve-ais-power-problem)
  - Epoch also expects developers to scale single campuses to multi-GW before turning to decentralized training. — [Epoch AI](https://epoch.ai/blog/could-decentralized-training-solve-ais-power-problem)
- **Building below the threshold.** The federal AI Data Center Moratorium Act reportedly covers facilities above 20 MW that are built to deliver at least 20 kW per rack or that use advanced liquid or immersion cooling. — [legisletter summary of S.4214](https://legisletter.org/bill/s4214-artificial-intelligence-data-center-moratorium-act); [Troutman Pepper](https://www.troutman.com/insights/policymakers-consider-temporary-pause-on-ai-data-center-construction-what-stakeholders-need-to-know/)
  - The 20 MW threshold is low compared with frontier campuses of 400–1,000+ MW. Splitting into sub-20 MW sites at 10 GW scale would take about 500 sites. A 20 kW/rack test with a cooling criterion would also catch most modern GPU racks (Blackwell NVL72-class racks run far above 20 kW; that figure is general industry knowledge, not from a fetched source).
  - The bill has no automatic sunset. It ends only when Congress passes comprehensive AI safety, labor, environmental, and consumer-protection legislation and expressly ends the moratorium. — [legisletter](https://legisletter.org/bill/s4214-artificial-intelligence-data-center-moratorium-act)
- **Chip efficiency inside existing shells.**
  - Nvidia/CoreWeave report that Vera Rubin NVL72 delivered 10x the tokens/sec per MW of GB200 NVL72 on a DeepSeek-R1 inference workload (mid-2026). — [CoreWeave](https://wf.coreweave.com/blog/nvidia-vera-rubin-nvl72-on-coreweave-10x-more-tokens-per-megawatt-than-blackwell)
  - Other claims run to 30x on SemiAnalysis's AgentX benchmark. Commentators warn these figures apply to one workload and accounting method, not across the board. — [wccftech](https://wccftech.com/nvidia-vera-rubin-nvl72-enters-the-stage-with-a-monstrous-10x-uplift-in-ai-vs-blackwell/amp/); [remio/SemiAnalysis lens](https://www.remio.ai/post/openai-semianalysis-lens-vera-rubin-nvl72-beats-gb200-but-the-tco-case-is-narrow)
  - Rubin started ramping in H2 2026. — [letsdatascience](https://letsdatascience.com/news/nvidia-rubin-platform-begins-h2-2026-ramp-5268d2db)
- **Moving compute abroad (Gulf).**
  - In May 2025 the US and UAE announced a 5 GW UAE–US AI Campus. Stargate UAE, a 1 GW cluster within it, is being built by G42, OpenAI, Oracle, Cisco, Nvidia and SoftBank, with the first 200 MW due online in 2026. — [The National](https://www.thenationalnews.com/future/technology/2025/11/20/uae-ai-nvidia-chips-us/)
  - In Nov 2025 the US authorized G42 and Saudi Arabia's Humain to buy up to the equivalent of 35,000 GB300s each. Humain plans up to 600,000 Nvidia chips across Saudi Arabia and the US over three years. — [The National](https://www.thenationalnews.com/future/technology/2025/11/20/uae-ai-nvidia-chips-us/)
- **The LessWrong critique** "Sanders's Data Center Moratorium Is Risky Strategy for AI" argues that a temporary moratorium is unlikely to meaningfully slow AI. Facilities would be built in friendlier jurisdictions, and the US would lose the leverage that hosting the compute gives it. It also argues that tying AI safety to the moratorium risks political backlash against more important regulation. — [LessWrong](https://www.lesswrong.com/posts/GSD8bEjREYioBDisr/sanders-s-data-center-moratorium-is-risky-strategy-for-ai) (search excerpt only)
- **China's buildout.**
  - China keeps about 12% of world AI-relevant compute despite export controls, through Huawei Ascend production, stockpiling and smuggling. — [AI 2027 Tracker](https://ai2027-tracker.com/predictions/china-compute-share/) (secondary)
  - Z.AI partly energized a 1 GW data center running only Chinese chips on July 20, 2026. — [Tom's Hardware](https://www.tomshardware.com/tech-industry/artificial-intelligence/z-ai-powers-up-1gw-ai-data-center-built-entirely-on-chinese-chips)
  - DeepSeek reportedly plans at least 160,000 Ascend 950DT chips for a GW-scale site in Ulanqab. — [tech-ish, Sept 13 2026](https://tech-ish.com/2026/09/13/deepseek-turns-to-huawei-for-160000-ai-chips-as-nvidia-stays-locked-out-of-china/)
  - Huawei targets about 600k Ascend 910C chips in 2026. — [Tom's Hardware](https://www.tomshardware.com/tech-industry/artificial-intelligence/z-ai-powers-up-1gw-ai-data-center-built-entirely-on-chinese-chips)
  - Huawei Horinger has about 124k H100e on 242 MW. — [Epoch AI directory](https://epoch.ai/data/ai-data-centers/directory/huawei-horinger)
- **US–China capability gap.** Since 2023, Chinese models have trailed the US frontier by about 7 months on average on Epoch's capabilities index. — [Epoch AI](https://epoch.ai/data-insights/us-vs-china-eci)

### Inferences
- **Algorithmic progress alone.** Halving every 8 months is about 2.8x per year in effective compute with zero new hardware. A full freeze of US compute would cut effective-compute growth from about 14x per year (5x hardware times 2.8x algorithms) to about 3x per year. That is roughly a 55–60% slowdown in log-space before any other substitutes. This is an illustrative calculation of mine. It assumes the two factors are independent, and Epoch's own work suggests some algorithmic gains depend on scale, which would make the slowdown larger.
- **Chip refresh.** Swapping Hopper/Blackwell for Rubin inside existing powered shells could add several-fold per-MW gains per generation. Inference gains, which matter for RL and test-time compute, look larger than pretraining gains. Whether a refresh counts as a covered "expansion" or "upgrade" under the bill is therefore a key design question.
- **Offshoring.** It needs 18–36+ months of lead time plus export licenses, which the US government controls. A US moratorium combined with continued Gulf chip exports would mostly relocate frontier compute rather than remove it, at a cost in time and some security exposure. A moratorium combined with tighter export controls would have a much larger effect.
- **Distributed training.** It lets developers route around single-site limits but not around a nationwide ban on all >20 MW AI facilities. Its main role as a substitute would be across borders, or across many sub-threshold sites.

### Gaps
- No quantified estimate found of the training-time (as opposed to inference) efficiency gain from Rubin over Blackwell.
- No primary source found on whether Prime Intellect-style decentralized training has reached frontier scale in 2026. Evidence suggests it remains far below frontier.
- No data found on how fast labs could stand up sub-20 MW, low-density facilities at scale.

## 4. Compute governance literature: how does a moratorium compare to the alternatives?

### Takeaway
The compute-governance literature, centered on Sastry, Heim et al. 2024, treats compute as an unusually governable lever because it is detectable, excludable, quantifiable, and comes from a concentrated supply chain. It favors targeted tools: export controls, FLOP reporting thresholds, chip know-your-customer rules, licensing of large runs, and hardware-enabled mechanisms. A blanket ban on facility construction is a blunter, domestic-only use of the same lever.

### Cited Findings
- Sastry, Heim and 17 co-authors (arXiv 2402.08797, Feb 13 2024) argue that AI-relevant compute is an effective intervention point because it is "detectable, excludable, and quantifiable" and comes from an extremely concentrated supply chain. They say governing it can strengthen three capacities: visibility, allocation, and enforcement. — [arXiv 2402.08797](https://arxiv.org/html/2402.08797v1); [Oxford AIGI](https://aigi.ox.ac.uk/?p=533)
- The concrete compute-governance tools in use today are export controls, FLOP reporting thresholds, and chip-level know-your-customer requirements. — [CASRAI guide](https://casrai.org/guides/compute-governance-export-controls-flop-thresholds); [CSER](https://cser.ac.uk/news/what-role-can-compute-play-ai-governance)
- Decentralized training could erode facility-based oversight. The arXiv 2507.07765 governance paper treats it as a growing challenge for monitoring, and Transformer argues it "isn't a policy nightmare — yet". — [arXiv 2507.07765](https://arxiv.org/pdf/2507.07765); [Transformer](https://transformernews.ai/p/decentralized-training-policy-implications)
- Brookings (Nicol Turner Lee and Darrell West, 2026) argues that data-center moratoriums "are not a substitute for oversight". It frames pauses as time to build transparency and community agreements, not as an end state. — [Brookings](https://www.brookings.edu/articles/data-center-moratoriums-are-not-a-substitute-for-oversight/) (search excerpt; mainly about local impacts, not AGI)
- ITIF argues that New York's moratorium "risks slowing America's AI future". This is an industry-aligned view that implicitly agrees moratoriums do slow AI. — [ITIF](https://itif.org/publications/new-yorks-data-center-moratorium-risks-slowing-americas-ai-future-says-itif.md)

### Inferences
- Compared with licensing large training runs or capping per-run FLOP, a facility moratorium:
  - catches all AI workloads, including commercial inference, scientific uses, and ordinary cloud work at high density
  - does not cover chips already installed or offshore compute
  - creates no visibility or verification regime
  
  It is broad on domestic economic cost and narrow on frontier-risk coverage.
- Under the governance literature's own logic, export controls and chip tracking (supply-chain chokepoints) are global levers. Facility construction is a local lever that capital can route around.

### Gaps
- No GovAI, RAND, CNAS, IAPS or CSET publication found (in the searches available) that directly models a US data-center construction moratorium as an AI-safety tool.

## 5. Expert estimates of how much a US-only pause would delay AGI

### Takeaway
No rigorous published model of the AGI delay from a US data-center moratorium was found. The proxies available are the US share of compute (~75%), the US–China lag (~6–7 months), and the size of the substitutes. Together they suggest a US-only construction halt with no export restrictions would delay frontier progress by somewhere from several months to perhaps 1–3 years, depending on length, grandfathering, and whether chips can move abroad. It would not halt AGI development globally.

### Cited Findings
- Chinese models have trailed the US frontier by about 7 months on average since 2023. — [Epoch AI](https://epoch.ai/data-insights/us-vs-china-eci)
- AI 2027 Tracker puts the leading Chinese lab about 6 months behind as of mid-2026. — [AI 2027 Tracker](https://ai2027-tracker.com/predictions/china-model-gap/)
- Analysts argue that US capability leads over China tend to be short-lived and cannot be sustained by denying high-end chips alone. — [Quincy Institute](https://quincyinst.org/research/the-wrong-race-the-us-china-and-ai-competition/)
- If Beijing "wakes up", a 1–2 year gap could shrink to six months. — [Benjamin Todd](https://benjamintodd.substack.com/p/why-a-us-ai-manhattan-project-could)
- LessWrong critique: a temporary moratorium "is unlikely to meaningfully slow AI development" because construction moves abroad. — [LessWrong](https://www.lesswrong.com/posts/GSD8bEjREYioBDisr/sanders-s-data-center-moratorium-is-risky-strategy-for-ai)
- **Legislative context.**
  - Sanders and Ocasio-Cortez introduced the AI Data Center Moratorium Act (S.4214 / H.R.9442, 119th Congress), explicitly framed around AI safety and not only local impacts. — [PBS NewsHour](https://www.pbs.org/newshour/politics/ocasio-cortez-and-sanders-push-bill-to-impose-ai-data-center-moratorium); [Mother Jones, March 2026](https://www.motherjones.com/politics/2026/03/bernie-sanders-ai-senate-bill-data-center-construction-moratorium-aoc-alexandria-ocasio-cortez/)
  - Date conflict: one search summary gave the introduction date as "May 2025", but the Mother Jones URL (March 2026) and the high bill numbers point to 2026. Verify against the primary source.
  - Rep. Pallone has backed a national moratorium. — [Broadband Breakfast](https://broadbandbreakfast.com/pallone-backs-national-moratorium-on-ai-data-centers/)
  - New York imposed a one-year statewide halt on new large data centers, first by Hochul executive order and then by the legislature (DLA Piper, July 2026). — [DLA Piper](https://www.dlapiper.com/en-us/insights/publications/2026/07/new-york-state-legislature-passes-first-in-the-nation-data-center-moratorium); [Bloomberg Government](https://news.bgov.com/states-of-play/hochul-halts-new-york-data-centers-for-a-year-states-of-play)
  - Sightline tracked 10+ new state moratorium proposals in a single month. — [Axios](https://axios.com/2026/02/24/ai-data-center-boom-projects-numbers)

### Inferences
These are my synthesis, not sourced estimates.

- **Halt versus slow.** A US-only moratorium would not halt AGI development:
  - Existing US capacity (several ~0.5–1 GW campuses) stays online.
  - Algorithmic progress continues at about 2.8x per year.
  - Chip refreshes raise per-MW output.
  - Gulf campuses (5 GW UAE plan) and China (~12% share, GW-scale domestic-chip sites) keep growing.
- **Size of the slowdown.** It could still be large in the near term. In 2026–2028 the US has about 75% of compute, and the next generation of frontier runs (2–5 GW per Anthropic) is being built almost entirely in the US. Plausible effects:
  - US frontier labs' compute growth drops from about 5x per year to about 1–2x per year from refresh only.
  - Labs redirect capex abroad, with an 18–36 month gap before offshore GW-scale capacity arrives.
- **Global frontier.** If chips can still be exported, the global frontier is probably delayed by about 1–2 years of compute growth, not stopped. If the moratorium comes with tight export controls on frontier chips and offshore training by US firms, the delay could be longer, and China's ~6–7 month lag becomes the limit on how much a US-only pause can delay global AGI. Past that point, the frontier passes to non-US actors.
- **Self-defeating dynamics.** Offshoring reduces US leverage, and a pause in a lead of only about 7 months could hand the frontier to China within a year or so. Both cut against the moratorium's safety rationale. Proponents would answer that the moratorium is meant as leverage to force safety legislation, not as a permanent compute cap.

### Gaps
- No published quantitative model (from Epoch, RAND, GovAI or others) of AGI delay from a US data-center moratorium was found. Any month or year figures in the final report should be labeled as illustrative reasoning, not expert consensus.
- No survey of forecasters on this specific question was found.
