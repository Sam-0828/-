📘 自適應濾波器（Adaptive Filter）- LMS 演算法
🧠 簡介

本專案展示 LMS（Least Mean Squares，最小均方）自適應濾波演算法 的基本概念與數學公式。

📌 初始化（Initialization）
\hat{h}(0) = zeros(p)

🔄 計算過程（Computation）

對於 ( n = 0,1,2,... )

📥 輸入向量（Input Vector）
\mathbf{x}(n) = [x(n), x(n-1), ..., x(n-p+1)]^T

❗ 誤差計算（Error）
e(n) = d(n) - \hat{h}^H(n)\mathbf{x}(n)

🔁 權重更新（Update Rule）
\hat{h}(n+1) = \hat{h}(n) + \frac{\mu e^*(n)\mathbf{x}(n)}{\mathbf{x}^H(n)\mathbf{x}(n)}

✨ 功能特色

📡 即時自適應學習

⚡ 計算簡單、效率高

🎯 廣泛應用於訊號處理

🛠️ 使用的 Markdown 語法




標題




次標題
粗體文字
斜體文字
行內程式碼
程式碼區塊
數學公式
無序清單
分隔線（---）
表格
引用（Quote）
圖片
勾選清單
Emoji 😄
📊 參數說明表
參數	說明
μ	步長（Step size）
p	濾波器階數
💡 重點說明

自適應濾波器可以根據輸入資料即時調整權重，以達到最佳估計效果。

🖼️ 圖片示意




📎 任務完成清單

建立 Repository

撰寫 README.md

🧑‍💻 作者

詹子軒
