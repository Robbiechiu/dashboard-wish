# 儀表板許願單 skill

羅伯特 AI 學院學員用。讓 Claude 一次問你一題，把「我想做一個儀表板」講清楚：要用來做什麼、資料從哪來、多久更新、想看什麼樣子、誰看，再一起定主儀表板和分頁，最後產出結構圖、規格檔和一段可以直接開工的許願句。

## 安裝（跟 Claude 說這句就好）

> 幫我安裝這個 skill：https://github.com/Robbiechiu/dashboard-wish ，裝到 ~/.claude/skills/dashboard-wish

Claude 會執行：

```bash
git clone https://github.com/Robbiechiu/dashboard-wish.git ~/.claude/skills/dashboard-wish
```

## 使用

裝好後重開 Claude Code，跟它說：

> 我想做一個儀表板

## 兩個步驟

1. **先看懂整體架構**：用瀏覽器打開資料夾裡的 `整體架構.html`——儀表板由哪三層組成、Claude 會問你哪些問題、為什麼問、老師的六個範例、八條規則。
2. **再用 skill 確認你要的東西**：跟 Claude 說「我想做一個儀表板」，它會一次問你一題，一步一步陪你把結構架起來。

## 更新

不用自己更新。每次使用時，skill 會先自動把自己更新到最新版。
