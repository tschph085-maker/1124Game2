# 小小夢境：理財鑰匙 · Dream Keys

[開啟網頁遊戲](https://tschph085-maker.github.io/1124Game2/)

使用 Godot 4.7.2 與 Blender 5.3.0 製作的原創 3D 理財解謎遊戲，適合國小中高年級。

## 兩關學習任務

1. 願望雜貨屋：分配 100 元零用錢，先照顧午餐與車資，至少儲蓄 20 元，不超支才能取得 KEY。
2. 種子投資室：保留備用金、分散種子配置，理解投資仍可能虧損，解題取得第二把 KEY。

各關顯示得分，最後呈現前後測比較與觀念進步，並可下載匿名學習紀錄。學習比較只代表本次練習表現，尚未進行兒童玩家實測或長期成效研究。

## 操作

WASD／方向鍵移動，空白鍵跳躍，E 互動，Esc 返回房間。也可使用畫面按鈕，建議桌機或平板橫向遊玩。

## 專案檔案

- `DreamKeys-Web.zip`：已測試的完整靜態網站，內含 HTML、JavaScript、WebAssembly、遊戲資料與授權聲明。
- `DreamKeys-GitHub.zip`：完整 Godot 專案、Blender 原始模型、建模腳本、測試與說明。下載解壓後，以 Godot 開啟 `DreamKeys/project.godot`。
- `.github/workflows/pages.yml`：自動解壓網站包到 `dist`，透過 GitHub Pages 發布。

網站使用單執行緒 Godot Web 匯出，不需要後端、帳號或 COOP/COEP 標頭。更新遊戲時重新匯出網站、替換 `DreamKeys-Web.zip` 並提交，Actions 會自動發布。

## 美術與授權

角色、模型與合成聲音為本專案原創。Little Nightmares 僅作為巨大家具比例與神祕空間的參考，未使用其角色或遊戲素材。中文字型使用 Noto Sans TC（SIL OFL 1.1）；Godot 執行環境與第三方授權保留在網站包內。
