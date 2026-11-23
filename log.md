# Sisyphus Wiki — 運作日誌

本文件依時間遞增記錄知識庫的所有操作歷程（入庫 Ingest、查詢沉澱 Query、健康檢查 Lint、簡報生成 Present）。

---

## [2026-11-23] init | Wiki 架構初始化與規範建立
- 建立核心資料夾：`concepts/`, `comparisons/`, `sources/`, `faq/`, `presentations/`
- 建立維護準則文件 [AGENTS.md](file:///C:/Users/iris/.gemini/antigravity/scratch/sisyphus-wiki/AGENTS.md)
- 初始化內容導覽 [index.md](file:///C:/Users/iris/.gemini/antigravity/scratch/sisyphus-wiki/index.md)

---

## [2026-11-23] ingest | 批次處理 raw 原始文獻（共 6 篇）
- 處理 6 篇 raw 哲學文獻，萃取產出 `sources/`（6篇）、`concepts/`（8篇）、`comparisons/`（4篇）、`faq/`（2篇）。
- 生成第一版教學簡報。

---

## [2026-11-23] refactor | 深度去 AI 感與智識風格重塑（去心靈雞湯化）
- **核心調整目標**：因應反思回饋，徹底剃除「心靈雞湯、職場打卡、過度淺白」的 AI 感，回歸卡謬原著冷峻、嚴密且深刻的認識論論證。
- **規範更新（AGENTS.md）**：明確禁止 pop-psychology，明定「深入淺出」是清晰梳理論證鏈與哲學矛盾，而非把哲學降級為心靈成長。
- **概念頁與對照頁全面重寫**：
  - 重寫 `concepts/荒謬.md`：著重世界的陌生化、時間作為死敵、理性飢渴與宇宙沉默的不可化約關係。
  - 重寫 `concepts/肉體自殺.md`：剖析自殺作為口供（l'aveu）的邏輯漏洞，以及消滅見證者並非解答謎題的論證。
  - 重寫 `concepts/哲學性自殺.md`：深入齊克果、謝斯托夫、雅斯培、胡塞爾如何將「理性的挫敗」調包為「神聖的超越」。
  - 重寫 `concepts/反抗.md`、`荒謬自由.md`、`熱情與經驗的數量.md`、`荒謬英雄.md`：回歸無上訴（vivre sans appel）、死刑犯黎明、數量倫理與薛西弗斯下山清醒時分（l'heure de conscience）的原著深意。
  - 重寫 `comparisons/卡謬-vs-齊克果-論荒謬與跳躍.md`：深入約伯之抗與信心跳躍的形上學斷裂。
  - 重寫 `faq/荒謬與虛無主義有何不同.md`：從二戰歷史與絕對主義鄉愁剖析虛無主義的邏輯錯誤。
- **HTML 簡報重構（presentations/ & index.html）**：
  - 剔除職場小測驗，改為杜斯妥也夫斯基《群魔》中基里洛夫「人神邏輯自殺」的思想實驗推導。
  - 升級為典雅沉靜的學術美感排版，保留四家哲學範式切換（卡謬、齊克果、虛無主義、沙特）與三大嚴肅哲學命題辨析。
