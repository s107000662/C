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
>* router(路由器):(動態路由 vs 靜態路由)[路由協定:路怎麼走 IS-IS、OSPF、IGRP、EIGRP、RIP、BGP。] 

### Layer-2:Data link
>* MAC address
>* switch(交換器)

### Layer-1:Physical
>* frame
>* HUb(集線器)

# TCP


# TCP vs OSI

# protocol協定

### telnet
>* 遠端連線
>* 一種應用層協定
>* 1969年開發出來
>* 使用虛擬終端機的形式，提供雙向、以文字字串為主的命令列介面互動功能
>* 不安全
### TCP/UDP埠列表

>* 20/TCP,UDP	檔案傳輸協定 - 預設資料埠
>* 21/TCP,UDP	檔案傳輸協定 - 控制埠	
>* 22/TCP,UDP	SSH（Secure Shell） - 遠端登入協定，用於安全登入檔案傳輸（SCP，SFTP）及埠重新定向	
>* 23/TCP,UDP	Telnet終端仿真協定 - 未加密文字通訊
>* 25/TCP,UDP	SMTP（簡單郵件傳輸協定） - 用於郵件伺服器間的電子郵件傳遞
>* 53/TCP,UDP	DNS（域名服務系統）
>* 80/TCP	超文字傳輸協定（超文字傳輸協定）- 用於傳輸網頁
>* 139/TCP,UDP	NetBIOS NetBIOS 對談服務
>* 389/TCP,UDP	輕型目錄存取協定 LDAP
>* 443/TCP	超文字傳輸安全協定 - 超文字傳輸協定 over TLS/SSL（加密傳輸）
>* 514/TCP	遠端外殼 protocol - 用於在遠端電腦上執行非互動式命令，並檢視返回結果
>* 514/UDP	Syslog 協定 - 用於系統登入

