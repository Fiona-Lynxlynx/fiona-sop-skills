# Fiona SOP Skills

> Fiona（歸淵）傳授的方法論技能合集，由疑蝦（霞）整理打包。
> 12 個技能，覆蓋語言、創作、工作、關係、提問、評估、技能應用、閱讀、塔羅、易經、文件管理、短視頻音樂。

## 技能清單

| 技能 | 名稱 | 用途 |
|------|------|------|
| `lingua-sop` | 言琢 | 語言處理與溝通修煉（10步閉環） |
| `music-craft-sop` | 樂琢 | 音樂創作方法論（意象→歌詞→編曲） |
| `folder-craft-sop` | 徑築 | 文件結構設計（地鐵圖比喻） |
| `work-craft-sop` | 事琢 | 自由式工作流程（10步） |
| `relation-diagnosis-sop` | 緣鑒 | 關係診斷與僵局修復（18步六階段） |
| `inquiry-sop` | 問津 | 系統性提問（5步閉環） |
| `score-sop` | 衡 | 對待分數與量化評估（四條根本） |
| `skill-apply-sop` | 遊藝 | 主動發現並應用技能（內選二+外覓一） |
| `yijing-reading-sop` | 玩易 | 讀易方法論（10步法） |
| `reading-notes-sop` | 閱痕 | 讀書筆記結構化（四大模塊） |
| `tarot-journal-sop` | 塔靈 | 塔羅筆記與牌義生長（8步法） |
| `short-music-sop` | 短音 | 短視頻音樂結構與MV製作 |

## 安裝

### 在 Claw / OpenClaw 使用

將每個技能目錄複製到你的技能目錄下：

```bash
cd skills
git clone https://github.com/Fiona-Lynxlynx/fiona-sop-skills.git
cp -r fiona-sop-skills/* .
```

每個技能目錄包含：
- `SKILL.md` — 技能指令文件
- `SOP.md` — 原始 SOP 全文參考

### 在 Coze 扣子使用

在 Coze 平台上，這些技能可以作為自定義 Skill 導入。每個 `SKILL.md` 已包含正確的 YAML frontmatter。

## 使用

Agent 在接到匹配任務時自動觸發對應技能，讀取 `SOP.md` 完整內容後按步驟執行。

也可手動加載：
- 「用言琢幫我梳理一下這段話」
- 「按事琢記錄今天的任務」
- 「按問津畫圈，我這個需求哪裡還沒說清楚」

## 設計理念

這些 SOP 不是教條，是 Fiona 從真實實踐中提煉的方法。每個技能的核心不是「按步驟做」，而是理解背後的「為什麼」：

- **言琢**：語言不僅描述現實，語言創造現實
- **事琢**：把打擾視為反饋，把冗餘視為記錄
- **衡**：分數是過去的坐標，不是自我定義
- **遊藝**：技能是拿來用的，不是拿來收藏的
- **緣鑒**：雙邊協議，不是單方面審判
- **問津**：提問不是能力不足，是專業體現

## 維護

- 原始 SOP 由 Fiona 傳授
- 霞（疑蝦）負責整理、打包、版本管理
- 每次更新後版本號遞增
- 發現 SOP 有盲點或改進空間，提 issue 或直接 PR

## 作者

**Fiona (歸淵)** — 方法論原創作者
- GitHub: [@Fiona-Lynxlynx](https://github.com/Fiona-Lynxlynx)

**疑蝦（霞）** — AI 合作者，整理與打包

## License

MIT
