# Detailed Outline — *From Persons to Families to Organizations: A Cross-Level CAS Foundation for Brief Health Screening*

**Source:** `main.tex` (draft of 2026-06-10, ~11,600 words; 7 sections, 8 tables, 1 figure)
**Companion documents:** `advisor-outline.docx` (high-level summary for advisor review), `review-response.md` (disposition of GPT-5.5 Pro pre-review)
**Citation keys** in brackets refer to `references.bib`.

---

## Argument spine (one line per section)

1. **Introduction** — A real measurement gap exists; the clinical fix invites a two-level-leap objection; thesis: decompose the leap through family systems.
2. **Three Systems, One Pattern** — Persons, families, and organizations each instantiate CAS properties; the differences between levels are catalogued, not suppressed.
3. **Screening as a Level-General Pattern** — The brief-screening design pattern arose independently at two adjacent CAS levels; transfer analysis says what carries to a third.
4. **Cross-Level Measurement Architecture** — Five-element assessment-system abstraction + construct correspondences + multilevel measurement machinery; OHA as worked application; governance commitments.
5. **Implications** — Seven-commitment design discipline; staged known-answer simulation calibration; Kane argument-based validation roadmap.
6. **Limitations** — Seven bounded limitations, stated as part of the contribution.
7. **Conclusion** — Two validated predecessors shift the burden of argument; the architecture is reusable beyond the OHA.

---

## Front matter

- **Title:** From Persons to Families to Organizations: A Cross-Level CAS Foundation for Brief Health Screening
- **Abstract** (single paragraph): gap → two-level-leap problem → three nested CAS instantiations → family science as intermediate precedent (FAD, SCORE) → derived architecture (five-element abstraction, correspondences, multilevel foundations) → OHA as worked application → claim boundary (design rationale, not validity; staged companion program) → implications (design, simulation calibration, governance, validation).
- **Keywords:** organizational health, complex adaptive systems, brief screening, family assessment, multilevel measurement, instrument design, measurement architecture

---

## 1. Introduction (`sec:introduction`)

**Role:** Establish the gap, state the objection honestly, announce the thesis and the claim discipline, enumerate contributions.

- **¶1 — The measurement gap.** Organizations fail without measurement, not without warning. Two unhelpful extremes: comprehensive assessments (McKinsey OHI, Denison) too burdensome for recurring use [camp2024, denison1995, keller2011]; routine measures (pulse surveys, SE effectiveness metrics) too narrow [brown2022, elm2012]. Gap claim is cited and bounded: "to the authors' knowledge … open to counterexample," not a proven negative.
- **¶2 — The clinical solution.** PHQ-9: nine items, under two minutes, validated against comprehensive clinician-administered assessment [kroenke2001, thombs2021]; GAD-7 replicates [spitzer2006]. Prior program paper proposed adapting this logic → the OHA, six-domain brief screener for SE settings [carr2025].
- **¶3 — The objection (stated at full strength).** PHQ-9 respondent, instrument, and system coincide in one bounded individual. An organization is none of these: multi-actor, emergent health, no member observes it whole. Direct transfer crosses **two levels at once**: one actor → many; self-reported internal state → system-referent emergent property. A skeptic is entitled to ask whether anything more than metaphor connects the endpoints.
- **¶4 — Thesis.** The leap becomes principled when decomposed into two single-level steps — and the intermediate level is already occupied. Family systems: genuine multi-actor systems; family science treated them as systems for ~70 years [jackson1957, minuchin1974, bowen1978, cox1997]; four decades of validated multidomain, multi-informant, repeatable instruments (FAD, SCORE) [epstein1983, stratton2010, stratton2014, hamilton2016]. The brief-plus-comprehensive pattern re-emerged *within* that tradition: FAD General Functioning as standalone screen [boterhovendehaan2015]; SCORE-15 distilled from longer pool [stratton2010, stratton2014]. Key independence fact: **FAD predates PHQ-9 by ~two decades** — the family instance cannot be derivative. The pattern recurs because the functional pressures recur.
- **¶5 — Two kinds of evidence.** (a) Structural: all three levels instantiate defining CAS properties → measurement strategies keyed to those properties are candidates for transfer. (b) Empirical-by-precedent: the screening pattern itself has now appeared at two adjacent levels under the same constraints. Together: from cross-domain metaphor to *next instance of an established pattern*.
- **¶6 — Claim discipline.** The architecture supplies **design rationale**, not validity. Family instruments are design precedents, not validators; validity is an organizational-level empirical obligation [kane2006, aera2014].
- **¶7 — Scope and contributions.** Conceptual paper; empirical program reported separately. Four contributions: (1) family systems as theoretically grounded intermediate CAS level (§2); (2) brief screening as level-general pattern, with families vs. teams anchoring argument (§3); (3) the cross-level measurement architecture with OHA worked application and governance (§4); (4) implications for design, simulation characterization, validation planning (§5). §6 limitations; §7 conclusion.

---

## 2. Three Systems, One Pattern: CAS at Three Levels of Analysis (`sec:three-systems`)

### 2.1 Complex Adaptive Systems and Claim Discipline (`sec:cas-discipline`)

**Role:** Define the property set and discipline the "X is a CAS" claim form before using it.

- **¶1 — Definition and property set.** CAS = interdependent agents whose local interactions produce unpredictable system-level behavior [holland1995]. Recurring properties: self-organization; feedback regulation; emergence [goldstein1999]; nonlinearity; adaptation; critical transitions [anderson1999, scheffer2009].
- **¶2 — Claim discipline.** An as-CAS claim asserts *only* instantiation of the structural property set — licensing transfer candidacy, not sameness of kind. What transfers must be established property by property; differences constrain the answer (→ §2.5).
- **Exhibits:**
  - **Table 1** (`tab:cas-properties`): 6 CAS properties × 3 levels — characteristic manifestations (e.g., emergence: network state / relational property / systemic capacity).
  - **Figure 1** (`fig:ladder`): the cross-level ladder (TikZ). Three rungs, each pairing brief + comprehensive instrument; dashed annotations name the adjustments entering at each boundary (person→family: assessor multiplies, construct becomes emergent, items shift referent; family→org: scale/nesting, role stratification/power, designed purposive system).

### 2.2 Persons as Complex Adaptive Systems (`sec:person-cas`)

**Role:** Ground the bottom rung in the network theory of mental disorders.

- **¶1 — Network theory.** Symptoms are causal agents, not passive indicators of a latent disease [borsboom2017]. Feedback loops (sleep → fatigue → appraisal → mood → sleep); strong connectivity → self-sustaining disorder state = attractor dynamics [borsboom2017, robinaugh2020].
- **¶2 — Measurement consequences.** Attractor systems exhibit critical transitions preceded by generic early-warning signals (rising variance, critical slowing down) [scheffer2009]; documented for depression onset *and* remission [vandeLeemput2014]. Implications: monitoring ≥ snapshot; dense coupling means a small, well-chosen indicator sample carries global state information. This is the theoretical reading of why brief screeners work (developed §3.1).

### 2.3 Family Systems as Complex Adaptive Systems (`sec:family-cas`)

**Role:** The first load-bearing novelty — family-as-CAS is *derived from family science itself*, not imposed.

- **¶1 — Intellectual lineage.** Founding commitment of family science, predating CAS vocabulary: von Bertalanffy GST [vonbertalanffy1968] → family therapy. Jackson: family homeostasis (self-correcting equilibrium) [jackson1957]. Minuchin: structured wholes, subsystems (spousal/parental/sibling), boundary permeability from enmeshed to disengaged [minuchin1974]. Bowen: family as emotional unit; differentiation of self; triangles [bowen1978]. Watzlawick: first- vs. second-order change [watzlawick1974]. Cox & Paley: consolidation for developmental science — circular causality, homeostasis + adaptive reorganization [cox1997].
- **¶2 — The mapping.** Read against §2.1's property set, this is a CAS description written before the term existed. **Table 2** (`tab:family-cas-mapping`): term-by-term correspondence, 8 rows — homeostasis ↔ attractor + negative feedback; circular causality ↔ feedback loops; subsystems/boundaries ↔ modularity/coupling; enmeshment–disengagement ↔ pathological coupling extremes; first/second-order change ↔ parameter change vs. regime shift; rules/scripts/routines ↔ emergent self-organized order; differentiation/triangles ↔ agent heterogeneity; life-cycle adaptation ↔ adaptive reorganization [olson2000].
- **¶3 — From theory to measurement models.** McMaster Model: explicitly systemic premises; six dimensions (problem solving, communication, roles, affective responsiveness, affective involvement, behavior control) as a domain decomposition of an emergent construct [epstein1978, miller2000]. Olson Circumplex: cohesion × flexibility (+ communication); *balanced* levels healthy, extremes pathological — in CAS terms, a coupling-strength/adaptability hypothesis [olson2000]. Both models: items reference the family as a whole; answered by multiple members (→ §3.2).

### 2.4 Organizations as Complex Adaptive Systems (`sec:org-cas`)

**Role:** Top rung; also installs the SE pathology taxonomy and restates the gap in CAS terms.

- **¶1 — Org-as-CAS literature.** Interdependent elements → emergent outcomes [anderson1999, schneider2006]; multilevel emergence formalized [kozlowski2000, kozlowski2013]. Level-specific nonlinearity: punctuated equilibrium [gersick1991, romanelli1994]; abrupt collapse under stress [weick1993]. **Explicit hedge:** organizational early-warning signatures = open empirical question, motivating hypothesis throughout — not established finding [scheffer2009, vandeLeemput2014].
- **¶2 — Organizational health as the emergent construct.** Miles: survives + copes + develops [miles1965]; contemporary: align, execute, renew, sustain [camp2024, keller2011]. Systemic, hence narrow proxies fail — the state lives in the *alignment among facets* [denison1995, schneider2006].
- **¶3 — SE pathology as diagnostic taxonomy.** Four categories (knowledge/understanding, organization, resources, implementation); explicit medical analogy — presentations, causes, detection [davidz2018]. Converts a diffuse construct into an enumerable space of assessable concerns, in the working language of the assessed organizations. OHA domain structure draws on it [carr2025] (→ §4.4).
- **¶4 — The gap, restated in CAS terms.** Emergent state + nonlinear change ⇒ instruments must (a) sample interdependent domains, (b) draw on multiple vantage points, (c) repeat at low burden. Comprehensive meets (a) not (c); pulse meets (c) not (a); neither meets (b) systematically [camp2024, brown2022, elm2012].

### 2.5 Differences That Matter (`sec:differences`)

**Role:** The disanalogies that shape the architecture as much as the analogies.

- **¶1 — Person vs. multi-actor: locus of report.** Self-report's respondent/system coincidence breaks; informant disagreement becomes a *structural feature* of measurement, not a nuisance (→ §3.2, §4.3).
- **¶2 — Family vs. organization.** Scale (2–10 vs. handful–thousands, nested subunits); formation (given vs. contractual/fluid); purpose (no charter vs. designed, purposive, formal accountability); authority (generational/diffuse vs. formalized hierarchy → power differentials → candor consequences [edmondson1999]); intimacy/affective intensity has no full organizational counterpart (caution for affect-laden constructs).
- **¶3 — Within-level heterogeneity.** Persons, families, organizations all internally heterogeneous; CAS property strength plausibly varies with size, formalization, membership stability. **Target class:** intact organizational units with continuing membership and shared fate — not organizations in general (→ §6, limitation 5).
- **¶4 — Transfer rule preview.** Content never transfers (no family item belongs on an org instrument; no clinical cutoff means anything for a team). What may transfer is *architecture* — and only where the motivating property is shared.

---

## 3. Brief Screening as a Level-General Measurement Pattern (`sec:screening-pattern`)

### 3.1 The Clinical Pattern (`sec:clinical-pattern`)

**Role:** Extract the design pattern from its first instance.

- **¶1 — PHQ-9 design facts.** Nine DSM-IV criteria → nine items, common 4-point frequency scale, 0–27, severity bands, validated cutoff; 88%/88% sensitivity/specificity vs. comprehensive interview, sustained in IPD meta-analysis [kroenke2001, thombs2021]. SCID as comparator — screener doesn't replace it, it *determines who needs it* [first1996]. GAD-7 replicates the architecture [spitzer2006].
- **¶2 — Five design principles.** (1) Sample core indicators across the construct's domains, don't exhaustively assess; (2) consistent low-burden response format; (3) interpretable scoring with actionable thresholds; (4) **definitionally**: validation against a comprehensive reference — brevity's cost made known and acceptable; (5) (usually implicit) designed for repetition — trajectory carries diagnostic information no single administration provides.
- **¶3 — CAS reading + epistemic split.** Dense coupling → few well-chosen nodes index global state [borsboom2017]; attractor dynamics → repeated measurement captures trajectory/early-warning information snapshots cannot in principle provide [scheffer2009, vandeLeemput2014]. Screening = measurement strategy matched to CAS structure, expected wherever the properties recur and burden constraints bind. **Two epistemic weights:** indicator-sampling claim supported at individual level; organizational early-warning is a hypothesis the research program must test (→ §5.3).

### 3.2 The Family-System Replication (`sec:family-replication`)

**Role:** The pattern's independent second instance — under *harder* conditions.

- **¶1 — Harder problem.** Construct emergent and relational; no informant observes it whole; severe burden constraints (clinical sessions, large surveys).
- **¶2 — FAD = multidomain exemplar.** 60 items, six McMaster scales + 12-item General Functioning [epstein1983, miller2000]. Three features: (a) samples interdependent relational domains (like a screener samples a symptom network); (b) multiple members rate the same system; McMaster practice reads disagreement as information about the family — convergent with the informant-discrepancy literature: modest cross-informant correlations, systematically patterned → discrepancies are data [miller2000, achenbach1987, delosreyes2005]; (c) General Functioning = brief instrument *nested within* the comprehensive one, validated standalone, incl. shortened in epidemiological surveys [boterhovendehaan2015]. The brief+comprehensive pairing exists *within* the FAD family.
- **¶3 — SCORE = longitudinal exemplar.** SCORE-40 → deliberately distilled SCORE-15 for every-session completion [stratton2010]; three subscales (strengths/adaptability; overwhelmed by difficulties; disrupted communication); detects change between early sessions [stratton2014]. Existence proof: brief systemic instrument tracking trajectory of an emergent relational state over short cycles — precisely the organizational value proposition. Field maturity: FAD and SCORE among the small set judged psychometrically adequate and clinically useful [hamilton2016].
- **¶4 — The pattern across levels.** **Table 3** (`tab:pairings`): 3 levels × {comprehensive reference, brief instrument, monitoring role} — SCID/PHQ-9; full FAD + SCORE-40 / FAD-GF + SCORE-15; OHRA (~100 items)/OHA (~20 items). Independence: FAD predates PHQ-9 by 18 years; SCORE arose from systemic therapy's own outcome-monitoring needs. One instance = idiosyncrasy; two independent instances under the same constraints = level-general solution. Burden of argument shifts: the OHA is a *candidate third instance*, not a stretched metaphor. (Does not prove success at level three.)

### 3.3 Why Family Systems Anchor the Intermediate Level (`sec:why-families`)

**Role:** Answer the "why not teams?" objection with explicit criteria; land on complementarity. (Rewritten per review concern #2.)

- **¶1 — The objection + five criteria.** Teams seem the natural intermediate. Anchor choice must rest on criteria, not surface similarity. The intermediate rung must supply validated precedent for: (1) emergent, system-referent construct measured as collective property; (2) multi-informant administration with discrepancy-as-information; (3) brief instrument validated against comprehensive comparator *within the same tradition*; (4) routine repeated administration with demonstrated change sensitivity; (5) published norms/cutoffs/benchmarks usable as known-answer targets (→ §5.2 calibration).
- **¶2 — What teams genuinely supply (criteria 1–2).** Emergent collective constructs (climate, collective efficacy, reflexivity); referent-shift practice formalized there [chan1998]; TCI as validated multidomain climate measure [andersonwest1998]; TDS as comprehensive diagnostic [wageman2005]; domain-proximal construct content [mathieu2008].
- **¶3 — What teams don't supply (criteria 3–5).** No team analog of FAD-GF/SCORE-15 (brief, normed, repeatable, validated in-tradition, adopted for routine monitoring) [boterhovendehaan2015, stratton2014]; operationalization remains study-specific [mathieu2008]; benchmarks are research findings, not clinical-grade norms/cutoffs/change-sensitivity infrastructure.
- **¶4 — Two softer considerations.** Families are natural persistent systems (like the target class: intact units, continuing membership, shared fate) vs. ad hoc project groups; family therapy's system-as-patient stance [minuchin1974, miller2000] = the stance org health assessment and SE pathology take [davidz2018, miles1965] — precedent supplies an assessment *philosophy*, not just instruments.
- **¶5 — Resolution: complementarity with division of labor.** Families anchor the *screening pattern*; teams contribute construct content, contextualization, and independent confirmation that collective-referent measurement works in work settings. Families = best-instrumented intermediate level, not the only conceivable one (→ §6, limitation 4).

### 3.4 What Transfers, What Adapts, and What Does Not Transfer (`sec:transfer-analysis`)

**Role:** Discipline the transfer with a single rule and an element-by-element classification.

- **¶1 — The rule.** An element transfers to the extent the structural property motivating it is shared (§2.1); it adapts or fails to transfer to the extent it depends on level-specific features (§2.5).
- **Table 4** (`tab:transfer`), 9 design elements:
  - **Transfers:** multidomain sampling (emergence + dense coupling; content still org-derived); brief+comprehensive pairing (burden–coverage trade-off; requires building an org comparator); consistent low-burden format [clark1995, hinkin1998]; repeated administration (cadence adapted to organizational timescales).
  - **Adapts:** system-referent item wording (referent-shift composition [chan1998]); multi-informant design with discrepancy-as-evidence (org informants stratify by role/hierarchy/power; candor gradients [edmondson1999, delosreyes2005]).
  - **Does not transfer:** item content (org content from org health theory + SE pathology [davidz2018]); norms/cutoffs/severity bands (population-specific empirical facts); validity evidence (attaches to score interpretations at a level [kane2006, aera2014]).
- **¶2 — The two most-elided entries.** Norms don't transfer; validity doesn't transfer [kane2006, messick1995, aera2014]. The architecture = the design-stage interpretive argument a validation effort requires — a testable theory of why the instrument should work, **not** a substitute for testing.

---

## 4. A Cross-Level Measurement Architecture for Organizational Health Screening (`sec:architecture`)

### 4.1 The Assessment-System Abstraction (`sec:assessment-system`)

**Role:** Core architectural move — five elements convert "does screening transfer?" into five precise questions and locate every adjustment at a specific boundary.

- **¶1 — Five elements.** Instrument; assessor(s); system under test; generic system type (theoretical model of the system class + diagnostic taxonomy); stakeholders. **Table 5** (`tab:assessment-system`): all five instantiated at the three levels (e.g., assessors: patient self-report → multiple family members → multiple assessors stratified by role: frontline/supervisor/executive).
- **¶2 — The payoff (the leap, decomposed).**
  - **Person → family boundary:** assessor multiplies; system under test becomes emergent relational unit; item referent shifts from self to system. These are the *measurement-theoretically hard* transitions — and family assessment has already made them, with validated results.
  - **Family → organization boundary:** scale + nested structure; assessor stratification by formal role/authority (vs. family position); generic system type shifts natural-intimate → designed-purposive, with SE pathology as taxonomy [davidz2018]; stakeholder set widens beyond members.
  - Every organizational adjustment is either solved at a lower level or explicitly new — and the new ones (scale, role stratification, purposive structure) are exactly where org measurement theory has tools (→ §4.3).

### 4.2 Construct Correspondences Across Levels (`sec:correspondences`)

**Role:** Content-level design guidance — explicitly hypotheses, not equivalences.

- **¶1 — The mapping.** **Table 6** (`tab:correspondences`), 9 rows (FAD/SCORE → organizational analog): communication → communication quality/coordination/information flow; roles → role clarity/accountability/decision rights; problem solving → organizational learning/issue resolution; behavior control → norms/governance/operating discipline; affective responsiveness + involvement → trust/psychological safety/engagement; general functioning → overall health-index logic; strengths/adaptability → resilience/change capacity; overwhelmed by difficulties → friction/overload/strain; change over time → longitudinal monitoring/intervention response. Each row = testable design hypothesis.
- **¶2 — Discipline via disanalogies.** Affective constructs translate *loosest* — mapped onto organizational literatures with their own validated measures (trust, psychological safety [edmondson1999, frazier2017]), not transferred. Structural/process constructs translate *tightest* (shared CAS substrate of coordination/regulation/adaptation). Some constructs don't map: enmeshment/disengagement as affective phenomena — only their structural lesson transfers (over- and under-coupling both degrade adaptive capacity; org forms: silos, dissent-suppressing cohesion). Conservatism rule: a row appears only where an organizational literature exists to receive it.

### 4.3 Multilevel Measurement Foundations (`sec:multilevel-foundations`)

**Role:** Show the family→org boundary's new demands are met by established multilevel measurement theory; commit to a concrete evaluation plan. (Expanded per review concern #6.)

- **¶1 — Thread 1: construct emergence and composition.** Composition vs. compilation [kozlowski2000, morgeson1999]; Chan's typology [chan1998]. Two load-bearing models: **referent-shift consensus** ("this unit…", within-unit consensus justifies aggregation) = what family instruments already do; adopted by the OHA. **Dispersion composition** (within-unit variance as focal construct) = formalization of family discrepancy analysis [delosreyes2005].
- **¶2 — Thread 2: aggregation discipline.** Agreement must be demonstrated, not assumed: r_wg(j) and interpretive conventions [james1984, lebreton2008, bliese2000]. Architecture commitment: every unit-level score ships with an agreement statistic; systematic cross-role disagreement = *finding about the organization* (dispersion logic), not unreliability to suppress.
- **¶3 — Thread 3: response distortion.** Socially desirable responding [paulhus1984]; common-method variance [podsakoff2003]; hierarchy adds a *structured* distortion gradient — candor varies with psychological safety, and that variance is itself diagnostic of climate [edmondson1999]. Family parallel in form (disclosure depends on system safety) but org version is power-stratified → role-stratified analysis + brief, low-threat item design [clark1995, hinkin1998].
- **¶4 — Loop closed.** Person→family demands met by family assessment tradition; family→org demands met by multilevel measurement theory. *At no point does the architecture require a measurement operation without precedent.*
- **¶5 — Concrete evaluation plan.** Internal consistency within domains and within roles; CFA: six correlated domain factors, higher-order health factor as an empirical question, not an assumption; measurement invariance across assessor roles before cross-role comparison (role-dependent item functioning plausible and informative) [putnick2016]; within-unit agreement with every aggregate [lebreton2008, bliese2000]; low-agreement domains → dispersion-model interpretation; pre-fixed reporting rules incl. minimum cell sizes (→ §4.5).

### 4.4 The OHA as a Worked Application (`sec:oha-application`)

**Role:** Instantiate the architecture; show it has bite. (Expanded per review concerns #4–5.)

- **¶1 — The instrument.** ~20 positively framed Likert items, six domains [carr2025]. **Table 7** (`tab:oha-domains`): Knowledge & Understanding; Process Maturity; Resource Allocation; Leadership & Decision-Making; Culture & Collaboration; Implementation & Execution — each with theoretical source (SE pathology categories [davidz2018] + org health theory + CAS analog) and SE-relevant focus.
- **¶2 — Six domains as an argued choice.** Four pathology categories = skeleton; "organization" category split into Process Maturity + Leadership/Decision-Making (distinct failure loci per pathology evidence and the comprehensive frameworks [davidz2018, camp2024, denison1995]); Culture & Collaboration added because emergent relational properties (trust, integration, information flow) are underrepresented in an execution-focused taxonomy. 6 domains × 3–4 items = inside the routine-administration burden envelope while preserving multidomain sampling — same coverage-vs-burden balance that fixed McMaster at six dimensions [epstein1978]. **Table 8** (`tab:oha-items`): one published illustrative item per domain (operational pool refined and frozen during instrument-development phase).
- **¶3 — The architecture has bite.** Published illustrative items mix self-referent ("my responsibilities") and unit-referent ("our organizational culture") wordings → referent-shift commitment is a *refinement criterion applied to the pool* before freeze, not a post hoc description.
- **¶4 — Element-by-element traceability.** Multidomain structure ← level-general sampling principle (content org-derived per transfer analysis). Unit-referent items ← referent-shift [chan1998]. Multi-assessor across frontline/supervisor/executive, agreement reported with every unit score, divergence analyzed as alignment evidence ← FAD multi-informant practice formalized [miller2000, chan1998, james1984, lebreton2008]. Recurring administration (quarterly or comparable) with trajectory carrying diagnostic weight ← SCORE-15 monitoring role at org timescales [stratton2014]. Primary output = six-domain profile; total score = pragmatic summary, not reflective measure of a single latent dimension. Paired comprehensive comparator = OHRA (~100 items, assembled from public-domain descriptions of established frameworks [camp2024, denison1990, denison1995]).
- **¶5 — Positioning vs. OHI/Denison.** Complement, not competitor: those traditions support comprehensive system-level measurement; what their use models lack is a low-burden recurring screen indicating *when* comprehensive assessment is warranted. They occupy the comprehensive-assessment role; OHRA is assembled from their public descriptions for exactly that reason.
- **¶6 — Claim boundary.** Architecture explains design; it does not establish validity. OHRA = reference-class comparator for research use, not gold standard. Domain coherence, discrimination, change sensitivity, distortion robustness = empirical questions for the staged program.

### 4.5 Administration, Governance, and Ethics (`sec:governance`)

**Role:** The stakeholder element makes the screener a governance object; design commitments at that layer complete the architecture. (New per review concern #8.)

- **¶1 — Three organizational risks.** (1) Power differentials: respondents report on a system containing people with authority over their careers; responses under perceived surveillance measure fear, not health [edmondson1999, paulhus1984]. (2) Identifiability: small units + role-stratified reporting can expose individuals despite nominal anonymity. (3) Purpose drift: system diagnosis quietly repurposed for individual evaluation — destroys ethics *and* measurement properties.
- **¶2 — Design commitments (same standing as item wording and scoring).** Confidentiality protections fixed and communicated in advance; minimum cell sizes (role-level scores only above identifiability threshold; unit summaries require multiple assessors across multiple roles; small cells suppressed into higher aggregates); results returned to the assessed unit itself in the same form as to any stakeholder; data ownership/access/retention specified pre-administration; unit-as-patient framing — no individual-level inference produced or permitted. Commitments are *psychometric as well as ethical* (distortion analyses presuppose conditions where honest responding is rational). Research administrations add informed consent + IRB on top.

---

## 5. Implications (`sec:implications`)

### 5.1 Implications for Instrument Design (`sec:design-implications`)

**Role:** Compress the architecture into a portable seven-commitment design discipline.

1. **Define the emergent construct and its taxonomy first** (DSM ← PHQ-9; McMaster ← FAD; SE pathology ← OHA) [kroenke2001, epstein1978, davidz2018].
2. **Sample interdependent domains; do not catalogue** — rely on dense coupling to propagate state [borsboom2017].
3. **Write system-referent items** — engage referent-shift deliberately [chan1998].
4. **Design for multiple positioned informants** — report agreement; treat structured divergence as a finding [james1984, lebreton2008, delosreyes2005].
5. **Keep it brief enough to repeat, and repeat it** — set length from cadence; trajectory is the primary signal [stratton2014, vandeLeemput2014].
6. **Pair the screener with a comprehensive comparator** — establish brevity's cost and the triggered follow-up [kroenke2001].
7. **Publish the instrument and its rationale** — trust through documentation, critique, cumulative validation.

### 5.2 Implications for Simulation-Based Characterization (`sec:simulation-implications`)

**Role:** The ladder's second payoff — staged known-answer calibration for LLM-simulated respondents (the practicum's three-step design).

- **¶1 — Prospect and problem.** LLM persona-conditioned survey simulation [argyle2023, park2023]; known failure modes: compressed/stereotyped distributions, prompt sensitivity [bisbee2024, tjuatja2024]; deeper problem: **no published organizational benchmarks** to check simulated-respondent plausibility.
- **¶2 — Staged calibration (what the architecture supplies).** Two adjacent levels with published benchmarks → graduated test sequence: **Step 1** — reproduce individual-level psychometric relationships (PHQ-9 severity structure, brief-vs-comprehensive agreement) [kroenke2001]. **Step 2** — multi-agent family systems reproduce family-level signatures (FAD domain patterns; multi-informant agreement + informative divergence; SCORE-15 change sensitivity) [epstein1983, stratton2014]. **Step 3** — organizational application: agent-based dynamics define known ground truth [bonabeau2002]; OHA characterized against OHRA. Family level makes the sequence graduated: it checks multi-informant coherence and longitudinal tracking — capabilities the org application requires and individual calibration cannot check. Implemented in the research program; reported separately.
- **¶3 — Claim boundary and sequencing.** Staged calibration buys bounded trust in the *methodology*, not instrument validity. Output = predicted measurement profile (testable expectations) → pilot administration tests it against real respondents → larger-scale validation unchanged as the standard. Simulation complements, never substitutes; misspecification risk concentrated exactly where benchmarks don't exist — reported as methodology findings.

### 5.3 Implications for Validation Planning (`sec:validation-implications`)

**Role:** Map the architecture onto Kane's argument-based framework, inference by inference.

- Kane framework: validity = supported interpretive argument [kane2006, cronbach1955, messick1995, aera2014]. Architecture contributes the design-rationale strand and sharpens each layer:
  - **Scoring:** items cohere within assigned domains (simulation probes; field data confirms).
  - **Generalization:** interpretable cross-assessor structure — convergence where state is broadly observable, patterned divergence where vantage points differ (agreement machinery of §4.3).
  - **Extrapolation:** brief–comprehensive convergence (OHA–OHRA as the organizational instance of the ladder-defining relationship); criterion/discriminant evidence — prediction of retention, delivery performance, incident experience; distinguishing healthy-under-load from dysfunctional units.
  - **Implication:** domain profiles and trajectories support useful follow-up decisions — evidenced only by practitioner use.
- Family precedents inform the predictions; they contribute **no evidence** to the organizational argument. Staging: computational characterization → pilot feasibility → larger-scale empirical study.

---

## 6. Limitations and Boundary Conditions (`sec:limitations`)

**Role:** Seven precise limitations, stated as part of the contribution.

1. **Design rationale ≠ validity.** The architecture makes the design-stage theory explicit and falsifiable; it does not discharge the empirical burden [kane2006, aera2014].
2. **Families ≠ organizations.** §2.5 disanalogies are real and consequential; design logic transfers, never content/norms/evidence; Table 6 rows are hypotheses whose organizational halves stand on organizational theory and data.
3. **Family precedents have their own limitations.** FAD factor structure debated; informant access varies; norms population-specific [hamilton2016, boterhovendehaan2015]. The argument needs family measurement to be credible and mature (it is), not unproblematic (no tradition is).
4. **Family anchor justified by measurement maturity, not uniqueness.** Teams, workgroups, classrooms, care teams = alternative rungs; fuller ladder a natural extension; the argument needs the family rung load-bearing, not exclusive [wageman2005].
5. **Screening logic has boundary conditions.** Presumes dense interdependence; member-observable functioning; stable composition; stable construct definition. Outside: radical reorganization, transient/peripheral membership (heavily matrixed, gig-style), undecomposable constructs. Predictable failure modes; boundary locations are an empirical question.
6. **The six domains sample organizational health; they do not exhaust it.** Diversity climate, equity, justice touched by Culture & Collaboration but not measured; sector-specific and equity-extended variants are natural successors.
7. **This is a theory paper.** Claims are structural/architectural; empirical program (staged calibration → pilot) reported separately; governance practicability itself a pilot question. Judge now on coherence, fidelity to source literatures, precision of licensed predictions; later on whether predictions survive data.

---

## 7. Conclusion (`sec:conclusion`)

- **¶1 — The argument, restated.** The single PHQ-9 analogy overreaches (two levels in one step) and is unnecessary (the intermediate level is occupied). Family science treated relational systems as systems before complexity science named the vocabulary; family assessment built validated multidomain, multi-informant, repeatable instruments — with brief forms paired to comprehensive comparators — two decades before the clinical exemplar. Three nested CAS instantiations; the pattern arose independently at the first two.
- **¶2 — The architecture, restated.** Five-element abstraction locating each scaling adjustment at a boundary (hardest already solved); construct correspondences as design guidance without equivalence claims; multilevel foundations (referent-shift, dispersion, aggregation discipline, role-stratified distortion). Transfer analysis: what carries, what adapts, what must be re-established (content, norms, validity). OHA instantiates; the program it organizes: staged known-answer calibration, then argument-based validation of the identified open inferences.
- **¶3 — Broader contribution.** Reusable beyond this instrument and domain: wherever an emergent state of a multi-actor system needs routine monitoring, the architecture specifies what a defensible brief screener must do and must still prove. "Three levels are enough to establish the pattern; they are unlikely to be the only three."

---

## Exhibit inventory

| # | Label | Location | Carries |
|---|-------|----------|---------|
| Table 1 | `tab:cas-properties` | §2.1 | 6 CAS properties × 3 levels |
| Figure 1 | `fig:ladder` | §2.1 | The cross-level ladder with boundary annotations |
| Table 2 | `tab:family-cas-mapping` | §2.3 | Term-by-term family systems ↔ CAS mapping (8 rows) |
| Table 3 | `tab:pairings` | §3.2 | Brief + comprehensive pairings at 3 levels |
| Table 4 | `tab:transfer` | §3.4 | Transfer analysis: transfers / adapts / does not (9 elements) |
| Table 5 | `tab:assessment-system` | §4.1 | Five-element assessment system × 3 levels |
| Table 6 | `tab:correspondences` | §4.2 | Family → organizational construct hypotheses (9 rows) |
| Table 7 | `tab:oha-domains` | §4.4 | Six OHA domains, sources, SE focus |
| Table 8 | `tab:oha-items` | §4.4 | One illustrative published item per domain |

## Recurring claim-discipline threads (woven through every section)

- Design rationale ≠ validity; precedents ≠ validators [kane2006, aera2014] — §1, §3.4, §4.4, §5.3, §6.
- Organizational early-warning = motivating hypothesis, not finding — §2.4, §3.1, §5.3.
- Content, norms, and validity never transfer — §2.5, §3.4, §6.
- Target class: intact units, continuing membership, shared fate — §2.5, §6.
- Simulation complements, never substitutes for, empirical validation — §5.2.
