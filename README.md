# Research Paper Writing Skills

[简体中文](README.zh-CN.md)

An Agent Skill for scientific writing, literature reviews, manuscript review, and peer-review responses. It helps researchers build a coherent argument, check what each source supports, and edit Chinese or English papers while preserving the scope of their claims.

## What you can do

| Task | What the skill produces |
| --- | --- |
| Frame a paper or diagnose a draft | A research question, reverse outline, proposed section order, or map of claims and evidence |
| Search and synthesize literature | A comparison across studies and a record of source access, evidential limits, and missing evidence |
| Draft, restructure, or polish a manuscript | A section organized around its research question, or a scoped edit that preserves the scientific meaning |
| Review a manuscript | A prioritized report on argument, methods, inference, and figure or table consistency |
| Prepare a revision and response | Point-by-point answers tied to the manuscript changes and verification of the requested files |

## Use the skill

Copy the entire [skill folder](skills/evidence-grounded-paper-writing/) into a skills directory recognized by your agent. It follows the [Agent Skills specification](https://agentskills.io/specification). The folder includes the entry point and five guides. In an agent without skill discovery, provide the [entry point](skills/evidence-grounded-paper-writing/SKILL.md) and the relevant guide as instructions.

Try one of these requests with your own material or with the [fictional practice cases](examples/).

- “Read this draft and build a reverse outline. Show which paragraphs answer the research question and propose a better order. Give me the plan first.”
- “Compare what these papers establish about the same outcome. State which designs are comparable and which claims still need the original figures or methods.”
- “Draft a point-by-point response from the submitted and revised files. Locate each reported change in the revised manuscript.”

Each task can be used on its own. For a revision, specify the baseline and any style sample. For a narrow edit, specify the passage and the scientific details that must be preserved. The workflow works with text supplied in chat as well as manuscripts in Markdown, LaTeX, or Word when supported by the agent.

## Methods and design references

- Paragraph-level argument diagnosis draws on [George Mason University's reverse outlining guide](https://writingcenter.gmu.edu/writing-resources/writing-as-process/reverse-outlining). The literature workflow implements question-led synthesis, a practice described in [Purdue OWL's literature review guide](https://owl.purdue.edu/owl/research_and_citation/conducting_research/writing_a_literature_review.html).
- The claim-to-evidence check and separate task entry points were informed by [SNL-UCSB's paper-writing workflow](https://github.com/SNL-UCSB/paper-writing-skill/blob/main/story_mode.md) and the [Academic Research Skills architecture](https://github.com/Imbad0202/academic-research-skills/blob/main/docs/ARCHITECTURE.md).
- [SANRA](https://pmc.ncbi.nlm.nih.gov/articles/PMC6434870/) provides perspectives on the appraisal of narrative reviews. For applicable study designs and venues, check the reporting guidance for the actual article type, such as [PRISMA 2020](https://www.prisma-statement.org/prisma-2020) or guidance indexed by the [EQUATOR Network](https://www.equator-network.org/).
