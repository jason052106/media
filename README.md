#  媒體播放器 (Media Player)
這是一個使用 C# Windows Forms 搭配 Windows Media Player (WMP) COM 元件開發的輕量級影音播放器。以自訂的使用者介面取代了傳統 WMP 的預設控制面板，提供更乾淨、客製化的視覺體驗。

##  功能特色 
* 支援多種格式：可播放常見的影音格式，包含 .mp4, .wmv, .avi 等。

* 自訂控制介面：隱藏了原生的 WMP 播放列

* 基礎播放控制：瀏覽檔案 (Browse)」、「播放 (Play)」、「暫停 (Pause)」與「停止 (Stop)」功能。

## 開發環境
語言：C#

框架：.NET Framework / Windows Forms (WinForms)

核心元件：AxWMPLib.AxWindowsMediaPlayer 

IDE：Visual Studio 

## 如何執行 

將本專案下載或 Clone 到本機。

在專案資料夾中找到 .sln (方案檔) 並雙擊開啟。

按下鍵盤的 F5 或是點擊上方的「開始」按鈕，即可編譯並執行程式。

## 使用說明 
開啟應用程式後，點擊 `瀏覽 / Browse` 按鈕。

在彈出的檔案選擇視窗中，選擇你要播放的影片檔案，點選`開啟`。

影片載入後會先處於停止狀態，點擊 `播放 / Play` 即可開始觀看。

播放過程中，可隨時使用 `暫停 / Pause` 或 `停止 / Stop` 按鈕來控制進度。

<img width="795" height="710" alt="image" src="https://github.com/user-attachments/assets/ba3cdf31-5a49-4d68-ae22-91eecaa0094f" />
