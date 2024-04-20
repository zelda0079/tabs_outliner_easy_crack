# tabs_outliner_easy_crack
tabs_outliner_easy_crack

# 簡單破解Tabs outliner本地儲存的備份
# 此方法只能打開每日自動保存的頁面，錯手刪除又沒有手動備份時能救回分頁

1. 打開Tabs outliner
2. 開啟設定
3. 選BACKUP
4. 按下Enable Google Drive Backup Controls
5. 如果你是第1次使用這功能，先授權你GOOGLE帳號去使用
6. 完成第5步後，在BACKUP視窗按下F12，會跳到去控制台
![解說](https://live.staticflickr.com/65535/53665994721_c8d52ac976_o.png)
7. 第1步，按source；第2步，選options-backup.js；第3步，搜尋PRO_LICENSE_KEY_VALID
8. 第4步，將  if(isLocal && !PRO_LICENSE_KEY_VALID) {
    alert("You need to buy Paid Mode License Key to enable this feature.");
    return
  }刪掉
9. 第5步，按CTRL+S
10. 現在你可以回去按VIEW查看自動儲存在本地的備份了
11. 這個改動不會影響你的插件，不會真的存檔到本地插件的文件
> # 注意千萬不要去改動插件的代碼，你只要改動1個字，即使加一個ENTER，插件就會無法運行，因為有檢查文件是否改動的功能
