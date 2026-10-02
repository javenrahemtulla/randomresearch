# Suffering Risks (S-Risks) from Advanced AI: Literature, Mechanisms, "Infinite" Framing, and Relevance to AI Pause / Compute Moratorium Policy

Research note. Current as of 2026-10-02. Method caveat: the egress proxy blocked direct fetches of longtermrisk.org, informatica.si, worldscientific.com, arxiv.org, philarchive.org, wikipedia, EA Forum and magnusvinding.com, so the findings below come from search-result abstracts and snippets of those primary pages (URLs cited are the primary pages). Exact quotations and page-level detail should be re-checked before anyone quotes them verbatim. Items I could not confirm from a source are listed under Gaps rather than stated as fact.

Epistemic tiering used throughout:
- **[Academic]**: peer-reviewed or formal academic venue (Informatica, Utilitas, Ethics, J. of AI and Consciousness, arXiv reports by academic teams).
- **[Org/grey]**: research-org reports and books (CLR, CRS, Anthropic) that are not peer reviewed but are written carefully.
- **[Online/speculative]**: LessWrong, EA Forum and blog posts, and popular memes (Roko's basilisk).

---

## 1. Definitions and foundational work

### Takeaway
"S-risk" was coined and developed mostly by a small effective-altruist / suffering-focused community: the Foundational Research Institute, now the Center on Long-Term Risk (CLR); Brian Tomasik; Lukas Gloor; Max Daniel; David Althaus; Tobias Baumann and the Center for Reducing Suffering (CRS); and Kaj Sotala. The standard definition is suffering on an astronomical scale, "significant relative to expected future suffering." The main peer-reviewed anchor is Sotala & Gloor (Informatica, 2017). Most of the rest is grey literature from the organizations themselves.

### Cited Findings
- **Canonical definition [Org/grey]:** s-risks are "risks of events that bring about suffering in cosmically significant amounts," where "significant" means significant relative to expected future suffering. Source: Max Daniel's talk "S-risks: Why they are the worst existential risks, and how to prevent them," EAG Boston 2017 — [CLR](https://longtermrisk.org/s-risks-talk-eag-boston-2017/); [EA Forum version](https://forum.effectivealtruism.org/posts/7g7ou3g8nM7seASBP/why-s-risks-are-the-worst-existential-risks-and-how-to)
- **Daniel's argument that s-risks are "worse than extinction":** they contain large amounts of what we disvalue, such as intense involuntary suffering, and they would have even larger scope because they would affect a significant part of the universe — [CLR / Daniel 2017](https://longtermrisk.org/s-risks-talk-eag-boston-2017/)
- **Taxonomy (CLR's beginner's guide) [Org/grey]:**
  - **Incidental** s-risks: unintended consequences of pursuing large-scale goals.
  - **Agential** s-risks: intentional harm by intelligent beings with influence over many resources.
  - **Natural** s-risks: processes that occur without agents' intervention.
  - Source: [CLR beginner's guide](https://longtermrisk.org/beginners-guide-to-reducing-s-risks/)
- **"Common denominator" framing [Org/grey]:** CLR argues that virtually everyone agrees involuntary suffering should, all else equal, be avoided. On that view, preventing astronomical suffering is "a common denominator of almost all (plausible) value systems." This is offered as a reason s-risk work is not only for negative utilitarians — [CLR S-risk FAQ](https://longtermrisk.org/s-risk-faq/); [CRS S-risk FAQ](https://centerforreducingsuffering.org/research/faq/)
- **CLR's current focus [Org/grey]:** CLR "aims to reduce risks of astronomical suffering (s-risk) from advanced AI systems" and is "primarily concerned with threat models involving the deliberate creation of suffering during conflict between advanced agentic AI systems" — [CLR research overview](https://longtermrisk.org/research-overview/); [CLR publications](https://longtermrisk.org/publications-old)
- **Sotala & Gloor, "Superintelligence as a Cause or Cure for Risks of Astronomical Suffering," *Informatica* 41(4), December 2017 [Academic]:**
  - Argues that s-risks are "risks of comparable severity and probability as risks of extinction."
  - Argues that superintelligent AI can be both a cause of s-risks and a way to prevent them.
  - Argues that some AI safety work helps against s-risks, and that a class of safeguards may help specifically against s-risks.
  - Sources: [CLR full text](https://longtermrisk.org/superintelligence-cause-cure-risks-astronomical-suffering); [PDF](https://longtermrisk.org/files/Sotala-Gloor-Superintelligent-AI-and-Suffering-Risks.pdf); [PhilArchive](https://philarchive.org/rec/SOTSAA); [dLib.si](https://dlib.si/URN:NBN:SI:doc-XUOJ3W5M/DC); [FLI podcast with Sotala](https://futureoflife.org/podcast/podcast-astronomical-future-suffering-and-superintelligence-with-kaj-sotala/)
- **Tobias Baumann, *Avoiding the Worst: How to Prevent a Moral Catastrophe* (2022) [Org/grey; book from CRS]:**
  - Defines s-risks as risks that the future contains astronomical amounts of total suffering on an unprecedented scale.
  - Covers risk factors, moral advocacy, political interventions and emerging technologies.
  - Sources: [Stafforini entry](https://stafforini.com/works/tobias-baumann-2022-new-book-srisks/); [EA Forum announcement mirror](https://ea.greaterwrong.com/posts/XyCLLYkBCPw44jpmQ/new-book-on-s-risks)
  - A 2023 academic review in *Eidos* (Universidad del Norte) summarizes Baumann's argument this way: if s-risk probability is not very low (the reviewer says Baumann assigns at least 0.001), then "any plausible expected value theory" makes preventing the worst outcomes a top priority. The reviewer also flags deep uncertainty about long-term effects as a caveat — [Eidos review](https://rcientificas.uninorte.edu.co/index.php/eidos/article/download/15723/214421447711/214421476217?inline=1)
- **Althaus & Baumann, "Reducing long-term risks from malevolent actors" (CLR / EA Forum, 29 April 2020) [Org/grey]:**
  - Notes that dictators with highly narcissistic, psychopathic or sadistic traits were involved in some of history's greatest catastrophes.
  - Proposes manipulation-proof measures of malevolence to screen leaders and CEOs.
  - Proposes selecting against such traits in genetically enhanced humans.
  - Source: [CLR](https://longtermrisk.org/research/reducing-long-term-risks-from-malevolent-actors/)
- **Bostrom, "mind crime" (term introduced in *Superintelligence*, 2014):** scenarios where "an AI's cognitive processes are intrinsically doing moral harm," for example because the AI contains trillions of suffering conscious beings. The sub-cases are:
  - sapient models of humans;
  - sapient models of civilizations, such as aliens simulated in detail;
  - sapient subsystems, where the most efficient cognitive subsystems are conscious.
  - The wiki entry stresses that even a low probability that simulations matter morally "cannot be ignored" when there are trillions of them.
  - Source: [LessWrong/Arbital Mindcrime wiki](https://www.lesswrong.com/w/mindcrime); [Arbital](https://arbital.greaterwrong.com/p/mindcrime)
  - Note: the wiki itself is [Online], summarizing Bostrom's [Academic/book] concept.

### Inferences
- The field is small and institutionally concentrated: CLR, CRS and a handful of researchers. Sotala & Gloor (2017) is the main peer-reviewed s-risk paper. Its strongest claim, "comparable severity and probability" to extinction, is asserted and argued informally, not estimated quantitatively.
- Because the "worse than extinction" framing rests on scope (cosmic scale) plus intensity (involuntary extreme suffering), it inherits all of longtermism's scale assumptions. See section 4.

### Gaps
- **Althaus & Gloor, "Reducing Risks of Astronomical Suffering: A Neglected Priority" (FRI 2016, revised 2019):** I could not fetch the text (blocked), so I cannot quote its specific claims.
- **Tomasik's foundational essays** (e.g., "Risks of Astronomical Future Suffering," reducing-suffering.org): not retrieved. Tomasik's near-miss page is cited in section 2.
- **Daniel 2017 probability statements:** I could not verify specific probability language. Any claim that Daniel said s-risks are "not much less likely" than extinction is unconfirmed.

---

## 2. Mechanisms by which advanced AI could cause s-risks

### Takeaway
The literature names several routes:
- **Incidental suffering:** sentient subroutines, or detailed simulations ("mind crime").
- **Near-miss alignment:** an AI that gets human values almost right, including the "sign flip" variant.
- **Agential suffering:** AI-vs-AI conflict and threats/extortion, which is CLR's top priority, and malevolent humans empowered by AI.
- **Digital minds at scale.**

Popular variants such as Roko's basilisk are distorted versions of the agential/threat mechanism and were rejected by the community that produced them.

### Cited Findings
- **Conflict and threats [Org/grey]:**
  - CLR believes s-risks from conflict are "among the most important, tractable, and neglected." It holds that "strategic threats by powerful AI agents or AI-assisted humans against altruistic values" may be among the largest sources of expected suffering.
  - Its research agenda, "Cooperation, Conflict, and Transformative AI," draws on international relations, game theory, behavioral economics, ML, decision theory and formal epistemology.
  - Sources: [CLR research overview](https://longtermrisk.org/research-overview/); [Alignment Forum sequence](https://www.alignmentforum.org/s/p947tK8CoBbdpPtyK)
- **Current CLR technical work [Org/grey]:**
  - A "Model Personas" agenda studies how malicious propensities emerge in LLMs ("spitefulness, sadism, and punitiveness") and how such propensities generalize out of distribution.
  - "Safe Pareto Improvements" are modifications to bargaining strategies that make all parties better off whatever their original strategies, as a robust way to prevent catastrophic AI-AI conflict.
  - Source: [CLR research overview](https://longtermrisk.org/research-overview/)
- **Near-miss alignment [Online/Org]:** getting alignment mostly right but slightly wrong could, in some scenarios, produce astronomical suffering — [Tomasik, "Near Miss" (reducing-suffering.org)](https://reducing-suffering.org/near-miss/)
- **"Sign flip" / hyperexistential separation [Online]:**
  - Yudkowsky (Arbital) proposed designing AIs to be "separated in design space" from AIs that would produce a fate worse than death if the sign of their utility function were flipped. The canonical example is an AI with a perfect representation of human values V that, after a sign flip (e.g., a cosmic ray or bug), maximizes −V.
  - LessWrong and EA Forum posts argue that "mediocre" alignment and human-modelling approaches invite "beyond-catastrophic alignment near-misses (i.e. S-risks)." They argue this is worse under short timelines, where "hail mary" techniques are more likely.
  - Sources: [LessWrong, "Likelihood of hyperexistential catastrophe from a bug"](https://www.lesswrong.com/posts/WMhiJf3xx9ZopC2tP/likelihood-of-hyperexistential-catastrophe-from-a-bug); [GreaterWrong, "How easily can we separate a friendly AI in design space"](https://www.greaterwrong.com/posts/KFKBwbBobfFYCqFrN/how-easily-can-we-separate-a-friendly-ai-in-design-space); [EA Forum, "Mediocre AI safety as existential risk"](https://forum.effectivealtruism.org/posts/j4G5Gqxa6JmbbQYzX/mediocre-ai-safety-as-existential-risk)
  - A real-world anecdote often cited: OpenAI's 2019 GPT-2 fine-tuning sign-flip bug, which produced maximally "bad" text. I did not re-verify it here (see Gaps).
- **Mind crime / sentient subroutines and simulations:** see Bostrom in section 1 — [Mindcrime wiki](https://www.lesswrong.com/w/mindcrime)
- **Malevolent actors with AI:** [Althaus & Baumann 2020](https://longtermrisk.org/research/reducing-long-term-risks-from-malevolent-actors/)
- **Roko's basilisk [Online/speculative]:**
  - A 2010 LessWrong post argued that a powerful future AI would have an incentive to torture those who knew of it but did not help create it (acausal blackmail).
  - It was "broadly rejected on Less Wrong." The main objection is that, once the agent exists, carrying out the threat would be a waste of resources with no causal benefit.
  - Yudkowsky's ban on discussing it produced a Streisand effect.
  - Sources: [LessWrong wiki](https://www.lesswrong.com/w/rokos-basilisk); [Wikipedia](https://en.wikipedia.org/wiki/Roko%27s_basilisk)
- **Possible tension with AI control:** one EA Forum post argues that if future AIs are moral patients, this raises the downside risk, "including S-risk," of "AI control"-style interventions — [EA Forum, "A brief list of ways AI safety efforts could be net negative"](https://forum.effectivealtruism.org/posts/XNc6uNWMXuai4Tnom/a-brief-list-of-ways-ai-safety-efforts-could-be-net-negative)

### Inferences
- Roko's basilisk is best described as a popular but rejected variant of the threats/extortion mechanism. The serious version is CLR's work on bargaining and commitment between AI systems, which is about avoiding threat-making equilibria, not about a vengeful AI. Debaters who invoke the basilisk weaken the case.
- Near-miss and sign-flip arguments imply that partial alignment progress could raise s-risk relative to no alignment. This is an unusual and counterintuitive result, and it is mainly argued in online fora rather than peer-reviewed venues.

### Gaps
- **AI-enabled totalitarian lock-in** as an s-risk route: no specific sourced findings this session.
- **"I Have No Mouth, and I Must Scream"** (Harlan Ellison, 1967) as a cultural reference point: not sourced this session.
- **OpenAI GPT-2 sign-flip bug (2019):** not verified this session.
- **Quantitative probability estimates** for any of these mechanisms: none found beyond Baumann's ≥0.001 lower bound (as reported by a reviewer). The literature generally avoids point estimates.

---

## 3. Digital sentience research and AI welfare

### Takeaway
Since 2023 the "digital minds" strand has moved into mainstream academic and industry settings:
- Butlin, Long et al. (2023) found no current AI is conscious but "no obvious barriers" to building conscious AI.
- Long, Sebo et al. (2024) argued there is a "realistic possibility" of near-term AI moral patienthood.
- Anthropic launched a formal model welfare program (April 2025) and shipped a welfare-motivated feature (August 2025).
- Metzinger's 2021 call for a global moratorium on synthetic phenomenology until 2050 is the most direct "pause"-style argument from this strand.

### Cited Findings
- **Butlin, Long et al., "Consciousness in Artificial Intelligence: Insights from the Science of Consciousness" (arXiv 2308.08708, August 2023) [Academic, 19 authors]:**
  - Derives computational "indicator properties" from five theories: recurrent processing, global workspace, higher-order, predictive processing and attention schema.
  - Concludes that "no current AI systems are conscious" but "there are no obvious barriers to building conscious AI systems."
  - Source: [arXiv](https://arxiv.org/abs/2308.08708v1)
- **Long, Sebo, Butlin et al., "Taking AI Welfare Seriously" (arXiv 2411.00986, November 2024; NYU, Oxford, LSE et al.) [Academic/grey]:**
  - Argues there is "a realistic possibility that some AI systems will be conscious and/or robustly agentic in the near future."
  - Recommends that AI companies acknowledge AI welfare as an issue, assess systems for consciousness and robust agency, and prepare policies.
  - Sources: [arXiv](https://arxiv.org/abs/2411.00986v1); [PhilArchive](https://philarchive.org/rec/LONTAW)
- **Anthropic model welfare program [Industry]:**
  - Announced 24 April 2025 and led by Kyle Fish, hired in 2024 as Anthropic's first full-time AI welfare researcher.
  - Covers three areas: when models might deserve moral consideration, model preferences and signs of distress, and low-cost interventions.
  - Fish has publicly given roughly a 15% guess that a current model like Claude is conscious, framed as a guess under deep uncertainty.
  - Sources: [SiliconANGLE](https://siliconangle.com/2025/04/24/anthropic-launches-ai-welfare-research-program/); [80,000 Hours podcast with Kyle Fish](https://80000hours.org/podcast/episodes/kyle-fish-ai-welfare-anthropic/)
- **Anthropic conversation-ending feature [Industry]:**
  - In August 2025 Anthropic gave Claude Opus 4 / 4.1 the ability to end "persistently harmful or abusive" conversations, "as a last resort" in "rare, extreme cases." It was developed "primarily as part of exploratory work on potential AI welfare."
  - Anthropic says it remains "highly uncertain about the potential moral status of Claude and other LLMs."
  - Sources: [Anthropic](https://www.anthropic.com/research/end-subset-conversations); [AI Business](https://aibusiness.com/nlp/claude-can-now-end-inappropriate-conversations)
- **Metzinger, "Artificial Suffering: An Argument for a Global Moratorium on Synthetic Phenomenology," *Journal of Artificial Intelligence and Consciousness* 8(1), 2021 (DOI 10.1142/S270507852150003X) [Academic]:**
  - Proposes a global moratorium until 2050 that would strictly ban research that "directly aims at or knowingly risks the emergence of artificial consciousness on post-biotic carrier systems."
  - Rests on minimizing "ENP risk," the risk of an explosion of negative phenomenology.
  - Grounds the proposal in the empirical plausibility that future machines will have conscious self-models with autonomously created goals. If those goals are thwarted, the machines would be in states they want to avoid but cannot escape.
  - Part two of the paper sets out how the moratorium could be refined into evidence-based constraints.
  - Sources: [World Scientific DOI](https://www.worldscientific.com/doi/10.1142/S270507852150003X); [Stafforini summary](https://stafforini.com/works/metzinger-2021-artificial-suffering-argument/); [EA Forum discussion](https://forum.effectivealtruism.org/posts/JCBPexSaGCfLtq3DP/the-problem-of-artificial-suffering)
- **Academic critique of Metzinger:** a 2024 paper in *Studies in Logic, Grammar and Rhetoric* argues that Metzinger's moratorium "as formulated is not justified," while acknowledging his broader warning — [SLGR 2024 (DOAJ)](https://doaj.org/article/392015f980fe4a55803cefbf761645bc); [reference-global](https://reference-global.com/article/10.2478/slgr-2024-0023)
- **Precautionary framing:** Jonathan Birch's *The Edge of Sentience* (OUP, 2024) discusses risk and precaution for humans, other animals and AI — [OUP](https://academic.oup.com/book/57949/chapter/475705528)

### Inferences
- Metzinger's moratorium targets research aimed at or knowingly risking machine consciousness, not compute in general. It is therefore an analogy for, not a direct argument for, a hyperscale data-center moratorium.
- An argument linking compute buildout to s-risk would need two steps:
  1. More and larger frontier training/inference runs raise the probability and number of potentially sentient systems.
  2. Under uncertainty, precaution should apply. Butlin et al. ("no obvious barriers") and Long/Sebo ("realistic possibility") support step 1 only weakly and qualitatively.
- The mainstreaming of AI welfare at Anthropic gives the digital-sentience concern more credibility than the older, speculative s-risk material. But Anthropic's stance is "high uncertainty and low-cost interventions," not a pause.

### Gaps
- Any 2026 updates to Anthropic's welfare program, or new consciousness-assessment results for frontier models: not retrieved.
- Metzinger's own commentary on LLMs and compute scaling after 2023: not retrieved.

---

## 4. How "infinite" or astronomical suffering is argued, and how it is critiqued

### Takeaway
Serious s-risk writers argue for astronomical, finite suffering, not literally infinite suffering. The magnitude comes from three things:
- Bostrom-style scale figures, such as 10^38 potential lives per century from the Virgo Supercluster.
- Permanence through lock-in.
- The possibility of digital minds running at high speed and in vast numbers.

"Infinite suffering" talk invites the well-developed critiques of infinite ethics, Pascal's mugging and fanaticism. The more defensible framing is: a non-negligible probability times an astronomically large but finite magnitude, plus robustness across value systems.

### Cited Findings
- **Bostrom, "Astronomical Waste" (*Utilitas* 15(3), 2003) [Academic]:**
  - Estimates that about 10^38 potential human lives are lost per century of delayed colonization of the local supercluster, or about 10^29 per second.
  - Based on ~10^42 ops/s per star with advanced nanotech versus ~10^17 ops/s per human brain.
  - Source: [Bostrom](https://nickbostrom.com/astronomical/waste)
  - Note: Bostrom uses this to argue for valuing a good future. S-risk writers flip the sign: the same compute could run suffering minds.
- **Bostrom, "Infinite Ethics" [Academic]:**
  - Aggregative consequentialism faces "paralysis" in a possibly infinite universe, because finite acts cannot change an infinite total.
  - The fixes cause "fanaticism," "distortion," and erosion of the original intuitions.
  - Source: [Bostrom](https://nickbostrom.com/ethics/infinite); [PhilPapers](https://philpapers.org/rec/ETHIE)
- **Wilkinson, "In Defence of Fanaticism," *Ethics* 132 (2022): 445–477 [Academic]:**
  - Argues that avoiding fanaticism (preferring certain modest value over tiny chances of vast value) is costly. Doing so means declining attractive trade-offs, ranking lotteries inconsistently, or letting rankings depend on remote, unaffected events.
  - This is a defense of the reasoning pattern s-risk arguments rely on.
  - Source: [GPI](https://globalprioritiesinstitute.org/hayden-wilkinson-in-defence-of-fanaticism/page/22)
- **Pascal's mugging critique [Online + academic theses]:**
  - Expected value theory lets tiny probabilities of astronomical value dominate decisions. Pascal's mugging (Yudkowsky) is the modern form of the 1670 Wager problem.
  - Going infinite rather than "merely very large" triggers cancellation arguments: every option has infinite expected value.
  - Sources: [LessWrong, "Fanatical longtermists: why is Pascal's wager wrong?"](https://www.lesswrong.com/posts/cgteC8kvpnc4EHWCi/fanatical-longtermists-why-is-pascal-s-wager-wrong); [Effective Thesis](https://www.effectivethesis.org/finished-theses/pascals-mugging-expected-utility-theory)
- **Fanaticism under moral uncertainty [Academic, arXiv]:** "Moral Uncertainty and the Problem of Fanaticism" (2023) treats fanaticism as a core problem for expected-value aggregation across moral views — [arXiv 2312.11589](https://arxiv.org/pdf/2312.11589)
- **Sign uncertainty [Online]:** reducing extinction risk may increase s-risk, and moral uncertainty about how to weigh the two means interventions can backfire — [EA Forum discussion (Pascal's mugging and abandoning credences)](https://ea.greaterwrong.com/posts/kHeRZPGzRvgJG7Mix/pascal-s-mugging-and-abandoning-credences)
- **Mind crime scale argument:** even a low probability that simulations are morally relevant "cannot be ignored" because "there can be trillions of them" — [Mindcrime wiki](https://www.lesswrong.com/w/mindcrime)

### Inferences (framing guidance for debaters)
- **Avoid literal "infinite" claims.** They invite the infinite-ethics paralysis and cancellation objections and the Pascal's Wager comparison. "Astronomical but finite, possibly effectively permanent" is the defensible version, and it matches how Baumann, CLR and Sotala & Gloor actually phrase it.
- **Do not rest the case on magnitude alone.** Baumann's stated threshold (s-risk probability ≥ 0.001) shows the field claims the probability is not Pascalian. A debater should defend a non-trivial probability with concrete mechanisms (conflict/threat dynamics, near-miss alignment, digital minds at scale) rather than relying on a vast payoff to swamp any probability.
- **Expect these lines of attack:**
  1. Unfalsifiability: no observable leading indicators. The partial rebuttal is that consciousness-indicator frameworks (Butlin et al.) and malevolence measures (Althaus & Baumann) offer some measurable proxies.
  2. Low probability or fanaticism.
  3. Sign uncertainty: a pause or alignment work may raise or lower s-risk.
  4. Moral weight: are digital minds sentient at all?
- **Robustness argument:** CLR's "common denominator" claim (almost all value systems disvalue involuntary suffering) can deflect the objection that "this only matters to negative utilitarians." The fanaticism critique still applies to the size of the weight placed on it.

### Gaps
- Time-dilation and upload-torture arguments (subjective centuries of suffering per wall-clock hour): not found in an academic source this session. Treat as [Online/speculative] unless sourced.
- No sourced academic paper estimating the number of digital minds a future could contain specifically in s-risk terms, beyond Bostrom's 10^38 (which concerns positive value).

---

## 5. Do s-risk researchers favor pausing AI or a compute moratorium?

### Takeaway
The community is divided and mostly not pro-pause:
- **The suffering-focused core (CLR, Vinding/CRS)** generally treats a pause as having ambiguous sign for s-risk. Its preferred levers are cooperative AI, worst-case/"fail-safe" AI safety, malevolence screening and AI welfare policy.
- **Metzinger** is the clearest pro-moratorium voice. His target is synthetic phenomenology, not compute as such.
- **The digital-welfare mainstream** (Long, Sebo, Anthropic) recommends assessment and policy preparation, not a halt.

### Cited Findings
- **Magnus Vinding (CRS), "Thoughts on AI pause" (June 2024) [Online/grey]:**
  - Argues that for s-risk reduction one must compare the s-risks of "loss of control to AI" with those of "humans maintaining control." It is not clear which is worse.
  - Argues that it is not evident that pause advocacy is the most effective way to reduce future suffering. Worst-case AI safety and direct s-risk mitigation may be more tractable.
  - Notes that a pause could make multipolar scenarios more likely by giving more groups time to build AGI. That could increase conflict-based s-risks.
  - Sources: [Vinding blog](https://magnusvinding.com/2024/06/06/thoughts-on-ai-pause/); [Stafforini entry](https://stafforini.com/works/vinding-2024-thoughts-ai-pause/)
- **Broader EA pause debate:** the Center for Effective Altruism hosted a 2023 AI Pause Debate among longtermists, forecasters and x-risk activists — [EA Forum "Pause For Thought"](https://forum.effectivealtruism.org/posts/7WfMYzLfcTyDtD6Gn/pause-for-thought-the-ai-pause-debate). Counterpoints in the same broader community: [Katja Grace, "Let's think about slowing down AI"](https://forum.effectivealtruism.org/posts/vwK3v3Mekf6Jjpeep/let-s-think-about-slowing-down-ai-1) (pro-consideration); ["It's not obvious that getting dangerous AI later is better"](https://forum.effectivealtruism.org/posts/bLWG7onTMKzdozez8/it-s-not-obvious-that-getting-dangerous-ai-later-is-better) (skeptical). An EA Forum post titled ["Risk of AI deceleration"](https://forum-bots.effectivealtruism.org/posts/Z4tsromjxAbMpAtiZ/risk-of-ai-deceleration) also exists in this cluster.
- **Comparative advantage argument:** an Alignment Forum / LessWrong post argues that AI alignment researchers may be especially well placed to reduce s-risks — implying the field's lever is shaping AI design, not stopping it — [GreaterWrong](https://www.greaterwrong.com/posts/hkHus8eqwofkzwciX/ai-alignment-researchers-may-have-a-comparative-advantage-in)
- **CLR's priority is conflict between AI systems, worked on through cooperation and bargaining research (Safe Pareto Improvements) and LLM persona research,** not slowing deployment — [CLR research overview](https://longtermrisk.org/research-overview/)
- **Sotala & Gloor frame superintelligence as a possible *cure* for s-risks as well as a cause.** This cuts against a simple "stop AI" conclusion — [Sotala & Gloor 2017](https://longtermrisk.org/superintelligence-cause-cure-risks-astronomical-suffering)
- **Metzinger: global moratorium on synthetic phenomenology until 2050** — [World Scientific](https://www.worldscientific.com/doi/10.1142/S270507852150003X)

### Inferences (relevance to a federal hyperscale data-center moratorium)
- **Pro-moratorium use of s-risk:**
  - Metzinger's ENP precaution, combined with Butlin/Long's "no obvious barriers" and Long/Sebo's "realistic possibility," supports slowing the creation of very large numbers of potentially sentient systems until welfare science matures.
  - A compute cap is a crude but enforceable proxy for limiting how many potentially sentient digital minds are created.
  - Near-miss/sign-flip arguments suggest that rushing alignment under short timelines raises worst-case risk, which favors buying time.
- **Anti-moratorium or ambiguous use:**
  - Core s-risk researchers (Vinding, CLR) say a pause has ambiguous sign. It may increase multipolarity and therefore AI-AI conflict and threat risk, especially if a *unilateral* national moratorium shifts frontier development to other actors.
  - S-risk advocates prefer targeted interventions: cooperative-AI design, worst-case safeguards, malevolence screening and welfare assessment.
- **Net:** a debater can honestly say that the s-risk literature contains one prominent academic moratorium argument (Metzinger) and several precautionary premises. The specialist s-risk organizations do not, as institutions, endorse compute pauses.

### Gaps
- No CLR institutional statement on AI pauses or compute caps was found.
- No s-risk literature was found that specifically addresses data-center or hyperscale-compute moratoria.
- Brian Tomasik's own view on pausing AI: not found this session.
- Post-2024 developments (2025–2026 statements by CLR, CRS or Metzinger on pause proposals): not retrieved.
