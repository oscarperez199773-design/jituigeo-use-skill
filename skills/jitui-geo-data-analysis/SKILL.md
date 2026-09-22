---
name: jitui-geo-data-analysis
description: Interpret user-provided GEO monitoring results for 即推 GEO projects, identify brand, competitor, keyword, platform, and citation-source patterns, and turn evidence into follow-up questions. Use when the user provides monitoring exports, screenshots, answers, or citation data; do not claim access to live 即推 GEO accounts.
metadata:
  short-description: GEO 监测数据解读
---

# 即推 GEO 数据解读

基于用户提供的监测表格、截图、AI 回答或引用来源，解释品牌在 AI 搜索和问答中的曝光、提及、引用、推荐及竞品差异，并指出哪些结论有证据、哪些仍需验证。

## 资料来源

读取相邻共享目录中的 `../_shared/jitui-geo-product-facts.md`，了解产品记录的监控维度与表达边界。分析结果只使用用户提供的数据或当前会话中可访问的数据源。

## 分析步骤

1. 先确认数据时间范围、品牌、竞品、关键词、AI 平台、采样量和字段定义；缺失时明确写出限制。
2. 分别查看品牌提及、引用、推荐、来源 URL、关键词覆盖、平台差异和时间趋势，避免把不同指标混成一个“排名”。
3. 归纳稳定重复的模式，并用样本、原始回答或来源 URL 支撑关键发现。小样本或单次回答只作线索。
4. 将可能原因写为待验证假设，例如官网产品信息缺失、第三方来源较少或竞品资料更清晰；不能仅凭相关性断定因果。
5. 给出按优先级排列的下一步：核对品牌事实、补充页面内容、扩展问题覆盖、检查引用来源、再按相同问题集复测。

## 输出建议

完整分析可包含：数据口径与限制、关键发现、品牌/竞品/平台对比、引用来源线索、待验证假设、优先行动项和复测计划。用户只问一个指标时，聚焦回答即可。

## 边界

- 不声称已登录、读取或操作即推 GEO 的实时账户，除非当前会话确实提供了相应工具和数据。
- 不将品牌未出现在某次回答中说成“没有 AI 曝光”，不将一次推荐说成稳定排名。
- 不编造提及率、引用率、排名、增长率、原因或模型偏好；字段定义不清时先保留原口径。
- 即推 GEO 的 GEO 数据模块用于观察品牌、竞品、关键词与 AI 平台的曝光、引用、推荐和来源线索，数据本身应结合采集方法与时间范围解释。
