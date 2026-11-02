---
layout: single
title: "模型评测与可靠部署"
permalink: /portfolio/model-evaluation-deployment/
author_profile: true
---

<div class="project-card__visual project-card__visual--evaluation" aria-hidden="true">
  <span>EVAL / SERVE</span>
  <strong>Reliable AI Systems</strong>
</div>

<p class="project-lead">围绕真实业务场景建立从数据治理、离线评测到在线服务和运行监控的工程闭环，使模型结果可比较、版本可回归、服务可观测、异常可降级。</p>

<div class="project-facts">
  <div class="project-fact"><span>关注重点</span><strong>质量与性能双重验证</strong></div>
  <div class="project-fact"><span>服务框架</span><strong>SGLang / vLLM / FastAPI</strong></div>
  <div class="project-fact"><span>工程目标</span><strong>稳定、可追溯、可恢复</strong></div>
</div>

## 项目目标

模型在实验集上取得较高指标并不代表可以直接进入生产环境。真实业务还会面对输入分布变化、长文本截断、并发压力、依赖服务故障和模型版本迭代。本项目将评测、部署与运维视为同一条质量链路，减少“离线效果好、线上不可用”的落差。

## 我的工作

- 建立训练集、验证集、固定回归集、难例集和线上抽样集的分层数据结构。
- 统一指标口径，结合总体指标、类别指标、错误类型和业务风险进行多维评估。
- 设计模型版本对比、提示词回归、上下文长度和边界输入测试。
- 对吞吐、首 token 延迟、端到端时延、并发能力和显存占用进行性能压测。
- 建设健康检查、日志审计、输入输出追踪、服务自启动和故障恢复机制。
- 为模型不可用、低置信度和业务规则冲突场景设计降级与人工确认路径。

## 工程闭环

<div class="project-process" aria-label="模型工程闭环">
  <div class="project-process__step"><span>01</span><strong>数据与标签治理</strong></div>
  <div class="project-process__step"><span>02</span><strong>离线质量评测</strong></div>
  <div class="project-process__step"><span>03</span><strong>性能与压力测试</strong></div>
  <div class="project-process__step"><span>04</span><strong>灰度发布与回归</strong></div>
  <div class="project-process__step"><span>05</span><strong>监控、降级与复盘</strong></div>
</div>

## 实践重点

<ul class="project-output-list">
  <li><strong>可比较：</strong>固定模型、数据、提示词和统计方式，避免不同实验之间指标失真。</li>
  <li><strong>可追溯：</strong>记录模型版本、请求参数、输入输出、异常原因和评测结果。</li>
  <li><strong>可恢复：</strong>通过健康检查、自动拉起、超时重试和备选路径降低单点故障影响。</li>
  <li><strong>可演进：</strong>将线上错误转化为难例和回归样本，持续推动数据与模型迭代。</li>
</ul>

## 技术栈

<div class="project-tags">
  <span>PyTorch</span><span>Transformers</span><span>SGLang</span><span>vLLM</span><span>FastAPI</span><span>CUDA</span><span>NCCL</span><span>Regression Testing</span>
</div>

<a class="project-back-link" href="/research/">← 返回研究项目</a>
