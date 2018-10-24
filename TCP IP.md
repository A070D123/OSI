# netork model

Layer-functionties-protocol-hardware-data format

# OSI

### Layer-7:Application
>* 不安全的協定:telnet(23)  ftp(20/21)  http(80)      DNS(53)
>* 安全的協定:   ssh(22)    sftp(22?)   https(443)    DNSsec()
>* HUb

### Layer-6:Presentation
>* 格式轉換format 加解密
>* 

### Layer-5:session
>* 
>* 

### Layer-4:Transport
>* TCP vs UDP
>* port address

### Layer-3:network
>* IP address
>* router(路由器):(動態路由 vs 靜態路由)[路由協定:路怎麼走 RIP BGP] 

### Layer-2:Data link
>* MAC address
>* switch(交換器)

### Layer-1:Physical
>* frame
>* HUb

# TCP


# TCP vs OSI

# protocol協定

### telnet
>* 遠端連線
>* 一種應用層協定
>* 1969年開發出來
>* 使用虛擬終端機的形式，提供雙向、以文字字串為主的命令列介面互動功能
>* 不安全

### File Transfer Protocol (FTP) (不安全)
>* 密碼和檔案內容都使用明文傳輸，可能發生竊聽。
>* 因為必須開放一個隨機的埠以建立連接，當防火牆存在時，用戶端很難過濾處於主動模式下的FTP流量。
>* 伺服器可能會被告知連接一個第三方電腦的保留埠。
>* 此方式在需要傳輸檔案數量很多的小檔案時，效能不好
>* 被動模式只要求伺服器端產生一個監聽相應埠的行程，這樣就可以繞過用戶端安裝了防火牆的問題。

### Secure Shell (SSH) (安全)
>* SSH的經典用途是登入到遠端電腦中執行命令。
>* 伺服器端需要開啟SSH守護行程以便接受遠端的連接，而用戶需要使用SSH用戶端與其建立連接。
>* SSH以非對稱加密實現身分驗證。
>* 是一種加密的網路傳輸協定，可在不安全的網路中為網路服務提供安全的傳輸環境
>* 因為SSH只驗證提供用戶是否擁有與公鑰相符合的私鑰，只要接受公鑰而且金鑰符合伺服器就會授予許可。


