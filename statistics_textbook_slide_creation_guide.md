# Replicable Guide for Creating Graduate Statistics Textbook Chapter Slide Decks

**Version:** 1.0  
**Purpose:** Convert a full graduate-level statistics textbook chapter into a coherent, visually rigorous, narrated slide deck using a gated, reviewable process.

---

## 1. Purpose and design philosophy

This guide defines a repeatable process for turning a textbook chapter into a graduate-level instructional presentation. The process combines:

1. **Consulting-style information architecture**: answer-first structure, explicit slide messages, rigorous hierarchy, purposeful exhibits, consistent layouts, source/provenance labeling, and a strong appendix.
2. **Instructional-design principles**: explicit learning objectives, prerequisite activation, concept formation, worked examples, interpretation, retrieval opportunities, scaffolding, and cumulative review.
3. **Statistics-specific discipline**: precise notation, separation of assumptions from conclusions, distinction between mathematical definition and interpretation, transparent data-generating stories, correct graphical encodings, and reproducible calculations.
4. **Narration-first design**: the deck is designed so each slide and its narration form a coherent instructional unit; the narration should extend the slide rather than simply read it verbatim.
5. **Human approval gates**: no later production stage is treated as final until the preceding stage is approved.

### Core principle

> **The textbook is the authoritative content source; the slide deck is an instructional transformation of that content, not a summary created from memory.**

The deck should preserve the chapter's mathematical/statistical accuracy while making its conceptual structure visible and learnable.

---

# 2. What to borrow from consulting-slide practice

| Consulting concept | Adaptation for a statistics textbook deck |
|---|---|
| **Answer-first / pyramid principle** | Lead each section with the concept or result students need to understand, then provide definitions, intuition, derivation, examples, and implications as supporting material. |
| **Action title** | Use a **teaching title**: a concise sentence stating what the student should understand from the slide. Avoid labels such as “Central Limit Theorem” when a claim such as “Averaging independent observations produces an approximately normal sampling distribution” is more useful. |
| **One-slide-one-message** | Use **one primary teachable idea per slide**. A derivation may occupy several slides; a single theorem should not be compressed into a single overloaded slide merely to satisfy a slide count. |
| **Standard slide archetypes** | Maintain a reusable library of instructional archetypes: concept, intuition, definition, theorem, derivation, worked example, counterexample, visualization, algorithm, interpretation, practice, recap, and summary. |
| **Visual hierarchy** | Make the title, key equation/graphic, interpretation, and source/provenance visually distinct. Students should know what to look at first, second, and third. |
| **Exhibit-first thinking** | Choose the representation that best answers the teaching question: graph, table, diagram, simulation, equation, number line, probability distribution, flowchart, or worked calculation. |
| **Source line on every slide** | Cite textbook pages/sections, external datasets, figures, papers, code, or adapted illustrations on the slide where they are used. |
| **Appendix / backup** | Use an appendix for extended derivations, technical proofs, notation tables, extra examples, supplementary figures, simulation details, and reference material. |
| **Standalone readability** | A learner should be able to understand the central claim of a slide without the narrator, while the narration supplies additional explanation and interpretation. |
| **Storyline / issue sequence** | Organize the deck around a learning progression: motivation → prerequisite idea → core concept → formalization → worked example → interpretation → application → practice → recap. |
| **Page/template consistency** | Use a restrained design system so students spend cognitive effort on statistics rather than on learning the visual language of the deck. |

### What NOT to import blindly

Consulting decks optimize for executive comprehension and rapid decision-making. Graduate statistics instruction has a different objective. Therefore:

- Do not optimize for the fewest possible slides.
- Do not remove necessary mathematical steps solely to make a slide look cleaner.
- Do not replace rigorous definitions with slogans.
- Do not use decorative data visualizations merely to make slides more visual.
- Do not force every concept into a 2x2, waterfall, or other consulting archetype.
- Do not treat a recommendation-oriented action title as appropriate for a theorem whose exact statement matters.

---

# 3. Evidence base and governing principles

The process is informed by the following evidence and practice literature.

### Presentation and slide design

- Naegle, K. M. (2021). *Ten simple rules for effective presentation slides*. **PLoS Computational Biology, 17**(12), e1009554. https://doi.org/10.1371/journal.pcbi.1009554
  - Particularly relevant to: one idea per slide, message-oriented headings, readability, citations, and avoiding overloaded slides.
- Duarte, N. (2008). *Slide:ology: The art and science of creating great presentations*. O'Reilly Media. ISBN 978-0-596-52234-6.
- Duarte, N. (2010). *Resonate: Present visual stories that transform audiences*. Wiley. ISBN 978-0-470-63201-7.
- Minto, B. (2021). *The pyramid principle: Logic in writing and thinking* (3rd ed.). Pearson/Financial Times Publishing. ISBN 978-1-292-37226-6.

### Multimedia learning and cognitive load

- Mayer, R. E. (2020). *Multimedia learning* (3rd ed.). Cambridge University Press. https://doi.org/10.1017/9781316941355
- Mutlu-Bayraktar, D., Coşgun, V., & Altan, T. (2019). Cognitive load in multimedia learning environments: A systematic review. *Computers & Education, 141*, 103618. https://doi.org/10.1016/j.compedu.2019.103618
- van Gog, T., Paas, F., & Sweller, J. (2010). Cognitive load theory: Advances in research on worked examples, animations, and cognitive load measurement. *Educational Psychology Review, 22*, 375–378. https://doi.org/10.1007/s10648-010-9145-4

### Statistics-specific instructional evidence

- Hadfield, K. F. (2021). Providing ability to probability: Reducing cognitive load through worked-out examples. *Teaching Statistics, 43*(1), 24–30. https://doi.org/10.1111/test.12244

### Retrieval and active learning

- Agarwal, P. K., Nunes, L. D., & Blunt, J. R. (2021). Retrieval practice consistently benefits student learning: A systematic review of applied research in schools and classrooms. *Educational Psychology Review, 33*, 1409–1453. https://doi.org/10.1007/s10648-021-09595-9
- Carpenter, S. K., Pan, S. C., & Butler, A. C. (2022). The science of effective learning with spacing and retrieval practice. *Nature Reviews Psychology, 1*, 496–511. https://doi.org/10.1038/s44159-022-00089-1

### Visual encoding and decision/interpretation

- Cleveland, W. S., & McGill, R. (1984). Graphical perception: Theory, experimentation, and application to the development of graphical methods. *Journal of the American Statistical Association, 79*(387), 531–554. https://doi.org/10.1080/01621459.1984.10478080
- Midway, S. R. (2020). Principles of effective data visualization. *Patterns, 1*(9), 100141. https://doi.org/10.1016/j.patter.2020.100141
- Padilla, L. M., Creem-Regehr, S. H., Hegarty, M., & Stefanucci, J. K. (2018). Decision making with visualizations: A cognitive framework across disciplines. *Cognitive Research: Principles and Implications, 3*, 29. https://doi.org/10.1186/s41235-018-0120-9

These sources support the guide's general principles; they do **not** imply that every consulting convention has been directly validated as a causal intervention in graduate statistics education.

---

# 4. The gated production process

## Overview

The recommended workflow has seven gates.

| Gate | Stage | Human approval required? | Primary output |
|---|---|---:|---|
| **G0** | Input + style contract | Yes | Chapter package + deck brief |
| **G1** | Chapter analysis | Yes | Concept map + prerequisite map + learning objectives |
| **G2** | Learning architecture | Yes | Section sequence + instructional strategy |
| **G3** | Slide storyboard | Yes | Slide-by-slide outline with titles/messages |
| **G4** | Slide specifications | Yes | Exact slide content + figures + equations + citations |
| **G5** | Narration | Yes | Slide-by-slide narration scripts |
| **G6** | QA + final package | Yes | Final deck specification + QA report |

### Mandatory checkpoint rule

At each gate:

1. Present the proposed output in a structured form.
2. Identify assumptions or ambiguities.
3. Identify items requiring subject-matter review.
4. **Stop.** Do not proceed to the next gate until the user explicitly approves or requests changes.

Suggested approval commands:

- `APPROVE G1`
- `REVISE G1: ...`
- `APPROVE G1 WITH NOTES: ...`
- `REJECT G1 — restart from ...`

A system implementing this process should treat an approval as a state transition, not as conversational encouragement.

---

# 5. G0 — Input and style contract

## Required chapter input

The user should provide the complete chapter text whenever possible, including:

- chapter title
- section/subsection headings
- definitions
- theorems/propositions/lemmas
- equations
- worked examples
- exercises
- figures/tables if available
- captions
- footnotes/endnotes
- references

If the textbook chapter contains source-specific figures, tables, or mathematical notation, provide the original files when possible rather than relying on extracted text alone.

## Recommended deck brief

Before analyzing the chapter, establish:

```yaml
course_level: graduate
subject: statistics
chapter: "<chapter title>"
audience:
  background: "<expected prerequisites>"
  program: "<MS / PhD / mixed>"
delivery:
  mode: narrated_asynchronous
  target_duration_minutes: 45
  approximate_words_per_minute: 145
design:
  aspect_ratio: 16:9
  visual_style: "clean academic / restrained consulting"
  equation_style: "LaTeX"
  citation_style: "author-year or textbook section notation"
  footer_source_required: true
content:
  preserve_textbook_notation: true
  permit_external_examples: false
  permit_synthetic_data: true
  synthetic_data_must_be_labeled: true
  include_practice_questions: true
  include_appendix: true
```

### Important default

When the user does not provide a target slide count, estimate slide count from **instructional load and narration time**, not from chapter page count.

A reasonable starting heuristic for narrated graduate statistics content is approximately **45–90 seconds of narration per substantive slide**, with shorter slides for definitions, questions, and transition/visualization moments and longer slides for worked examples. The final count should be determined after the storyboard is constructed.

---

# 6. G1 — Chapter analysis

The goal of G1 is **not to create slides yet**. First determine what the chapter teaches.

## 6.1 Extract the chapter's knowledge structure

Create a table like:

| ID | Chapter element | Type | Importance | Dependencies | Student difficulty | Candidate teaching treatment |
|---|---|---|---|---|---|---|
| C01 | Sampling distribution | Core concept | Essential | sampling, random variable | High | intuition + simulation + definition |
| C02 | Standard error | Core concept | Essential | variance, SD | High | definition + worked example |
| C03 | CLT conditions | Assumption | Essential | independence | High | visual checklist + counterexample |
| C04 | Application | Example | Supporting | C01–C03 | Medium | worked example |

### Classify every important chapter element as one or more of:

- definition
- notation
- intuition
- theorem/result
- assumption/condition
- derivation
- algorithm/procedure
- worked example
- counterexample
- interpretation
- application
- common misconception
- comparison
- limitation
- exercise/practice
- summary

## 6.2 Identify prerequisite dependencies

Construct a directed dependency graph.

Example:

```text
Variance
   ↓
Sampling variability
   ↓
Standard error
   ↓
Sampling distribution
   ↓
Central Limit Theorem
   ↓
Normal approximation
   ↓
Confidence interval construction
```

The deck ordering should usually respect the dependency graph unless an intentional motivational preview is used.

## 6.3 Identify “hard points”

For graduate statistics, explicitly flag concepts that are likely to require extra instructional treatment:

- similar-looking distributions that represent different random quantities
- conditional versus marginal quantities
- parameter versus statistic
- population versus sample versus sampling distribution
- estimator versus estimate
- standard deviation versus standard error
- probability statements versus confidence statements
- assumptions whose role is easy to overlook
- transformations that change interpretation
- mathematical equivalence with different conceptual meaning
- asymptotic results and their finite-sample limitations

## 6.4 G1 output example

```markdown
### Chapter learning architecture

**Central idea:** Sampling variability can be modeled and summarized through sampling distributions, enabling probabilistic reasoning about statistics.

**Essential concepts:**
1. Population, sample, statistic, parameter
2. Sampling distributions
3. Standard error
4. Central Limit Theorem
5. Conditions and limitations
6. Normal approximation
7. Application to inference

**High-risk misconceptions:**
- A statistic is not the same thing as a parameter.
- A sampling distribution is not the same thing as the distribution of individual observations.
- Standard error is not the same as standard deviation of the raw data.

**Prerequisites:** random variables, expectation, variance, normal distribution.
```

### G1 checkpoint

**Human reviews:**
- Are the concepts correctly identified?
- Are the prerequisites realistic?
- Are important misconceptions identified?
- Is the relative importance of concepts correct?

**Stop for approval.**

---

# 7. G2 — Learning architecture

Now convert the chapter's knowledge structure into a teaching sequence.

## 7.1 Use a learning progression, not a table-of-contents sequence

A robust default sequence is:

1. **Orient** — What problem/question is this chapter solving?
2. **Activate prerequisites** — What must students already know?
3. **Motivate** — Why does the new concept matter?
4. **Build intuition** — What does it mean before formal notation?
5. **Formalize** — Definition, notation, assumptions.
6. **Show mechanism** — Derivation, algorithm, or mathematical relationship.
7. **Work an example** — Full example with reasoning exposed.
8. **Interpret** — What does the result mean statistically?
9. **Test boundaries** — Counterexample, failure mode, or assumption violation.
10. **Apply** — New problem or realistic use case.
11. **Retrieve** — Ask students to recall/apply without looking at the explanation.
12. **Summarize** — What should the student now be able to do?

Not every chapter requires all 12 stages, but major concepts should usually contain at least **motivation → concept → formalization → example → interpretation**.

## 7.2 Slide ordering rules

Prioritize:

### Dependency before application
Teach a concept before relying on it.

### Intuition before dense formalism when appropriate
For unfamiliar statistical objects, establish what quantity is being discussed before presenting notation.

### Definition before derivation
Students should know exactly what an object means before following an algebraic derivation involving it.

### Derivation before interpretation of a derived formula
When the derivation is pedagogically necessary, do not show a final equation without explaining what each component represents.

### Example immediately after abstraction
After a difficult definition or theorem, use an example soon enough that students can map the abstract statement to a concrete case.

### Counterexample after conditions
When a theorem/result requires assumptions, demonstrate what can go wrong when an assumption fails.

### Retrieval before final summary
Ask learners to generate the idea or solve a small problem before revealing the recap.

## 7.3 Consulting concept translated into educational storyline

Consulting:

```text
Question → Answer → Evidence → Implications → Action
```

Education:

```text
Learning question → Core idea → Evidence/derivation → Example → Interpretation → Practice → Transfer
```

This is the central adaptation for the entire project.

### G2 checkpoint

Review:

- Is the ordering logically teachable?
- Are prerequisites respected?
- Does every major concept receive enough instructional treatment?
- Are there unnecessary historical/background digressions?
- Does the sequence balance intuition and mathematical rigor?
- Are examples placed immediately after concepts that need them?

**Stop for approval.**

---

# 8. G3 — Slide storyboard

The storyboard is the **most important review gate** because changes here are much cheaper than changes after slide production or narration.

## 8.1 Required storyboard fields

Create one row per slide:

| Slide | Section | Slide type | Teaching title | Learning objective | Primary message | Evidence / visual | Narration purpose | Prerequisite | Citation | Status |
|---:|---|---|---|---|---|---|---|---|---|---|
| 1 | Intro | Opening | Sampling variability is the bridge from observed samples to population inference | Explain why sampling distributions matter | Samples vary, so inference needs a model of that variation | Simple repeated-sampling illustration | Motivate chapter | None | Textbook Ch. X | REVIEW |
| 2 | Concept | Intuition | Repeated samples produce a distribution of statistics | Explain sampling distribution | A statistic varies across samples | Simulation animation | Build intuition | C01 | Textbook §X.X | REVIEW |
| 3 | Formalization | Definition | A sampling distribution describes the probability behavior of a statistic | State formal definition | Distinguish it from data distribution | Equation + annotated notation | Formalize | Slide 2 | Textbook §X.X | REVIEW |

## 8.2 Slide-type library

Use these instructional archetypes as defaults.

### A. Opening / motivation
Use when introducing a chapter or major section.

### B. Learning objectives
Use at chapter or major-section level rather than mechanically repeating objectives on every slide.

### C. Intuition / mental model
Use a diagram, simulation, analogy, or visual thought experiment.

### D. Definition
Use when exact terminology matters.

### E. Notation map
Use when several symbols are introduced together.

### F. Theorem / result
State the result, conditions, and interpretation.

### G. Derivation
Break a complex derivation into digestible stages.

### H. Worked example
Show the complete reasoning, not merely the answer.

### I. Partially completed example
Ask the learner to supply a missing step.

### J. Counterexample / misconception
Show what fails and why.

### K. Visualization
Use simulation, distribution plot, sampling diagram, geometry, or data display.

### L. Algorithm / procedure
Present a reusable sequence of steps.

### M. Interpretation
Translate mathematical output into statistical language.

### N. Comparison
Distinguish related concepts or methods.

### O. Practice / retrieval
Pose a short problem before revealing the answer.

### P. Summary / mental model
Compress the chapter into a small set of connected ideas.

### Q. Appendix / technical detail
Provide extra derivation, tables, assumptions, or examples.

## 8.3 Teaching-title rule

Titles should normally be **claims, questions, or pedagogically useful instructions**, not merely topic labels.

Weak:

> Central Limit Theorem

Better:

> The CLT explains why many sample means are approximately normal

Better when the conditions are central:

> With independent observations and finite variance, sample means become approximately normal as n grows

For a definition slide:

> A sampling distribution describes how a statistic varies across repeated samples

For a worked example:

> A sample mean can be standardized using its standard error

For a misconception slide:

> A small p-value does not measure the probability that the null hypothesis is true

## 8.4 One-message rule

Every slide must have:

1. one **primary learning claim**;
2. one dominant visual/structural treatment;
3. a small number of supporting details.

The rule permits complexity when the complexity is the lesson itself. For example, a theorem statement may contain multiple conditions, but they should jointly support one learning objective.

### G3 checkpoint

The reviewer should be able to read only the slide titles and understand the chapter's teaching storyline.

**Required review question:**

> “If I remove all body text and figures and read only the titles, does this sequence still teach a coherent story?”

If not, revise the titles/order before proceeding.

**Stop for approval.**

---

# 9. G4 — Slide specification

After the storyboard is approved, create the actual content specification for each slide.

## 9.1 Required slide-spec schema

```yaml
slide_id: S07
title: "A sampling distribution describes how a statistic varies across repeated samples"
slide_type: definition
learning_objective: "Define a sampling distribution and distinguish it from the distribution of raw observations."
primary_message: "The sampling distribution is a probability distribution over a statistic induced by repeated sampling."
body:
  - "Choose a statistic T(X1,...,Xn)."
  - "Imagine repeatedly drawing samples of size n."
  - "The resulting values of T form a distribution."
equation:
  latex: "T = T(X_1,\\ldots,X_n)"
  interpretation: "T is a random variable because the sample is random."
visual:
  type: "repeated-sampling diagram"
  description: "Population at left; four sample draws in the middle; one statistic from each sample; histogram of statistics at right."
  purpose: "Make the distinction between data distribution and sampling distribution visually explicit."
annotations:
  - "Highlight the statistic, not the individual observations."
source:
  textbook: "Chapter 5, Section 5.2"
  external: []
accessibility:
  alt_text: "Repeated samples from one population produce multiple values of a sample statistic, which form a sampling distribution."
narration_goal: "Explain the conceptual distinction and prepare students for the formal definition."

qa_flags:
  notation_checked: true
  source_checked: true
  visual_claim_checked: true
  equation_checked: true
```

## 9.2 Slide body rules

### Text should support narration, not duplicate it

The slide should contain:

- definitions
- equations
- essential labels
- concise interpretations
- key assumptions
- highlighted steps
- direct questions when appropriate

The narration can supply:

- transitions
- elaboration
- examples
- verbal interpretation
- explanation of why a step matters
- warnings about common mistakes

### Avoid “teleprompter slides”

Do not place the entire narration script on the slide unless the material itself is a reading passage or the wording is essential.

---

# 10. Statistics-specific content rules

## 10.1 Every mathematical object gets a job

When introducing notation, explicitly state:

- what the symbol denotes;
- whether it is fixed or random;
- whether it is a parameter, statistic, estimator, estimate, variable, or observed value;
- the population/sample context;
- the units when useful.

Example:

```text
μ = population mean (fixed but unknown parameter)
X̄ = sample mean (random statistic before observing the sample)
x̄ = observed value of the sample mean
```

## 10.2 Separate four layers

For important formulas, distinguish:

1. **Definition** — what the quantity is.
2. **Computation** — how it is calculated.
3. **Statistical meaning** — what it represents.
4. **Interpretation** — how to communicate the result in context.

Do not collapse these into one line when the distinction matters.

## 10.3 State assumptions close to the result they govern

Do not place important assumptions ten slides away from the theorem that needs them.

Use a compact structure:

> **Result**  
> Conditions: independent observations; finite variance; sufficiently large n  
> Interpretation: ...

## 10.4 Use worked examples strategically

For difficult procedural material, prefer:

```text
Worked example
    ↓
Partially worked example
    ↓
Independent practice
```

Worked examples are particularly useful when the task has multiple interacting steps and students are likely to experience high cognitive load. Statistics-specific evidence also supports worked-out examples in probability instruction. See Hadfield (2021).

## 10.5 Include counterexamples

A graduate statistics deck should frequently answer:

> “What would make this argument fail?”

Use counterexamples for:

- violated assumptions
- misleading interpretations
- confounded quantities
- pathological cases
- non-identifiability
- small-sample limitations
- inappropriate graphical interpretations

## 10.6 Favor interpretation over arithmetic when the arithmetic is routine

A slide should spend cognitive real estate on the statistical reasoning that is difficult, not merely display arithmetic that software can perform.

For example:

> “The estimated coefficient is 0.42”

is incomplete.

Prefer:

> “Holding the other predictors fixed, a one-unit increase in X is associated with a 0.42-unit increase in the conditional mean of Y.”

Then show the numerical computation as supporting evidence.

---

# 11. Figure and illustration rules

## 11.1 Every visual needs a teaching purpose

For every figure, specify:

> **What should the learner notice?**

If the answer is vague, redesign or remove the figure.

## 11.2 Recommended visual types

Use:

- statistical plots
- repeated-sampling simulations
- annotated probability distributions
- conceptual diagrams
- causal/path diagrams
- number lines
- geometry
- flowcharts
- algorithm diagrams
- tables when exact lookup matters
- equations with progressive highlighting

## 11.3 Use animation logic even in static specifications

For a narrated deck, describe progressive reveals when useful:

1. show the population;
2. show sample 1;
3. show sample 2;
4. show the statistic for each;
5. reveal the resulting sampling distribution.

If the final authoring tool cannot animate objects, create separate states or slides only when the instructional benefit warrants it.

## 11.4 Reproducibility rule

Whenever a figure is generated from data, record:

- data source;
- transformation;
- sample size;
- simulation seed if applicable;
- software/library used when relevant;
- important plotting parameters.

Do not invent empirical results.

Synthetic examples are permitted only when clearly labeled as synthetic or illustrative.

## 11.5 Accessibility

Every substantive visual should have concise alt text or an equivalent accessibility description.

Use color redundantly with:

- labels
- line types
- symbols
- direct annotation

Do not depend on color alone to distinguish statistical quantities.

---

# 12. Formatting and visual hierarchy standards

## 12.1 Recommended hierarchy

Each slide should generally have this visual priority:

```text
1. Teaching title
2. Dominant visual / equation / result
3. Key interpretation or annotation
4. Supporting explanation
5. Source / provenance
```

## 12.2 Layout system

Create a small library of reusable layouts rather than designing every slide from scratch.

Suggested layouts:

1. **Title + full-width exhibit**
2. **Title + left explanation / right exhibit**
3. **Title + three-part conceptual model**
4. **Title + equation + interpretation**
5. **Title + worked example steps**
6. **Title + comparison table**
7. **Title + question + reveal**
8. **Title + before/after**
9. **Title + process flow**
10. **Title + summary model**

The layout library should standardize alignment, margins, footer, source line, typography, and spacing—not dictate the content.

## 12.3 Typography

Recommended principles:

- Use one primary sans-serif family unless the institution specifies otherwise.
- Use a high-contrast hierarchy for title, section labels, body text, equations, and notes.
- Avoid long paragraphs on slides.
- Use consistent mathematical typesetting throughout.
- Do not shrink text to fit; split the slide instead.

## 12.4 Equations

Equations should be typeset cleanly and accompanied by verbal interpretation when the equation is pedagogically important.

Example:

```text
SE(X̄) = σ / √n

Interpretation:
The standard error decreases as sample size increases because averaging reduces sampling variability.
```

## 12.5 Source line

Every slide containing externally sourced or adapted material should have a compact source line.

Examples:

```text
Source: Textbook, Ch. 6 §6.3.
```

```text
Source: Adapted from Cleveland & McGill (1984); textbook Figure 7.2.
```

```text
Data: U.S. Census Bureau, 2025 ACS 1-year estimates; analysis by author.
```

The source line should identify provenance without becoming the visual focus of the slide.

---

# 13. G5 — Narration script generation

The narration is a separate deliverable, not merely copied slide text.

## 13.1 Narration objectives

The script should:

1. orient the learner;
2. explain what the slide is showing;
3. connect it to the previous slide;
4. explain the important reasoning;
5. emphasize interpretation;
6. flag misconceptions or assumptions where useful;
7. transition to the next idea.

## 13.2 Narration structure

A strong default pattern is:

```text
[Transition]
Connect to previous idea.

[Main explanation]
Explain the slide's core concept.

[Interpretation]
Translate the mathematics/figure into statistical meaning.

[Why it matters]
Explain the role in the larger chapter.

[Transition]
Set up the next slide.
```

## 13.3 Do not read the slide verbatim

Bad:

> “The standard error is sigma divided by the square root of n. The standard error decreases as sample size increases.”

Better:

> “This equation gives us the standard error of the sample mean. The important point is not only the formula but the relationship it reveals: because n appears under the square root in the denominator, larger samples produce less sampling variability. In other words, if we repeatedly drew larger samples, the resulting sample means would cluster more tightly around the population mean.”

## 13.4 Narration should name what the learner should look at

Use verbal pointers such as:

- “Notice the widening spread…”
- “Focus on the denominator…”
- “The key difference between these two distributions is…”
- “The shaded region represents…”

This is particularly important for data visualizations and diagrams.

## 13.5 Pronunciation / TTS rules

The narration script should be written for speech synthesis.

Use:

- complete spoken names for symbols when ambiguity exists;
- punctuation that supports natural pauses;
- short sentences for dense mathematics;
- explicit spoken transitions;
- “x-bar” or a configured pronunciation convention for symbols if the TTS system cannot reliably pronounce notation;
- consistent pronunciation of technical terms throughout the course.

Maintain a pronunciation glossary for terms such as:

```yaml
"heteroskedasticity": "..."
"likelihood": "..."
"chi-squared": "..."
"Cox proportional hazards": "..."
```

## 13.6 Narration timing

Estimate duration from word count and the configured TTS speech rate.

```text
estimated_seconds = word_count / words_per_second
```

Flag slides whose narration is materially longer or shorter than the target range.

### G5 checkpoint

Review a sample of scripts against the slides:

- Does the narration explain the visual?
- Does it add value beyond slide text?
- Is every equation interpreted?
- Is the language natural when spoken?
- Are there unsupported claims?
- Does the script prepare the transition to the next slide?

**Stop for approval.**

---

# 14. Retrieval and practice slides

Narrated asynchronous decks should not be purely passive.

## Recommended placement

After a major concept cluster, insert a short retrieval prompt.

Example:

### Slide title
> Which quantity has the smallest sampling variance?

### Slide body

```text
A. A sample mean based on n = 10
B. A sample mean based on n = 100
C. An individual observation
D. All are equal
```

### Narration

Ask the learner to pause before revealing the answer.

Then use a separate answer slide or progressive reveal:

> **Correct answer: B.** The variance of the sample mean decreases as n increases, holding the population variance fixed.

Retrieval practice has strong evidence for improving learning and retention, including applied educational settings. See Agarwal et al. (2021) and Carpenter et al. (2022).

Do not overuse questions. The goal is **meaningful retrieval**, not constant interruption.

---

# 15. Summary-slide design

A good section or chapter summary is not a compressed table of contents.

Use a **conceptual model**.

Example:

```text
Observed data
      ↓
Statistic
      ↓
Sampling distribution
      ↓
Standard error
      ↓
Reference distribution
      ↓
Inference
```

Then add one or two sentences explaining the causal/logical relationships.

A summary should answer:

> “What are the few ideas I should still remember a week from now?”

---

# 16. Appendix design

Create an appendix when it improves the main learning flow without sacrificing access to rigor.

Recommended appendix categories:

### A. Mathematical detail

- extended derivations
- proofs
- algebraic identities
- matrix notation

### B. Statistical detail

- assumptions
- asymptotic qualifications
- edge cases
- alternative estimators

### C. Data / simulation detail

- data dictionary
- simulation setup
- random seeds
- code snippets

### D. Reference figures

- alternative parameter settings
- additional distributions
- full-resolution versions of complex figures

### E. Terminology / notation

- notation table
- glossary

### F. Additional practice

- more examples
- answer sketches
- extension problems

The appendix should still be indexed from the main deck when relevant.

---

# 17. G6 — Quality assurance

Final QA should be systematic rather than impressionistic.

## 17.1 Content QA

Check:

- every substantive claim is supported by the textbook or a cited external source;
- no theorem has lost a condition;
- notation is consistent with the textbook;
- mathematical statements are correct;
- examples are numerically correct;
- axes and legends are correct;
- units are correct;
- interpretation matches the displayed result;
- causal language is not stronger than the evidence permits;
- synthetic data are clearly labeled.

## 17.2 Pedagogical QA

Check:

- every major concept has a learning objective;
- prerequisites appear before dependent concepts;
- difficult concepts have an intuition/example treatment;
- important assumptions are visible;
- worked examples expose reasoning;
- misconceptions/counterexamples appear where needed;
- students get retrieval opportunities;
- the final summary reconnects the chapter's concepts.

## 17.3 Visual QA

Check:

- title states the slide's teaching claim;
- one dominant message exists;
- visual hierarchy is obvious;
- text is readable at presentation distance;
- equations are legible;
- no chart contains unnecessary decoration;
- colors have meaning and remain interpretable without color;
- alignment and margins are consistent;
- source lines are present;
- figures have alt text.

## 17.4 Narration QA

Check:

- narration does not merely read the slide;
- narration references the visual explicitly;
- terminology is consistent;
- pronunciation is handled;
- sentence length is suitable for TTS;
- narration duration is within target range;
- transitions are coherent;
- no slide depends entirely on audio for essential information unless intentionally designed that way.

## 17.5 Standalone-readability test

For each slide ask:

> If the learner encounters this slide without audio, can they identify the topic, central claim, important evidence/equation, and immediate interpretation?

The answer should normally be yes.

---

# 18. Recommended output package for each chapter

The process should generate the following files/artifacts.

```text
chapter_05/
│
├── 00_input/
│   ├── chapter_source.md
│   └── chapter_assets/
│
├── 01_analysis/
│   ├── concept_map.md
│   ├── prerequisite_map.md
│   ├── misconceptions.md
│   └── learning_objectives.md
│
├── 02_architecture/
│   └── learning_sequence.md
│
├── 03_storyboard/
│   └── slide_storyboard.md
│
├── 04_specs/
│   ├── slide_001.md
│   ├── slide_002.md
│   ├── ...
│   └── slide_manifest.yaml
│
├── 05_narration/
│   ├── slide_001_script.md
│   ├── slide_002_script.md
│   ├── ...
│   └── narration_manifest.yaml
│
├── 06_assets/
│   ├── figures/
│   ├── diagrams/
│   ├── simulations/
│   └── data/
│
├── 07_qa/
│   ├── content_qa.md
│   ├── pedagogical_qa.md
│   ├── visual_qa.md
│   ├── narration_qa.md
│   └── final_approval.md
│
└── chapter_05_deck.md
```

---

# 19. Complete example: from textbook concept to slides

Suppose the chapter contains the Central Limit Theorem.

## G1 analysis

```markdown
Core concept: CLT
Prerequisites:
- random variables
- expectation
- variance
- independence

Misconceptions:
- CLT does not say the raw data become normal
- CLT concerns the distribution of an estimator/statistic
- the approximation depends on assumptions and sample size
```

## G2 sequence

```text
1. Why inference needs sampling distributions
2. Repeated samples create variability in X̄
3. Sampling distribution of X̄
4. Standard error of X̄
5. CLT intuition through simulation
6. CLT formal statement
7. Conditions and limitations
8. Worked numerical example
9. Counterexample / skewed population with small n
10. Practical interpretation
11. Retrieval question
12. Chapter summary
```

## G3 storyboard examples

### Slide 1
**Title:** Sample means vary, so inference needs a model of that variation

**Purpose:** Motivate the problem.

### Slide 2
**Title:** Repeated samples produce many different values of the sample mean

**Visual:** Four or more samples from a common population, showing their means.

### Slide 3
**Title:** The sampling distribution describes the probability behavior of X-bar

**Visual:** Histogram of simulated sample means.

### Slide 4
**Title:** Larger samples make the distribution of X-bar narrower

**Visual:** Two sampling distributions for n = 10 and n = 100.

### Slide 5
**Title:** The CLT explains why many sample-mean distributions become approximately normal

**Visual:** Simulation showing increasing n.

### Slide 6
**Title:** The CLT requires assumptions that determine whether the approximation is trustworthy

**Visual:** Conditions checklist.

### Slide 7
**Title:** The standardized sample mean approaches a standard normal distribution

**Equation:**

```text
(X̄ − μ) / (σ / √n)  →  N(0,1)
```

### Slide 8
**Title:** A worked example turns the CLT into a probability calculation

**Visual:** Annotated calculation.

### Slide 9
**Title:** A small sample from a highly skewed population can make the normal approximation poor

**Visual:** Counterexample simulation.

### Slide 10
**Title:** The CLT is a statement about a statistic's sampling distribution, not the raw data

**Visual:** Side-by-side raw-data distribution vs sampling distribution.

### Slide 11
**Title:** Can you identify which distribution the CLT is describing?

**Interaction:** Multiple-choice retrieval question.

### Slide 12
**Title:** The CLT connects sampling variability, standard error, and normal approximation

**Visual:** Concept map.

---

# 20. Recommended review interface

When asking the human reviewer to approve a gate, show the material in the smallest useful review unit.

## For G1
Show:

- chapter concept map;
- learning objectives;
- prerequisite map;
- misconceptions.

## For G2
Show:

- section sequence;
- rationale for ordering;
- proposed number of slides by section;
- placement of worked examples and retrieval questions.

## For G3
Show a storyboard table containing:

- slide number;
- teaching title;
- slide type;
- objective;
- visual concept;
- one-sentence message.

This should be the primary place for major structural revisions.

## For G4
Show several representative complete slide specifications before generating the full set:

- one concept slide;
- one equation/derivation slide;
- one worked-example slide;
- one data visualization slide;
- one retrieval slide.

After those exemplars establish the style, complete the remainder.

## For G5
Show a sample of narration scripts:

- one conceptual slide;
- one equation slide;
- one figure-heavy slide;
- one worked example;
- one retrieval slide.

Then generate the remaining scripts after approval.

---

# 21. Change-control rules

To keep the process efficient across many chapters, classify changes.

### Local change
Affects one slide only.

Example:

> “Change the wording of slide 18.”

Update only the relevant slide and narration.

### Structural change
Affects ordering or dependencies.

Example:

> “Move the assumptions before the theorem.”

Revisit G2/G3 and identify downstream slides whose dependencies changed.

### Global style change
Affects all chapters.

Example:

> “Use a smaller title and add a persistent section marker.”

Apply through the master design system rather than manually patching individual slides.

### Content-authority change
Occurs when the textbook itself is updated or corrected.

Re-run content validation from G1 onward for affected concepts.

---

# 22. Rules for AI-generated content

Because the workflow uses AI, adopt explicit anti-hallucination rules.

## Rule 1 — Source authority

The textbook chapter is the primary source. AI may reorganize and explain the material but must not silently alter substantive claims.

## Rule 2 — External material

If external sources are permitted, mark every externally introduced claim, data source, example, or figure.

## Rule 3 — No fabricated evidence

Never invent:

- citations
- empirical results
- data values presented as real
- theorem conditions
- numerical examples attributed to a source
- quotations

## Rule 4 — Numerical verification

All nontrivial numerical examples should be independently recalculated.

## Rule 5 — Equation verification

Equations should be checked for:

- algebraic correctness;
- symbol consistency;
- dimensional/units consistency;
- assumptions;
- transcription errors.

## Rule 6 — Preserve uncertainty

When the textbook states a limitation or qualification, retain it unless the reviewer explicitly approves its removal.

## Rule 7 — Distinguish explanation from source text

Do not create quotations unless the source text is explicitly available and quoted accurately. Paraphrases should not be presented as quotations.

---

# 23. Master prompt / operating specification

The following can be used as the core instruction for an AI system implementing the process.

```text
You are creating a graduate-level statistics textbook chapter presentation.

AUTHORITATIVE SOURCE:
The supplied textbook chapter is the primary authority for substantive content,
notation, definitions, assumptions, formulas, and examples.

OBJECTIVE:
Transform the chapter into a narrated instructional deck that is rigorous,
visually clear, pedagogically sequenced, and suitable for graduate students.

DESIGN PRINCIPLES:
1. Use answer-first information architecture where appropriate, but translate
   the consulting model into learning progression rather than executive decision support.
2. Use one primary teachable idea per slide.
3. Use teaching titles that state the slide's learning claim.
4. Make the dominant evidence, equation, or visual immediately apparent.
5. Preserve mathematical rigor and all materially important assumptions.
6. Use intuition, formal definition, derivation, worked example, interpretation,
   counterexample, and retrieval practice as needed.
7. Use visuals only when they improve understanding.
8. Cite textbook sections and all external sources on the relevant slide.
9. Make each slide understandable without relying entirely on narration.
10. Use an appendix for technical depth that would disrupt the main learning path.
11. Never invent sources, data, numerical results, or mathematical claims.

PROCESS:
G0 Input and style contract
G1 Chapter analysis -> STOP FOR APPROVAL
G2 Learning architecture -> STOP FOR APPROVAL
G3 Slide storyboard -> STOP FOR APPROVAL
G4 Slide specifications -> STOP FOR APPROVAL
G5 Narration scripts -> STOP FOR APPROVAL
G6 QA and final package -> STOP FOR APPROVAL

At each gate, present only the information needed for effective review and
explicitly identify assumptions, unresolved questions, and items requiring
subject-matter verification.

Do not proceed to the next gate unless the human explicitly approves the current gate.

G3 TITLE RULE:
Prefer a sentence stating what the learner should understand over a topic label.

G4 VISUAL RULE:
For every visual state what the learner should notice and why the visual is needed.

G5 NARRATION RULE:
Narration should explain and interpret the slide, not simply read its text.

FINAL QA:
Check content accuracy, mathematical correctness, notation, assumptions,
visual integrity, accessibility, source attribution, narrative coherence,
and TTS suitability.
```

---

# 24. Minimal slide record template

Use this template for each slide after storyboard approval.

```markdown
# Slide SXX — <Teaching title>

**Section:** <section>

**Slide type:** <type>

**Learning objective:** <what the learner should be able to understand/do>

**Primary message:** <one sentence>

## On-slide content

- <bullet / definition / key statement>
- <bullet / equation / interpretation>

## Equation

```latex
<LaTeX>
```

## Figure / illustration

**Type:** <chart / diagram / simulation / table / etc.>

**What the learner should notice:** <specific visual takeaway>

**Construction notes:** <data, labels, animation/reveal, annotations>

**Accessibility / alt text:** <description>

## Source

<textbook or external source>

## Narration goal

<what the audio must accomplish>

## Narration script

<approved script>

## QA

- [ ] Content checked
- [ ] Equation checked
- [ ] Figure checked
- [ ] Source checked
- [ ] Accessibility checked
- [ ] Narration checked
```

---

# 25. Final acceptance checklist

A chapter deck is ready for production/rendering when all statements below are true.

## Story

- [ ] The slide-title sequence tells a coherent learning story.
- [ ] Each major concept has adequate instructional treatment.
- [ ] Prerequisites appear before dependent concepts.
- [ ] The chapter closes with an integrated conceptual summary.

## Content

- [ ] Textbook claims are preserved accurately.
- [ ] Mathematical notation is consistent.
- [ ] Assumptions are explicit.
- [ ] Examples are correct.
- [ ] Interpretations are statistically correct.
- [ ] Limitations and counterexamples are included where important.

## Pedagogy

- [ ] Difficult concepts have intuitive support.
- [ ] Worked examples are used where procedural load is high.
- [ ] Retrieval practice occurs after major concept clusters.
- [ ] Students are asked to interpret, not merely calculate.
- [ ] The deck does not overwhelm students with unnecessary detail.

## Design

- [ ] Each slide has one dominant teaching message.
- [ ] Titles communicate claims rather than merely labels.
- [ ] Visuals have explicit instructional purposes.
- [ ] Layouts and typography are consistent.
- [ ] Sources appear on relevant slides.
- [ ] All substantive visuals have accessibility descriptions.

## Narration

- [ ] Narration adds explanation beyond slide text.
- [ ] Every major visual is verbally interpreted.
- [ ] Scripts sound natural when spoken.
- [ ] Technical terms have stable pronunciation.
- [ ] Slide-to-slide transitions are clear.

## QA

- [ ] Numerical and mathematical checks passed.
- [ ] Source/provenance checks passed.
- [ ] Final human approval received.

---

# 26. Recommended default production sequence

For repeated use across textbook chapters, the most efficient implementation is:

```text
FULL CHAPTER
    ↓
G0 Input + style contract
    ↓ APPROVE
G1 Concept map + prerequisites + misconceptions
    ↓ APPROVE
G2 Learning sequence
    ↓ APPROVE
G3 Full storyboard
    ↓ APPROVE
G4 Five representative slide specs
    ↓ APPROVE STYLE
G4 Full slide specs
    ↓ APPROVE CONTENT
G5 Representative narration scripts
    ↓ APPROVE VOICE
G5 Full narration
    ↓ APPROVE
G6 Automated + human QA
    ↓ APPROVE
FINAL SLIDE DECK + AUDIO PACKAGE
```

The two most important interventions are **G1/G2**, because a flawed knowledge architecture produces a flawed deck, and **G3**, because structural changes are substantially cheaper before detailed slide production and narration.

---

# 27. Practical default ratios for a graduate statistics deck

These are starting points, not universal laws.

For a typical 45–60 minute narrated chapter:

- **10–15%** orientation, motivation, and objectives
- **45–55%** core concepts, definitions, and explanations
- **15–25%** worked examples and applications
- **5–10%** retrieval/practice
- **5–10%** synthesis and summary
- technical appendix as needed

For a mathematically intensive chapter, increase the proportion of worked derivations and interpretation slides rather than simply shrinking more content onto fewer slides.

---

# 28. Guiding test for every slide

Before approving any slide, ask five questions:

1. **What should the learner understand after this slide?**
2. **Where is that idea visible?**
3. **Why is this visual or equation the right representation?**
4. **What does the narration add?**
5. **What misconception or misunderstanding could still remain?**

If the team cannot answer these questions crisply, the slide is not ready.

---

# 29. One-sentence design standard

> **Every slide should make one important statistical idea easier to see, understand, remember, or apply—and the slide order should make those ideas accumulate into a coherent mental model.**
