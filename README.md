# test_0519.io
-----
## 這個是在幹嘛的

1. Compile 失敗。
   * 處理方式: Nuget Restore
2. System.Data.SqlClient.SqlException: 資料庫中已經有一個名為 'XXX' 的物件
   * 處理方式: 刪除資料庫
3. 沒有足夠的權限建立資料庫
   * 處理方式 : 給予連線的使用者於資料庫中擁有Create db, table 的權限