# TsungHan Chuang｜Project Portfolio

本頁統整本人在資料分析、量化交易與機器學習領域的實作總覽，涵蓋策略回測、Alpha 因子生成與機器學習應用，並包含國內外競賽成果。

---

## 專案一：台指期量化回測系統  
[前往專案](https://github.com/CTHQuant/taifex-futures-backtesting)

> 台指期多因子回測系統，整合權值股紅K與成交量比作為進場依據，支援每日 TP/SL 計算與報酬率追蹤。

- 日振幅模組動態評估市場波動度
- 自動化生成每日 PnL 與進場記錄
- Sharpe Ratio：5.46，Margin：37.42‰

---

## 專案二：WorldQuant Alpha 策略自動生成器  
[前往專案](https://github.com/CTHQuant/worldquant-alpha-ga-optimizer)

> 使用 Genetic Algorithm 結合 Fast Expression template，批次生成策略，並對接 simulate API 回收績效與自動篩選。

- 整合模板、data space、neutralization 等模組化設計
- 自動產生與評估數千組 Alpha 表達式
- 2025 WorldQuant IQC 全球排名第 57、台灣區第 1

---

## 專案三：SinoPac AI GO 2025 股票預測模型  
[前往專案](https://github.com/CTHQuant/ml-stock-prediction-optuna)

> 針對台股個股漲跌預測設計的機器學習架構，結合 LGBM/XGBoost/CatBoost，並採用 Pseudo-labeling 解決資料不平衡問題。

- F1 Score：0.8615，競賽排名第 14 / 868（前 1.6%）
- Optuna 自動搜尋最佳參數組合
- 半監督式學習結合技術指標與統計特徵

---

## 技術專長與應用領域

- **金融數據建模與特徵工程**：處理高頻與日線數據，熟悉 K 棒結構判斷與成交量異常建模
- **機器學習分類任務建構**：熟練使用 LGBM、XGB、CAT 與 Sklearn Pipeline 進行分類與風險預測
- **超參數優化與策略搜尋**：Optuna、GridSearch 與遺傳演算法整合應用於模型選擇與 Alpha 結構生成
- **策略回測與績效視覺化**：使用 Pandas / Polars 處理回測資料，Matplotlib 呈現 PnL 與績效指標
- **端對端建模能力**：具備從資料清洗、特徵選取、模型調參、部署與分析的全流程實作經驗

---

## 關於我

莊宗瀚（TsungHan Chuang）  
GitHub： [https://github.com/CTHQuant](https://github.com/CTHQuant)  
LinkedIn： [https://linkedin.com/in/宗瀚-莊-1a8588358/]

---

## 使用方式

本頁作為專案總覽首頁，可附於履歷、LinkedIn 或技術簡報中，快速導引至各完整專案倉庫。