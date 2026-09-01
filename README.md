# changlabtw.github.io

organization site，只有一頁導引頁。訪客到 <https://changlabtw.github.io/>
會被轉到實驗室網站 <https://changlabtw.github.io/lab/>。

## 為什麼是空的

`changlabtw.github.io` 的根命名空間**留給工具的 project site**：

| repo | 網址 |
|---|---|
| `lab` | <https://changlabtw.github.io/lab/> — 實驗室網站 |
| `wpSBOOT` | <https://changlabtw.github.io/wpSBOOT/> |
| `GODoc`、`PSLCNN`、… | `https://changlabtw.github.io/<repo>/` |

規則是「一個 repo 一個路徑段」。實驗室網站若佔用根目錄，它的頁面
（`research.html`、`team.html` …）會跟工具混在同一層命名空間裡。

## 部署

Settings → Pages → Source 選 **Deploy from a branch**，`main` / `/ (root)`。
只有一個靜態檔案，不需要建置。
