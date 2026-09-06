# Codex Agent 安裝流程圖

[回到入口](README.md) · [開啟逐步教學](GUIDE.md)

實線是基本路線；技能與 GitHub 是完成基本驗證後的選配。

```mermaid
flowchart TD
    A[開始：準備官方帳號與電腦] --> B[01 安裝官方應用程式並登入]
    B --> C[02 建立並開啟自己的 codex_agent 資料夾]
    C --> D{能建立並讀回檔案嗎？}
    D -- 否 --> E[核對工作目錄、檔名與寫入權限]
    E --> C
    D -- 是 --> F[03 建立 AGENTS.md 與核心偏好]
    F --> G[04 分開記憶、草稿、參考資料與日記]
    G --> H[05 開新對話驗證規則與記憶]
    H --> I{讀到正確的本地檔案嗎？}
    I -- 否 --> J[檢查入口指示、檔案位置與實際內容]
    J --> H
    I -- 是 --> K[基本安裝完成]
    K -. 選配 .-> L[06 先盤點，再挑一項技能實測]
    K -. 選配 .-> M[07 建立自己的私人 GitHub 備份]
    L --> N[08 完成第一份作品並保存成果]
    M --> N
    K --> N
    N --> O[日常：交代任務 → 確認成果 → 記錄工作]
    classDef base fill:#151515,color:#ffffff,stroke:#D4AF64,stroke-width:2px;
    classDef check fill:#FAF8F2,color:#151515,stroke:#8A681F,stroke-width:2px;
    class A,B,C,F,G,H,K,L,M,N,O base;
    class D,E,I,J check;
```

## 看不到圖時

部分 Markdown 閱讀器不支援 Mermaid。可回到 GitHub 看本頁，或直接使用下面文字流程：

1. 安裝、登入 → 開啟自己的資料夾。
2. 寫入測試失敗 → 先修正路徑或權限；成功才往下。
3. 建立規則 → 整理資料夾 → 開新對話驗證。
4. 沒讀到 → 修正入口與路徑；讀到代表基本安裝完成。
5. 有需要才加技能、設定私人備份。
6. 完成第一件工作 → 存檔 → 記錄 → 下次接續。

下載本頁的 `.md` 即保留可編輯流程圖原始碼，不需要另外購買繪圖工具。
