================================================================================
TEMPLATE A — Project Brief（项目简报）
================================================================================
Title（题目）:
Stroke type（卒中类型: AIS/ICH/SAH）:
Stage（阶段: hyperacute/acute/subacute/chronic）:
Intervention（干预: 药物/化合物/靶点/通路）:
Comparator（对照: vehicle/standard care/other drug）:
Evidence scope（证据范围: preclinical/clinical/both）:
Review type（综述类型: narrative/systematic/meta if feasible）:
Time range（时间范围）:
Language（语言）:
Key outcomes（关键结局）:
  - Preclinical:
  - Clinical:
Key keywords（关键词）:
Constraints（限制/偏好）:
Notes（备注）:

================================================================================
TEMPLATE B — PICO/PECO（用于系统综述）
================================================================================
P / Population（人群/动物/模型）:
I / Exposure or Intervention（暴露/干预）:
C / Comparator（对照）:
O / Outcomes（结局）:
Study types（研究类型: RCT/observational/animal/in vitro）:
Exclusion criteria（排除标准）:

================================================================================
TEMPLATE C — Search Strategy（检索策略）
================================================================================
Databases（数据库）:
  - PubMed/MEDLINE:
  - Embase:
  - Web of Science/Scopus (optional):

Trial registries（注册库，如含临床证据）:
  - ClinicalTrials.gov:
  - (optional) WHO ICTRP:

Concept blocks（概念块）:
1) Stroke terms（卒中相关）:
2) Intervention/Target terms（干预/靶点相关）:
3) Model terms（模型相关，如做预临床）:
4) Outcomes terms（结局相关，可选）:

PubMed draft query（示例结构）:
( stroke terms ) AND ( intervention/target terms ) AND ( model terms OR clinical terms )

Filters（筛选条件）:
  - Year range:
  - Language:
  - Article types:
Notes（备注：是否排除 review；是否纳入 conference 等）:

================================================================================
TEMPLATE D — PubMed 检索式骨架（填词即可用）
================================================================================
# Block 1: Stroke
("stroke"[Title/Abstract] OR "ischemic stroke"[Title/Abstract] OR "cerebral ischemia"[Title/Abstract]
 OR "intracerebral hemorrhage"[Title/Abstract] OR "subarachnoid hemorrhage"[Title/Abstract]
 OR "middle cerebral artery occlusion"[Title/Abstract] OR MCAO[Title/Abstract])

# Block 2: Target/Drug (fill your terms)
AND
("YOUR_DRUG"[Title/Abstract] OR "YOUR_TARGET"[Title/Abstract] OR "YOUR_PATHWAY"[Title/Abstract])

# Block 3: Preclinical model (optional)
AND
(animal[Title/Abstract] OR mice[Title/Abstract] OR rat[Title/Abstract] OR OGD[Title/Abstract]
 OR "oxygen-glucose deprivation"[Title/Abstract])

# Optional: Limit by year/language in PubMed UI

================================================================================
TEMPLATE E — Screening Log（筛选记录/排除原因）
================================================================================
Screening stages:
1) Title/Abstract screening
2) Full-text screening

Common exclusion reasons（排除原因分类）:
- Not stroke / wrong disease
- Not pharmacological intervention (e.g., surgery/device only)
- Wrong model / wrong population
- No relevant outcomes
- Not original research (review/editorial)
- Insufficient data (for meta, if applicable)
- Duplicate / overlapping cohort

================================================================================
TEMPLATE F — Preclinical Evidence Extraction Table（预临床抽取表）
================================================================================
说明：一篇文献一行；如果一个研究有多个剂量/时间窗，可以拆成多行。

| Study | Year | Species/strain | Model (tMCAO/pMCAO/ICH etc.) | Sex/age | Comorbidity | Random/Blind | Dose/route/freq | Time-to-tx window | n/group | Primary outcomes | Key results | Mechanism markers | Safety notes |
|---|---:|---|---|---|---|---|---|---|---:|---|---|---|---|

================================================================================
TEMPLATE G — Clinical Evidence / Trial Table（临床证据/试验表）
================================================================================
| Trial/Study | Registry ID | Phase | Design | N | Population | Time window | Co-therapy (tPA/EVT) | Intervention vs control | Primary endpoint | Main result | Safety (sICH/AE) | Notes/subgroups |
|---|---|---|---|---:|---|---|---|---|---|---|---|---|

================================================================================
TEMPLATE H — Mechanism → Evidence Map（机制-证据对照表）
================================================================================
| Mechanism node | Target/pathway | Drug examples | Preclinical strength | Clinical strength | Main translation risk |
|---|---|---|---|---|---|
| e.g., neuroinflammation | NLRP3 inflammasome | MCC950... | moderate | weak | time window / safety / exposure |

Evidence strength suggestion（强度建议）:
- none / weak / moderate / strong（可在论文中自定义判据）

================================================================================
TEMPLATE I — PK/PD & BBB Penetration Sheet（药代/药效与脑穿透）
================================================================================
| Compound | Dose/route | Species | Plasma exposure (Cmax/AUC) | Brain exposure | BBB evidence type | PD marker | Notes (metabolites, transporters) |
|---|---|---|---|---|---|---|---|

================================================================================
TEMPLATE J — Risk-of-Bias Quick Sheet（偏倚/质量快速表）
================================================================================
Preclinical（预临床）
| Study | Randomization | Blinding | Allocation concealment | Sample size rationale | Temp control | Exclusions reported | Conflicts/funding |
|---|---|---|---|---|---|---|---|

Clinical（临床）
| Trial | Registered | Randomization described | Blinding | Attrition handled | Selective reporting risk | CONSORT items ok | Funding/conflicts |
|---|---|---|---|---|---|---|---|

================================================================================
TEMPLATE K — Translational Gap Paragraph Skeleton（转化差距段落骨架）
================================================================================
Although preclinical findings suggest that [drug/target] improves [key outcome] via [mechanism],
translation to clinical efficacy remains uncertain. Key gaps include:
(i) alignment of the time-to-treatment window with real-world stroke workflows,
(ii) confirmation of adequate brain exposure/BBB penetration at tolerated doses,
(iii) safety risks such as hemorrhagic transformation or systemic adverse effects,
and (iv) endpoint comparability between animal models and clinical outcomes.
Future studies should prioritize [two concrete recommendations], ideally with [design features:
randomization/blinding, clinically relevant time windows, standardized functional outcomes].

================================================================================
TEMPLATE L — Section Outline（成文大纲模板）
================================================================================
1. Introduction（疾病负担 + 未满足需求）
2. Pathophysiology & Target Rationale（机制链条 + 靶点合理性）
3. Pharmacology Overview（化合物/类别，作用机制，PK/PD，BBB）
4. Preclinical Evidence（按策略或靶点分节；配预临床表）
5. Clinical Evidence（按试验/人群/时间窗；配临床表）
6. Translational Challenges（时间窗、暴露、模型有效性、终点、安全性）
7. Future Directions（模型、联合治疗、临床试验设计）
8. Conclusion
9. References
