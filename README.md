# Hi there, I'm 簡偉玲 (Wei-Ling Chien) 👋

[![AWS Certified](https://img.shields.io/badge/AWS-Certified_Cloud_Practitioner-FF9900?logo=amazonaws&logoColor=white)](#)
[![Academic Ranking](https://img.shields.io/badge/Soochow_Univ-IM_Top_7.9%25-blue)](#)
[![GPA](https://img.shields.io/badge/GPA-3.8%2F4.0-brightgreen)](#)
[![TOEIC](https://img.shields.io/badge/TOEIC-670-green)](#)

目前就讀東吳大學資訊管理學系四年級（班排前 7.9% / 系排前 9.5% / GPA 3.8），具備 AWS Certified Cloud Practitioner 認證。

曾選修 **雲端架構配置 (AWS/Supabase)、機器學習（模型評估/門檻調優）、推薦系統導論（演算法/混合推薦）、分散式運算 (Hadoop/MapReduce) 與系統分析 (SA&SD)** 等課程。

---

## 🚀 專案展示 (Featured Projects)

### 🌸 1. [動態臉部辨識之美妝 AR 教學 App (BlushNote)](https://github.com/rujoxum/makeup-ar-app)
> **時間**：2026.3 ~ Present｜**角色**：後端與演算法設計主導
> **技術棧**：`Python` `Supabase` `Row Level Security (RLS)` `Apple Vision` `Monte Carlo Simulation`
- **雲端資安與隱私隔離**：規劃 Supabase 資料庫架構，並實作 Row Level Security (RLS) 綁定 `auth.uid()`，確保使用者隱私數據於多租戶環境下被安全隔離。
- **邊緣影像處理與驗證**：結合 Apple Vision 框架進行邊緣端影像處理，並透過蒙地卡羅演算法初步驗證推薦邏輯之可行性與一致性（Top@3 準確率 0.9728）。

---

### 💳 2. [高度不平衡信用卡詐欺偵測](https://github.com/rujoxum/credit-card-fraud-detection)
> **角色**：獨立開發
> **技術棧**：`Python` `SMOTE` `XGBoost` `PR-AUC` `Cost-Sensitive Threshold Tuning`
- **不平衡數據處理**：針對 Kaggle 28 萬筆交易導入 SMOTE 過抽樣，並捨棄易失真的 Accuracy / ROC-AUC，以 **PR-AUC (0.9338)** 與 **F1-Score** 為主要評估標準。
- **成本敏感決策門檻調優**：考量誤擋正常交易之客服營運成本，將最佳決策門檻調至 `0.822`，使 XGBoost 的 **Precision 提升至 93.33%**，在維持 93.33% Recall 下極小化誤判成本。

---

### 🎵 3. [Spotify 多維度音樂推薦系統](https://github.com/rujoxum/spotify-music-recommender)
> **時間**：2025.10 ~ 2025.12｜**角色**：兩人獨立開發
> **技術棧**：`Python` `Scikit-Learn (Audio KNN)` `NLTK (TF-IDF)` `Spotify Web API` `Streamlit`
- **混合推薦演算法**：結合 Audio KNN 音訊特徵與歌詞 TF-IDF 文本向量，打造兼具曲風與語意相似度的混合式音樂推薦系統。
- **互動前台與視覺化**：使用 Streamlit 建構互動式前端介面與數據視覺化面板，提升使用者互動體驗與音樂試聽流暢度。

---

### 🐘 4. [大數據分析巨量集群](https://github.com/rujoxum/hadoop-tweet-sentiment)
> **時間**：2026.4｜**角色**：獨立開發
> **技術棧**：`Hadoop MapReduce` `HDFS` `Java` `Linux Ubuntu` `VirtualBox` `Shell Script`
- **雙節點叢集搭建**：於 Linux 虛擬機環境手動搭建 Master-Slave 雙節點集群，建立穩定分散式運算環境。
- **MapReduce 輿情分析**：撰寫 MapReduce 腳本處理大量社群數據，進行文字解析與情緒趨勢時間序列統計分析。

---

### ☁️ 5. [雲端 Web 伺服器部署與 S3 整合](https://github.com/rujoxum/aws-pet-adoption-system)
> **時間**：2026.5｜**角色**：獨立開發
> **技術棧**：`AWS EC2` `Amazon S3` `Amazon DynamoDB` `PHP` `Apache` `PuTTY`
- **虛擬主機與環境建置**：透過 PuTTY 遠端連線並管理 AWS EC2 Linux 虛擬主機，建置 Web 伺服器環境（PHP / Apache）。
- **雲端物件儲存與 NoSQL 整合**：串接 AWS S3 作為靜態資源與檔案儲存庫，並結合 DynamoDB 進行動態資料讀寫，實現 Web 應用程式與雲端物件儲存的資料互動與架構部署。

---

### 🏛️ 6. [SCUnirea 校園學習管理系統](https://github.com/rujoxum/course-system-analysis)
> **角色**：專案組長 / 系統分析
> **技術棧**：`Structured Analysis (DFD/DD)` `3NF Schema Refactoring` `MS Access` `Figma Prototype`
- **三端權限隔離 (RBAC)**：完整規劃學生端 App、教師端工作台與校方行政後台之資料流邊界與權限。
- **Schema 3NF 重構**：主動重構資料庫架構，消除所有冗餘 1:1 資料表，於 Access 建置標準參照完整性約束。

---

## 🛠️ 專業技能 (Skills)

- **程式語言 (Languages)**：Python, Java, SQL, PHP, Bash/Shell Script
- **雲端與 OS (Cloud & OS)**：AWS (EC2, S3, DynamoDB, CCP Certified), Supabase (RLS/JWT Auth), Linux (Ubuntu), VirtualBox, PuTTY
- **後端與資料庫 (Backend & DB)**：Supabase, PHP, Apache 基礎, Database Normalization (3NF)
- **前端與視覺化 (Frontend & UI)**：Streamlit, Figma
- **AI & 數據分析 (AI & Data Analysis)**：Machine Learning (Scikit-learn, XGBoost, SMOTE), Hadoop MapReduce, LLM 應用, 推薦系統

---

## 🎓 教育背景與認證 (Education & Certifications)

- **東吳大學 資訊管理學系** (2023–2027 預計)｜GPA: 3.8 / 4.0
  - 修習課程：大數據分析、機器學習、推薦系統、資料庫管理、雲端運算、系統分析與設計
- **AWS Certified Cloud Practitioner (AWS CCP)** (2026.7)
- **TOEIC Listening & Reading 670** (2026.8)

---

## 📫 聯絡資訊 (Contact)
- **Phone**: 0909-087-680
- **Email**: jainwayline@gmail.com
- **Location**: 台灣，新北市淡水區
- **GitHub**: [github.rujoxum.com](https://github.rujoxum.com)
