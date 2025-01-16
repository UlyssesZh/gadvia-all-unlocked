# Gadvia 全解鎖存檔

遊戲
[Gadvia](https://web.archive.org/web/20250116200126/https://gadvia.wixsite.com/gadvia)
的全解鎖存檔.

該遊戲已於 2025-01-15 停止運營
([公告](https://web.archive.org/web/20250116200252/https://gadvia.wixsite.com/gadvia/%E5%89%AF%E6%9C%AC-%E9%97%9C%E6%96%BC%E5%88%AA%E9%99%A4%E5%B8%B3%E8%99%9F)).
然而, 使用這個存檔, 你仍然可以玩遊戲中的所有常規譜面.

## 聲明

這些存檔是原樣提供的, 沒有任何保證.
請自行承擔使用風險.

這個存檔的目的是彌補那些投入時間和金錢玩這個遊戲的玩家,
以及不讓譜師辛苦寫出的譜面被埋沒.

## 導入

在導入存檔之前, 你需要在 Android 設備上安裝遊戲.

### 無 root

這個方法只適用於舊的 Android 版本 (Android 12 之前).

1. 按照[這裡](https://developer.android.google.cn/tools/adb?hl=zh-cn)
  的指示使用 adb 連接到你的 Android 設備.
2. 從此倉庫下載文件 `gadvia-all-unlocked.ab`.
3. 執行命令 `adb restore gadvia-all-unlocked.ab`.
4. 你的 Android 設備應該提示輸入密碼. 只需將密碼留空並繼續.
5. 等待過程完成 (大約 1 秒).

### 有 root

1. 啟動 Gadvia 一次並退出.
2. 使用你喜歡的文件管理器或 adb 將文件 `com.hgca.uma.v2.playerprefs.xml` 放入目錄
  `/data/data/com.hgca.uma/shared_prefs`, 覆蓋原有的文件.

## 導入後

導入存檔後, 啟動遊戲.
你應該看到所有常規譜面都已解鎖且未遊玩.

"商店" 和 "冒險" 部分無法訪問,
因為它們需要連接到伺服器.
