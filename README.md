# study-assistant

一個初學者實驗室，學習 AI 如何讀取提示模板和 SKILL.md 文件。

## 怎麼用
1. 打開 `templates/summary.md`，複製裡面的 Prompt
2. 把 `[課文內容]` 換成你的課文，貼給 AI
3. 實驗過程與結論記錄在 `experiments/log.md`

## 目錄
- `templates/`：Prompt 模板
- `skills/`：Skill 文件
- `experiments/`：實驗記錄
## 實驗結論
1. AI 只讀得到我貼給它的內容；沒貼等於不存在，有的 AI 還會編造（幻覺）
2. 指令寫了才有，沒寫就沒有；想要穩定的格式，要寫進 Prompt 或 skill
3. 單次結果有隨機性，結論需要重複驗證
4. AI 選 skill 會綜合名稱、description 和整句語意；少量 skill 時很準，description 的風險要在 skill 變多時才測得出
5. 版本控制讓改壞的檔案可以找回，用 AI 改檔案前要先有 commit

詳細記錄見 `experiments/log.md`

## 版本
v1.0：完成模板與 skill 讀取實驗、Issues 迭代、版本回退練習
