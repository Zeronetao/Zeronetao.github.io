---
layout: single
title: "湖北港口统一对外服务平台"
permalink: /portfolio/hubei-port-platform/
author_profile: true
---

<figure class="project-hero">
  <img src="/images/hubei-port-platform.png" alt="湖北港口统一对外服务平台登录页面">
</figure>

<p class="project-lead">面向船公司、船代、货代、车队和港区等多类主体，项目以统一服务入口连接业务办理、EDI 报文交换、数据治理与智能应用，减少多系统切换、重复填报和人工流转。</p>

<div class="project-facts">
  <div class="project-fact"><span>我的角色</span><strong>大模型组组长</strong></div>
  <div class="project-fact"><span>核心方向</span><strong>领域微调与多模态智能</strong></div>
  <div class="project-fact"><span>交付形态</span><strong>私有化模型服务与业务工作流</strong></div>
</div>

## 项目背景与需求

湖北港口集团集装箱业务覆盖多个港区，外部客户与内部 TOS、箱管、场站、理货等系统之间需要持续交换船期、装卸船计划、放箱令、受理计划和箱动态等信息。原有服务入口和传输渠道较为分散，部分流程依赖邮件、表格和人工录入；不同港区在接口、报文、码表和数据口径上也存在差异。

项目重点解决五类问题：

- 统一客户登录、业务办理、资料提交、状态查询与结果反馈入口。
- 打通客户、平台与港区生产系统之间的 EDI、API、邮件和文件交换链路。
- 统一字段、码表、报文与业务状态，沉淀可追溯的集装箱专题数据。
- 将单证识别、文本提取、知识问答和报文转换嵌入实际业务流程。
- 通过权限、规则校验、人工复核和日志审计约束智能能力的使用边界。

## 我的角色与任务

作为大模型组组长，我负责从模型选型、数据治理到服务上线的完整技术链路，并协调模型能力与平台业务模块对接。

- **领域模型建设：** 完成训练数据清洗、标签复核、领域微调、多维评测和难例迭代，形成面向物流业务的分类与信息抽取能力。
- **多模态识别：** 建设 PDF、图片和复杂表格解析流程，结合 OCR、视觉语言模型与目标检测，支持单证字段、箱号、箱型、铅封号和车牌等信息提取。
- **推理服务集成：** 基于 SGLang 部署模型服务，通过 Dify、MCP 和领域 API 编排业务工作流，支撑上下文推理、工具调用与结构化输出。
- **评测与上线：** 建立固定测试集、难例集、回归评测和性能压测流程，对模型版本和业务规则进行联合验证。
- **生产保障：** 完成服务监控、日志审计、异常降级、故障恢复和自启动策略，保证私有化环境中的持续可用性。

## 技术路径

<div class="project-process" aria-label="项目技术路径">
  <div class="project-process__step"><span>01</span><strong>多渠道业务资料接入</strong></div>
  <div class="project-process__step"><span>02</span><strong>OCR 与多模态理解</strong></div>
  <div class="project-process__step"><span>03</span><strong>字段标准化与规则校验</strong></div>
  <div class="project-process__step"><span>04</span><strong>Dify 与 MCP 工作流编排</strong></div>
  <div class="project-process__step"><span>05</span><strong>业务回执与全链路审计</strong></div>
</div>

模型负责理解非标内容和生成候选结构，规则引擎负责必填项、码表、状态与权限校验。对低置信度或关键业务字段保留人工复核入口，避免将模型输出直接作为生产指令。

## 核心成果

<ul class="project-output-list">
  <li>完成 Qwen 系列语言模型、视觉语言模型、Embedding 与 Reranker 的私有化部署及统一服务接入。</li>
  <li>放箱令分类在多套测试集上的最高 F1 达到 <strong>98.78%</strong>，经难例迭代后生产准确率提升至 <strong>99.2%</strong>。</li>
  <li>形成覆盖物流单证、复杂表格和集装箱视觉信息的多模态解析能力，并输出业务可消费的结构化 JSON。</li>
  <li>建立模型、数据、规则、接口和监控协同的工程闭环，使智能能力能够在权限与审计边界内稳定运行。</li>
</ul>

## 技术栈

<div class="project-tags">
  <span>Qwen</span><span>Transformers</span><span>PEFT / LoRA</span><span>SGLang</span><span>PaddleOCR</span><span>YOLO</span><span>Dify</span><span>MCP</span><span>FastAPI</span><span>CUDA</span>
</div>

<a class="project-back-link" href="/research/">← 返回研究项目</a>
