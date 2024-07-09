# discord Bot
包含入庫存 出庫存 刪除庫存 查看已出貨庫存等...

#創建並設置機器人
創建 Discord 應用程序和機器人

1.前往 Discord 開發者門戶。
2.登錄並點擊“New Application”按鈕。
3.為你的應用程序命名，然後點擊“Create”。
4.在左側選單中選擇“Bot”，然後點擊“Add Bot”按鈕。
點擊“Yes, do it!”確認創建機器人。

獲取機器人令牌

在“Bot”頁面中，點擊“Copy”按鈕以複製“Token”。這個令牌是你的機器人的識別憑證，請妥善保管，不要與他人分享。
將這個令牌保存到你的.env 文件中，如下所示：

邀請機器人到你的伺服器

在左側選單中選擇“OAuth2”。
在“OAuth2”頁面中，選擇“URL Generator”。
在“SCOPES”部分選擇“bot”。
在“BOT PERMISSIONS”部分選擇所需的權限，建議選擇“Administrator”以獲得所有權限。
複製生成的邀請鏈接並在瀏覽器中打開，選擇你的伺服器並點擊“Authorize”將機器人添加到你的伺服器中。

#設定
將整個code下載下來並存在一個資料夾
安裝 requirements.txt  指令: pip install -r requirements.txt
進入.env 的文件 修改成自己的令牌 DISCORD_TOKEN=你的Discord機器人令牌

#執行
python main.py
