---
name: stroke-pharmacology-literature-review
description: >
  Help write narrative reviews, systematic reviews, and evidence syntheses in stroke pharmacology
  (ischemic stroke / hemorrhagic stroke). Topics include neuroprotection, anti-inflammation,
  BBB protection, oxidative stress, cell death pathways (apoptosis/pyroptosis/ferroptosis),
  PK/PD and brain penetration, preclinical models (e.g., MCAO), and clinical trials.
  支持中文触发：脑卒中/缺血性卒中/出血性卒中/神经保护/药理机制/动物实验(MCAO)/临床试验/系统综述/Meta分析/综述写作。
---

# Stroke Pharmacology Literature Review Skill（脑卒中药理综述技能）

## What this skill is for
This skill provides a structured workflow to plan, search, screen, extract, synthesize, and write:
- Narrative review（叙述性综述）
- PRISMA-style systematic review（系统综述）
- Meta-analysis（如数据适合；不强制）

## When to activate (trigger examples)
Use this skill when the user asks for things like:
- “写一篇缺血性脑卒中的神经保护药物综述”
- “总结 NLRP3/Nrf2/microglia/BBB 相关药理证据”
- “整理 MCAO 动物模型里某药物的给药窗与结局指标”
- “汇总某类卒中药物临床试验结果与失败原因”
- “帮我做系统综述/Meta：检索式、筛选标准、证据表、偏倚评估”

## Information to request (if missing)
If not provided, infer reasonably and proceed, but prefer clarifying from context:
1) Stroke type: ischemic / ICH / SAH
2) Intervention: drug / compound / target / pathway
3) Evidence scope: preclinical only / clinical only / both
4) Review type: narrative / systematic / meta (if feasible)
5) Time window & language limits (e.g., 2000–2026; English+Chinese)
6) Key outcomes: infarct volume, neuro score, edema, BBB integrity; NIHSS/mRS, sICH, mortality, etc.

## Outputs (deliverables)
- A review outline tailored to stroke pharmacology (mechanism + evidence strength + translation issues)
- Search strategy (PubMed/Embase/Web of Science) + trial registry check plan
- Screening criteria (inclusion/exclusion) + PRISMA-style flow description
- Evidence extraction tables (preclinical and clinical separated)
- Risk-of-bias / reporting completeness checklist summary
- Draft text section-by-section with citation placeholders

## Writing rules
- Separate preclinical vs clinical claims clearly; do not “upgrade” animal results to clinical efficacy.
- Prefer cautious academic language; avoid absolute claims.
- Every key factual claim should have a citation placeholder.
- Always discuss: therapeutic time window, BBB/brain exposure, safety (e.g., hemorrhagic transformation), and translatability.

## Files in this skill
- WORKFLOW.md  — step-by-step workflow (7 phases)
- DOMAINS.md   — stroke pharmacology taxonomy & keyword map
- TEMPLATES.md — copy/paste templates (project brief, search, extraction tables)

## Default structure for the paper (editable)
1. Introduction (clinical burden + unmet needs)
2. Pathophysiology & therapeutic targets (mechanism map)
3. Preclinical evidence (by target/strategy) + key study table
4. Clinical evidence (trials/registries) + key trial table
5. Translational gaps (time window, PK/PD, BBB, endpoints, model validity)
6. Future directions
7. Conclusion
8. References
