---
# try also 'default' to start simple
theme: seriph
# random image from a curated Unsplash collection by Anthony
# like them? see https://unsplash.com/collections/94734566/slidev
background: https://cover.sli.dev
# some information about your slides, markdown enabled
title: 篇章级事件抽取和关系推理研究
info: |
  ## 上海大学研究生硕士论文
  
  reading at [thesis](http://58.199.167.85:51876/read/gqtkbdqhybrq#9a302a)

# apply any unocss classes to the current slide
class: text-center
# https://sli.dev/custom/highlighters.html
highlighter: shiki
# https://sli.dev/guide/drawing
drawings:
  persist: false
# slide transition: https://sli.dev/guide/animations#slide-transitions
transition: slide-left
# enable MDC Syntax: https://sli.dev/guide/syntax#mdc-syntax
mdc: true
---

# 篇章级事件抽取和关系推理研究
## Research on Document-level Event Extraction and Relational Reasoning


<div class="pt-12">
  <span @click="$slidev.nav.next" class="px-2 py-1 rounded cursor-pointer" hover="bg-white bg-opacity-10">
    指导导师: 刘炜
  </span>
</div>

<div class="pt-6">
  <span @click="$slidev.nav.next" class="px-2 rounded cursor-pointer" hover="bg-white bg-opacity-10">
    庞张灯
  </span>
</div>



<!--
The last comment block of each slide will be treated as slide notes. It will be visible and editable in Presenter Mode along with the slide. [Read more in the docs](https://sli.dev/guide/syntax.html#notes)
-->

---
level: 2
---

# 目录

<Toc  minDepth="1" maxDepth="1"></Toc>


---
transition: fade-out
---

# 研究背景

篇章级文本在互联网上存在更为广泛，以及事件信息在各个领域和下游场景具有广泛的应用价值。

- 新闻领域，热点事件早发现和定位
- 金融领域，结构化事件信息可以供金融行业运营者和分析师使用
- 医疗领域，电子临床病历，快速、自动地从病历中提取有价值的信息
- 法律领域，法律事件提取可以提取重要角色、法律成分和事实，协助相关人员快速审查和澄清案件材料。

<br>
<br>


<!--
在新闻领域，网络时代舆论的产生和传播具有很高的时效性，热点事件\cite{9671529_news_application}越早发现和定位，政府就能越快掌握民众的需求并制定相应的政策和指引，从而减少社会不稳定因素。在海洋突发事件领域，可以根据当前事件推测可能发生的后续事件，以便及时采取措施避免进一步的损失。在金融领域 \cite{yang-etal-2018-dcfee}，结构化事件信息可以供金融行业运营者和分析师使用，也可以用于风控、问答、知识图谱构建等下游任务。在医疗领域\cite{LIU201834-drug}，电子临床病历变得越来越普遍，使得快速、自动地从病历中提取有价值的信息成为可能。自动化技术可以从临床医学数据中提取对科学研究有用的信息，提高研究人员的生产力并加速药物开发的进步。在法律领域\cite{feng-etal-2022-legal}，法律事件提取可以提取重要角色、法律成分和事实，直接协助相关人员快速审查和澄清案件材料。
-->


---
transition: slide-up
level: 1
---

# 研究内容关系图

<div align="center" class="pt-2">
 <img src="/thesis-framework.jpg" width = "65%" height = "65%" alt="图片名称" align=center />
</div>

---
layout: default
---

# 基于检索增强的篇章级事件检测

<div align="center" class="pt-2">
 <img src="/event-detection-framework.jpg" width = "65%" height = "65%" alt="event-detection" align=center />
</div>

---
layout: default
---

# 基于代码生成的篇章级事件论元抽取

<div align="center" class="pt-2">
 <img src="/event-argument-framework.jpg" width = "50%" height = "50%" alt="event-argument" align=center />
</div>

---
layout: default
---

# 基于图神经网络的篇章级事件关系分类

<div align="center" class="pt-2">
 <img src="/event-relation-framework.jpg" width = "65%" height = "65%" alt="event-relation" align=center />
</div>

---
layout: end
class: text-center
level: 2
---

# 请各位领导批评指正


