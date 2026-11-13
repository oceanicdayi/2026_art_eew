# 未抵達的幾秒 — 地震預警互動藝術

科技爭取時間。演練，讓時間有了去處。

以地震科學為背景，透過波形、倒數、選擇與兩次行動軌跡，探索從「收到預警」到「理解並開始防護」的落差。

## 作品

- 第一幕：在模擬預警中選擇確認訊息、觀望或開始防護。
- 演練：理解「趴下、掩護、穩住」。
- 第二幕：帶著記憶再體驗，並列兩次選擇紀錄。
- 支援暫停、重玩、不倒數模式與可選的合成聲音（非官方警報音）。

## 科學與創作界線

12 秒、圓環與波形均為藝術模擬，不是即時地震資訊、真實地震資料或災損預測。點選紀錄不是防護能力評分，也不能當作演練成效的實驗證據。預警有近震央盲區；防護動作須依環境調整，網頁體驗不能取代實地演練。

參考：[中央氣象署強震即時警報原理](https://scweb.cwa.gov.tw/zh-tw/guidance/eew/3)、[互動式地震避難指南](https://scweb.cwa.gov.tw/webdata/PDF/Earthquake_precautions/)。

## 執行與發布

純 HTML / CSS / JavaScript，無建置程序。以靜態伺服器提供根目錄即可，例如 `python3 -m http.server 8000`。Google Fonts 需網路，無法載入時使用系統字型。

GitHub Pages：Settings → Pages → Deploy from a branch → `main` / `/ (root)`。

預期網址：https://oceanicdayi.github.io/2026_art_eew/
