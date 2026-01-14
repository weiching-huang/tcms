才藝教室管理系統（Full Stack Side Project）

個人獨立開發 | React、Node.js、Express、MongoDB、JWT、Redux Toolkit、Tailwind CSS、Vercel、Render

為了解決教室人力管理繁瑣問題所設計，使用 React + Node.js + MongoDB，前端部屬於Vercel，自建後端 API 並部署於 Render。

專案簡介：

 「才藝教室管理系統」是一個為補習班或才藝教室設計的全端系統，整合了課程、出缺席、繳費、公告與分帳管理等功能，讓管理者、老師與學生能在同一平台上完成教務與課務流程。此系統採用 RESTful API 架構，並以 JWT 實作多角色身分驗證機制，達到資料安全與操作分權。

系統角色與主要功能：

 管理者 (Admin)
課程管理：課程 CRUD、指定授課老師、設定課程人數上限與分帳比例。
帳號管理：建立／刪除老師與學生帳號。
分帳管理：核算教師收入（pending → paid）、生成月度報表。
繳費管理：學生繳費狀態追蹤。
公告管理：新增／刪除公告。
 老師 (Teacher)
查看所屬課程與學生名單，進行點名與出缺席紀錄管理。
公告管理：新增自己課程公告。
查閱個人分帳收入與結算狀況。
 學生 (Student)
報名課程、查看繳費狀態與出缺席紀錄。
查看公告與請假申請。
技術實作：

前端： 使用 React + Redux Toolkit 實作狀態管理，並以 Tailwind 建立響應式設計介面。
後端： 採用 Node.js + Express 建構 RESTful API，搭配 JWT Token 實現登入驗證與角色權限控管。
資料庫： 使用 MongoDB Atlas 進行雲端資料儲存與查詢。
部署： 前端架設於 Vercel，後端以 Render 部署。
測試與開發工具： 以 Postman 測試 API、使用 Git/GitHub 進行版本控制。
專案亮點與貢獻：

完成從建立model、資料庫、各API路由設計、到前後端整合的全流程開發。
實作多角色授權架構，確保不同使用者間資料安全。
利用 Redux Toolkit 模組化狀態管理，優化資料流與維護性。
以 RESTful 思維設計 API，達到清晰的前後端分工與可擴充性。
