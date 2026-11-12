# OpenCode Go 模型指南

> 非官方整理，数据以 OpenCode 官方为准。

一个**单文件、零依赖**的 OpenCode Go 套餐模型参考页：32 个模型的能力分、请求额度、token 单价、上下文、输出上限、模态支持、性价比与避坑建议。

## 在线访问

https://hector404dada.github.io/opencode-go-model-guide/

## 特点

- **深浅双主题**：首次访问跟随系统，右上角切换并记住选择
- **iOS 风格毛玻璃**：半透明玻璃面板 + 环境光晕，数据仍然清晰可读
- **桌面表格 / 手机卡片**：宽屏显示完整对比表，窄屏自动切换为模型卡片
- **可排序、可筛选**：桌面点击表头，手机使用排序下拉
- **完整键盘支持**：跳过导航、表头排序、焦点环、`aria-sort`
- **打印友好**：A4 横向、浅色、表头重复、行不跨页
- **单文件**：所有 CSS / JS / SVG 内联，双击 `index.html` 即可打开

## 数据来源

- 本机 `opencode api get /api/model` 官方元数据
- OpenCode 官方 Go 文档额度表：<https://opencode.ai/v2/docs/console/go>
- 公开基准：AA Intelligence / AA Agentic 2026-10、BenchLM、Vals AI、官方发布博客

数据核对日期：**2026-11-12**。

## 本地打开

直接双击 `index.html`，不需要本地服务器，也不需要安装依赖。

## 说明

- 本页为非官方整理，模型清单、价格和额度可能随官方调整而变化。
- 新模型的能力分为公开基准综合估值，仅供参考。
- OpenCode 与 OpenCode logo 是 Anomaly 的商标；本页仅用于信息整理。
