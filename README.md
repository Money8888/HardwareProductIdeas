# HardwareProductIdeas · 国内外开源硬件创意精选

一个由 AI 自动维护的开源硬件创意精选集。

## 这是什么

每天自动抓取国内外主流开源硬件资讯源，经 AI 判别、翻译、分类后，精选出最具创意的产品与项目，整理为中文日报：

- **邮件推送**：每日精选以 HTML 邮件形式推送到订阅邮箱（邮件内图片可点击跳转原文）
- **公众号草稿**：同步生成微信公众号图文草稿（草稿内链接不可跳转，为平台机制，故草稿版为纯图文）
- **本仓库**：归档每日发邮件的原文内容（HTML 正文 + 结构化 JSON 数据），供回看与检索

## 内容分类

每日精选固定按以下 5 类整理，顺序固定、**行业趋势恒为最后一个模块**：

| 分类 | 说明 |
|------|------|
| 💡 立创开源广场 | 立创开源广场新工程 |
| 🛠️ 开发板·模块 | 开发板/模块/芯片 |
| 🔬 前沿创新 | 前沿硬件/制造创新 |
| 📟 智能硬件 | 智能硬件/消费创意 |
| 🌐 行业趋势 | 行业趋势速览 |

## 资讯来源

Hackaday / CNX Software / Adafruit / Seeed / Make / Tindie / Pimoroni / Phoronix / 立创开源广场 / Solidot / IT之家 / 树莓派实验室 / 极客岛 等公开资讯源。

## 目录结构

```
README.md                    本说明
data/
  digest_YYYYMMDD.md         当日邮件正文（HTML 渲染为 Markdown，GitHub 可直接渲染展示）
  digest_YYYYMMDD.json       当日精选结构化数据（中文标题/描述/分类/图片/来源/原文链接）
```

> 说明：`digest_YYYYMMDD.md` 为当日发送邮件的正文内容（由邮件 HTML 渲染而来），`digest_YYYYMMDD.json` 为对应的结构化数据；本仓库只归档发邮件所需文件，不含 HTML 源码与任何脚本、中间产物。

## 提交方式

- 提交身份：`Money8888 <43008386+Money8888@users.noreply.github.com>`（GitHub noreply）
- 凭据：GitHub Personal Access Token（经本地 store 凭据文件，走 HTTPS）
- 代理：本地 7890 代理监听时自动启用（访问 GitHub 需要）

## 使用说明

- 仓库内容仅供学习参考，版权归原作者所有
- 英文资讯均已由 AI 翻译为中文，可能存在误差