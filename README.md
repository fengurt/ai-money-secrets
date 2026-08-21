# 🤖 AI Money Secrets

> AI 赚钱/副业/变现情报精选，持续更新中。

[![采集数据量](https://img.shields.io/badge/secrets-55+-green.svg)](secrets.json)
[![更新日期](https://img.shields.io/badge/last_update-2026--08--21-blue.svg)](daily/2026-08-21.md)

---

## 📂 目录

- [数据文件](secrets.json) — 结构化情报（JSON格式）
- [日报汇总](daily/) — 每日采集记录

---

## 🔍 收录标准

- 来源可信（少数派、知乎、CSDN、腾讯云、博客园等）
- 具有实操价值（真实案例 + 可落地方法）
- 涵盖多种变现路径（独立开发、副业接单、内容创作、AI工具等）

---

## 📊 数据概览

| 维度 | 数据 |
|------|------|
| 总条目 | 55+ |
| 主要来源 | 少数派、知乎、CSDN、腾讯云、博客园、YouTube |
| 变现方向 | 独立开发、副业接单、AI工具、Logo设计、内容创作、数字人等 |

---

## 🚀 快速使用

```bash
# 查看所有数据
cat secrets.json | jq '.[].title'

# 按来源筛选
cat secrets.json | jq '.[] | select(.source == "知乎")'

# 按关键词搜索
cat secrets.json | jq '.[] | select(.title | test("独立开发"))'
```

---

## 📅 更新日志

- **2026-08-21** 搜索5组关键词，新增0条（均已收录），累计55条
- [历史日报 →](daily/)
