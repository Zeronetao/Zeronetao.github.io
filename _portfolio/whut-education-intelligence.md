---
layout: single
title: "理工育人智链"
permalink: /portfolio/whut-education-intelligence/
author_profile: true
---

<figure class="project-hero">
  <img src="/images/whut-education-intelligence.jpg" alt="理工育人智链项目视觉图">
</figure>

<p class="project-lead">面向学生成长支持与重点学生分层帮扶，项目汇聚学业、消费、网络行为及校园活动等多源数据，建设学生画像、数据分析和模型评估能力，为辅导员与管理人员提供可解释、可复核的辅助依据。</p>

<div class="project-facts">
  <div class="project-fact"><span>我的角色</span><strong>数据挖掘核心成员</strong></div>
  <div class="project-fact"><span>核心方向</span><strong>行为分析与模型评估</strong></div>
  <div class="project-fact"><span>项目产出</span><strong>3 份技术报告 · 3 篇论文</strong></div>
</div>

## 项目背景与需求

学校重点学生群体帮扶覆盖心理关怀、经济困难、学业困难、网络成瘾、重大疾病、就业困难、支持系统薄弱及其他特殊困难等情形。专项工作要求依据困难类型和严重程度进行四级关注管理，形成“摸排、评估、干预、反馈、动态调整”的持续闭环，并为重点学生建立可追溯的帮扶档案。

传统学生工作数据分散在不同业务系统中，更多呈现单项结果，难以从学生成长过程和多维行为中发现隐藏关联。项目需要解决以下问题：

- **多源数据治理：** 梳理学生基本信息、学业表现、消费记录、网络日志和校园活动等数据，核验字段、口径、规模与可用性。
- **学生画像与关联分析：** 从数据中识别行为变化与变量关系，为个性化发展支持和重点群体摸排提供证据。
- **分层帮扶支持：** 将四级关注规则、动态升降级机制和帮扶过程记录转化为可执行、可追踪的业务能力。
- **模型有效性评估：** 在标签稀缺、类别不平衡和特征缺失的条件下检验模型边界，防止将相关性或模型分数直接当作个体结论。

## 我的工作

作为项目数据挖掘核心成员，我参与数据底座分析、行为特征建模、关联规则挖掘和预警模型评估，并将实验过程、结论与局限沉淀为技术报告和论文。

- **数据资产审计：** 对接 ClickHouse 数据库，开发 Python 脚本完成数据库与表资产盘点、字段核验、数据规模统计、质量检查和模型所需特征可用性分析。
- **网络行为分析：** 从网络日志中构造在线时长、上下行流量、数据包和访问频次等特征，结合先验规则与随机森林识别夜间上网行为，并对精度、召回率和数据分布变化进行对比分析。
- **消费与关联挖掘：** 分析食堂午晚餐消费分布，使用支持度、置信度和提升度研究经济情况与学业、心理状态之间的关系，以统计证据校验业务假设。
- **预警模型评估：** 围绕学籍、成绩、家庭、心理关怀与夜宿等特征评估学生安全预警模型，比较随机森林、One-Class SVM、Isolation Forest 与 VAE 在类别不平衡场景下的表现。
- **失效原因分析：** 通过误判与漏判样本分析发现，部分重点样本缺少可区分特征，模型难以可靠识别；据此提出补充数据维度、完善标签和保留人工研判的改进建议。
- **研究成果沉淀：** 项目累计形成 3 份技术报告和 3 篇论文，其中我个人完成 1 份技术报告和 1 篇论文。

## 分析与评估路径

<div class="project-process" aria-label="育人智链数据分析与模型评估路径">
  <div class="project-process__step"><span>01</span><strong>数据资产盘点</strong></div>
  <div class="project-process__step"><span>02</span><strong>特征与规则设计</strong></div>
  <div class="project-process__step"><span>03</span><strong>统计与关联分析</strong></div>
  <div class="project-process__step"><span>04</span><strong>模型训练与评估</strong></div>
  <div class="project-process__step"><span>05</span><strong>误差分析与迭代</strong></div>
</div>

项目同时采用业务规则、统计分析、监督学习与异常检测方法。对网络行为等有明确业务条件的任务，先验规则提供稳定基线，机器学习模型补充复杂模式识别；对极少数样本场景，则通过异常检测验证可行性，并明确精度与召回率之间的代价。

## 项目成果

<ul class="project-output-list">
  <li>围绕学生端、辅导员端和教师端梳理 <strong>149 项</strong>功能；阶段汇报时已形成 124 项功能说明，覆盖率达到 <strong>83%</strong>。</li>
  <li>完成网络日志、食堂消费、经济与学业及心理关联等专题分析，为学生画像和业务规则设计提供量化依据。</li>
  <li>完成学生安全预警模型的多算法对比，识别类别极不平衡、有效特征不足和数据分布变化带来的模型风险。</li>
  <li>项目累计产出 <strong>3 份技术报告、3 篇论文</strong>；个人产出 <strong>1 份技术报告、1 篇论文</strong>。</li>
</ul>

## 应用边界

学生画像与预警结果仅用于辅助发现需要进一步关注的线索，不代替辅导员、心理教师及相关部门的专业判断。项目强调最小必要数据使用、分级授权、结果可解释和人工复核，避免依据单一行为或群体统计结果对学生作出自动化定性。

## 技术栈

<div class="project-tags">
  <span>Python</span><span>ClickHouse</span><span>Pandas</span><span>Random Forest</span><span>Association Rules</span><span>One-Class SVM</span><span>Isolation Forest</span><span>VAE</span>
</div>

<a class="project-back-link" href="/research/">← 返回研究项目</a>
