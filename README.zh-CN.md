# 科研论文写作、审查与返修

[English](README.md)

这项技能适用于科研论文写作、文献综述、稿件自审和逐点回复审稿意见。它围绕两个问题开展工作：文章需要论证什么，现有证据能把论证推进到哪一步。支持中英文论文，可从选题和提纲开始，也可以只核对引文、审查一张表或润色一段。

## 能做什么

| 任务 | 主要产物 |
| --- | --- |
| 构思与结构诊断 | 研究问题、逆向提纲、章节调整方案，或论点与证据对应表 |
| 文献检索与综合 | 围绕同一问题的跨研究比较，标明原文核验程度、适用范围与缺失资料 |
| 起草、重组与润色 | 按科学问题展开的章节，或保留原有科学含义的局部改稿 |
| 稿件审查 | 按影响排序的问题清单，注明位置、依据和可行改法 |
| 返修与交付 | 与实际修改相对应的逐点回复，以及所需交付文件的核验 |

## 如何使用

把整个[技能目录](skills/evidence-grounded-paper-writing/)放到所用助手能够识别的技能位置。目录包含一个入口和五份按任务选读的指南，遵循 [Agent Skills 规范](https://agentskills.io/specification)。如果助手无法识别技能目录，可以直接提供[入口](skills/evidence-grounded-paper-writing/SKILL.md)和本次任务对应的指南。

可以用自己的稿件，也可以先用[虚构练习案例](examples/)试运行。

- “按段落提取这篇综述实际在论证的内容，找出断裂处，并给出旧结构与新结构的对照。先给方案。”
- “比较这些文章在什么条件下得出一致结果。请注明哪些可以直接比较，哪些结论还要核查原文的方法或图表。”
- “根据投稿底稿和修订稿逐点写回复信，逐条标明修改后的实际位置。”

返修前可指定投稿底稿、工作稿及作为风格参考的样稿。局部润色时，直接给出要改的段落和必须保留的科学细节。可在对话文本中使用，也可在助手支持的情况下处理 Markdown、LaTeX 或 Word 文件。

## 方法来源

- 用逆向提纲提取每段实际写出的观点，再重组论证。对多篇文献，围绕可比较的问题综合证据。参见[乔治梅森大学的逆向提纲指南](https://writingcenter.gmu.edu/writing-resources/writing-as-process/reverse-outlining)和[普渡大学的文献综述指南](https://owl.purdue.edu/owl/research_and_citation/conducting_research/writing_a_literature_review.html)。
- 论点与证据的对应检查、按任务加载指南的设计，参考 [SNL-UCSB 的论文写作流程](https://github.com/SNL-UCSB/paper-writing-skill/blob/main/story_mode.md)和 [Academic Research Skills 的架构](https://github.com/Imbad0202/academic-research-skills/blob/main/docs/ARCHITECTURE.md)。
- [SANRA](https://pmc.ncbi.nlm.nih.gov/articles/PMC6434870/)提供叙述性综述的审读视角。需要核对报告规范时，根据实际研究设计与投稿要求选择适用指南，例如 [PRISMA 2020](https://www.prisma-statement.org/prisma-2020)或 [EQUATOR Network](https://www.equator-network.org/)收录的规范。
