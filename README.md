# RAG 旅遊Demo問答

## 簡介
本專案是一個基於檢索增強生成（Retrieval-Augmented Generation, RAG）技術的旅遊問答系統，透過結合檢索與生成技術，提供更準確且即時的旅遊資訊回應。

此系統可直接運行於 Google Colab 上，並透過 Gradio 提供使用者友好的介面進行互動。使用者可以上傳旅遊相關 PDF 文件，系統將自動處理內容並回答使用者的問題。

## 安裝與使用

### 環境準備
請確保具備以下環境：
- **Google Colab**（推薦）或本地 Python 環境（Python 3.8 以上）
- 相關 Python 套件（可手動安裝或透過 `requirements.txt` 安裝）

### 在 Google Colab 上運行
1. 開啟 Google Colab 並掛載 Google Drive（可選）。
2. 安裝相依套件。
3. 設定 API 金鑰：
   在 Colab 中執行以下命令來設定 OpenAI API 金鑰。

4. 啟動 Gradio 介面並上傳文件：
   執行以下程式碼以啟動 Gradio Web UI，使用者可上傳 PDF 旅遊文件並進行問答互動。

Gradio 將產生一個可公開存取的網址，點擊該連結即可上傳文件並進行問答。

## 使用技術
本專案使用以下技術：
- **RAG（檢索增強生成）**: 結合檢索與生成技術，提升問答質量。
- **LangChain**: 用於構建 LLM 應用。
- **ChromaDB**: 向量資料庫，用以提高檢索效率。
- **OpenAI Embeddings**: 用於向量化文字資料。
- **Gradio**: 提供 Web 介面，允許文件上傳與問答互動。
- **Google Colab**: 雲端運行環境，無需本地安裝。
