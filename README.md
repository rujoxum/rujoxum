# Hi there, I'm 簡偉玲 (Wei-Ling Chien) 👋

[![AWS Certified](https://img.shields.io/badge/AWS-Certified_Cloud_Practitioner-FF9900?logo=amazonaws&logoColor=white)](#)
[![Academic Ranking](https://img.shields.io/badge/Soochow_Univ-IM_Top_7.9%25-blue)](#)
[![TOEIC](https://img.shields.io/badge/TOEIC-670-green)](#)

目前就讀東吳大學資訊管理學系（班排前 7.9% / 系排前 9.5%），專長於 **雲端資料庫架構設計 (Supabase/RLS)、機器學習 (不平衡數據調優)、分散式運算 (Hadoop/MapReduce) 與系統分析 (SA&SD)**。

持有 **AWS Certified Cloud Practitioner (CCP)** 國際認證，致力於將「資料隱私保護設計」與「可解釋決策模型」落地於個人化服務產品中。

---

## 🚀 核心專案展示 (Featured Projects)

### 🌸 1. [美妝 AR 教學 App (BlushNote)](https://github.com/rujoxum/makeup-ar-app)
> **技術棧**：`Python` `Supabase` `Row Level Security (RLS)` `iOS Native Vision` `Monte Carlo Simulation`
* **隱私導向邊緣架構**：設計臉型與膚色特徵留在裝置端運算，雲端僅存取去識別化標籤，落實資料最小化原則。
* **底層細粒度資安**：於 Supabase 綁定 `auth.uid()` 設置 RLS 政策，阻絕多租戶環境下的越權存取。
* **演算法驗證與排序**：以 Monte Carlo 執行 30 輪模擬實驗，驗證得出 **Top@3 準確率 0.9728**、覆蓋率 99.94% 且 Exposure Gini 僅 0.3504 之高公平性排序模型。

---

### 💳 2. [高度不平衡信用卡詐欺偵測](https://github.com/rujoxum/credit-card-fraud-detection)
> **技術棧**：`Python` `SMOTE` `XGBoost` `PR-AUC` `Cost-Sensitive Threshold Tuning`
* **不平衡數據處理**：針對 Kaggle 28 萬筆交易導入 SMOTE 過抽樣，並捨棄易失真的 Accuracy / ROC-AUC，以 **PR-AUC (0.9338)** 與 **F1-Score** 為主要評估標準。
* **成本敏感決策門檻調優**：考量誤擋正常交易之客服營運成本，將最佳決策門檻調至 `0.822`，使 XGBoost 的 **Precision 提升至 93.33%**，在維持 93.33% Recall 下極小化誤判成本。

---

### 🎵 3. [Spotify 多維度混合音樂推薦系統](https://github.com/rujoxum/spotify-music-recommender)
> **技術棧**：`Python` `Scikit-Learn (KNN)` `NLTK (TF-IDF)` `Spotify Web API` `Streamlit`
* **四維度混合推薦引擎**：融合音訊特徵 KNN、Russell 心情雙軸空間 (Valence-Energy)、歌詞語意 TF-IDF 餘弦相似度與熱門度榜單（消除冷啟動）。
* **API 串接與前端交付**：串接 Spotify Web API 獲取專輯封面與試聽連結，並以 Streamlit 封裝可即時互動試聽之 Web 介面。

---

### 🐘 4. [Hadoop 分散式推文輿情趨勢分析](https://github.com/rujoxum/hadoop-tweet-sentiment)
> **技術棧**：`Hadoop HDFS` `Java MapReduce` `Linux Ubuntu` `Distributed Systems`
* **雙節點叢集搭建**：在 Linux 虛擬機環境架設 Master-Worker 雙節點 Hadoop 運算叢集。
* **MapReduce 分散式腳本**：撰寫 MapReduce 程式處理數萬筆公開推文資料，執行大數據比對與情緒趨勢時間序列分析。

---

### 🏛️ 5. [SCUnirea 校園學習管理系統](https://github.com/rujoxum/course-system-analysis)
> **技術棧**：`Structured Analysis (DFD/DD)` `3NF Schema Refactoring` `MS Access` `Figma Prototype`
* **三端權限隔離 (RBAC)**：完整規劃「學生端 App、教師端工作台、校方行政後台」之資料流邊界與權限。
* **Schema 3NF 重構**：評估多表 JOIN 開銷後，主動重構資料庫架構，消除所有冗餘 1:1 資料表，於 Access 建置標準 $1 \to \infty$ 參照完整性約束。

---

## 🛠️ 技術棧與能力 (Skills & Certification)

* **雲端與架構**：AWS CCP Certified, Supabase (RLS/JWT Auth), Database Normalization (3NF)
* **資料科學與 ML**：Python, Scikit-Learn, XGBoost, Random Forest, SMOTE, NLTK, TF-IDF
* **巨量資料與工具**：Hadoop HDFS, MapReduce, Linux (Ubuntu), Git/GitHub, Streamlit, Figma

---

## 📫 聯絡方式 (Contact)
* **Email**: jainwayline@gmail.com
* **Location**: New Taipei City, Taiwan
