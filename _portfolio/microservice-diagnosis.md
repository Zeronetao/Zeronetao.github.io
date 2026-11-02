---
layout: single
title: "动态微服务根因分析"
permalink: /portfolio/microservice-diagnosis/
author_profile: true
---

<div class="project-card__visual project-card__visual--diagnosis" aria-hidden="true">
  <span>MRC / KLD</span>
  <strong>Dynamic Microservice Diagnosis</strong>
</div>

<p class="project-lead">面向服务拓扑、运行负载和故障模式持续变化的微服务系统，研究如何联合利用指标、日志、调用关系等多源可观测数据，实现细粒度故障归因与根因定位。</p>

<div class="project-facts">
  <div class="project-fact"><span>项目类型</span><strong>科研项目</strong></div>
  <div class="project-fact"><span>研究问题</span><strong>动态环境下的故障诊断</strong></div>
  <div class="project-fact"><span>当前产出</span><strong>MRC 与 KLD 两项工作</strong></div>
</div>

## 问题背景

微服务系统中的故障往往跨越多个服务与观测模态。拓扑变化、日志分布漂移和异常传播会削弱静态诊断方法的稳定性，仅依赖单一指标也难以解释复杂故障链路。项目聚焦两个问题：如何让不同模态共同支持细粒度归因，以及如何利用动态特征和日志语义提升持续变化环境中的诊断能力。

## 我的工作

- 梳理动态微服务诊断的任务定义、数据组织方式与评测协议。
- 研究多模态协同优化机制，使指标、日志和调用关系在诊断过程中互相补充。
- 设计日志感知的联合学习方法，刻画运行状态变化与故障特征之间的联系。
- 建立基线复现、消融实验、鲁棒性分析和错误案例复盘流程。
- 将实验结果整理为可复现的研究记录，并推进论文写作与投稿。

## 研究路径

<div class="project-process" aria-label="研究路径">
  <div class="project-process__step"><span>01</span><strong>多源可观测数据对齐</strong></div>
  <div class="project-process__step"><span>02</span><strong>动态状态与拓扑建模</strong></div>
  <div class="project-process__step"><span>03</span><strong>跨模态联合学习</strong></div>
  <div class="project-process__step"><span>04</span><strong>细粒度诊断归因</strong></div>
  <div class="project-process__step"><span>05</span><strong>鲁棒性与误差分析</strong></div>
</div>

## 研究产出

- **MRC**：Multimodal Fine-Grained Diagnostic Attribution via Collaborative Optimization，FSE 2027 在投。
- **KLD**：Kinetic Log-Aware Joint Learning for Dynamic Microservice Diagnosis，ICLR 2027 在投。

## 关键词

<div class="project-tags">
  <span>Microservices</span><span>Root Cause Analysis</span><span>Multimodal Learning</span><span>Log Mining</span><span>Robustness</span>
</div>

<a class="project-back-link" href="/research/">← 返回研究项目</a>
