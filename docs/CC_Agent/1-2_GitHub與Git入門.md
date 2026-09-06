# 1-2 GitHub 與 Git 入門

## 為什麼要學這個

你的 AI agent 累積的規則、記憶、流程，全部都是「檔案」。如果電腦壞了、檔案被誤刪，這些心血就沒了。

GitHub 就是幫這些檔案「存檔備份」的地方，而且每一次存檔都有紀錄，可以回到任何一個時間點。你不需要變成工程師，只要懂四個動作在做什麼就夠了。

## 你會學到什麼

- 申請一個 GitHub 帳號
- 用白話理解 add / commit / push 這三個動作（加上 status 一起看）
- 知道自己的 AI agent 資料夾「有沒有存檔」

## 步驟

### 申請帳號
1. 前往 github.com，點右上角 Sign up
2. 用 email 註冊，設定帳號密碼
3. 收信驗證信箱

### 搞懂四個動作（用白話理解，不用先背指令）

| 指令 | 白話意思 | 比喻 |
|---|---|---|
| `git status` | 看一下有哪些東西改過、還沒存檔 | 打開行李箱看看有什麼還沒收 |
| `git add 檔案` | 把要存的東西放進待存清單 | 把要帶走的東西放進行李箱 |
| `git commit -m "說明"` | 正式存檔一次，留下這次改了什麼的紀錄 | 把行李箱關起來，貼上標籤寫今天去哪 |
| `git push` | 把存檔上傳到 GitHub | 把行李箱寄到遠端倉庫保管 |

### 建立第一個 repo（存放檔案的倉庫）

1. 登入 GitHub，點右上角「+」→「New repository」
2. 取一個名字（例如 `my_agent`），選擇 Private（私人）
3. 點「Create repository」

### 怎麼跟 AI 說

申請好帳號、建好 repo 之後，跟它說：

> 「幫我讀一下 `docs/CC_Agent/1-2_GitHub與Git入門.md`，然後帶我實際做一次 status／add／commit／push，一步一步確認我有沒有做對。」

## 常見卡關

| 狀況 | 解法 |
|---|---|
| push 時要求輸入密碼但打了密碼還是失敗 | GitHub 現在需要用「Personal Access Token」代替密碼，去 Settings → Developer settings 產生一組 |
| 不知道現在存到哪一步了 | 隨時打 `git status` 看目前狀態，這是最安全的習慣動作 |
| commit 訊息不知道怎麼寫 | 就用白話說明「這次改了什麼」即可，不用寫得很正式 |

## 動手練習

在 GitHub 建立一個屬於你自己的 repo，命名成你想幫 AI agent 取的名字。

## 完成檢查

- [ ] 有一個 GitHub 帳號
- [ ] 能用一句話解釋 add / commit / push 各自在做什麼
- [ ] 已經建立一個空的 repo

## 下一步

前往 [1-3 怎麼跟 Claude Code 協作最有效](1-3_怎麼跟Claude-Code協作最有效.md)，學會怎麼跟 AI 溝通才不會白費力氣。
