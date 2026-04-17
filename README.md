# Claude Opus 4.7 技術報告

> 2026/04/16 Anthropic 發布 Claude Opus 4.7 旗艦模型重點整理與 4.6 → 4.7 遷移指南。

## 內容

- 編碼 Benchmark 全面對比（SWE-bench / Terminal-Bench / CursorBench / GPQA / Finance Agent / BigLaw）
- 視覺能力 3× 提升（3.75 MP 影像輸入、視覺準確度 98.5%）
- 新 `xhigh` 推理等級說明
- Claude Code 新功能（`/ultrareview`、Auto Mode、Task Budgets）
- Agentic 能力提升（多步驟工作流 +15%、工具錯誤 1/3）
- 指令遵循與 Tokenizer 改動
- 安全性與 Cyber Verification Program
- 從 4.6 遷移到 4.7 的 5 步檢查清單

## 結構

```
.
├── index.html              # 單檔報告網頁
├── images/                 # 9 張教學組圖
└── .github/workflows/      # GitHub Pages 部署 workflow
```

## 本地預覽

```bash
python3 -m http.server 8765
# → open http://127.0.0.1:8765/
```

## 部署

推送到 `main` 自動觸發 GitHub Actions 部署到 Pages。

## 資料來源

- [Claude Opus 4.7 官方發布公告](https://www.anthropic.com/news/claude-opus-4-7)
- [Vellum AI · Benchmarks Explained](https://www.vellum.ai/blog/claude-opus-4-7-benchmarks-explained)
- [VentureBeat · 業界評析](https://venturebeat.com/technology/anthropic-releases-claude-opus-4-7-narrowly-retaking-lead-for-most-powerful-generally-available-llm)

---

© 2026 · 內部技術分享用途
