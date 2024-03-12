### 錄音檔轉文字程式碼使用
- 編輯器：請使用google colab
- 上方工具列的**執行階段**>變更執行階段類型>硬體加速器選**T4 GPU**
- 從第一個cell開始執行，執行完才換下一個(會出現綠色勾勾)
- 第二個cell是選檔案用的，這部分視情況，有時候會跑很久ㄏㄏ
- 第四個cell是執行語音轉文字的主程式碼，請**避免執行中斷**，不然要全部重跑
- 目前一小時的錄音檔案，視情況大致上跑20分鐘就會完成
- 有空再改善程式碼ㄏㄏ
- 跑完程式碼會自動下載.srt檔，會以字幕檔形式呈現，請用記事本開啟
- 長成這樣：<img width="168" alt="image" src="https://github.com/rru216/rru216/assets/140193449/68496fa2-f493-4132-9a12-3b21a94a03f6">

### 去除時間軸
- 編輯器：建議用Notepad++，免費又好用！
- 把文字檔用Notepad++打開
- 上方工具列**搜尋**>取代>**尋找內容**：`\d+\n\d{2}:\d{2}:\d{2},\d{3} --> \d{2}:\d{2}:\d{2},\d{3}\n`；**取代為**：`保持空白`
- **搜尋模式**選`規則運算式`>全部取代
- <img width="447" alt="image" src="https://github.com/rru216/rru216/assets/140193449/abdd535f-ee3d-4092-b5b9-44d83944a0ec">

### 去除空白行
- 跟上面一樣，改個文字而已
- <img width="444" alt="image" src="https://github.com/rru216/rru216/assets/140193449/b0711544-ab32-4a26-8058-0aa22315b1ac">



<!---
rru216/rru216 is a ✨ special ✨ repository because its `README.md` (this file) appears on your GitHub profile.
You can click the Preview link to take a look at your changes.
--->
