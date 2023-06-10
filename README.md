# -CMD_command
CMD commands

### 查看曾連接過的WIFI
netsh wlan show profiles
### 查看WIFI密码
netsh wlan show profile name="你要查的SSID" key=clear
### 查看IP信息
ipconfig /all
### 查詢網站IP
ping 網址
### 傳送封包
ping "ip address" -n "封包數量"
### 查看筆電電池狀態
powercfg/batteryreport 
### 合併CSV
copy *.csv all.csv
需先cd 進入該資料夾 它會合併該資料夾內所有csv
