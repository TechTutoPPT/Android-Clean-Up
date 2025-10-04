[![](https://github.com/TechTutoPPT/Android-Clean-Up/blob/main/IMG_8250.PNG)](https://youtu.be/Ys2bEbWPxFw)

即然上一影片已打開了開發者選項, 那就不要浪費了它強大的功能, 如果未打開的話可按以下操作開啟:
進入手機設定>關於手機>連續點擊版本號7次以開啟開發者選項>
於設定中搜尋開發者選項並進入該設定>啟用USB偵錯>透過USB線連接手機與電腦.

去官網下載今次的主角Universal Android Debloater GUI:
```
https://github.com/0x192/universal-android-debloater/releases
```
另亦要下載Android系統核心開發和調試工具包:
```
https://dl.google.com/android/repository/platform-tools-latest-windows.zip
```

先將工具包解壓, 再將主角uad_gui-windows.exe移動到工具包目錄內.
然後按Win+x>點選裝置管理員>查看裝置中是否有無法辨識的裝置(假如有多個這樣的裝置可透過拔插Android裝置去確認)>
若果有雙擊這裝置>點選更新驅動程式>瀏覽電腦上的驅動程式>瀏覽目錄指向工具包, 再點下一步去進行安裝.
完成後於檔案總管移動至工具包的目錄, 於上方路徑位置輸入cmd並按下Enter進入終端機, 然後執行以下指令查看裝置是否已就位:
```
adb devices
```
至此先來一則免責聲明: 後面的操作絕對有風險, 請明白自己的操作並為其負責, 
我親身經驗試過令一部手機的多任務按鍵失效, 需要重置解決, 所以我對您的裝置可能發生的任何事情一概不承擔任何責任.
明白風險後, 可執行以下指令開啟Universal Android Debloater GUI:
```
uad_gui-windows
```
版面中左上角看看是否已加載你的裝置, 預設選單是Recommended, 選單分別對應為:
Recommended 推薦
Advanced 進階
Expert 專家
Unsafe 不安全
Unlisted 未列出
意指刪除該選單內的應用其風險評級, 一般建議操作Recommended選單內的應用便可,
左上方亦提供Search packages...搜尋列, 可在這裡以應用名稱去搜尋目標,
對想刪除的應用, 操作如下:
點選左方應用名稱的方框, 再點選對應的Uninstall按鈕便可.

這裡再提供大家一個技巧, 你可點選多個目標, 然後點選右下方的Export current selection, 
這樣於工具包目錄中便會出現一個uad_exported_selection.txt檔案, 你將檔案內容徵詢一下AI, 
問問對應的是什麼功能, 刪除它是否安全, 這樣就更穩妥.


