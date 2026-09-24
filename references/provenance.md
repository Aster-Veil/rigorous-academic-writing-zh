# 设计来源

本文件供 skill 维护和来源核对使用，不属于普通写作任务的运行规范。外部材料用于形成候选问题类型；最终规则以事实保护、证据边界、学术规范和语境判断为准。

## 一、通用文本问题与来源核验

- [Wikipedia: Signs of AI writing，永久修订版 1370524124](https://en.wikipedia.org/w/index.php?title=Wikipedia:Signs_of_AI_writing&oldid=1370524124)
- [Wikipedia: WikiProject AI Cleanup，永久修订版 1370354867](https://en.wikipedia.org/w/index.php?title=Wikipedia:WikiProject_AI_Cleanup&oldid=1370354867)

这些页面支持把宣传性评价、模糊归因、浅层总结、编辑痕迹、引用错配和机械格式作为复核线索，同时强调单一风格特征不能证明作者身份或文本来源。

## 二、中文与学术写作候选规则

- [op7418/humanizer-zh](https://github.com/op7418/humanizer-zh)
- [AIScientists-Dev/academic-humanizer](https://github.com/AIScientists-Dev/academic-humanizer)
- [petergyang/no-ai-slop](https://github.com/petergyang/no-ai-slop)
- [cangtianhuang/humanizer-academic-zh](https://github.com/cangtianhuang/humanizer-academic-zh)
- [henmuc/codex-academic-humanizer](https://github.com/henmuc/codex-academic-humanizer)
- [larashero3-dotcom/lieflat-less-ai-tone](https://github.com/larashero3-dotcom/lieflat-less-ai-tone)

相关材料为中文翻译腔、术语稳定、概念标签、强结论、章节语体、引用保护和最小修改提供候选检查项。

其中 `lieflat-less-ai-tone` 提供中文人类文本与多模型生成文本的候选风格特征对照，用于区分统计差异与可执行写作规则。相关结果只用于排除或弱化缺乏独立写作质量依据的表面形式规则，不作为作者身份判断依据。

## 三、作者风格与节奏检查

- [Imbad0202/academic-research-skills](https://github.com/Imbad0202/academic-research-skills)
- [academic-paper draft writer](https://github.com/Imbad0202/academic-research-skills/blob/main/academic-paper/agents/draft_writer_agent.md)
- [academic-research-skills-codex](https://github.com/Imbad0202/academic-research-skills-codex)

相关材料为 Style Calibration、直接进入、句长与段长节奏检查提供设计线索。数值阈值在本 skill 中作为导航参数，不作为自动改写命令。

## 四、维护原则

来源记录仅保留可公开检索的材料。私人交流、内部简报、未公开课件及原稿中的身份、文件名和项目线索不进入参考文件；提炼后的通用方法可作为技能规则保留，不冒称为公开文献结论。

来源文件只回答规则来自何处；运行规范回答当前如何工作。新增来源时，先判断它是否带来新的行为约束，再决定是否修改 `SKILL.md` 或 operational references。

每条通用规则设置一个主要定义位置。其他 reference 只有在文稿类型、审校阶段或执行方式产生新的行为差异时才作具体化说明，不重复完整规则；维护时优先修改主要定义位置，并检查引用它的文件是否仍然一致。

## 五、GitHub 学术写作 Skill 对比

- [GitHub 学术撰写 Skill 对比（2026-08-29）](github-academic-writing-skills-2026-08-29.md)

本次对比支持四项维护决定：先用回归夹具修复已观察到的脚本误报；以正文外状态区分已独立核验、材料内支持、待核验、缺材料和冲突；把引用的存在与书目信息、命题支持、范围与定位作为按需核验；保持当前单 skill 和渐进 reference 路由，不引入多代理论文生产线或全量 claim ID。

## 六、学术标题与章节层级

- [学术论文与研究报告标题层级的修订依据（2026-08-29）](academic-heading-revision-research-2026-08-29.md)

该研究支持把“标题有 AI 痕迹”转译为并列堆叠、父子复述、颗粒度不齐、导航信息不足和计划—实施状态冲突等可审计问题。运行规则采用“标题—章节接口审计”：脚本只定位候选，语义审计根据章节功能、证据状态、专业术语和目标规范决定是否修改；不设置固定长度、连接词禁令或自动改名规则。

## 七、去防御性写作方法整合（2026-09-18）

本次读取以下固定版本，按当前技能的学术证据要求独立改写方法，未照搬其规则或示例：

- [Kiterlin/anti-defensive-writing：SKILL.md](https://github.com/Kiterlin/anti-defensive-writing/blob/bda84b2ffbac66f539010b50653c202baf637d53/SKILL.md)。吸收先表达主张、辨认句子功能、用明确条件处理含混措辞、围绕中心任务重组段落的方法。其 [引言示例](https://github.com/Kiterlin/anti-defensive-writing/blob/bda84b2ffbac66f539010b50653c202baf637d53/examples/academic-introduction.md) 的改写引入原文未给出的平台数量、14% 降幅和事件研究设计，不能当作等义改写模板。
- [Adkid-Zephyr/anti-defensive-writing-Skill：中文技能](https://github.com/Adkid-Zephyr/anti-defensive-writing-Skill/blob/102c8b21acf5eda3a0aef3d9779a65db646c8980/skills/anti-defensive-writing/SKILL.md)。吸收按研究问题与证据组织论文、明确贡献、让实验承担论证职责、避免把局部结果扩大为整体判断的方法。不采纳只围绕优势、不说输、按结果更换有利评价维度或删除削弱主线实验的指令；相关不利结果和预设评价口径仍须完整报告。

主入口保留写作方向与交付验收；表达参考集中定义限定分类、段落重组和工作视角转换；证据参考负责边界安置、评价口径与状态保护；论文结构参考负责贡献与实验的论证作用。文档审计引用表达规则，不重复完整处置流程。新增行为样例检验主张收缩、真实概念对照、独立阅读边界、工作视角转换及不利结果，不采用禁词或语气强度指标。

## 八、科学推理与章节功能（2026-09-22）

来源：[deathcats4/scientific-manuscript-editor，固定版本 04c22d1](https://github.com/deathcats4/scientific-manuscript-editor/tree/04c22d13af48f6d05443541aed862fca71e14412)。本轮在审阅主文件和参考规范后，按本技能既有结构提炼整合，未复制其文件体系。

- `manuscript-reasoning.md` 与 `scientific-integrity.md`：在证据参考中明确必要推理的显化，以及多类证据共同支持与并列回答的区别。
- `reference-learning.md`：在材料入口区分事实、引用、术语、论证和风格用途；不因提供了材料就自动赋予正文论证角色。
- `discussion.md`：在讨论部分明确综合应产生新的认识，已有结论可作为输入，不重复整条论证。
- `introduction.md` 与 `results.md`：限定研究空白、文献冲突及不显著结果的解释依据。

当前稿优先、跨章一致性与按需检查沿用既有规则；不增加逐项审批、固定段落模板或材料用途登记表。

## 九、标点与中英文混排（2026-09-22）

- [Cambridge English Grammar Today：Punctuation](https://dictionary.cambridge.org/grammar/british-grammar/punctuation)：核对英文逗号与定语从句、分号、冒号、引号和括号的功能。区分语法规则与体例选择，不将一般英语示例扩展为科技排版标准。
- [北卡罗来纳大学教堂山分校写作中心：Fragments and Run-ons](https://writingcenter.unc.edu/tips-and-tools/fragments-and-run-ons/)：核对独立分句、逗号拼接及通过句号、分号或适当连词修正句界的方法。
- [W3C《中文排版需求》](https://www.w3.org/TR/clreq/)：核对标点类别、符号形态、中西文混排与间距处理。所读版本标为 2026-09-01 的 Group Note Draft，作为公开设计参考，不视为强制规范，也不据其转述声称已直接核验 GB/T 15834—2011 原文。

据此在中文表达参考中加入初稿与终校共用的标点检查，按句法、语义和目标体例处理；条件安置、引文保护和避免全局误替换沿用本技能的语义保护原则。不设置标点频率指标，也不把某一种英美或地区体例规定为通用规则。

## 十、论文题名与章节标题（2026-09-22）

本次直接核对以下公开作者指南：

- [Springer Nature：Titles, Abstracts & Keywords](https://www.springernature.com/gp/authors/campaigns/writing-a-manuscript/titles-abstracts-keywords)：支持准确描述研究主题、保留可检索词、简洁表达，以及比较候选后精炼题名。
- [PLOS ONE：Submission Guidelines — Title](https://journals.plos.org/plosone/s/submission-guidelines#loc-title)：支持具体、描述性、简洁、可理解的题名及减少专业缩写；临床试验、系统综述和元分析在副标题中标明研究设计是该刊的明确要求，应用到其他文稿时须核对目标规范。
- [Nature：Formatting Guide — Titles](https://www.nature.com/nature/for-authors/formatting-guide)：支持兼顾检索信息与领域外读者的理解。其长度、缩写和标点限制属于该刊体例，不推广为中文学位论文通则。

论文结构参考集中定义题名撰写与回查；因果强度、成果状态和范围保护沿用本技能的证据原则。章节标题沿用第六节的修订依据，将共用规则从报告参考移至文档建模与审计参考，覆盖提纲、初稿和审校，并区分并列分类小节与承担不同论证阶段的章节。论文与报告均引用同一处规则，不要求局部标题任务建立全文模型。
