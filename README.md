# 🖥️ PC Assembly Simulator | 《砌機大挑戰》擬真主機板模擬器

[English](#english) | [繁體中文](#traditional-chinese)

---

<a name="english"></a>
## 🌐 English

### 📌 Overview
**PC Assembly Simulator** is an interactive, single-page web application designed for computer science classrooms and hardware enthusiasts. It provides an intuitive drag-and-drop environment for learning how to install key PC hardware components onto an ATX motherboard correctly.

### ✨ Key Features
* **Interactive Drag-and-Drop / Tap-to-Place:** Fully optimized for desktops, tablets (iPad/iOS), and mobile touch devices using the `DragDropTouch` polyfill.
* **Component-Specific Visual Feedback:**
  * CPU and Fan render crisp SVG icons inside slots upon placement.
  * Compact slots (RAM, M.2 SSD, PCIe GPU, Power, SATA) transform into high-contrast solid-color blocks with clean labels upon installation to prevent visual misalignment.
* **Real-time Scoring & Timer:** Features an integrated 180-second countdown, score calculation, and local classroom leaderboard with multi-tab `BroadcastChannel` synchronization.
* **Educational Safety & Error Popups:** Displays popups explaining correct hardware functions and safety warnings (e.g., anti-static precautions) when an incorrect placement is made.
* **Built-in Knowledge Base & Photo Gallery:** Includes expandable hardware function descriptions and a high-resolution photo reference gallery with lightbox zooming functionality.

### 🛠️ Hardware Components Covered
* **CPU** (Central Processing Unit)
* **CPU Cooler / Fan**
* **DDR5 RAM** (Dual-channel setup)
* **M.2 NVMe SSD**
* **PCIe 5.0 x16 GPU** (Graphics Card)
* **24-pin ATX Power Connector**
* **SATA Storage Interface**

### 🚀 Getting Started
1. Download or clone this repository.
2. Ensure the main HTML file is named `index.html`.
3. Open `index.html` directly in any modern web browser (Chrome, Safari, Edge, Firefox)—no server setup or installation required!

### ⚙️ Deployment
Deploy instantly via static hosting providers:
* **GitHub Pages:** Enable in `Settings > Pages` after pushing `index.html` to your main branch.
* **Netlify Drop / Vercel:** Drag and drop the folder containing `index.html` for instant HTTPS access.

---

<a name="traditional-chinese"></a>
## 繁體中文

### 📌 專案簡介
《砌機大挑戰》是一款專為電腦科課堂及硬體愛好者設計的單頁 Web 擬真主機板模擬器。透過直覺的拖放與點擊操作，引導學生學習如何將各類電腦硬體組件正確安裝至 ATX 主機板上。

### ✨ 核心功能
* **跨裝置拖放與點擊操作：** 內建 `DragDropTouch` 支援，全面兼容 PC、iPad 及平板移動裝置。
* **精準無視覺錯位設計：**
  * CPU 及 CPU 風扇在安裝後會顯示精美的 SVG 圖示。
  * 狹長型插槽（RAM、M.2 SSD、PCIe 獨立顯示卡、電源及 SATA）在安裝完成後轉為高對比純色塊與清晰文字標籤，確保無圖示溢出或錯位問題。
* **即時競賽與排行榜：** 包含 180 秒倒數計時、動態計分機制，並透過 `BroadcastChannel` 技術支援跨頁面即時全班排行榜同步。
* **硬體錯位防護與安全警告：** 放置錯誤時會即時彈出視窗介紹正確單元功能，並包含組裝前靜電安全提示。
* **知識庫與真實相片圖鑑：** 整合可展開的硬體功能說明卡片，以及支援點擊放大（Lightbox）的真實電腦硬體相片圖鑑。

### 🛠️ 包含之電腦硬體組件
* **CPU**（中央處理器）
* **CPU 散熱器**
* **DDR5 RAM**（雙通道記憶體）
* **M.2 NVMe SSD**（固態硬碟）
* **PCIe 5.0 x16 GPU**（獨立顯示卡）
* **24-pin ATX 電源插座**
* **SATA 6Gbps 儲存介面**

### 🚀 使用說明
1. 下載或 Clone 本專案儲存庫。
2. 確保主網頁檔案命名為 `index.html`。
3. 直接使用任何現代瀏覽器（Chrome, Safari, Edge, Firefox）開啟 `index.html` 即可執行，無需安裝任何後端環境。

### ⚙️ 線上部署
可透過免費靜態託管平台快速發佈：
* **GitHub Pages：** 將 `index.html` 推送至專案後，於 `Settings > Pages` 開啟部署。
* **Netlify Drop / Vercel：** 將包含 `index.html` 的資料夾直接拖放上傳，即可獲得課堂專用 URL。

---

### 📄 License
This project is licensed under the MIT License.