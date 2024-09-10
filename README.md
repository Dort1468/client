# 網路課程註冊系統

這是一個使用 MERN（MongoDB、Express、React、Node.js）技術堆疊開發的網路課程註冊練習專案。該專案允許使用者註冊為學生或導師，並以各自的身分登入使用。導師可以註冊新課程，學生可以搜尋並註冊他們感興趣的課程。

## 專案作者

作者: Billy Chen  
根據Udemy上Wilson Ren老師所開設的網頁開發課程的指示製作。

## 功能特點

- **使用者註冊與登入**
  - 註冊為學生或導師身分。
  - 支援學生與導師的登入系統。

- **課程管理**
  - 導師可以新增課程並設定課程詳細資訊（例如課程名稱、描述、費用等）。
  - 課程頁面顯示註冊的所有課程和詳細資訊，包括已註冊的學生人數。

- **課程搜尋與註冊**
  - 學生可以瀏覽和搜尋可註冊的課程。
  - 學生可以註冊他們感興趣的課程並查看已註冊的課程列表。

## 安裝與使用

### 1. 克隆專案

bash
git clone https://github.com/yourusername/course-registration-system.git
cd course-registration-system

### 2. 安裝伺服器端依賴項目

cd server
npm install

### 3. 安裝用戶端依賴項目

cd client
npm install

### 4. 設定環境變數

MONGODB_URI=你的MongoDB連結
JWT_SECRET=你的JWT密鑰
PORT=伺服器運行的端口

### 5. 啟動伺服器與用戶端

### 啟動伺服器
cd server
nodemon .\index.js

### 啟動用戶端
cd client
npm start

伺服器端應該會在指定的端口上啟動（預設為 http://localhost:8080），而用戶端應該會在 http://localhost:3000 上啟動。

## 使用技術
- **前端: React.js, React Router**
- **後端: Node.js, Express.js**
- **數據庫: MongoDB, Mongoose, Joi**
- **認證: JSON Web Token (JWT), passport-local**
- **其他: Axios, Bootstrap 等前端 UI 框架**
  

## 未來改進
 - 增加更多的課程篩選和排序功能。
 - 增加學生的課程反饋和評價系統。
 - 將課程資料移動到更安全的後端管理。
 - 提高前端和後端之間的錯誤處理和驗證機制。

## 聯繫方式
如有任何問題或建議，請聯繫作者 Billy Chen
