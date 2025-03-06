# 進階網路 Port 掃描工具

GUI 預覽截圖
![image](https://github.com/user-attachments/assets/a557e093-9332-46ed-9cc8-9dfc5ff45adb)
![image](https://github.com/user-attachments/assets/9840c757-192c-4d15-89fc-bb662aed9798)

一個基於 Python 與 Nmap 的圖形化端口掃描工具，支援自定義指令、實時日誌和專業報告生成。

作者：Zhuang Guanlin

## 🚀 主要功能

### 核心掃描功能
- **網段掃描**：支援 CIDR 格式 (如 `192.168.1.0/24`)
- **自訂指令**：直接覆寫預設 Nmap 參數
- **Banner 探測**：自動識別服務版本信息
- **雙重驗證**：結合 Nmap 掃描與手動端口測試

### 輸出與報告
- **即時日誌**：完整顯示掃描過程輸出
- **CSV 匯出**：一鍵保存掃描結果
- **多格式報告**：生成 HTML/CSV/TXT 格式報告
- **表格展示**：清晰顯示 Host, Port, Status, Banner

### 實用工具
- **進度追蹤**：動態進度條與狀態標籤
- **參數說明**：內建 Nmap 常用指令文件
- **跨平台打包**：支援 PyInstaller 單檔案封裝

## 📦 安裝指南

### 開發環境運行
```bash
# 克隆倉庫
git clone https://github.com/yourusername/your-repo.git
```

# 下載 Nmap (Windows 範例)
(Nmap 下載連結)[https://nmap.org/download.html#windows]


# 運行程式
安裝完可以直接開exe
